# Audio Reactive Gaussian Boundary

An interactive web visualization that creates a reactive gaussian boundary that vibrates based on speech input.

## Features

- Gaussian boundary with smooth sinusoidal vibration
- Audio reactive - speaks into your microphone to control the animation
- Colorful smoke particles that move and mix within the container
- Particles react to mouse interaction
- Boundary vibrations are synchronized with speech volume

## How to Use

1. Allow microphone access when prompted
2. Speak to create vibrations in the boundary
3. Click and drag inside the container to disturb the smoke particles
4. The animation pauses when there's no speech detected

## Technical Details

The visualization uses HTML5 Canvas and the Web Audio API to create a dynamic, audio-reactive animation. The gaussian boundary is smoothed using a Gaussian smoothing algorithm to prevent sharp peaks and create a fluid motion.

## License

MIT