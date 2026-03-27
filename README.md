📿 High-Sensitivity Chant Counter
A minimalist, web-based digital Mala (prayer beads) designed for practitioners of meditation, mantra, and chanting. This tool uses the Web Audio API to detect vocal resonance, allowing for hands-free counting, while also supporting traditional manual tapping.

✨ Features
Dual-Mode Counting:

Voice-Activated: Automatically increments the count when it detects your voice.

Manual Tap: Click or tap the center circle to count manually.

Intelligent Logic: * Automatically resets the bead count after 108 repetitions.

Increments the Total Malas counter upon completion of a full cycle.

Real-time Visualizer: A dynamic 3-bar frequency meter that visualizes your vocal input.

Haptic Feedback: Vibrates on mobile devices—a short pulse for beads and a long pulse for a completed Mala (108).

Sensitivity Control: Adjustable slider to fine-tune the microphone threshold based on your environment or vocal volume.

Smart Cooldown: Includes an 800ms "anti-double-count" delay to ensure deep breaths or echoes aren't registered as multiple chants.

🚀 Quick Start
Open the App: Save the code as an .html file and open it in any modern web browser.

Grant Permissions: Click "Tap to Start Listening" and allow microphone access when prompted.

Calibrate: Use the Sensitivity slider.

Lower values are more sensitive (detects whispers).

Higher values require louder sounds (better for noisy environments).

Chant: Begin your practice. The central counter will track your progress.

🛠️ Technology Stack
HTML5 & CSS3: Structural layout and custom animations.

Tailwind CSS: For the clean, stone-and-amber aesthetic and responsive design.

Vanilla JavaScript: Core logic for audio processing and state management.

Web Audio API: Used to create an AudioContext and AnalyserNode for real-time sound analysis.

📝 Usage Notes
Privacy: All audio processing happens locally on your device. No audio data is recorded, saved, or sent to any server.

Environment: For best results, use in a quiet room. If the counter skips or double-counts, adjust the Sensitivity slider.

Browser Support: Works best on Chrome, Edge, and Safari. Mobile browsers require an initial user interaction (the Start button) to enable the Audio Context.

🎨 Customization
You can easily modify the code to fit your specific practice:

Change the Goal: Find if (beads >= 108) in the script and change 108 to your preferred number (e.g., 27 or 54).

Change Cooldown: Adjust the 800 (milliseconds) in the checkVolume function to match the speed of your chanting.
