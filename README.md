# The Internet Dial-Up Time Machine

An interactive, educational website that takes visitors back to the 1990s to experience (and learn about) dial-up internet. It explains how dial-up worked, compares it with modern connections, provides facts on the evolution of connectivity and even lets you try a simulated modem connection!

**Live site:** https://diatasnimk-ui.github.io/Internet-connectivity-and-evolution-website/

## Features

- **How dial-up worked:** a tabbed walkthrough covering the computer, modem, phone line, ISP and the internet
- **Speed evolution:** animated meters comparing dial-up, DSL, cable and fibre, which fill when scrolled into view
- **Download comparison:** tabs showing how long a photo, song, movie and game would take on dial-up versus fibre
- **Why dial-up was problematic:** six fact cards covering speed, tied-up phone lines, connection times, stability, cost and security
- **Evolution of the internet:** tabbed timeline from dial-up through DSL and cable, broadband, and fibre and 5G
- **Quiz:** 10 randomly selected questions from a pack of 16, with scoring and feedback
- **Dial-up connection simulator:** a retro modem display with blinking indicator lights, a terminal output, a progress bar, random facts and Dial / Hang Up buttons
- **Dial-up sound:** an audio player with an explanation of what each part of the modem sound means
- **References and credits page**, plus an "About the Author" pop-up

## Accessibility and usability

- Tabs follow the WAI-ARIA tabs pattern and can be navigated with the keyboard (arrow keys, Enter and Space)
- Hamburger navigation menu with ARIA attributes for screen readers
- Alt text on images
- Responsive layouts for smaller screens
- "Back to top" button on long pages

## Project structure

```
├── index.html              Main page
├── dialupSimulation.html   Dial-up connection simulator and audio
├── References.html         References and credits
├── style.css               Styles shared by all pages
├── script.js               Interactivity shared by all pages
├── images/                 Photos and pixel art used on the site
├── audio/                  Dial-up modem sound
├── LICENSE
└── README.md
```

## Running locally

No build step or dependencies are needed. Download or clone the repository and open `index.html` in a web browser.

An internet connection is needed for the Google Fonts and Font Awesome icons, which are loaded from external sources.

## Built with

- HTML, CSS and JavaScript (using visual studio code)
- [Font Awesome](https://fontawesome.com/) and [Lucide](https://lucide.dev/) icons
- Google Fonts: Press Start 2P, Bebas Neue and VT323

## Credits

External code templates and learning resources are credited in full on the site's References page. In brief:

- Hamburger menu: [Christian Tietze](https://christiantietze.de/posts/2025/01/responsive-scalable-hamburger-menu-accessible-css/)
- Quiz template: [Sulaimon Olaniran on DEV](https://dev.to/sulaimonolaniran/building-a-simple-quiz-with-html-css-and-javascript-4elp)
- Back to top button: [W3Schools](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp)
- Tab accessibility: [W3C ARIA Authoring Practices](https://www.w3.org/WAI/ARIA/apg/patterns/tabs/) and [MDN](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Keyboard-navigable_JavaScript_widgets)
- Content sources: Uswitch, Wikipedia and others, listed on the References page

## License

See the [LICENSE](LICENSE) file for details.

## Author

Diatasnim Khan
