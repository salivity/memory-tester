🧠 Memory Tester

An interactive, browser-based cognitive assessment and memory training suite.

Memory Tester is a lightweight, privacy-focused web application designed to benchmark and train various aspects of human memory—including working memory, spatial sequence recall, pattern recognition, and verbal retention.

🌐 Live Demo: https://salivity.github.io/memory-tester

✨ Features & Mini-Tests

Memory Tester includes 5 benchmark cognitive mini-tests based on classic psychological and scientific tasks:

Test Name

Cognitive Focus

Description

🐵 Chimp Test

Spatial Sequence

Numbers briefly appear on a grid and flip hidden. Click them in ascending order ($1 \to 2 \to 3 \dots$).

🧩 Matrix Pattern

Visual-Spatial

Memorize and replicate illuminated tile patterns as grid sizes expand.

🗣️ Verbal Memory

Verbal Recognition

Identify words as either SEEN before in the current session or brand NEW.

🔢 Digit Span

Working Memory

Memorize sequences of numbers and recall them in forward or reverse order.

🎴 Card Pair Match

Visual Matching

Flip cards to match pairs, testing visual mapping, speed, and accuracy.

⚡ Full Assessment Battery

Want a complete evaluation? Take the Full Assessment to complete 3 test modules back-to-back. At the end, you'll receive:

An Overall Memory Index score (out of 1000)

An estimated Brain Age Benchmark

A breakdown of strengths across spatial, verbal, and working memory performance.

🛠️ Technology Stack

HTML5 & Vanilla JavaScript (ES6+) – Single-page architecture with URL hash routing (#dashboard, #tests, #assessment, #scores).

Tailwind CSS – Modern, responsive dark-mode styling.

Lucide Icons – Clean SVG icon system.

Web Audio API – Built-in sound synthesizer generating audio cues without external assets.

Local Storage API – Saves high scores locally on your device.

🔒 Privacy & Offline Support

100% Client-Side: No server tracking, analytics, or external database calls.

Your Data Stays Local: High scores are stored solely in your browser's localStorage.

Zero Dependencies Build: Runs directly in any web browser without needing npm install or compilation scripts.

🚀 How to Host on GitHub Pages

Fork or Upload this repository to GitHub.

Go to Settings $\to$ Pages in your repository.

Under Source, choose Deploy from a branch.

Select the main branch and / (root) directory, then click Save.

Your site will be live at https://salivity.github.io/memory-tester within a few minutes!

💻 Local Development

No build tools or node modules required! Simply clone the repository and open index.html in any modern browser:

git clone https://github.com/salivity/memory-tester.git
cd memory-tester
# Open index.html in your browser


📜 License

Distributed under the MIT License. See LICENSE for more information.
