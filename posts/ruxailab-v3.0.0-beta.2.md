---

RUXAILAB v3.0.0-beta.2 is now available for testing. This pre-release includes the latest features, improvements, and fixes contributed to the platform and is intended for community validation before the final release.

---

## What's Changed
* Feat chat build by @marcgc21 in https://github.com/ruxailab/RUXAILAB/pull/2248
* chore(deps): bump nanoid from 6.0.0 to 6.0.1 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2254
* chore(deps): bump jsonc-eslint-parser from 2.4.0 to 3.2.0 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2253
* chore(deps): bump the dev-dependencies-safe group with 3 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2252
* chore(deps): bump firebase from 12.16.0 to 12.17.1 in the firebase group by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2251
* chore(deps): bump the vue-ecosystem group with 2 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2250
* chore(functions): align Chat Builder OpenRouter env var names by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2278
* 2161 task review invitation redirects by role by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2279
* fix: redirect root path based on auth state instead of 404 by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2280
* feat: add reusable AI agents module by @mponsa12 in https://github.com/ruxailab/RUXAILAB/pull/2238
* 2232 feature implement protocol number to help identify anonymous answers on studies by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2281
* feat(sessions): when go to session button open new tab by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2282
* feat(session): notify members of session when updates on time or message/description by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2283
* fix(cooperators): fixed reactivity error on staff/participants + added intro for participants + fixed modal behaviour by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2284
* feat(focus-group): per-topic timer and observer notes for the live session by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2263
* fix(auth): prevent infinite recursion on VerifyEmail sign out by @Harshdeep-creator in https://github.com/ruxailab/RUXAILAB/pull/2242
* fix(invite-dialog): guard against null email on clear by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2245
* feat(error-handling): add global ErrorBoundary with fallback UI and structured logging by @HITESH-S-P in https://github.com/ruxailab/RUXAILAB/pull/2216
* feat(sessions): added welcome page on sessions module by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2296
* feat(moderated): added btn for facilitator to bring participants back to video call by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2300
* fix(moderated): return participant to videocall instead of redirect by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2301
* fix(firestore): add missing rules for settings, sessions, and participants collections by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2297
* 2285 feat: invites improve staff/participant and session emails notifications and invitation ux by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2303
* fix(moderator): hid preview option for moderated user study by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2304
* 2306 featnotifications improvement on notifications by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2307
* Refactor videocall by @marcgc21 in https://github.com/ruxailab/RUXAILAB/pull/2308
* Fix transcription by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2309
* Refactor videocall by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2315
* User test improvements by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2310
* chore(deps): bump the dev-dependencies-safe group across 1 directory with 6 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2314
* chore(deps): bump firebase from 12.17.1 to 12.18.0 in the firebase group by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2313
* chore(deps): bump vuetify from 3.13.1 to 3.13.2 in the vue-ecosystem group by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2312
* chore(deps): bump axios from 1.18.1 to 1.19.0 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2294
* chore(deps): bump lint-staged from 15.2.10 to 17.3.0 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2293
* chore(deps): bump yaml-eslint-parser from 1.2.2 to 2.1.0 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2292
* feat(focus-group): stimulus upload and live present by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2288
* feat(focus-group): live participation tracker by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2289
* feat(logging): add trusted study-log ingestion by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2295
* fix(storage): allow unauthenticated participants to upload media into storage for public tests (#2286) by @chirag-gupta-07 in https://github.com/ruxailab/RUXAILAB/pull/2302
* chore: commented study and storage limits by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2316
* 2286 fix improve firestore and storage rules for anonymous users and legacy data by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2319
* fix: resolve password label overlap on sign-in by @Ayushgupta2408 in https://github.com/ruxailab/RUXAILAB/pull/2322
* feat(focus-group): add breakout rooms with per-group video and chat by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2317
* feat(focus-group): add a private facilitator/observer backroom chat by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2318
* fix(firestore): add moderated session group indexes by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2329
* Fix sentiment by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2349
* feat(focus-group): let staff join breakout rooms and call the facilitator by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2330
* feat(logging): Log Explorer by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2338
* feat: implement AI agents for heuristic evaluations by @mponsa12 in https://github.com/ruxailab/RUXAILAB/pull/2277
* fix(utils): harden formatInitials against multi-space names and add formatUtils unit tests by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2333
* fix(auth): send signed out visitors to sign in before a study by @namanjain24-sudo in https://github.com/ruxailab/RUXAILAB/pull/2348
* fix(ux-creation): allow returning to study type options from template list by @Amitesh-exp in https://github.com/ruxailab/RUXAILAB/pull/2352
* fix: keep heuristic action buttons visible with long text by @utsavbhardwaj in https://github.com/ruxailab/RUXAILAB/pull/2356
* feat(focus-group): staff, participants and per-session live rooms by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2331
* fix(pre-test): enforce two options and fix option styling by @pyarchana in https://github.com/ruxailab/RUXAILAB/pull/2358
* fix(UserTest): scope consent decline cleanup to individual participant node by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2363
* chore(deps): bump axios from 1.19.0 to 1.20.0 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2343
* chore(deps): bump the vue-ecosystem group across 1 directory with 3 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2359
* chore(deps): bump the tiptap group with 7 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2365
* chore(deps): bump the dev-dependencies-safe group across 1 directory with 5 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2367
* chore(deps): bump livekit-client from 2.21.0 to 2.22.3 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2366
* chore(deps): bump the vue-ecosystem group with 3 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2369
* chore(deps): bump @vue/test-utils from 2.5.0 to 2.5.1 in the testing group by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2370
* chore(deps): bump firebase from 12.18.0 to 12.19.0 in the firebase group by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2371
* chore(deps): bump cypress from 15.21.0 to 16.1.0 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2373
* chore(deps): bump the dev-dependencies-safe group across 1 directory with 3 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2375
* Fix/linear regression improvements by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2376
* feat(focus-group): post-session answer review and thematic structuring by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2368
* fix(focus-group): improve session invites, privacy, and review flow by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2381
* feat(logging): improve unmoderated study activity logs by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2379
* feat(focus-group): improve guided sessions and invite routing by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2386
* sentiment analitys by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2390
* fix(email): make verification email render correctly across clients by @namanjain24-sudo in https://github.com/ruxailab/RUXAILAB/pull/2384
* Feat/transcription sentiment chart by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2347
* feat(i18n): add locale-aware date formatting composable by @namanjain24-sudo in https://github.com/ruxailab/RUXAILAB/pull/2385
* chore(deps): bump vuetify from 3.13.4 to 3.13.5 in the vue-ecosystem group by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2387
* chore(deps): bump the dev-dependencies-safe group with 4 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2388
* chore(deps): bump wavesurfer.js from 7.12.11 to 7.12.12 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2389
* fix(eye_tracking): resolve timing delay when displaying eye tracking overlay on top of video frame  by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2380
* fix(eye_tracking): allow anonymous users to proceed after calibration  by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2382
* fix(cooperators): style Admin role chip in cooperators table by @SajalDevX in https://github.com/ruxailab/RUXAILAB/pull/2395
* fix(focus-group): polish session collaboration UI by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2398
* feat(studies): fixed moderated & allow the logging. by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2402
* feat(focus-group): implement post-session analysis by @mohi-devhub in https://github.com/ruxailab/RUXAILAB/pull/2418
* feat(logs): add a participant timeline view by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2405
* fix(heuristics): correct heuristic evaluation response flow by @mponsa12 in https://github.com/ruxailab/RUXAILAB/pull/2407
* Improve heuristic AI evaluation workflow by @mponsa12 in https://github.com/ruxailab/RUXAILAB/pull/2431
* fix invite membership and anonymous by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2404
* fix(dashboard): show the next upcoming session on the dashboard card by @SajalDevX in https://github.com/ruxailab/RUXAILAB/pull/2397
* fix(i18n): translate hardcoded strings in Test Details dialog (#2399) by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2400
* chore(deps): bump the dev-dependencies-safe group with 4 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2409
* chore(deps): bump the vue-ecosystem group with 2 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2425
* chore(deps): bump livekit-client from 2.22.3 to 2.22.4 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2426
* chore(deps): bump nanoid from 6.0.1 to 6.0.2 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2427
* fix(backend): Cloud Functions authorization fails for studies using modern studyRoleMap (#2408) by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2410
* fix(rules): require RBAC read check on answers/{id}/analytics subcoll… by @namanjain24-sudo in https://github.com/ruxailab/RUXAILAB/pull/2413
* fix(auth): use correct logout action in signOut handlers by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2419
* fix(security): sanitize rich-text v-html sinks with DOMPurify by @namanjain24-sudo in https://github.com/ruxailab/RUXAILAB/pull/2414
* fix(functions): support Card Sorting studies in getMyStudyAnswer (#2417) by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2422
* fix(a11y): remove redundant aria-hidden from Vuetify field labels by @nothariharan in https://github.com/ruxailab/RUXAILAB/pull/2424
* feat: improve task performance charts and data on global analysis by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2448
* feat(methodologies): Card Sorting & Focus Group by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2450
* feat(logs): add study log overview and server-side export by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2451
* chore(deps): bump the vue-ecosystem group with 3 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2454
* chore(deps): bump dompurify from 3.4.11 to 3.4.17 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2455
* chore(deps): bump jspdf-autotable from 5.0.8 to 5.0.9 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2456
* chore(deps): bump the dev-dependencies-safe group across 1 directory with 4 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2459
* fix(auth): unsubscribe notifications listener on logout by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2453
* fix(style): updates on user study style by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2462
* Feat/queue analysis tasks by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2460
* fix(invites): add authentication and authorization checks in generateInvitationLink by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2441
* fix(auth): pass UID to deleteUserData and use router on account deletion by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2452
* fix(invites): keep an accepted staff membership in the study list of the user by @nothariharan in https://github.com/ruxailab/RUXAILAB/pull/2463
* fix(study): added logic to prevent data overwrites when multiple admins edit study simultaneously by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2465
* fix(auth): prevent unexpected user logouts during sessions and studies (#2446) by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2461
* refactor(user-test): replace screen-share animation with per-browser … by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2490
* feat(analytics): update metrics and descriptions for study efficiency and completion rates by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2485
* fix(testview): keep unmoderated study URLs free of the participant id by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2468
* Fix/testview missing study 404 by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2470
* fix(heuristic): navigate to analytics tab instead of dead route by @namanjain24-sudo in https://github.com/ruxailab/RUXAILAB/pull/2489
* feat(user-test): extend estimated time dashed lines to full chart width by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2491
* feat(analytics): added information icon into graphics by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2497
* feat(analytics): add SUS analytics strings to i18n + separeted max and min sus score from score range card by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2498
* fix(rules): scope queue job reads to the study and the job creator by @namanjain24-sudo in https://github.com/ruxailab/RUXAILAB/pull/2495
* fix(rules): require ownership to update a user document by @namanjain24-sudo in https://github.com/ruxailab/RUXAILAB/pull/2493
* chore(deps): bump livekit-client from 2.22.4 to 2.23.0 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2509
* chore(deps): bump vue-i18n from 11.4.14 to 11.4.16 in the vue-ecosystem group by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2506
* chore(deps): bump chart.js from 4.5.1 to 4.6.1 in the chartjs group by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2507
* fix(user-test): count 67.5 SUS scores in the rating chart by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2504
* fix(profile): allow saving single-field profile updates by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2066
* fix(i18n): add missing max150Characters message by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2512
* Revert "fix(auth): prevent unexpected user logouts during sessions and studies (#2446)" by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2513
* fix(i18n): add missing listTests.unknown message by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2516
* Patch vulnerable dependency resolutions by @KarinePistili with @Copilot in https://github.com/ruxailab/RUXAILAB/pull/2514
* Firebase deploy with current projects by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2518
* fix(card_sorting): fixed error with progress display on active studies card by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2540
* fix(style): padronize padding on create study steppers by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2541
* Refactor(shared): move study steps and recorder components to shared by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2542
* feat(steps): advance or complete pre-test and post-test by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2543
* feat(card_sorting): improved dendrogram visualization by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2546
* feat(card_sorting): added option to export dendrogram as png or latex by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2547
* Feat/session mobile by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2517
* Fix/2478 video audio sync by @tejasveersmatharu-debug in https://github.com/ruxailab/RUXAILAB/pull/2544
* 2474 featuser test add instrument on satisfaction variable by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2548
* feat(card_sorting): rename sorting step label to Card classification by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2549
* 2477 featuser test improve sus visualization by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2550
* fix(community): apply the search text when filtering community studies by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2552
* fix(i18n): use the titles.finalReport key for the final report title by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2523
* feat: added method selected on step 3 of study creation by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2554
* fix(user-test): show a no-audio state instead of offering transcription when no audio was recorded by @aaditiiiii1 in https://github.com/ruxailab/RUXAILAB/pull/2519
* 2536 featcard sorting card category matrix visualization by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2555
* Feat/card sorting by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2553
* 2556-feat(card sorting) display pretest and posttest results + add as filters by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2558
* fix(user-test): show the right day on the answers chart outside UTC by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2562
* fix(eye_tracking): improved logic to close calib screen with anonymous users by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2563
* feat: preview study by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2566
* fix(i18n): nest the Spanish notification type labels under notificationsPage.types by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2565
* fix(functions): throw HttpsError on deleteAuth failure (#2520) by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2545
* feat(logging): added more events to keep up with card sorting study type progress by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2568
* fix(i18n): add the missing Spanish Next Session labels by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2572
* fix(i18n): add the missing Spanish labels on the heuristic summary by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2580
* chore(deps): bump axios from 1.20.0 to 1.21.0 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2576
* chore(deps): bump the dev-dependencies-safe group with 4 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2575
* fix(functions): throw HttpsError on sendEmail failure by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2574
* feat: added new features on the user-test task analysis view by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2582
* Feat/card sorting updates by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2604
* chore(deps): bump the vue-ecosystem group with 2 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2608
* chore(deps): bump the dev-dependencies-safe group with 3 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2609
* chore(deps): bump gsap from 3.15.0 to 3.15.1 by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2610
* chore(deps): bump the dev-dependencies-safe group across 1 directory with 3 updates by @dependabot[bot] in https://github.com/ruxailab/RUXAILAB/pull/2615
* fix(functions): never sweep a call somebody is still connected to by @namanjain24-sudo in https://github.com/ruxailab/RUXAILAB/pull/2521
* #2525: Fix/2525 sorting cards disappear issue by @Utkarsharma7 in https://github.com/ruxailab/RUXAILAB/pull/2570
* fix(sessions): sort the owner and created columns of the sessions table by @SajalDevX in https://github.com/ruxailab/RUXAILAB/pull/2584
* fix(i18n): localize Heuristic Final Report hardcoded EN/ES strings (#2596) by @Utkarsharma7 in https://github.com/ruxailab/RUXAILAB/pull/2597
* fix(user-test): skip the consent for a returning participant who already accepted it by @tejasvasingh2004 in https://github.com/ruxailab/RUXAILAB/pull/2591
* fix: verify caller identity in resolveInvite and protect private invites by @AYUSH-P-SINGH in https://github.com/ruxailab/RUXAILAB/pull/2592
* fix(recorder): save the moderator audio recording by @iamtanishqjain in https://github.com/ruxailab/RUXAILAB/pull/2599
* fix(card-sorting): upload card and category images to Storage by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2607
* fix(card-sorting): reject duplicate card and category names in the editor by @tim48-robot in https://github.com/ruxailab/RUXAILAB/pull/2614
* Chore/update to node 24 by @KarinePistili in https://github.com/ruxailab/RUXAILAB/pull/2619
* fix(auth): show an error when password reset or verification email fails(#2616) by @Utkarsharma7 in https://github.com/ruxailab/RUXAILAB/pull/2617
* Patch high-severity dependency vulnerabilities by @KarinePistili with @Copilot in https://github.com/ruxailab/RUXAILAB/pull/2620
* Fix/optimize performance by @JulioManoel in https://github.com/ruxailab/RUXAILAB/pull/2625

## New Contributors
* @tejasveersmatharu-debug made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2280
* @Harshdeep-creator made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2242
* @HITESH-S-P made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2216
* @chirag-gupta-07 made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2302
* @Ayushgupta2408 made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2322
* @AYUSH-P-SINGH made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2333
* @namanjain24-sudo made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2348
* @Amitesh-exp made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2352
* @utsavbhardwaj made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2356
* @pyarchana made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2358
* @SajalDevX made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2395
* @nothariharan made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2424
* @iamtanishqjain made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2504
* @KarinePistili with @Copilot made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2514
* @aaditiiiii1 made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2519
* @Utkarsharma7 made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2570
* @tejasvasingh2004 made their first contribution in https://github.com/ruxailab/RUXAILAB/pull/2591

**Full Changelog**: https://github.com/ruxailab/RUXAILAB/compare/v3.0.0-beta.1...v3.0.0-beta.2

## Try It

You can find the complete release, source code, and additional information on GitHub.

**Release**: [v3.0.0-beta.2](https://github.com/ruxailab/RUXAILAB/releases/tag/v3.0.0-beta.2)

---

Thanks to everyone who contributed to this release.
