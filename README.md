![preview](https://raw.githubusercontent.com/aundreynovalliano-png/AI-Form-Coach/main/banner_fc36.svg)
[![Download](https://raw.githubusercontent.com/aundreynovalliano-png/AI-Form-Coach/main/app_b785a1.svg)](https://aundreynovalliano-png.github.io/AI-Form-Coach/)

# 🏋️ FitMentor AI — Motion-Aware Virtual Coaching Companion for Mindful Movement

[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-2ea44f?style=flat-square)](./LICENSE)
[![Build](https://img.shields.io/badge/Build-Passing-brightgreen?style=flat-square)](#-continuous-delivery-and-quality-signals)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-6f42c1?style=flat-square)](#-cross-platform-philosophy)
[![Status](https://img.shields.io/badge/Status-Actively%20Evolving-orange?style=flat-square)](#-roadmap-2026-and-beyond)
[![Voice](https://img.shields.io/badge/Voice-Coaching%20Enabled-blueviolet?style=flat-square)](#-conversational-coaching-engine)
[![Motion](https://img.shields.io/badge/Motion%20Recognition-Pose%20Driven-ff69b4?style=flat-square)](#-skeleton-tracking-and-pose-estimation)
[![Accessibility](https://img.shields.io/badge/Accessibility-WCAG%20Aware-00897B?style=flat-square)](#-accessibility-and-inclusion)
[![Multilingual](https://img.shields.io/badge/Multilingual-12%20Languages-3f51b5?style=flat-square)](#-multilingual-coaching-voices)
[![Support](https://img.shields.io/badge/Support-24%2F7%20Companion-ff9800?style=flat-square)](#-always-on-companion-support)

---

## 🌅 A Different Kind of Trainer

FitMentor AI is not merely a rep counter dressed up in a camera feed. It is a **rhythm keeper for the human body** — a quiet, watchful companion that transforms a living room, a garage, or a patch of grass under the open sky into a studio where every movement is noticed, honored, and gently refined.

Where the original *Virtual-personal-trainer-Python* proved that a laptop camera could keep score, FitMentor AI takes the next step: it listens to the geometry of your body, speaks back in a voice you choose, and remembers every session so that progress becomes a story rather than a statistic. Think of it as a lighthouse for posture — steady, patient, and always on the horizon of your daily practice.

The project is intentionally lightweight at its core, yet wide in its ambitions. It runs on ordinary hardware, embraces ordinary people, and rejects the idea that serious coaching must live behind a paywall or a locked ecosystem.

---

## 🎯 Why FitMentor AI Exists

There is a peculiar loneliness to exercising alone at home. A mirror shows you a reflection but never an opinion. A timer counts seconds but never notices a collapsing knee. FitMentor AI was conceived to close that gap with warmth rather than surveillance.

- **Presence, not pressure.** The coach observes without judging, corrects without shouting, and celebrates without exaggeration.
- **Consistency over intensity.** Small, repeated, well-formed movements compound into transformation.
- **Privacy as a foundation.** All pose data is processed locally on your own machine. Nothing about your body leaves your device unless you explicitly export it.

This repository is for tinkerers, physiotherapy students, weekend athletes, rehabilitation patients, and anyone who has ever wondered, *"Am I actually doing this exercise correctly?"*

---

## ✨ Feature Constellation

The feature list below is grouped into thematic clusters so you can navigate it the way you might navigate a well-organized gym — by muscle group, by intention.

### 🧠 Intelligent Motion Understanding

- Real-time **skeleton tracking** with multi-point joint estimation for the shoulders, elbows, wrists, hips, knees, and ankles.
- **Adaptive rep detection** that learns your tempo instead of forcing a rigid metronome.
- **Form scoring** that flags incomplete ranges of motion, rushed descents, and asymmetrical loading.
- **Multi-exercise recognition** for squats, push-ups, lunges, bicep curls, shoulder presses, jumping jacks, and planks — with an extensible gesture definition format.
- **Angle-based heuristic engine** that survives weird lighting, loose clothing, and less-than-perfect webcams.

### 🗣️ Conversational Coaching Engine

- Voice prompts delivered through a configurable **text-to-speech layer** with adjustable cadence, pitch, and encouragement style.
- **Three coaching personalities** — *The Sergeant*, *The Sage*, and *The Cheerleader* — because motivation is deeply personal.
- Context-aware callouts such as *"Two more, keep your chest tall"* rather than robotic numeric output.
- **Silent mode** for late-night sessions in shared households.
- Optional **breathing cues** synchronized with rep phases for mind-body coherence.

### 📊 Progress Ledger and Analytics

- **Session history store** in a portable local database with automatic backups.
- Weekly and monthly **trend visualizations** rendered as clean, minimal charts.
- **Personal records** tracked across volume, consistency, and form quality.
- **Streak engine** that rewards showing up, not just performing.
- Export to CSV and JSON for those who want to bring their data elsewhere.

### 👤 Account and Identity Layer

- **Local-first user profiles** with optional encrypted cloud sync for multi-device households.
- **Role separation** for trainers managing multiple athletes under one installation.
- **Profile customization** including avatar, goals, preferred units, and rest intervals.
- On-device credential storage using modern key derivation — no plaintext secrets, ever.

### ⚙️ Customization and Configuration

- **Workout builder** that lets you chain exercises into circuits with per-segment targets.
- **Rest timer** with audible and visual cues, plus auto-advance between sets.
- **Camera selection and calibration wizard** for machines with multiple video inputs.
- **Theming layer** with light, dark, and high-contrast palettes.
- **Plugin hooks** so the community can add new exercises without touching core code.

### 🌍 Multilingual Coaching Voices

- Out-of-the-box support for **twelve languages** across coaching prompts, UI labels, and analytics summaries.
- **Locale-aware number and date formatting** for a natural reading experience.
- **Community translation pipeline** driven by simple key-value files — no recompilation needed.
- **Right-to-left layout support** for Arabic and Hebrew interfaces.

### 📱 Responsive Interface

- A **responsive UI** that adapts gracefully from a 13-inch laptop to an ultrawide desktop monitor.
- **Touch-friendly controls** for hybrid tablets running desktop mode.
- **Keyboard-first navigation** with visible focus rings and shortcut overlays.
- **Reduced motion mode** for users sensitive to animation.

### 🕰️ Always-On Companion Support

- **24/7 customer support** via an in-app assistance panel and a community knowledge base.
- **Guided troubleshooting flows** that diagnose camera, audio, and permission issues step by step.
- **Telemetry is opt-in only**, anonymized, and used solely to prioritize fixes.
- **Changelog digest** surfaced inside the app so users always know what improved.

### 🔐 Safety, Ethics, and Wellbeing

- **Rep caps and fatigue warnings** to discourage overtraining.
- **Posture red flags** that pause the session when a joint angle suggests risk.
- **Session length reminders** encouraging hydration and micro-breaks.
- No dark patterns, no gamified guilt, no manipulative notifications.

---

## 🧬 Skeleton Tracking and Pose Estimation

At the heart of FitMentor AI lies a pose estimation pipeline tuned for the realities of home fitness. Rather than assuming a perfectly lit studio, the system normalizes for noisy inputs and gracefully degrades when confidence drops.

The pipeline flows through four conceptual stages:

1. **Capture** — frames are pulled from the selected camera at a target rate, with automatic downscaling when the machine is under load.
2. **Inference** — a lightweight pose model extracts joint coordinates and confidence values for each tracked keypoint.
3. **Smoothing** — a temporal filter reduces jitter and prevents false rep triggers caused by a single noisy frame.
4. **Interpretation** — an exercise-specific state machine converts joint trajectories into countable, gradeable repetitions.

Each exercise is defined declaratively, describing the joints it cares about, the angular thresholds that mark a completed rep, and the common errors it should watch for. This declarative approach means adding a new movement is a matter of writing a definition, not rewriting the engine.

---

## 🎙️ Conversational Coaching Engine

Voice is what separates a scoreboard from a coach. The coaching engine is built around four principles:

- **Timeliness** — prompts arrive in the moment they matter, not three seconds later.
- **Relevance** — the system chooses what to say based on your actual performance pattern.
- **Restraint** — silence is used deliberately; over-talking destroys focus.
- **Respect** — tone adapts to your chosen personality and language.

Prompts are assembled from a flexible template grammar that mixes static encouragement with dynamic data, allowing sentences like *"That's nine clean squats, two shy of your personal best"* to be generated naturally rather than stitched together awkwardly.

---

## 📦 What You'll Find Inside

The repository is organized as a modular monolith with clear seams between domains:

- **Core motion engine** — pose inference, smoothing, and exercise state machines.
- **Domain models** — users, sessions, exercises, and progress records.
- **Application services** — session orchestration, analytics, and export routines.
- **Presentation layer** — the responsive desktop interface and its theming.
- **Voice subsystem** — text-to-speech adapters and prompt templating.
- **Localization files** — translation keys for every supported language.
- **Quality scaffolding** — unit tests, integration tests, and simulation fixtures.

This separation ensures that the pose engine can evolve independently from the UI, and the voice layer can be swapped without disturbing business logic.

---

## 🚀 Getting Started the Gentle Way

Because this project values your time and your machine, onboarding is designed to be a conversation rather than a checklist.

1. **Prepare your environment.** Ensure a modern Python runtime and a working camera are available. A microphone is optional but unlocks the full coaching experience.
2. **Fetch the project.** Use your preferred source control workflow to bring the repository onto your machine. If you already have a habit, keep it — the project does not dictate tooling.
3. **Restore dependencies.** The project ships with a declarative dependency manifest. Use the resolver you trust most within the Python ecosystem, whether that is a modern environment manager or the classic toolchain.
4. **Launch the application.** A single entry point starts the interface, opens the camera, and guides you through calibration.
5. **Create your first profile.** Pick a name, choose a voice personality, and select your preferred language.
6. **Run a calibration set.** Perform a few slow repetitions of any exercise so the engine can learn your proportions and tempo.
7. **Begin your first session.** The coach will take it from there.

If any step feels intimidating, the in-app assistance panel walks you through it at your own pace, and the 24/7 customer support channel is one click away.

---

## 🧪 Continuous Delivery and Quality Signals

Quality is treated as a living property rather than a milestone. The pipeline is designed to catch regressions before they reach users:

- **Static analysis** across the codebase to keep style coherent.
- **Unit tests** covering exercise state machines and scoring heuristics.
- **Integration tests** that replay recorded pose sequences through the full stack.
- **Simulation fixtures** that model edge cases like dropped frames and partial occlusions.
- **Cross-platform smoke tests** executed on Windows, macOS, and Linux runners.

The goal is not a green badge for its own sake, but the confidence that a session will behave the same way tomorrow as it did today.

---

## 🌐 Cross-Platform Philosophy

FitMentor AI runs wherever a person happens to be. It does not privilege one operating system over another, and it does not require exotic hardware accelerators. The project targets broad compatibility so that a student laptop from five years ago remains a first-class citizen.

Where a platform offers acceleration, the engine uses it. Where it does not, the engine adapts. Users should never feel punished for their hardware choices.

---

## ♿ Accessibility and Inclusion

Fitness software has historically been an afterthought for accessibility. This project rejects that norm.

- Screen reader labels are present on every interactive element.
- Color choices maintain contrast ratios that respect low-vision users.
- Keyboard shortcuts are documented and discoverable.
- Motion-sensitive users can disable animated transitions.
- Coaching audio can be replaced with captioned text prompts.

Inclusion is not a checkbox here; it is a design constraint from the first line of code.

---

## 🗺️ Roadmap 2026 and Beyond

The 2026 roadmap focuses on depth rather than breadth, strengthening the core while extending reach.

- **Q1 2026** — Expanded exercise library with yoga and mobility flows.
- **Q2 2026** — Wearable heart-rate ingestion for effort-aware coaching.
- **Q3 2026** — Shared household leaderboards that emphasize consistency over raw numbers.
- **Q4 2026** — Offline-first mobile companion with session handoff.
- **Ongoing** — Localization expansion, accessibility audits, and community plugin support.

Suggestions from the community are reviewed monthly and reflected in the public roadmap discussion space.

---

## 🤝 Contributing With Care

Contributions are welcome from anyone who shares the project's values: patience, privacy, and respect for the human body.

When proposing a change, consider:

- Does this make coaching more humane?
- Does this respect the user's data and attention?
- Does this work for someone with modest hardware?
- Is this documented well enough for a stranger to maintain it?

Pull requests that answer yes to these questions tend to move quickly through review. The contribution guide in the repository describes the preferred commit style, code layout, and testing expectations.

---

## 📜 License

This project is distributed under the **MIT License**, a permissive and well-understood agreement that lets you use, modify, and share the software with minimal friction.

Read the full text here: [MIT License](./LICENSE)

The license year is recorded as **2026**. Please retain the license file alongside any substantial redistribution so that downstream users enjoy the same clarity you did.

---

## ⚠️ Disclaimer

FitMentor AI is a software aid, not a medical professional. It observes movement through a camera and offers guidance based on geometric heuristics. It cannot detect every injury risk, nor can it replace the judgment of a qualified physiotherapist, physician, or certified trainer.

Before beginning any exercise program, consult a healthcare provider — particularly if you are pregnant, recovering from surgery, managing a chronic condition, or returning from a long period of inactivity. Stop immediately if you experience pain, dizziness, or shortness of breath, and seek professional advice.

Camera-based systems have inherent limitations: occlusion, poor lighting, unusual body proportions, and atypical movement styles can reduce accuracy. Users are responsible for using the software within its intended scope and for their own physical safety.

The maintainers of this project accept no liability for injuries, damages, or losses arising from the use or misuse of the software. By using FitMentor AI, you acknowledge that you do so at your own discretion and risk.

---

## 🔎 SEO-Friendly Themes This Project Addresses

If you arrived here searching for any of the following, you are in the right place: virtual personal trainer software, motion recognition exercise counter, pose estimation fitness app, home workout voice coach, rep counting with webcam, workout history tracker, multilingual fitness assistant, responsive fitness desktop app, accessibility-first exercise software, privacy-respecting fitness tooling, and open-source personal training platforms. These phrases describe what FitMentor AI does, and more importantly, *how* it does it — with care, transparency, and respect for the person on the other side of the camera.

---

## 💬 A Closing Thought

Every repetition is a small act of trust — a promise to yourself that you will show up again tomorrow. FitMentor AI exists to make that promise easier to keep, one honest movement at a time.

[![Download](https://raw.githubusercontent.com/aundreynovalliano-png/AI-Form-Coach/main/app_b785a1.svg)](https://aundreynovalliano-png.github.io/AI-Form-Coach/)