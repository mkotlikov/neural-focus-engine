# Neural Phase Locking Focus Engine 🧠🎧

The **Neural Phase Locking Focus Engine** is a browser-based, open-source auditory entrainment tool designed to improve focus and cognitive state. Unlike traditional binaural beat apps that rely on a single mechanism, this engine utilizes a **Dual-Layer Entrainment** strategy to target the brain's synchronization mechanisms from two distinct angles simultaneously.

**Zero Dependencies.** This application is contained within a single HTML file with no external links, CDNs, or third-party scripts. It is privacy-focused and can be hosted offline.

## Core Mechanisms

### 1. Layer 1: Binaural Beats (Internal Entrainment)
*   **Mechanism:** Generates two pure sine waves with a slight frequency difference (e.g., 200Hz Left, 214Hz Right).
*   **Effect:** The brainstem (Superior Olivary Complex) processes this difference to create a perceived "beat" of 14Hz.
*   **Target:** Promotes **hemispheric synchronization** and sets the baseline cognitive state.

### 2. Layer 2: Neural Phase Locking (External Entrainment)
*   **Mechanism:** An Amplitude Modulation (AM) oscillator pulses the volume of the carrier tones at a high speed (Gamma frequencies).
*   **Effect:** The Auditory Cortex directly "locks" onto this physical rhythm.
*   **Target:** Triggers **Gamma synchrony**, associated with high-level information binding and problem-solving.

## The "Golden Ratio" Settings (Defaults)

The app initializes with a specific mix designed for deep work:

*   **Carrier Frequency:** `200 Hz` (Non-fatiguing base)
*   **Binaural Beat:** `14 Hz` (Beta - Active external attention)
*   **Phase Lock (AM):** `40 Hz` (Gamma - Cognitive binding)
*   **The Mix:**
    *   **Brown Noise (60%):** A "sonic wall" to mask external distractions.
    *   **Isochronic Tones (20%):** kept low to prevent listening fatigue.
    *   **AM Depth (40%):** Moderate pulse to trigger phase locking without annoyance.

## User Interface

*   **Aesthetic:** "Slate & Blue" dark mode to reduce eye strain.
*   **Visualizer:** Real-time oscilloscope (HTML5 Canvas) showing phase coherence.
*   **Controls:** Granular sliders for Frequency (Carrier, Beat, AM) and Mixer (Tone, Noise, Depth).
*   **Presets:**
    *   `🚀 Deep Focus` (Beta/Gamma)
    *   `🌊 Flow State` (Alpha/Beta)
    *   `🌙 Relaxation` (Theta)

## Technical Implementation

*   **Stack:** Single-file `index.html` (HTML/CSS/JS).
*   **Audio Engine:** **Web Audio API** (Native).
*   **Precision:** Real-time synthesis using 64-bit floating-point precision. No pre-recorded MP3s.
*   **Brown Noise:** Custom buffer algorithm with 1/f² spectral slope for warmth.

## Usage

Simply open `index.html` in any modern web browser. 

```bash
# To run locally with a simple server (optional, but recommended for some browser security policies)
python3 -m http.server
# Open http://localhost:8000
```