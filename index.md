---
layout: default
---

<p align="center">
  <img src="assets/icon_master_1024.png" alt="RecoveryIQ Logo" width="150" height="150" />
</p>

# RecoveryIQ

<p align="center">
  <strong>Precision Recovery. Built for Serious Lifters.</strong>
</p>

<p align="center">
  <a href="https://apps.apple.com/us/app/recoveryiq/id6759882173">
    <img src="https://img.shields.io/badge/Download_on_the-App_Store-0D96F6?style=for-the-badge&logo=apple&logoColor=white" alt="Download on the App Store" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/App_Version-1.0.0-blue.svg" alt="App Version" />
  <img src="https://img.shields.io/badge/Docs_Version-1.0-green.svg" alt="Docs Version" />
  <img src="https://img.shields.io/badge/Platform-iOS-lightgrey.svg" alt="Platform iOS" />
  <img src="https://img.shields.io/badge/Data-100%25_On--Device-brightgreen.svg" alt="Data On-Device" />
</p>

---

![Dashboard](assets/dashboard_web.png)

RecoveryIQ is an advanced iOS application designed for dedicated lifters, bodybuilders, and athletes who want to optimize their training based on their body's actual physiological readiness. By integrating seamlessly with Apple HealthKit and Apple Watch, the app translates raw biometric data—such as Heart Rate Variability (HRV), Resting Heart Rate (RHR), and Sleep Quality—into actionable, muscle-specific insights.

**No account. No cloud. No subscriptions. All your data stays on your iPhone.**

---

## Table of Contents

