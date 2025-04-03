# Interactive Vibe Coding Study Guide

## Description

This project is an interactive study guide based on the concepts presented in Matthew Berman's video tutorial: [**Vibe Coding Complete Tutorial and Tips - Cursor / Windsurf**](https://youtu.be/v7UcVPO4y3c?si=y5D84kHyDQTyz3VY).

The guide aims to help users learn and reinforce their understanding of vibe coding principles, tools, workflow, and best practices as covered in the video. It presents the information in distinct sections and includes interactive elements like quizzes, flashcards, and a self-assessment tool to enhance the learning experience.

## Creation Process

This interactive study guide was created through a collaborative process:

1.  **Source Material:** The content is derived directly from the transcript of Matthew Berman's video tutorial linked above.
2.  **Content Structuring:** Key information from the transcript was organized into logical sections.
3.  **AI Collaboration:** The initial structuring, content extraction, interactive element design (quizzes, flashcards, assessment), and code generation were performed by **Gemini 2.5** using the **Canvas** feature within the Gemini app.
4.  **Instruction & Iteration:** The development process was guided by instructions and iterative refinement prompts provided by **[Dominik Lukeš](https://linkedin.com/in/dominiklukes)**.
5.  **Technology:** The guide is built as a single `index.html` file using:
    * HTML
    * Tailwind CSS (via CDN) for styling.
    * Vanilla JavaScript for interactivity (navigation, quizzes, flashcards, chart generation).
    * Chart.js (via CDN) for the self-assessment radar chart.
    * Lucide Icons (SVG via CDN) for visual elements.

## Features

* **Section-Based Learning:** Content organized into logical sections corresponding to the video's topics.
* **Sidebar Navigation:** Easy navigation between sections.
* **Progress Tracking:** Visual progress bar tracking completion of core sections.
* **Interactive Quizzes:** Multiple-choice and true/false questions with immediate feedback to test understanding within sections and a final review quiz.
* **Interactive Flashcards:** Key terms and concepts presented with illustrative icons; click to reveal definitions.
* **Confidence Self-Assessment:** Allows users to rate their confidence in key areas and visualizes the results using a radar (spider) chart.
* **Responsive Design:** Adapts to different screen sizes using Tailwind CSS.

## How to Use

1.  **Download:** Obtain the `index.html` file from this repository.
2.  **Open Locally:** Simply open the `index.html` file in a modern web browser.
3.  **Deploy (Optional - e.g., GitHub Pages):**
    * Upload the `index.html` file to a GitHub repository.
    * Go to the repository's **Settings**.
    * Navigate to the **Pages** section.
    * Under "Build and deployment", select **Deploy from a branch**.
    * Choose the branch containing `index.html` (e.g., `main`).
    * Select `/ (root)` as the folder.
    * Click **Save**.
    * Your study guide will be deployed to `https://<your-username>.github.io/<repository-name>/`.

## Licensing

This project uses a dual-license approach:

### Code License (MIT)

The underlying code used to create and display this interactive study guide (HTML, CSS, JavaScript) is licensed under the MIT License:

```
MIT License

Copyright (c) 2025 [Your Name or Organization - if applicable, otherwise remove]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Content License (CC0)

The textual content of this study guide (summaries, quiz questions, flashcard definitions, etc.), which is derived from the original video transcript by Matthew Berman, is dedicated to the public domain using the Creative Commons CC0 1.0 Universal license.

```
CC0 1.0 Universal (CC0 1.0)
Public Domain Dedication

The person who associated a work with this deed has dedicated the work to the
public domain by waiving all of his or her rights to the work worldwide under
copyright law, including all related and neighboring rights, to the extent
allowed by law.

You can copy, modify, distribute and perform the work, even for commercial
purposes, all without asking permission. See Other Information below.

Other Information: [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/)
```

In essence, you are free to use, adapt, and share the textual content, while the code structure enabling the interactivity follows the MIT license terms.

## Attribution

* **Source Material:** Based on the video "[Vibe Coding Complete Tutorial and Tips - Cursor / Windsurf](https://youtu.be/v7UcVPO4y3c?si=y5D84kHyDQTyz3VY)" by Matthew Berman.
* **Development:** Created collaboratively by Gemini 2.5 and [Dominik Lukeš](https://linkedin.com/in/dominiklukes).
