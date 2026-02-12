# Cloud-CoreSync
Cloud CoreSync: A comprehensive personality profiler blending Enneagram, MBTI, instincts, love languages, values, and spirituality to uncover your core self and compatibility for romantic, familial, and friendly connections.
# Overview
Cloud CoreSync is a comprehensive, interactive personality profiler designed to delve deep into your core self, motivations, values, and relational dynamics. By synthesizing elements from established systems like the Enneagram, Myers-Briggs Type Indicator (MBTI), Instinctual Variants (IVQ-inspired), Love Languages, and more, this tool provides a holistic view of who you are and how you connect with others. Whether you’re seeking self-awareness, improving family relationships, or evaluating compatibility for lifelong romantic partnerships, Cloud CoreSync offers actionable insights through a user-friendly, browser-based test.
Built as a static HTML application with JavaScript for interactivity and auto-scoring, it’s easy to host on platforms like GitHub Pages, Tiiny Host, or any static web server. Results are calculated client-side and can be automatically emailed to a configured address for review, making it ideal for personal use, coaching, or small-scale assessments.
This project emphasizes privacy and consent: Users are informed upfront that submissions send results to a specified email, with no data stored on servers.
# Key Features
•  Multi-System Integration: Combines questions from Enneagram (core motivations/fears), MBTI-inspired preferences (E/I, S/N, T/F, J/P), Instinctual Drives (SP/SO/SX stacking), Love Languages (Words, Time, Gifts, Service, Touch), values ranking, motivations/desires, spirituality, morality, and creativity.
•  Interactive Format: Clickable radio buttons, dropdowns, and checkboxes for easy navigation across 6 sections (~80-100 questions, 20-30 minutes).
•  Auto-Scoring: JavaScript computes results instantly, including MBTI type, Enneagram core, instinctual stack, primary love language, value rankings, and averaged scores for motivations/spirituality/etc. Outputs as a clean JSON for easy sharing or analysis.
•  Email Submission: Integrates EmailJS to send results directly to your email upon submission—no backend required.
•  Compatibility Framework: Designed for comparing results across friendly, familial, and romantic contexts (manual comparison via pasted JSON to AI like Grok).
•  Privacy-Focused: All processing happens in the browser; optional email consent notice ensures compliance.
•  Customizable: Easily tweak questions, scoring logic, or add features via HTML/JS edits.
•  Mobile-Friendly: Responsive design for seamless use on desktops, tablets, or phones.
# Installation and Setup
# Prerequisites
•  A web browser (e.g., Chrome, Firefox) for testing locally.
•  For hosting: A static web host like GitHub Pages, Tiiny Host, Netlify, or Vercel.
•  For email submissions: A free EmailJS account (setup guide below).
# Quick Start
# 1.  Clone the Repository:
git clone https://github.com/yourusername/cloud-coresync.git
cd cloud-coresync
# 2.  Open Locally:
	•  Double-click personality-test.html to run in your browser for testing.
# 3.  Configure EmailJS (for auto-submissions):
	•  Sign up at emailjs.com.
	•  Add an Email Service (e.g., connect your Gmail).
	•  Create an Email Template with placeholders like {{results_json}} and {{submission_time}}.
	•  In personality-test.html, replace placeholders:
		•  YOUR_PUBLIC_KEY (from Account tab).
		•  YOUR_SERVICE_ID (from Email Services).
		•  YOUR_TEMPLATE_ID (from Email Templates).
		•  YOUR_EMAIL_ADDRESS (where results are sent).
	•  Update the consent notice in the HTML if needed.
4.  Host Online:
	•  GitHub Pages: Push to your repo, go to Settings > Pages > Set source to main branch. Get your link: https://yourusername.github.io/cloud-coresync/.
	•  Tiiny Host: Upload personality-test.html as a zip; get an instant URL.
	•  Share the link with users—they take the test directly in their browser.
# Usage
# 1.  Taking the Test:
	•  Navigate sections via top buttons.
	•  Answer all questions (forced-choice, ratings, selections).
	•  Click “Submit and Send Results”.
	•  Results display as copyable JSON; simultaneously emailed to the configured address.
# 2.  Interpreting Results:
	•  JSON includes: MBTI type, Enneagram core/wing estimates, instinct stack (e.g., sx/so/sp), love language primary, ranked values, motivation averages, spirituality/morality/creativity scores.
	•  For deeper analysis: Paste JSON into an AI like Grok (on xAI) with a query like “Analyze this Cloud CoreSync result for romantic compatibility.”
	•  Compare with others: Share your JSON and theirs for manual or AI-assisted matching (e.g., 70%+ alignment suggests strong harmony).
3.  Customization Tips:
	•  Edit questions in HTML sections.
	•  Adjust scoring in the calculateAndSendResults() JS function.
	•  Add more features, like local storage for saving drafts.
Privacy and Legal Notes
•  Data Handling: No server-side storage; all computations are client-side. Email submissions require explicit user consent via the on-page notice.
•  Compliance: This tool is for personal/educational use. Ensure your usage complies with local data protection laws (e.g., add more disclaimers if distributing widely).
•  Limitations: Not a professional psychological assessment—results are indicative only. Consult experts for clinical advice.
# Contributing
Fork the repo, make changes, and submit a pull request. Suggestions for new features (e.g., advanced compatibility calculator) are welcome!
# License
This project is licensed under the MIT License - see the LICENSE file for details.
# Contact
Created by Taylor L. Cloud. For questions or collaborations, reach out via email.
# Happy syncing! 🌟