1. [Features](#features)
2. [Key Metrics Explained](#key-metrics-explained)
3. [Requirements](#requirements)
4. [Privacy & Your Data](#privacy--your-data)
5. [Getting Started](#getting-started)
   - [First Launch & Permissions](#first-launch--permissions)
   - [Setting Up Your Profile](#setting-up-your-profile)
   - [Calibration Period](#calibration-period)
6. [How to Use RecoveryIQ](#how-to-use-recoveryiq)
   - [Step 1 — Morning Check-In](#step-1--morning-check-in)
   - [Step 2 — Pre-Workout Review](#step-2--pre-workout-review)
   - [Step 3 — After Your Workout: Enriching Apple Watch Data](#step-3--after-your-workout-enriching-apple-watch-data)
   - [Step 4 — Tracking Progress Over Time](#step-4--tracking-progress-over-time)
7. [The Muscles Screen & Recovery Map](#the-muscles-screen--recovery-map)
   - [How the Recovery Map Works](#how-the-recovery-map-works)
   - [Color Guide](#color-guide)
   - [Tapping a Muscle for Details](#tapping-a-muscle-for-details)
8. [App Screens Reference](#app-screens-reference)
9. [Settings & Personalization](#settings--personalization)
10. [Real-World Scenarios](#real-world-scenarios)
    - [Scenario 1: The PPL Lifter Navigating a Fatigued Week](#scenario-1-the-ppl-lifter-navigating-a-fatigued-week)
    - [Scenario 2: The Watch-First Athlete](#scenario-2-the-watch-first-athlete)
    - [Scenario 3: Catching Overtraining Before It Catches You](#scenario-3-catching-overtraining-before-it-catches-you)
    - [Scenario 4: New to the App — The First 30 Days](#scenario-4-new-to-the-app--the-first-30-days)
11. [Understanding Your Readiness Score](#understanding-your-readiness-score)
12. [Frequently Asked Questions](#frequently-asked-questions)

---

## Features

### Daily Readiness Score
![Signals](assets/signals_web.png)

Stop guessing if you've fully recovered. RecoveryIQ processes your overnight biometrics to calculate a daily Readiness Score (0–100), accompanied by intelligent guidance on whether you should push hard, focus on lighter work, or prioritize rest. The app also tracks your Acute:Chronic Workload Ratio (ACWR) to warn you if you're overreaching.

### Intelligent Muscle Tracking
![Muscles](assets/muscles_web.png)

Unlike standard fitness apps, RecoveryIQ tracks fatigue at the individual muscle group level. After you enrich your Apple Watch workouts with muscle data, the app's advanced DOMS (Delayed Onset Muscle Soreness) decay model visually displays which muscles are fully recovered, moderately fatigued, or need more rest. Get specific recommendations on which exercises to avoid based on your localized fatigue state.

### Comprehensive History & Trends
![History](assets/history_web.png)

Analyze your progress over time with detailed 30-day, 90-day, and 365-day trend charts. Cross-reference your physiological readiness scores against your logged workout intensity to discover your optimal training conditions. Learn exactly how many consecutive training days your body can handle before performance drops.

---

## Key Metrics Explained

To get the most out of RecoveryIQ, it helps to understand the core metrics it tracks and why they matter:

**Readiness Score (0–100):** A composite score reflecting your overall physiological state for the day. A score above 75 means you're primed for a hard workout. A score below 50 suggests prioritizing active recovery or rest. Calculated from your overnight HRV, Resting Heart Rate, Sleep Quality, and training workload.

**Heart Rate Variability (HRV):** The variation in time between each heartbeat. Higher HRV generally indicates that your autonomic nervous system is recovered and ready to handle training stress. RecoveryIQ tracks your HRV relative to your personal rolling 30-day baseline and computes a z-score deviation to detect meaningful changes.

**Resting Heart Rate (RHR):** The number of times your heart beats per minute while at complete rest. An unusually elevated RHR can be an early indicator of incomplete cardiovascular recovery, accumulated fatigue, or an oncoming illness.

**Acute:Chronic Workload Ratio (ACWR):** A measure of your training load balance. It compares your recent 7-day training intensity (acute) to your historical 28-day training intensity (chronic). An ACWR between 0.8 and 1.3 is the optimal "sweet spot." An ACWR above 1.5 signals elevated overtraining or injury risk.

**Delayed Onset Muscle Soreness (DOMS) Estimate:** Not just how sore you *feel* — this is a mathematical decay model of how fatigued a specific muscle group is, based on workout intensity, time elapsed, and your global readiness. Each muscle has its own half-life: large muscles like Chest, Quads, Lats, and Glutes take the longest to recover (60h half-life), medium muscles like Hamstrings and Delts take 48h, and smaller accessory muscles like Biceps and Triceps recover faster (36h half-life).

**Estimated 1-Rep Max (e1RM):** Calculated using the Epley formula (`Weight × (1 + Reps ÷ 30)`). Tracking this over time reveals your strength trajectory even when rep ranges vary session to session.

---

## Requirements

- iPhone running **iOS 17** or later
- **Apple Watch** (Series 4 or later recommended) for automatic biometric capture (HRV, RHR, sleep)
- **Apple Health** app with data sharing enabled for RecoveryIQ
- The built-in **Workout** app (or any HealthKit-compatible app) for logging training sessions on your Watch

> The Muscles screen and DOMS recovery model require you to enrich your Watch-logged workouts with muscle group data inside RecoveryIQ. The richer your input, the more accurate your recovery map.

---

## Privacy & Your Data

RecoveryIQ was built with a clear philosophy: **your health data belongs to you and only you.**

- **No account required.** You never create a login or provide an email address.
- **No cloud sync.** Nothing is transmitted to any server, ever.
- **No ads.** Your data is not monetized or shared with third parties.
- **100% on-device.** All biometrics, workout history, and recovery calculations live in an encrypted local SQLite database on your iPhone.
- **No internet connection needed.** The app functions fully offline at all times.

If you delete the app, your local data is removed with it. There is no recovery from an external backup — so treat it like any important local file.

---

## Getting Started

### First Launch & Permissions

When you open RecoveryIQ for the first time, you will be prompted to grant **Apple HealthKit permissions**. This is essential for the app to read your biometric data. You should enable access for:

- Heart Rate Variability (HRV)
- Resting Heart Rate
- Sleep Analysis
- Workouts
- Active Energy / Heart Rate

You can review and adjust these permissions at any time in **iPhone Settings → Privacy & Security → Health → RecoveryIQ**.

### Setting Up Your Profile

Before the app can give you personalized guidance, head to the **Settings** tab and fill in your profile. This information improves the accuracy of recovery calculations and contextual recommendations:

- **Age** — used to adjust baseline expectations for HRV and RHR norms.
- **Biological Sex** — factors into physiological baseline modeling.
- **Training Experience** — choose from Beginner, Intermediate, or Advanced. More experienced athletes recover differently from the same stimulus.
- **Supplements** — toggle which recovery-relevant supplements you regularly take (e.g., creatine, magnesium). This provides context for the insight engine.

None of this information ever leaves your device.

### Calibration Period

RecoveryIQ needs at least **7 days of biometric data** to establish your personal baseline for HRV and RHR, and **30 days** to reach full confidence in its readiness calculations. During this period:

- The app will still show you data and scores, but they'll be anchored to population norms rather than your personal baseline.
- A confidence multiplier gradually ramps up from 60% on Day 1 to 100% on Day 30+, pulling your readiness score closer to a neutral 50 while calibration is ongoing.
- The more consistently you wear your Apple Watch to sleep, the faster this calibration improves.

**The app is most powerful after 30 days of consistent use.** Wear your Watch, log your workouts, and let the baseline build.

---

## How to Use RecoveryIQ

### Step 1 — Morning Check-In

Your day with RecoveryIQ starts the moment you wake up — even before you touch the app. Your Apple Watch has been silently collecting HRV, RHR, and sleep stage data overnight. When you open RecoveryIQ, it syncs this data from Apple Health automatically.

**On the Dashboard you'll see:**

- Your **Readiness Score** — a single number telling you how recovered you are today.
- **KPI cards** for HRV, RHR, Sleep, and ACWR, each with a 7-day sparkline showing your trend.
- An **Insight Card** that translates your metrics into a plain-English recommendation ("HRV is slightly below baseline — train at 70–80% intensity today").
- A **muscle fatigue strip** showing your most impacted muscles at a glance.

> **Tip:** Check the Insight Card color. Green means go hard, amber means train smart, red means rest is the priority.

---

### Step 2 — Pre-Workout Review

Before heading to the gym, tap the **Muscles** tab. This is your pre-workout intelligence briefing.

The full-body recovery map shows all 18 tracked muscle groups color-coded by their current recovery state. Before committing to today's planned split, ask yourself: are the muscles I'm planning to train actually ready?

- If you planned a **Push day** but your Front Delts are still glowing orange from two days ago, you can pivot to a chest-heavy session and swap heavy overhead pressing for lighter lateral work.
- If your **Quads** are red and you're considering legs, the app will suggest exercises to avoid (heavy squats, leg press) and safe alternatives that don't load those patterns.

This is where RecoveryIQ pays dividends — turning a rigid program into an intelligent, responsive one.

---

### Step 3 — After Your Workout: Enriching Apple Watch Data

This is the most important step for unlocking the full power of RecoveryIQ, and it's unique to how the app is designed.

**Here's how it works:**

Your Apple Watch automatically logs your training session via the built-in Workout app. You select your workout type (Strength Training, HIIT, etc.), start the timer, train, and end the session. The Watch captures duration, heart rate zones, active calories, and more — and syncs everything to Apple Health.

However, your Watch has no idea *which muscles you trained* or *how hard it felt*. That's the missing piece. RecoveryIQ lets you add that context after the fact.

**Step-by-step:**

1. **Open the History tab** and switch to the **Workouts** view. You'll see today's Apple Watch session already appears, synced from Health.
2. **Tap "Edit Details"** on the workout card. A sheet slides up.
3. **Select your muscle groups.** Tap each muscle you targeted (e.g., Chest, Triceps, Front Delts for a push day). RecoveryIQ tracks 18 muscle groups organized into Push, Pull, Legs, Shoulders, and Core categories.
4. **Set your RPE (Rate of Perceived Exertion)** on a 1–10 scale. This directly scales the DOMS magnitude — an RPE 8 chest session creates ~80% of max possible fatigue, while an RPE 4 pump session creates only ~40%.
5. **Rate your Session Feel** — a qualitative tag (💀 Destroyed → 💪 Great) that helps you correlate subjective performance against your readiness score over time.
6. **(Optional but recommended) Log your Top Set.** Select a muscle, enter your working weight and reps. The app instantly calculates your estimated 1-Rep Max using the Epley formula. If it's a PR, you'll see a 🏆 badge. This unlocks the **Performance tab** in History, showing your e1RM trend week-over-week.
7. **Tap Save.** RecoveryIQ immediately updates the DOMS model for every muscle you selected, recomputes your recovery percentages, and the body map updates on the Muscles screen.

> **Why this matters:** Without this enrichment step, the Muscles screen has nothing to show. Once you complete it, the Recovery Map comes alive — and by the next morning, the muscles you trained will correctly appear as yellow or amber, telling you they're still recovering. Train over them anyway and they'll accumulate DOMS toward red.

---

### Step 4 — Tracking Progress Over Time

On rest days or at the end of the week, open the **History** tab to review your patterns.

- The **Recovery tab** shows a bar chart of your daily Readiness Scores over 30, 90, 180, or 365 days. Look for the 💪 markers — those are days you trained. Do your scores consistently dip after 4 consecutive training days? That's your personal limit.
- The **Workouts tab** shows a calendar heatmap of your sessions. Tap any day to see the full detail — what muscles you targeted, your RPE, feel rating, and what your Readiness Score was that morning.
- The **Performance tab** shows your e1RM trend per muscle group over the last 12 weeks. This is your long-term strength curve — are you getting stronger, plateauing, or regressing?
- The **Signals screen** shows 90-day charts for HRV, RHR, and Sleep. Check the ACWR zone bar — if the white pip is drifting into the Caution (1.3–1.5) or Danger (>1.5) zone, it's time to reduce volume.

---

## The Muscles Screen & Recovery Map

The Muscles screen is RecoveryIQ's signature feature. It's a full-body silhouette (front and back view) where each of the 18 tracked muscles is colored to reflect its current recovery state.

### How the Recovery Map Works

The Recovery Map is **driven entirely by your workout enrichment data**. Here's the data pipeline:

1. You complete a workout on your Apple Watch.
2. Apple Watch syncs session data to Apple Health.
3. RecoveryIQ reads that session from HealthKit (duration, heart rate, calories).
4. You open RecoveryIQ and tap **Edit Details** on the workout to add muscle groups, RPE, and optionally a Top Set.
5. RecoveryIQ runs the DOMS decay model for each selected muscle, anchored to a 24-hour peak (soreness typically peaks ~24 hours after training) and decaying exponentially using muscle-specific half-lives.
6. If your global Readiness Score is below 60 that day, the decay rate slows by 30% — because your body is less efficient at recovering when it's already under stress.
7. The body map updates in real time.

**Without enrichment data, the muscles remain uncolored.** The more sessions you enrich, the more accurate and complete your recovery map becomes.

### Color Guide

| Color | Recovery % | Meaning |
|---|---|---|
| 🟢 Bright Green | 90–100% | Fully Recovered — ready to train hard |
| 🟢 Light Green | 75–90% | Good — ready for normal training |
| 🟡 Yellow | 60–75% | Moderate — train at reduced intensity |
| 🟠 Orange | 40–60% | Caution — avoid direct heavy work |
| 🔴 Red | 0–40% | High Fatigue — rest this muscle group |

### Tapping a Muscle for Details

Tap any muscle on the body map to open a detail panel showing:

- **Recovery %** and **DOMS %**
- **Last Trained** (Today / Yesterday / X days ago)
- **Session Intensity** (RPE you logged)
- **Estimated Ready In** (hours until the muscle crosses back into green)
- **Exercises to Avoid** — specific movements that heavily load this muscle
- **Safe Exercises** — movements that spare the fatigued muscle while still allowing productive training

---

## App Screens Reference

| Screen | What it Shows |
|---|---|
| **Dashboard** | Readiness Score gauge, HRV / Sleep / RHR / ACWR KPI cards, daily insight text, 7-day readiness bar chart, muscle fatigue strip |
| **Signals** | 90-day trend charts for HRV, RHR, and Sleep; ACWR zone indicator |
| **Muscles** | Interactive full-body recovery map — tap any muscle for DOMS %, recovery ETA, exercise guidance |
| **History → Recovery** | Bar chart of daily readiness scores (30D / 90D / 180D / 365D) with workout markers |
| **History → Workouts** | Calendar heatmap of training sessions; tap any session to see full detail |
| **History → Performance** | Weekly e1RM trend per muscle group (last 12 weeks); 90-day volume breakdown |
| **Settings** | Personal profile (age, sex, training experience), supplement toggles, HealthKit permissions |

---

## Settings & Personalization

Navigate to the **Settings** tab to configure your profile and personalize how RecoveryIQ interprets your data.

**Profile fields:**
- **Age** — affects HRV norm expectations (HRV naturally declines with age; the app accounts for this).
- **Biological Sex** — used in baseline adjustments.
- **Training Experience Level** — Beginner, Intermediate, or Advanced. Advanced lifters often have higher baseline HRV and recover more efficiently, so the model adjusts accordingly.

**Supplement Toggles:**
Toggle the supplements you regularly take. This gives the insight engine additional context when generating recovery guidance. Supplements tracked include common recovery aids like creatine, magnesium, and others.

> All settings are stored locally. Changing your profile immediately affects future readiness calculations — it does not retroactively alter your history.

---

## Real-World Scenarios

### Scenario 1: The PPL Lifter Navigating a Fatigued Week

**Alex** runs a Push/Pull/Legs split, 6 days a week. It's Thursday — technically a Push day — but Alex had a grueling leg session on Tuesday and a heavy pull day on Wednesday.

1. **Morning:** Alex opens RecoveryIQ. Readiness Score: **58** (amber zone). The insight reads: *"HRV 1.2 SD below baseline. Elevated training load — reduce intensity today."*
2. **Muscles screen:** Front Delts: 🟠 Orange (52% recovered). Chest: 🟢 Light Green (78% recovered). Triceps: 🟢 Bright Green (91% recovered). Quads: 🔴 Red (31% recovered).
3. **Plan adjustment:** Alex taps Front Delts. The "Exercises to Avoid" list includes Overhead Press and Arnold Press. The "Safe Exercises" list shows Chest Flys, Cable Crossovers, Tricep Pushdowns.
4. **Session:** Alex runs a chest-and-triceps focused push day, skipping all heavy shoulder pressing. RPE ends up at 7.
5. **Post-workout enrichment:** Alex opens History, taps Edit Details, selects Chest and Triceps, sets RPE 7, logs a Top Set of 225 lbs × 6 on Bench. e1RM calculates to **270 lbs**. 🏆 PR detected.
6. **Next morning:** Chest is now 🟡 Yellow, Triceps 🟢 Light Green. The map accurately reflects what was trained.

---

### Scenario 2: The Watch-First Athlete

**Jordan** never manually logs workouts — they rely entirely on their Apple Watch to auto-detect sessions. RecoveryIQ is built for this workflow.

1. Jordan completes a Back & Biceps session tracked on Apple Watch: 62 min, average HR Zone 3.
2. Opens RecoveryIQ → History → Workouts. The session is already there (synced from Health).
3. Taps **Edit Details**: selects Lats, Upper Back, Rear Delts, Biceps. Sets RPE 8. Logs Top Set: Lat Pulldown, 200 lbs × 5. e1RM: **233 lbs**.
4. Saves. The Muscles screen now shows Lats 🟠 Orange, Biceps 🟡 Yellow — correctly reflecting the session intensity.
5. Next day Jordan checks before training. The app suggests avoiding heavy rows and direct bicep curls. Jordan pivots to a chest and legs session instead — muscles that are fully green.

This is the intended primary workflow: **Watch records → Health syncs → RecoveryIQ enriches.**

---

### Scenario 3: Catching Overtraining Before It Catches You

**Morgan** has been training hard for 5 straight weeks without a deload. Everything feels fine subjectively — but the numbers are telling a different story.

1. Morgan's Readiness Score has been sitting between 48–55 for 8 days straight.
2. The **Signals screen** shows ACWR at **1.48** — just below the danger threshold, but the trend line is pointing up.
3. The Dashboard Insight card reads: *"Acute workload is elevated. HRV has trended downward for 6 consecutive days. A deload or rest day is strongly recommended."*
4. Morgan opens **History → Recovery**. The chart shows a clear downward trend in readiness scores over the last 3 weeks, with 💪 markers on almost every bar. There are almost no rest days.
5. Morgan schedules a full deload week — lower weight, higher reps, no sessions to failure. After 5 days, Readiness climbs back to **74**. HRV recovers. ACWR drops to **1.1**.

RecoveryIQ didn't prevent overtraining — Morgan did, by trusting the data over the ego.

---

### Scenario 4: New to the App — The First 30 Days

**Sam** just downloaded RecoveryIQ after years of training by feel.

- **Week 1:** The readiness scores seem a little flat — hovering around 55–65 regardless of how Sam feels. This is normal. The app is in calibration mode, blending Sam's emerging baseline with population norms. Sam wears their Watch every night and enriches every workout.
- **Week 2:** The scores start to diverge meaningfully. On a day after poor sleep (5.5 hrs, no deep sleep), the score drops to 44. Sam skips the planned heavy session and does a light active recovery day instead.
- **Week 3:** Sam notices a pattern in the History tab — Readiness Scores are consistently 10+ points lower after back-to-back leg days. The quads and hamstrings are slow recoverers for Sam's body.
- **Day 30:** Full confidence unlocked. Sam now has a personalized baseline for HRV and RHR. The app's recommendations feel "tuned" — and for the first time, Sam trains with objective data instead of guesswork.

**The lesson:** The first month is an investment. The more you use it, the smarter it gets.

---

## Understanding Your Readiness Score

RecoveryIQ's Readiness Score is not arbitrary — it's a weighted composite of four physiological signals that update based on data availability:

**When workouts are logged:**

| Signal | Weight |
|---|---|
| HRV Score | 40% |
| ACWR Score | 30% |
| Sleep Score | 20% |
| RHR Score | 10% |

**On days with no workout history (biometrics only):**

| Signal | Weight |
|---|---|
| HRV Score | 50% |
| Sleep Score | 30% |
| RHR Score | 20% |

**Training Zones:**

| Score | Zone | Guidance |
|---|---|---|
| 75–100 | 🟢 Go Hard | Your body is primed. Push intensity, add volume, test PRs. |
| 50–74 | 🟡 Train Smart | Train, but manage intensity. Focus on recovered muscle groups. |
| 0–49 | 🔴 Rest | Prioritize sleep, nutrition, and active recovery over the gym. |

---

## Frequently Asked Questions

**Do I need an Apple Watch?**
An Apple Watch is strongly recommended. Without it, RecoveryIQ cannot read overnight HRV or sleep stage data, which significantly limits the accuracy of your Readiness Score. The app can still function with manually-logged workouts, but the biometric half of the score will be unavailable.

**Why is my Muscles screen blank?**
The Recovery Map only populates after you enrich at least one workout with muscle group data. Complete a workout on your Apple Watch, then open History → Workouts, tap the session, and tap "Edit Details" to select muscle groups and set your RPE.

**How accurate is the DOMS model?**
The model is based on established sports science research — exponential decay from a 24-hour post-workout peak, with muscle-specific half-lives. It's not a direct measure of soreness, but a physiological estimate. Your subjective RPE logging directly influences the model's output — higher RPE = more aggressive DOMS curve.

**Will the app work without an internet connection?**
Yes, completely. RecoveryIQ has no network dependency whatsoever. All data processing, calculations, and storage happen entirely on your iPhone.

**Can I use RecoveryIQ without logging workouts at all?**
Yes. The app will still provide a biometric-based Readiness Score from your HRV, RHR, and sleep data. The Muscles screen will be unavailable, and ACWR will show as pending — but the Dashboard and Signals screens will be fully functional.

**What happens if I miss a few days of wearing my Watch?**
RecoveryIQ uses a rolling 3-day trailing sync window with a +6-hour time boundary shift, meaning it handles gaps gracefully. Missing days appear as gaps in charts rather than distorting your trends. Your baseline will not degrade from occasional gaps.

**Is my data backed up anywhere?**
No. All data is stored locally in an on-device SQLite database. If you delete the app or replace your iPhone without transferring data, your history will be lost. There is currently no iCloud backup integration.

---

<p align="center">
  <a href="https://apps.apple.com/us/app/recoveryiq/id6759882173">
    <img src="https://img.shields.io/badge/Download_on_the-App_Store-0D96F6?style=for-the-badge&logo=apple&logoColor=white" alt="Download on the App Store" />
  </a>
</p>

<p align="center">
  <em>Built for athletes who know that recovery is training too.</em>
</p>
