--- COPY FROM HERE ---
# ✨ NeonChef ✨ <br> _Your AI-Powered Culinary Co-Pilot in a Neon Universe!_

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPONAME?style=social)](https://github.com/YOUR_USERNAME/YOUR_REPONAME/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/YOUR_REPONAME?style=social)](https://github.com/YOUR_USERNAME/YOUR_REPONAME/network/members)

> Dive into the culinary cosmos with NeonChef, a hyper-stylized, AI-driven recipe finder that transforms your meal ideas and even dish photos into delectable recipes. Crafted with a futuristic aesthetic by **Dear Virus**, NeonChef isn't just a tool; it's an experience.

---

## 🚀 Core Features

*   🧠 **AI Recipe Generation:** Powered by Google's Gemini API, get detailed recipes from text queries or by simply uploading an image of a dish!
*   🌍 **Multi-Language Support:** Journey through global cuisines with recipes in English, Urdu, Hindi, and Arabic. The AI adapts the entire recipe content to your chosen language.
*   🎨 **Dynamic Theming Engine:** Immerse yourself in 5 distinct, visually stunning themes:
    *   🔮 **Default:** A sleek, modern purple-hued interface.
    *   ☀️ **Light:** Clean, bright, and accessible.
    *   🤖 **Cyber:** A high-tech, TRON-inspired digital grid.
    *   🌈 **Neon:** Pulsating lights and vibrant retro-futurism.
    *   💻 **Hacker:** A classic green-on-black terminal aesthetic.
*   🍲 **Advanced Filtering:** Refine your search by dietary preferences (Vegetarian, Vegan, Gluten-Free, etc.) and cuisine types.
*   📸 **Image-to-Recipe:** Snap a photo, upload it, and let NeonChef's AI identify the dish and conjure up the recipe.
*   ✨ **Futuristic UI/UX:**
    *   Animated backgrounds and floating 3D elements.
    *   Custom cursor effects tailored to each theme.
    *   Smooth transitions and interactive elements.
    *   Responsive design for seamless use on any device.
*   📋 **Recipe Management:** Easily copy recipe text or export it as a `.txt` file.
*   👨‍💻 **Developer Showcase:** A cool, toggleable panel revealing the creator's (Dear Virus) contact information.

---

## 🛠️ Tech Stack & Architecture

*   **Frontend:** Pure HTML5, CSS3, and Vanilla JavaScript – no heavy frameworks, just raw digital alchemy!
*   **AI Engine:** [Google Gemini API (1.5 Flash Latest)](https://ai.google.dev/models/gemini) for intelligent recipe generation and image understanding.
*   **Styling:**
    *   CSS Variables for robust theming and maintainability.
    *   Keyframe animations for dynamic visual effects.
    *   Flexbox & Grid for responsive layouts.
*   **Localization:** Client-side UI string translations + AI-powered content translation.

---

## 🔮 Theme Showcase

Experience NeonChef in its full visual glory. Each theme offers a unique aesthetic and interactive cursor.

### 1. Default Theme
*Sleek, modern, and mystically purple.*
![Default Theme](docs/screenshot-default.png)

### 2. Light Theme
*Clean, crisp, and universally accessible.*
![Light Theme](docs/screenshot-light.png)

### 3. Cyber Theme
*Enter the digital frontier with a TRON-inspired grid.*
![Cyber Theme](docs/screenshot-cyber.png)

### 4. Neon Theme
*Vibrant, pulsating, and retro-futuristic.*
![Neon Theme](docs/screenshot-neon.png)

### 5. Hacker Theme
*Code-green terminal vibes for the elite coder-chef.*
![Hacker Theme](docs/screenshot-hacker.png)

*(Remember to replace `docs/` with your actual screenshot folder path if different!)*

---

## ⚡ Getting Started

To get NeonChef running locally and explore its digital kitchen:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/YOUR_USERNAME/YOUR_REPONAME.git
    cd YOUR_REPONAME
    ```
    *(Replace `YOUR_USERNAME/YOUR_REPONAME` with your actual GitHub username and repository name)*

2.  **🚨 IMPORTANT: Configure API Key 🚨**
    *   Open the `index.html` file in a text editor.
    *   Locate the JavaScript section (usually near the bottom, within `<script>` tags).
    *   Find the line:
        ```javascript
        const API_KEY = 'YOUR_GEMINI_API_KEY';
        ```
    *   Replace `'YOUR_GEMINI_API_KEY'` with your **actual Google Gemini API Key**.
    *   **NeonChef will not function without a valid API key.** You can obtain one from [Google AI Studio](https://aistudio.google.com/app/apikey).

3.  **Launch NeonChef:**
    *   Simply open the `index.html` file in your favorite web browser (e.g., Chrome, Firefox, Edge).

4.  **Start Cooking (Virtually!):**
    *   Type ingredients or dish names into the search bar.
    *   Upload an image of a dish to see the AI in action.
    *   Play with the language selector and theme buttons!

---

## 💡 How to Use NeonChef

1.  **Search for Recipes:**
    *   Enter ingredients, dish names, or general food ideas into the main search bar.
    *   Hit "Search" or press Enter.
2.  **Image Upload:**
    *   Click the "Drag & drop" area or drag an image file onto it.
    *   The AI will attempt to identify the dish and provide its recipe.
3.  **Apply Filters:**
    *   Use the "Dietary Preferences" and "Cuisine Type" dropdowns to narrow down your search.
4.  **Change Language:**
    *   Select your preferred language from the dropdown in the header. The UI text and AI-generated recipe content will adapt.
5.  **Switch Themes:**
    *   Click on the colored circles in the header to instantly transform NeonChef's appearance.
6.  **View Results:**
    *   Recipe cards will appear with a title, image (if applicable), metadata (prep time, difficulty, etc.), ingredients, and step-by-step instructions.
7.  **Recipe Actions:**
    *   **Copy:** Click the "Copy Recipe" button to copy the full recipe text to your clipboard.
    *   **Export:** Click the "Export" button to download the recipe as a `.txt` file.
8.  **Developer Info:**
    *   Click the 👨‍💻 icon in the bottom-right corner to toggle the developer info panel.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📜 License

Distributed under the MIT License. See `LICENSE` file for more information (if you add one, otherwise this line is fine).

---

## ✨ Acknowledgements & Creator

*   **Crafted with passion by Dear Virus (Syed Muhammad Khubaib Shah)**
*   Google Gemini API for the AI magic.
*   Inspiration from futuristic aesthetics and the joy of cooking!

---

💖 Thank you for checking out NeonChef! May your culinary adventures be ever more exciting. 💖

--- END OF COPY ---
