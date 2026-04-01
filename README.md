A 3D Interactive Data Analytics Portfolio built with a Spatial Data aesthetic, glassmorphism design, and reactive particle animations.
🚀 Live Demo · 📄 Resume · 💼 LinkedIn · 🐙 GitHub
</div>

✨ Features

🌌 Reactive Particle Field — 120 animated data-point particles that respond to mouse movement and connect via network lines
🖱️ Custom Dual-Layer Cursor — Glowing cyan dot with a trailing ring that scales on hover
🃏 3D Tilt Project Cards — Cards tilt in 3D perspective as you move your cursor over them
⚓ Floating Glassmorphic Dock — Fixed bottom dock with LinkedIn, GitHub, Twitter, and Resume download
🔮 Animated Data Node — Rotating SVG node with orbiting satellite dots in the hero section
🎴 Skill Orbs — 8 glowing orbs with spinning conic gradient borders on hover
📜 Scroll Reveal Animations — Sections animate in as you scroll down the page
📱 Responsive Design — Gracefully scales down to mobile with 2D fallback layout


🛠️ Tech Stack
LayerTechnologyMarkupHTML5StylingCSS3 (Custom Properties, Glassmorphism, Animations)InteractivityVanilla JavaScript (Canvas API, IntersectionObserver)FontsGoogle Fonts — Syne + Space MonoIconsInline SVGHostingGitHub Pages / Netlify / Vercel

No frameworks. No dependencies. Zero build step — just open index.html.


📁 Project Structure
portfolio/
│
├── index.html          # Complete single-file portfolio
├── resume.pdf          # Your resume (add this file)
└── README.md           # This file

🚀 Getting Started
Option 1 — GitHub Pages (Recommended)

Fork or clone this repository
Add your resume.pdf to the root folder
Go to Settings → Pages → Source → main branch
Your portfolio is live at https://your-username.github.io/portfolio

Option 2 — Netlify (Drag & Drop)

Download the repo as a ZIP
Go to netlify.com and drag the folder onto the dashboard
Done — live in seconds at yourname.netlify.app

Option 3 — Local Preview
bashgit clone https://github.com/your-username/portfolio.git
cd portfolio
# Open index.html in your browser — no server needed
open index.html

⚙️ Customisation Guide
1. Update Personal Info
Open index.html and search for the following placeholders:
PlaceholderWhat to Replacemailto:shahzar@example.comYour real email addresshref="https://linkedin.com"Your LinkedIn profile URLhref="https://github.com"Your GitHub profile URLhref="https://twitter.com"Your Twitter/X profile URLalert('Resume download...')Replace with href="resume.pdf"
2. Add Your Resume
Drop your resume.pdf in the same folder as index.html, then update both resume buttons:
html<!-- Find this pattern and replace the href -->
href="#" onclick="alert('...')"
<!-- Change to -->
href="resume.pdf"
3. Add Your Photo (Optional)
Replace the emoji 👨‍💻 in the .avatar-inner div with an <img> tag:
html<img src="your-photo.jpg" alt="Shahzar" style="width:100%;height:100%;object-fit:cover;border-radius:50%;">
4. Change Colors
All colors are CSS variables at the top of the <style> block:
css:root {
  --midnight: #0A192F;   /* Background */
  --cyan: #64FFDA;       /* Accent color */
}

📊 Sections
#SectionContent01HeroName, title, animated data node, CTA buttons02AboutCS background, ISPR internship, Student Voice Leader role, stats03SkillsPython, Power BI, Excel, SQL, Data Cleaning, Pandas, ML, EDA04ProjectsCOVID-19 Dashboard, Car Price Engine, Online Retail RFM05ResearchEthical Aspects in Cyber Security publication06ContactEmail CTA + floating social dock

🔬 Featured Projects
🦠 COVID-19 Mortality Dashboard

Python · Pandas · Power BI · DAX

Analysed comorbidity risks across patient datasets to surface which conditions most significantly amplified COVID-19 mortality — delivered as an interactive Power BI dashboard for non-technical stakeholders.

🚗 Car Price Prediction Engine

Python · Scikit-learn · Linear Regression · Feature Engineering

Built a locally-calibrated ML model for Pakistan's used-car market (PakWheels) achieving 94.17% prediction accuracy — deployable as an API or browser extension for fair-price estimation.

🛒 Online Retail Insights

Python · Pandas · RFM Analysis · Matplotlib · UCI ML Repository

Cleaned a messy transactional dataset and applied RFM segmentation to identify that the top 15% of customers generate ~60% of revenue, enabling targeted retention strategy.

📄 Research Publication
"Ethical Aspects In Cyber Security: Maintaining Data Integrity and Protection"
Investigates the intersection of ethics and cybersecurity — examining frameworks for preserving data integrity, organisational responsibilities, and the moral dimensions of security trade-offs beyond compliance.

📬 Contact
PlatformLink📧 jappashahzar@example.com💼 [LinkedInlinkedin.com/in/shahzar](https://www.linkedin.com/in/muhammad-shahzar-nasir-208174249/)🐙 GitHubgithub.com/shahzar🐦 Twittertwitter.com/shahzar

📜 License
This project is open source and available under the MIT License.

<div align="center">
Designed & Built by Muhammad Shahzar Nasir
Data Analyst · Insight Architect · CS Graduate — The Superior University
⭐ If you found this useful, consider giving it a star!
</div>
