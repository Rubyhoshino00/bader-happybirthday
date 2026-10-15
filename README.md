# Moonlit Chapter 25 — Bader's Birthday Visual Novel

A browser-based anime-inspired visual novel gift from Mira to Bader. The title **Chapter 25** is the story title; Bader turns **24** on 18 November 2026 (born 18 November 2002).

## Included features
- Anime-style title screen, layered scene backgrounds, dialogue box, chapter labels and progress indicator.
- Branching choices with different scenes and personalized ending text.
- Typewriter dialogue effect, dialogue log, back/continue controls and keyboard right-arrow support.
- Save/load progress in the current browser using localStorage.
- Procedural ambient music generated locally with Web Audio (no external audio files required).
- Optional browser text-to-speech narration for dialogue. The available voice depends on the device/browser and is not a recorded human voice.
- Auto-advance toggle and a copyable birthday wish.
- Responsive layout for phones and computers; no build step or third-party JavaScript library.

## Publish on GitHub Pages
1. Create/open the repository `moonlit-chapter-25` on GitHub.
2. Upload the **contents** of this folder, not the enclosing folder: `index.html`, `style.css`, `script.js`, and the `assets` folder.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for the Pages deployment and open the URL GitHub displays in Settings → Pages.

## How to use
- Tap **Enter the story**. Browser audio requires a user gesture, so tap Music on if you want the generated soundtrack.
- Tap **Voice on** to use the device's built-in text-to-speech. Voice availability and quality vary by browser and installed voices.
- Use **Save** and **Load** to save/restore progress on the same browser and device. Browser storage is not shared between devices.
- **Auto** advances non-choice dialogue automatically. Choices pause the story until selected.
- Use **Log** to reread earlier dialogue.

## Editing the story
Story nodes and choices are in `script.js` in the `nodes` object. Scene art filenames are mapped in `sceneImages`. Keep filenames and paths consistent when replacing assets.

## Notes
This is a static GitHub Pages site: it does not require a server or API keys. The music is synthesized by the browser and the voice is system text-to-speech, not pre-recorded character acting. For fully voiced professional character performances, replace the browser speech with recorded audio files you have permission to use.
