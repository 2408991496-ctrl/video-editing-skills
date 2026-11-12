---
name: follow-button-cta
description: Create an end-of-video follow prompt with a readable profile card, a button-click animation, and synchronized click audio.
---
# Follow Button CTA

Use this skill when the user asks for a follow-button animation, a profile card, or a clickable follow prompt at the end of a video.

## Inputs
- The user's profile screenshot or matching project asset, including the correct username and avatar.
- The timing of the closing call to action, such as “Follow me.”
- Any visual reference, the frame dimensions, and the current subtitle style.

## Workflow
1. Base the graphic on the supplied profile. Preserve the username, avatar, and account numbers accurately. If the user requests a number change, edit only the specified field and match the font size, weight, and baseline of neighboring numbers.
2. Bring the profile or account card on screen during the closing spoken prompt. Make it large enough to read without covering the speaker's face or lower subtitles.
3. Make the click unmistakable: move a pointer or hand gesture toward the button, press it, add a brief scale or highlight response, and show the followed state. Synchronize a short click sound to the exact press frame.
4. Hold the account and followed state long enough to recognize them, then end naturally. Keep the sound effect below the final spoken line.
5. If the screenshot cannot be edited directly, create a localized overlay for the button change that matches the original interface.

## Quality checks
Inspect frames before, during, and after the click. Verify account accuracy, clear visual feedback, synchronized audio, readable on-screen text, and an unobstructed face and subtitles. Treat the click as a video animation, not as a real follow action on the account.
