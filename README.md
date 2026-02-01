# Neural Focus Engine 🧠🎧

The Neural Focus Engine is a browser-based generative audio application designed to enhance cognitive states through Neural Phase Locking.

Unlike traditional playlists or loops, this engine uses real-time generative code to create infinite, non-repetitive musical textures that are modulated at specific brainwave frequencies. The result is a focus tool that helps you enter deep work states without the "listener fatigue" caused by repetitive audio loops.

## Features

### Neural Entrainment Modes

The engine uses Amplitude Modulation (AM) to pulse the audio volume, encouraging neural synchronization:

* Create (Gamma 40Hz): High-frequency pulsing for peak concentration and problem-solving.
* Focus (Beta 14Hz): Alert, sharp pulses for sustained attention.
* Relax (Alpha 10Hz): Smoother pulses for calm and light meditation.
* Sleep (Delta 2Hz): Deep, rolling waves for rest.

### Adaptive Soundscapes

* Ambient Drift: Slow, washing textures optimized for long-duration listening.
* Neuro Flow: Fast, arpeggiated styles with sharp envelopes for high-energy tasks.

### Advanced Controls

* Neural Intensity Slider: Control the depth of the modulation (0% = pure music, 100% = heavy entrainment).
* Real-time Visualizer: See the specific brainwave frequency and note events as they happen.

## Quick Start

Simply open the index.html file in any modern web browser (Chrome, Firefox, Safari, Edge). No server is required for local use.

## Technical Architecture

* Frontend: Pure HTML5, CSS3, Vanilla JavaScript.
* Audio Engine: Web Audio API (Native browser support).
* Synthesis: 
    * Generative Sequencer: Stochastic scheduler picking from a Pentatonic scale.
    * Algorithmic Reverb: Mathematically generated impulse responses using decaying white noise.
    * LFO Modulation: A Low-Frequency Oscillator acts as a "gate" for the master volume to induce phase locking.

## Usage Guide

* Initialize: Click "Initialize Engine" to start the audio context.
* Select Mode: Choose your desired cognitive state (Create, Focus, Relax, Sleep).
* Select Style: Choose between "Ambient Drift" or "Neuro Flow".
* Adjust Intensity: Use the slider to find a comfortable level of pulsing.
    * Tip: 50% is the recommended sweet spot for effective entrainment without distraction.