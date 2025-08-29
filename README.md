# Facial Recognition Software with Masks and Body Points Overlay

This project is a browser-based application hosted on GitHub Pages that uses MediaPipe's Holistic Landmarker for real-time detection of face landmarks, body pose points, and hand landmarks. It includes segmentation masks for the body, which are overlaid semi-transparently. The app plots all detected points on a canvas UI overlay.

## Features
- Real-time webcam video processing.
- Face landmark detection (robust to masks, though accuracy may vary).
- Body pose estimation and plotting of all body points.
- Hand landmark detection.
- Body segmentation masks for privacy or effects.
- Fully client-side, no server required.

## Setup
1. Clone this repository or download the files.
2. Open `index.html` in a modern browser (Chrome recommended for best performance).
3. Click "Start Webcam" and allow camera access.

## Deployment on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` and this README.md to the root.
3. In repository Settings > Pages, select "main" branch as source.
4. Visit `https://yourusername.github.io/your-repo-name/` to see the live site.

## Dependencies
- MediaPipe Tasks Vision (loaded via CDN, no installation needed).

## Notes
- This is for educational purposes. Facial recognition with masks may not be 100% accurate.
- Ensure your browser supports WebAssembly and GPU acceleration for optimal performance.
- No additional files needed; everything is in `index.html`.

## License
MIT License. Feel free to modify and use.
