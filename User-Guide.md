Aether Pro User Guide

Welcome to Aether Pro, a high-fidelity prompt engineering tool powered by Gemini AI. This guide will walk you through the interface and help you generate professional-grade prompts for images, videos, audio, and code.

Interface Overview

The interface is designed with a "Liquid Glass" aesthetic, divided into three main sections:

1. Input Section (Left)

Positive Prompt: The main text area where you describe your core idea (e.g., "A futuristic city in the rain").

Negative Prompt: A secondary area to list elements you want to exclude (e.g., "blur, low quality, text").

2. Control Panel (Right)

Output Type: Select the medium you are generating for. Options include:

Generative Image (Midjourney, DALL-E)

Website UI (Figma descriptions)

Mobile App (App screenshots)

Game Asset (Sprites, textures)

Cinematic Video (Sora, Runway)

Audio/SFX (AudioLDM, Suno)

Model Version: Tailor the output syntax for specific AI models (e.g., Midjourney v6.0 vs. DALL-E 3).

Aspect Ratio: Quick toggle chips for common ratios (1:1, 16:9, 9:16, 4:3).

3. Action Bar (Bottom)

Mode Selectors:

Standard: Generates a descriptive, natural language prompt.

JSON: Outputs structured data object (useful for API integration).

Token Opt (TOON): Generates a condensed, keyword-heavy string to save tokens.

Enhance Button: The "Magic Wand" button that sends your inputs to Gemini AI for processing.

Features

🎲 Surprise Me (Gemini Powered)

Click the Dice Icon in the top-right header. Gemini will generate a unique, creative concept for you to start with.

📜 History Panel

Click the History Icon (clock) to slide out a panel showing your last 10 generated prompts. Click any item in the history to restore it to the editor.

🔊 Text-to-Speech (Read Aloud)

After generating a prompt, click the Speaker Icon in the result box. The tool uses Gemini's Neural Text-to-Speech model to read the prompt back to you, helping you hear the "flow" of the description.

📋 One-Click Copy

Use the Copy Button to instantly copy the generated result to your clipboard, ready to paste into Discord (Midjourney) or your AI tool of choice.

Troubleshooting

"TTS Failed": Ensure your internet connection is stable. The text-to-speech feature requires a call to the Google Cloud API.

Copy Not Working: If the copy button fails, the tool attempts a fallback method. Ensure you have granted clipboard permissions if requested.
