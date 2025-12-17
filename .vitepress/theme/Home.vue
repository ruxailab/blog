<script setup lang="ts">
import { ref, computed } from 'vue'
import Date from './Date.vue'
import { data as posts } from './posts.data.js'
import { useData } from 'vitepress'

const { frontmatter } = useData()

const query = ref('')

const filteredPosts = computed(() => {
  const q = String(query.value || '').trim().toLowerCase()
  if (!q) return posts
  return posts.filter((p) => p.title.toLowerCase().includes(q))
})
</script>

<template>
  <div class="divide-y divide-gray-200 dark:divide-slate-200/5">
    <!--
    <div class="pt-6 pb-8 space-y-2 md:space-y-5">
      <h1
        class="text-3xl leading-9 font-extrabold text-gray-900 primary-color dark:text-white tracking-tight sm:text-4xl sm:leading-10 md:text-6xl md:leading-14"
      >
        {{ frontmatter.title }}
      </h1>
      <p class="text-lg leading-7 text-gray-500 dark:text-white">
        {{ frontmatter.subtext }}
      </p>
    </div>
    -->
    <div class="pt-4 pb-6">
      <label for="search" class="sr-only">Search posts by title</label>
      <input
        id="search"
        v-model="query"
        type="search"
        placeholder="Search posts by title..."
        class="w-full px-4 py-2 border rounded-md focus:outline-none focus:ring-2 focus:ring-primary-color"
        aria-label="Search posts by title"
      />
    </div>

    <ul class="divide-y divide-gray-200 dark:divide-slate-200/5">
      <li class="py-12" v-for="{ title, url, date, excerpt } of filteredPosts">
        <article
          class="space-y-2 xl:grid xl:grid-cols-4 xl:space-y-0 xl:items-baseline"
        >
          <Date :date="date" />
          <div class="space-y-5 xl:col-span-3">
            <div class="space-y-0">
              <h2 class="text-2xl leading-8 font-bold tracking-tight">
                <a class="text-gray-900 dark:text-white" :href="url">{{
                  title
                }}</a>
              </h2>
              <div
                v-if="excerpt"
                class="prose dark:prose-invert max-w-none text-gray-500 dark:text-gray-300"
                v-html="excerpt"
              ></div>
            </div>
            <div class="text-base leading-6 font-medium">
              <a class="link" aria-label="read more" :href="url">Read more →</a>
            </div>
          </div>
        </article>
      </li>
    </ul>

    <div v-if="filteredPosts.length === 0" class="py-12 text-gray-500">
      No posts found matching "{{ query }}".
    </div>
  </div>
</template>
