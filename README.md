RX PROPOSAL WEB — "Be My Girlfriend?" 💌

A fun single‑file HTML project — built as a playful way to propose to someone special. The UI has cute animations and smart interactions with Yes/No buttons.

> Repo: RX-PROPOSAL-WEB




---

✨ Features

Single HTML file (inline CSS + JS)

Mobile‑friendly responsive design

Moving No button (mischief mode 😈)

Heart rain animation when clicking Yes 💖

Lightweight — no build system required



---

📂 Folder Structure

RX-PROPOSAL-WEB/
└─ index.html

> You can also create an assets/ folder for separate CSS/JS if needed, but the current version keeps everything inside index.html.




---

▶️ Run Locally

Option 1: Direct Browser

1. Clone or download the project.


2. Open the folder and double‑click index.html. ✅



Option 2: VS Code Live Server

1. Install the Live Server extension in VS Code.


2. Open index.html → Right click → Open with Live Server



Option 3: Node.js lightweight server (optional)

# Start a local server with live reload
git clone https://github.com/rxabdullah007/RX-PROPOSAL-WEB.git
cd RX-PROPOSAL-WEB
npx live-server index.html
# or
npx http-server


---

🚀 Deploy on Netlify (2‑minute setup)

Method A — Drag & Drop (Easiest)

1. Prepare the project folder (must contain index.html).


2. Go to Netlify Drop.


3. Drag & drop the whole folder.


4. Instantly get a live URL (e.g., https://your-site.netlify.app).



Method B — GitHub Deploy

1. Repo link: RX-PROPOSAL-WEB


2. In Netlify Dashboard → Add new site → Import from Git


3. Authorize GitHub and select the repo.


4. Build command: (leave empty)
Publish directory: /


5. Click Deploy.



Custom Domain (Optional)

In Netlify → Domain settings, connect your own domain.



---

🛠️ Customization Guide

Change Title/Heading

In index.html: <h1 id="question">Will you be my girlfriend?</h1> → edit the text.


Custom Yes Message

In the script, update this line:


message.textContent = "Awww 😍 Take love from rX Abdullah !";

No Button Behavior

Logic is inside noBtn.addEventListener('click', ... ). You can adjust steps, text, or emojis.


Heart Animation Speed

Inside heartEffect(), the interval (currently 100ms) controls heart spawn rate:


setInterval(() => { /* hearts */ }, 100);


---

❓ Troubleshooting

Page not opening? Ensure index.html is at the root.

Blank page on Netlify? Check publish directory = / and leave build command empty.

Layout cut off on mobile? Adjust CSS media query font-sizes.



---

🤝 Contribution

PRs and Issues are welcome! Suggestions like confetti effect, background customization, or typing animation are great ideas.


---

📜 License

Free for personal/romantic use. For commercial usage, ask for permission.


---

👨‍💻 Credits

Developed with ❤️ by rX Abdullah

> If this template helped you, please ⭐️ the repo!



