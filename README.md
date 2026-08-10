# Prato de Areia

An interactive audiovisual experiment where sound, movement and touch shape a field of particles inspired by Chladni patterns.

## About

Prato de Areia is an interactive visual experiment built around the relationship between sound and movement.

A field of particles behaves like sand on a vibrating surface, forming constantly changing geometric patterns.

The music controls the evolution of the pattern, while touch interaction allows the user to disturb and influence the particles directly.

The experience is designed to be explored rather than simply watched.

## Interaction

Tap the screen to start the experience.

Once active:

- Music continuously influences the visual pattern
- Bass frequencies trigger changes in the pattern
- Touch pushes and disturbs the particles
- The interface automatically hides while the experience is running
- Tapping again pauses or resumes the music

Two controls are available:

**Areia**
Controls the number of particles in the simulation.

**Movimento**
Controls the amount of random particle movement.

## Visual System

The simulation uses a circular field of particles.

Each particle is influenced by a mathematical function that creates radial and angular patterns inspired by Chladni figures.

The system continuously changes between different radial and angular modes, creating new configurations as the music evolves.

The particle field contains up to 80,000 particles.

## Sound

The project uses `p5.sound` and FFT analysis to analyze the music in real time.

The bass frequency is used as the main trigger for changing the visual pattern.

When the bass reaches a defined threshold, the system selects new radial and angular modes.

This creates a direct relationship between the rhythm of the music and the movement of the particles.

## Touch

Touch interaction creates a local force field around the point of contact.

Particles near the touch point are pushed and rotated, temporarily disturbing the pattern.

This creates a physical relationship between the user and the simulated surface.

## Technology

- JavaScript
- HTML
- CSS
- p5.js
- p5.sound
- Web Audio / FFT

## Project Structure

```text
prato_de_areia/
│
├── index.html
└── song.mp3
```
The visual system, interaction logic and audio analysis are contained in index.html.

Running

Open index.html in a modern browser.
 
For the intended experience:

Disable silent mode
Increase the volume
Tap the screen
Interact with the particle field

Headphones or speakers are recommended.

Concept

The project explores a simple question:

What if music could behave like a physical force?

Instead of displaying sound as a waveform, spectrum or traditional visualization, the project translates audio into the movement of thousands of particles.

The result is a constantly changing visual surface where sound, mathematics and touch interact.

Status

Interactive audiovisual experiment.

Author
João Medeiros
