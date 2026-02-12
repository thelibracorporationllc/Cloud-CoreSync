# Cloud-CoreSync
Cloud CoreSync: A comprehensive personality profiler blending Enneagram, MBTI, instincts, love languages, values, and spirituality to uncover your core self and compatibility for romantic, familial, and friendly connections.
Overview
Cloud CoreSync is a comprehensive, interactive personality profiler designed to delve deep into your core self, motivations, values, and relational dynamics. By synthesizing elements from established systems like the Enneagram, Myers-Briggs Type Indicator (MBTI), Instinctual Variants (IVQ-inspired), Love Languages, and more, this tool provides a holistic view of who you are and how you connect with others. Whether you’re seeking self-awareness, improving family relationships, or evaluating compatibility for lifelong romantic partnerships, Cloud CoreSync offers actionable insights through a user-friendly, browser-based test.
Built as a static HTML application with JavaScript for interactivity and auto-scoring, it’s easy to host on platforms like GitHub Pages, Tiiny Host, or any static web server. Results are calculated client-side and can be automatically emailed to a configured address for review, making it ideal for personal use, coaching, or small-scale assessments.
This project emphasizes privacy and consent: Users are informed upfront that submissions send results to a specified email, with no data stored on servers.
Key Features
•  Multi-System Integration: Combines questions from Enneagram (core motivations/fears), MBTI-inspired preferences (E/I, S/N, T/F, J/P), Instinctual Drives (SP/SO/SX stacking), Love Languages (Words, Time, Gifts, Service, Touch), values ranking, motivations/desires, spirituality, morality, and creativity.
•  Interactive Format: Clickable radio buttons, dropdowns, and checkboxes for easy navigation across 6 sections (~80-100 questions, 20-30 minutes).
•  Auto-Scoring: JavaScript computes results instantly, including MBTI type, Enneagram core, instinctual stack, primary love language, value rankings, and averaged scores for motivations/spirituality/etc. Outputs as a clean JSON for easy sharing or analysis.
•  Email Submission: Integrates EmailJS to send results directly to your email upon submission—no backend required.
•  Compatibility Framework: Designed for comparing results across friendly, familial, and romantic contexts (manual comparison via pasted JSON to AI like Grok).
•  Privacy-Focused: All processing happens in the browser; optional email consent notice ensures compliance.
•  Customizable: Easily tweak questions, scoring logic, or add features via HTML/JS edits.
•  Mobile-Friendly: Responsive design for seamless use on desktops, tablets, or phones.
Installation and Setup
Prerequisites
•  A web browser (e.g., Chrome, Firefox) for testing locally.
•  For hosting: A static web host like GitHub Pages, Tiiny Host, Netlify, or Vercel.
•  For email submissions: A free EmailJS account (setup guide below).
