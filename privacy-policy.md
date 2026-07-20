---
title: DexFuel Privacy Policy
permalink: /privacy-policy/
---

# DexFuel Privacy Policy

Last updated: July 20, 2026

DexFuel is designed as a local-first nutrition, fitness, and habit tracking app. The core app works without an account.

DexFuel does not include third-party ads and does not use tracking for advertising.

## Information Stored On Your Device

DexFuel may store your profile, nutrition targets, food logs, workout logs, saved foods, saved meals, recipe favorites, weight entries, step summaries, recorded outdoor routes, imported GPX routes, offline-map references, and optional peptide schedules on your device.

Rescue Mode private notes are used to build the on-screen plan and are not saved as raw text.

## Motion, Location, And Health Data

If you enable step tracking, DexFuel reads step count from Apple Health when available so it can match the Health app total across iPhone and Apple Watch sources. If Apple Health is unavailable, DexFuel may use the device motion sensor as a fallback. Step data is used for in-app coaching and is not sold or used for advertising.

If you start an outdoor activity, DexFuel uses precise location while recording—and, with your permission, in the background—to create the route, distance, pace, speed, and elevation summary. Route recording stops when you finish or discard the activity. You may optionally save completed workouts and routes to Apple Health.

The Health Signals and Rest & Recovery views can read only the Apple Health categories you approve, including steps, sleep sessions, resting heart rate, heart-rate variability (HRV), cardio fitness, active energy, weight, cycling power, and workout context. DexFuel uses these values to show movement and recovery context; it does not diagnose a condition or invent missing values. Apple Health access can be changed in iOS Settings.

If you use Mapbox maps, the Mapbox SDK requests map resources and may process technical network and map-usage information under Mapbox's terms. Offline outdoor or satellite regions are downloaded only when you request them. Satellite imagery is map imagery, not satellite communication or emergency coverage.

## Optional Online Features

If online food import is enabled and you use it, DexFuel sends your search text or barcode to Open Food Facts. When the production server has USDA search enabled, food search text is sent through the DexFuel proxy to USDA FoodData Central; the USDA service key remains on the server. These services process the request under their own privacy terms.

If you allow cloud Dex AI, DexFuel sends your prompt plus only the relevant profile, target, recent log, and schedule context needed for the requested feature to the DexFuel AI proxy. Your locally entered profile name and the peptide-feature flag are removed before online processing. The proxy sends the request to the configured third-party AI processor. The current planned processor is WandGX (`llm.wandgx.com`). You can keep cloud Dex AI off and use local coaching rules.

If photo macro estimates are enabled in a build and you choose to use them, DexFuel may send selected meal photo data to the configured DexFuel AI service for processing. Photo estimates must be reviewed before logging.

If you allow cloud Dex AI, DexFuel may send a logged meal name and ingredient list through its proxy to WandGX to create a representative meal image. Generated image bytes return through the proxy and are saved as a local app file; the provider credential is not included in the app. If your iPhone and custom DexFuel build support Apple Image Playground, meal image creation may instead use Apple on-device image generation. When generation is unavailable, DexFuel uses a curated static meal image.

## Health And Fitness Data

DexFuel uses health, nutrition, fitness, and peptide schedule information only to provide tracking, planning, and educational coaching inside the app. DexFuel does not sell this information and does not use it for advertising or tracking.

DexFuel does not send Apple Health data online merely because Apple Health is enabled. Health, fitness, or profile context leaves the device only when it is relevant to an online feature you explicitly allowed and requested.

## Processing And Retention

The DexFuel proxy is designed not to intentionally persist AI prompt bodies, photos, or responses at the application layer. It temporarily processes request data to return the requested result. Short-lived network-address counters are held in memory for abuse prevention and expire automatically. A production hosting provider may process limited security and network logs according to the deployment configuration.

The configured third-party AI processor may process request content to return the result. DexFuel does not use submitted content to build advertising profiles. Before a production AI deployment changes processors or retention settings, this policy and the App Store privacy answers must be updated.

## Peptide Tracking

Peptide tracking is user-entered schedule support only. DexFuel does not prescribe peptides, dosing, injections, treatment plans, or medical decisions.

## Data Deletion

You can clear local DexFuel data from the app in Profile > Clear data. You can turn cloud Dex AI sharing on or off in Privacy & Data.

DexFuel has no required account and the application proxy does not intentionally maintain a user prompt history. For questions about an online request or a deletion request involving production service records, use the support contact below.

More privacy controls are described in the DexFuel privacy choices page.

## Contact

Support: https://guccigross.github.io/DexFuel-site/support/

## Nutrition Data Attribution

Product information may be provided by Open Food Facts under its applicable open database and contents licenses. USDA FoodData Central data is provided by the United States Department of Agriculture. Imported values can be incomplete or inaccurate; verify the product label before relying on them.
