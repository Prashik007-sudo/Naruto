🌀 Rasengan — Hand Gesture Effect

Summon a Rasengan orb above your open palm using your webcam!

A browser-based project that uses hand gesture recognition to create a Naruto-inspired Rasengan effect in real time.

✨ Features

🖐️ Open-Palm Detection: Summons a Rasengan when an open palm is detected.

👐 Two-Hand Support: Supports up to two hands, with an independent Rasengan for each hand.

🎥 Real-Time Webcam: Uses your webcam to track hand movements.

🔵 Visual Effects: Blends the Rasengan video into the webcam feed using CSS mix-blend-mode: screen.

🌑 Vignette Effect: Adds darkened edges to enhance the visual experience.

⚡ No Build Required: Runs directly in a browser without a JavaScript build system.

🔒 Browser-Based Processing: Hand tracking runs in the browser without a project backend or application code that uploads webcam frames.

🧠 How It Works

The browser accesses the webcam with your permission.

MediaPipe Hands detects hand landmarks and identifies the left and right hands.

The application checks whether at least three fingers are extended.

When an open palm is detected, the corresponding Rasengan video restarts and fades in.

The Rasengan is positioned above the hand using its detected landmarks.

When the palm closes or the hand disappears from view, the effect fades out.

🛠️ Technologies Used

HTML5 — Structures the application and displays the webcam and video effects.

CSS3 — Handles layout, mirroring, vignette effects, and video blending.

JavaScript — Implements gesture detection, positioning, and animation logic.

MediaPipe Hands — Detects hands and estimates their 21 landmarks.

MediaPipe Camera Utils — Captures webcam frames for hand tracking.

jsDelivr CDN — Loads the required MediaPipe libraries.

🙌 Credits

MediaPipe for hand tracking.

jsDelivr for CDN hosting.