# Touchless VFX Controller - Project Roadmap

## ✅ Completed Features
These features have been successfully built and shipped to the project:

- [x] **Project Architecture Restructuring:** Extracted monolithic code into clean `index.html`, `main.js`, and `style.css` files.
- [x] **Glassmorphism UI:** Built a highly requested, modern frosted-glass control panel.
- [x] **Intuitive Control Mapping:** Replaced hidden keyboard shortcuts with a clickable, responsive UI.
- [x] **Camera & AI Loading Handlers:** Added a visual text overlay that indicates AI download/initialization progress so the user isn't stuck on a dark screen.
- [x] **Bright Feed Mode:** Removed the dark composite filter for a completely natural, high-brightness camera preview.
- [x] **Auto-Minimizing Layout:** UI collapses down into a compact, light-themed pill when a power is selected. 
- [x] **Draggable Panel Handle:** Allowed unrestricted `.drag-handle` movement anywhere on the canvas.
- [x] **Smart Edge Docking:** Dragging to the far left or right of the screen auto-formats the UI into a space-saving vertical icon strip.
- [x] **Record & Save Video:** Add a recording button that captures the HTML5 Canvas to an `.mp4` or `.webm` file and automatically downloads it directly to your computer.

---

## 🚀 Creative Ideas to Add Next (TODO)
Here are some fun, highly creative enhancements we could tackle next. Keep checking these off as we build them out!

- [ ] **Dynamic Sound Effects (SFX):** Add audio! Deep rumbling sounds when fire is active, crackling electricity for lightning, or charging sounds on pinch gestures.
- [ ] **Intensity Sliders:** Allow the user to manually control the amount, speed, and size of the particles through a UI slider rather than it just being random.
- [ ] **Background Removal (Green Screen):** Utilize Mediapipe's `Selfie Segmentation` model to remove your bedroom/office background and drop you into a Volcano or Outer Space scene when powers are activated.
- [ ] **Screen Shake Mechanics:** Make the entire canvas artificially "shake" during massive energy surges or when both hands violently clap together.
- [ ] **New Power - Matrix Rain:** Drop digital, glowing green code directly from your fingertips.
- [ ] **New Power - Doctor Strange Shields:** Render a glowing, rotating mandala/shield on your palm when you hold your hand fully open and flat.
- [ ] **Face VFX Integration:** Track the face and add glowing eyes, or energy auras that match the selected hand power.
