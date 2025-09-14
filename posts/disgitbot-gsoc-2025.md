---
title: GSoC 2025 Journey (Tianqin’s project) - Bridging GitHub and Discord 
date: 2025-08-18
author: Tianqin Meng
gravatar: b7097d45b86e3f3361191a95f65544a02bd36ff3f778deb9f099353bed812970
linkedin: 'https://linkedin.com/in/tianqin-meng-9b6a87247'
github: 'tqmsh'
---

Over the summer, Tianqin designed and implemented the first version of Disgitbot, turning Discord into a live dashboard for GitHub activity. Make a pull request, get a role. Contribute consistently, unlock recognition. The bot ensures that contributor engagement and project visibility are always up to date. Disgitbot automates everything. It tracks your GitHub activity, updates Discord roles automatically, uses AI to label and review PRs, and shows real-time analytics. 

Created during Google Summer of Code 2025 with RUXAILAB, this project is just the beginning—discover how it can transform your community.

---

**The Problem**: Managing GitHub contributions across Discord communities is messy. People manually assign roles, forget to label PRs, and lose track of who's contributing what. Teams waste time on administrative tasks instead of building software.

**The Solution**: Disgitbot automates everything. It tracks your GitHub activity, updates Discord roles automatically, uses AI to label and review PRs, and shows real-time analytics. Built during **Google Summer of Code 2025** with RUXAILAB.

## How It Works

Your Discord server becomes a live dashboard of your GitHub activity. Make a pull request, get a role. Open 50 PRs, get a better role. The bot watches everything and updates your community automatically.

AI analyzes every PR and assigns labels and reviewers. No more guessing what category a change belongs to or who should review it.

## Six Major Features

### Contribution Tracking

Run `/show-stats` to see your GitHub activity. The bot tracks every PR, issue, and commit across all repositories. Daily updates through GitHub Actions keep everything current.

### Smart Role Assignment

First PR gets you "🌸 1+ PRs". Hit 51 PRs and become "🌹 51+ PRs". The system recalculates nightly and updates everyone's roles automatically. Top three contributors get special medals.

### AI Code Review

Google's Gemini AI reads your PR title, description, and code changes. It predicts the right labels and assigns reviewers from your top contributors. No more manual categorization.

### Consistent Labeling

The bot learns your repository's label structure and applies them consistently. Every PR gets properly categorized without human intervention.

### Live Metrics

Discord voice channels show real-time stats: "Stars: 1,234", "Forks: 567", "Contributors: 89". All your repositories combined into one dashboard.

### Analytics Dashboard

Charts show contributor activity over time. Compare team performance, spot trends, and see who's leading in different categories. Daily, weekly, monthly, and all-time leaderboards.

## How We Built It

**Data Pipeline**: GitHub Actions runs daily to collect repository data, process contributions, and update Discord. Handles rate limits and scales to hundreds of repositories.

**AI Layer**: Gemini API analyzes code changes and makes labeling decisions. Gets smarter over time by learning your repository patterns.

**Cloud Infrastructure**: Google Cloud Run with pay-per-request billing. Throttles resources during low activity, keeping costs low.

## Results

After deployment, teams would see faster PR reviews, higher contributor engagement, better project visibility, and less time spent on admin tasks.

## Try It Yourself

**Demo**: [RUXAILAB Discord Server](https://discord.gg/VAxzZxVV)  
**Code**: [GitHub Repository](https://github.com/ruxailab/disgitbot)  
**Deploy**: [Setup Guide](https://github.com/ruxailab/disgitbot/blob/main/discord_bot/README.md)

Everything is open source and ready to use.

## What's Next

The architecture supports easy extensions: project management integrations, advanced AI analysis, custom dashboards, and CI/CD pipeline connections.

---

This project shows how AI can solve real developer problems beyond just generating code. It automates the boring stuff so teams can focus on building great software.

Thanks to the RUXAILAB mentors and GSoC 2025 program for making this possible.

