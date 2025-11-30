Aether — Liquid Glass Prompt Enhancer Pro

Aether is a single-file, high-fidelity prompt engineering tool built using HTML, CSS, and Vanilla JavaScript.
It uses the Google Gemini API to convert simple user ideas into professional, production-quality prompts for generative AI models like Midjourney, DALL-E 3, and Stable Diffusion.

Aether features a modern liquid-glass UI, advanced prompt enhancement logic, voice output, multi-model formatting, and smart generation history — all packed into a single HTML file.

✨ Features
🔹 Gemini-Powered Prompt Enhancement

Uses gemini-2.5-flash-preview to analyze, expand, and refine user input.

Considers context, medium, tone, and selected model.

Outputs structured prompts optimized for:

Midjourney v6

Niji 6

DALL-E 3

Stable Diffusion XL (SDXL)

🔹 Neural Text-to-Speech

Integrated gemini-2.5-flash-preview-tts

Reads generated prompts aloud using realistic neural voices.

🔹 Liquid Glass UI

Aesthetic glassmorphism interface

Animated gradients & soft shadows

Fully responsive for desktop & mobile

🔹 Multi-Model Output

Automatically adjusts prompt syntax per selected AI model.

Produces clear, optimized, ready-to-copy output.

🔹 Smart History

Saves your recent prompts and outputs.

Quickly recall previous generations with one click.

🔹 Token Optimization Mode

Special “TOON Mode”

Condenses prompts into token-efficient formats for cheaper and faster use.

🚀 Quick Start
1. Download the File

Download the file:
prompt_enhancer.html

2. Add Your API Key

Aether requires a Google Gemini API key.

Open prompt_enhancer.html in a code editor.

Scroll to the bottom inside the <script> tag.

Find:

const apiKey = "";


Replace with your key:

const apiKey = "YOUR_GEMINI_API_KEY";


Save the file.

Note:
If running in an environment that injects the key automatically (like a preview sandbox), you may leave apiKey empty.

3. Run the App

No installation required.

Just double-click the file:

prompt_enhancer.html


It will open in your browser and run locally.

🛠️ Tech Stack
Category	Technology
Core	HTML5, CSS3, JavaScript (ES6+)
AI	Google Gemini API (gemini-2.5-flash-preview, gemini-2.5-flash-preview-tts)
Icons	Lucide Icons (CDN)
Fonts	Google Fonts — Outfit
Architecture	Single-file client-side tool
📂 Project Structure
prompt_enhancer.html
├── UI (HTML)
├── Styles (CSS: glassmorphism + animation)
└── Logic (JS: Gemini API + History + TTS)


Everything is bundled into one file for simplicity and portability.

📝 License

This project is licensed under the MIT License.
You are free to use, modify, distribute, and enhance.
