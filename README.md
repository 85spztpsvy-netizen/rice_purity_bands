[README.md](https://github.com/user-attachments/files/23810438/README.md)
# 🎸 Band Purity Tests
An interactive, humorous fandom-themed “purity test” generator for dozens of bands and artists.  
Select a band, check off items that apply to you, and get a “purity score” based on how deep you are in the fandom trenches.

This project is built as a **single-page HTML application** with dynamic views, custom styling, and JavaScript-driven interactivity.

## 🌟 Features

### ✔ Multi-Band Purity Test System
Includes fully written question lists for many artists, such as:

- Rush
- My Chemical Romance
- Yes
- John Mayer
- Alice in Chains
- Genesis
- Mötley Crüe
- Def Leppard
- Led Zeppelin
- Bee Gees
- Deep Purple
- Guns N’ Roses
- Charli XCX
- A. G. Cook
- The Beatles
- Jonas Brothers
- 5 Seconds of Summer
- Fall Out Boy
- The Who
- The Rolling Stones
- Kendrick Lamar
- BABYMETAL
- Katy Perry
… and more.

Each band has its own unique list of funny, affectionate fandom “sins” to check off.

## 🧠 How It Works

### 💡 Single-Page Application Design
The page dynamically switches between:

- **Home View** – choose a band
- **Test View** – answer an interactive checklist
- **Score View** – see your score & navigation options
- **Results View** – view a summary of all your scores

All content stays on one page; no reloading required.

### 🎛 Interactive JavaScript Logic
- Questions are generated from a `tests` object inside the `<script>` block  
- Checkboxes are created dynamically  
- Score is calculated by counting checked items  
- Multiple state views are shown/hidden with class toggles  
- Includes “previous/next band” navigation  
- Stores results across band switches during the session

## 🎨 Styling
The project includes:

- Custom color palette (cream, parchment, deep brown)  
- Button styling for band selectors  
- Clean serif font for a playful, vintage aesthetic  
- Card-based score/results layout  
- Responsive grid layout for band list  

All styling is contained inline within a `<style>` tag.

## 📁 File Structure

```
index.html    # Main interactive site
```

All HTML, CSS, and JavaScript are embedded in one file for easy deployment on GitHub Pages or Netlify.

## 🚀 How to Run

### Option 1 — Open Locally
1. Download the file  
2. Double-click `index.html`  
3. It opens in any browser

### Option 2 — Publish on GitHub Pages
1. Upload `index.html` to a GitHub repo  
2. Enable **Settings → Pages → Deploy from branch**  
3. Visit the generated public site URL

## 🌐 Live Demo (optional)
Add your GitHub Pages link here after deployment:

```
https://your-username.github.io/band-purity-tests/
```

## 🤝 Contributing
This project is just for fun, but feel free to:

- Add more bands  
- Add more fandom questions  
- Improve UI/UX  
- Split into separate HTML/CSS/JS files  
- Add animations or transitions  

## 📜 License
This project is for entertainment and non-commercial use only.  
Feel free to remix—but don’t take it too seriously 😄
