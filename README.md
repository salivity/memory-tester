# Memory Tester 🧠

> A lightweight, client-side cognitive testing suite to measure spatial memory, working memory, and verbal recall.

🔗 **Live Demo:** [https://salivity.github.io/memory-tester](https://salivity.github.io/memory-tester)

---

## Overview

**Memory Tester** is a standalone, browser-based cognitive test app designed to evaluate different aspects of human memory. It is built entirely in vanilla HTML5, CSS (Tailwind), and JavaScript with zero build steps or external dependencies.

Whether you want to train your working memory, test your spatial recall against chimpanzee benchmarks, or run a full cognitive evaluation, all tests run locally in your browser.

---

## Included Tests

| Test | Cognitive Domain | Description |
| :--- | :--- | :--- |
| **Chimp Test** | Spatial & Working Memory | Click numbers in ascending sequence after they turn hidden. Based on working memory experiments with primates. |
| **Matrix Recall** | Visual-Spatial Memory | Memorize and reproduce illuminated patterns on expanding grids ($3 \times 3$ up to $5 \times 5$). |
| **Verbal Memory** | Verbal Working Memory | Determine if a word presented on screen is **NEW** or has already been **SEEN** in the session. |
| **Digit Span** | Short-Term Capacity | Remember sequences of numbers in **Forward** or **Reverse** order based on Miller's $7 \pm 2$ capacity model. |
| **Card Matching** | Associative Memory & Speed | Match pairs of hidden symbols on a card grid in the fewest moves and fastest time. |
| **Full Assessment** | Composite Benchmark | A structured multi-test battery that calculates an overall **Cognitive Memory Index** ($0 - 1000$) and estimated brain age. |

---

## Key Features

* **Zero Frameworks / Zero Build Tools:** Single-file architecture using native browser APIs.
* **Hash-Based Routing:** Seamless navigation (`#dashboard`, `#chimp`, `#matrix`, `#verbal`, `#digit`, `#cards`, `#assessment`, `#scores`) without page reloads.
* **Web Audio Synthesis:** Sound effects generated dynamically using the Web Audio API—no external audio files required.
* **Local Persistence:** Personal bests and high scores save automatically to your browser's `localStorage`.
* **Privacy Focused:** 100% client-side. No user data, scores, or telemetry leave your device.
* **Responsive Design:** Optimized for mobile phones, tablets, and desktop displays.

---

## Quick Start & Local Setup

Because Memory Tester has no build steps or dependencies, running it locally requires no installation:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/salivity/memory-tester.git](https://github.com/salivity/memory-tester.git)
   cd memory-tester
