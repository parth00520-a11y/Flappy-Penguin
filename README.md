# Flappy-Penguin
📖 Overview
<p>Flappy Penguin is a fun CSS art project build entirely with HTML and CSS. It renders an animated penguin character standing in a scenic landscape, complete with mountains, a sun, and an ocean ground. The penguin features a waving arm animation and scales up when clicked.</p>
<p>This project was created as part of the freeCodeCamp Responsive Web Design Certification curriculum.</p>

<hr>

✨ Features
<p>- 🎨Pure CSS art-no JavaScript at all</p>
<p>- 🎨CSS custom properties for easy colour theming</p>
<p>- 🌊Animated waving arm using @Keyframes</p>
<p>- 👆Click/tap interaction: penguin scales up on :active</p>
<p>- 🗻Scenic background with mountains(skew + rotate transforms) and a sun</p>
<p>- 📐Responsive layout with percentage-based sizing</p>
<p>- 🧩Layered z-index composition for depth</p>

<hr>

📁 Projuct Structure
<p>Flappy-Penguin/</p>
<p>├── flappy.html   # Main HTML file — defines the penguin's DOM structure</p>
<p>├── flappy.css    # All styles — layout, colours, animations, CSS variables</p>
<p>├── README.md     # Project documentation</p>

<hr>

🚀 How to Use
<p>-Open Locally</p>
 <p>1.Clone or download this repository:</p>
 <p>git clone https://github.com/parth00520-a11y/Flappy-Penguin.git</p>
 <p>2.Make sure flappy.html and flappy.css are in same folder.</p>
 <p>3.Open flappy.html in any modern web browser.</p>

 <hr>

🎨 Customisation
<p>Three CSS custom properties at the top of flappy.css control the penquin's colour palette:</p>

<p>Example </p>
<span>:root {
  --penguin-face: white;
  --penguin-skin: steelblue;
  --penguin-picorna: gold;
}</span>

<hr>

🎬 Animations
<h3>Wave animation</h3>
<p>The right arm continuously waves using @Keyframes wave rule that rotates between 110deg and 130deg with scaleX(-1) to mirror the arm shape.</p>

<h3>Click to Scale</h3>
<p>Clicking or tapping the penguin triggers .penguin:active, which scales the entire penguin to 1.5x its size with a smooth 1s ease-in-out transition back.</p>

<hr>

🌐 Browser Support
<p>Works in all modern browers that supports CSS custom properties and CSS transforms:</p>
<p>Chrome ✅</p>
<p>Firefox ✅</p>
<p>Safari ✅</p>
<p>Edge ✅</p>

<hr>

👨‍💻 Credits
<p>- Build by parth00520-ally as a freeCodeCamp Responsive Web Design Project.</p>
<p>- Inspired by the freeCodeCamp CSS Penguin curriculum challenge.</p>
