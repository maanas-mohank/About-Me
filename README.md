# maanas — personal website & portfolio

a minimal, terminal-and-circuit-inspired personal website showcasing hardware, electronics, and software projects, credentials, and achievements. built with lightweight, dependency-free vanilla html, css, and javascript.
<img width="1422" height="898" alt="image" src="https://github.com/user-attachments/assets/b60a53e6-2efd-464c-ad34-7e37f1b2fa1e" />

## highlights

* **aesthetic theme:** dark circuit-grid pattern (`#06140f`) with high-contrast emerald/neon green accents.

* **pure vanilla stack:** zero external build dependencies, packages, or heavy frameworks—super fast load times.

* **responsive layout:** formatted cleanly for both mobile screens and desktop displays.

* **interactive easter egg:** press `f` on the keyboard to trigger an animated, retro-styled face-off between an esp32 and a raspberry pi.

## file structure

```
.
├── index.html          # main landing page (bio, featured projects, links & easter egg)
├── credentials.html    # academic background, program selections, and awards
├── photo.jpg           # profile avatar (referenced on index.html)
└── readme.md           # repository documentation
```

## key sections & content

### 1. `index.html` (home)

* **profile:** intro to maanas (class xi student passionate about hardware, embedded systems, and tech).

* **featured projects:**

  * **avem:** vehicle emission monitor that dynamically regulates engine speed when emissions breach legal thresholds and suggests local puc centers.

  * **grocify:** smart grocery tracking application utilizing computer vision to detect fresh produce freshness and preemptively notify users of expiration.

* **connect:** direct email and linkedin profiles.

* **easter egg ("esp32 vs. raspberry pi"):**

  * **trigger:** press `f` anywhere on the page.

  * **exit:** press `esc`, click the close button `✕`, or click outside the stage overlay.

### 2. `credentials.html` (achievements & education)

* **competitions & stem programs:**

  * the junior academy — *the new york academy of sciences*

  * 3rd place shark tank (*smaraneeyam*) — vr temple application concept

  * 2nd place dream pitch (*kalam 2047 / jnanagni*)

  * top 100 in *youth ideathon* (thinkstartup & esri india at iit delhi)

  * top 20 recognition by the education minister of tamil nadu (vit & *the times of india*)

* **schooling:**

  * sunshine chennai senior secondary school

  * dav public school, chennai

## running the site locally

because the project is built with static web files, you don't need any package managers:

### option 1: direct file opening

double-click `index.html` in your file explorer to open it directly in any web browser.

### option 2: local http server (python)

if you prefer running a local server:

```
# python 3.x
python3 -m http.server 8000
```

then visit `http://localhost:8000` in your browser.

### option 3: vs code live server

1. install the **live server** extension in vs code.

2. right-click `index.html` and select **"open with live server"**.

## deployment

the site is ready for static web hosting. you can host it instantly via:

* **github pages:** go to repository settings → **pages** → deploy from branch `main` / `root`.

* **cloudflare pages** or **vercel** / **netlify**: simply link your git repository without adding build commands.
