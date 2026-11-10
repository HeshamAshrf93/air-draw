# air-draw

Draw in the air with your finger in front of a webcam. The app recognizes what you drew and turns it into a 3D object.

> Status: early development.

## Planned features

- [ ] Fingertip tracking from the webcam (MediaPipe Hands)
- [ ] Draw / pause / erase with simple gestures
- [ ] 2D sketch canvas
- [ ] Shape recognition (circle, square, star, arrow, ...)
- [ ] Sketch to 3D: extrude or revolve the drawing into a 3D mesh
- [ ] Optional AI mode: describe or recognize the sketch and generate a matching 3D model
- [ ] Export to glTF / OBJ
- [ ] Automated tests for the drawing and shape logic

## Planned usage

```bash
npm install
npm run dev
```

## Roadmap

1. Project setup: Vite, Three.js, tests, CI
2. Fingertip tracking
3. Drawing gestures
4. Shape recognition
5. Sketch to 3D mesh
6. AI mode
7. Export
8. Docs and live demo

## Privacy

Camera frames are processed locally in the browser and are never uploaded.

## License

MIT, see [LICENSE](LICENSE).

---
Built by [Hesham Ashraf](https://www.linkedin.com/in/hesham-ashrf)
