# Prato de Areia

An interactive audiovisual experiment inspired by the movement of sand on a vibrating surface.

The experience uses particles, sound and touch to create constantly changing geometric patterns.

## About

The project explores the relationship between:

- sound
- vibration
- movement
- touch
- geometric patterns

The visual system is built with thousands of particles distributed across a circular surface. Their movement generates patterns inspired by Chladni figures.

The shape of the pattern changes according to the music, while touch interaction disturbs and moves the particles in real time.

## Interaction

Tap or click the screen to start the experience.

Once active:

- **Touch / pointer** disturbs the particles
- **Music** drives changes in the geometric pattern
- **Bass frequencies** trigger changes in the radial and angular patterns
- **Areia** controls the number of particles
- **Movimento** controls the amount of random movement

The interface automatically hides while the experience is running.

## Technology

- HTML
- JavaScript
- p5.js
- p5.sound
- Web Audio / FFT analysis

## How it works

The experience creates a circular field of particles and calculates their position using a radial and angular function.

The particles are continuously influenced by:

1. A circular Chladni-inspired pattern
2. The movement parameter
3. Touch interaction
4. Audio frequency analysis

The audio is analyzed using an FFT. When the bass reaches a defined threshold, the system randomly changes the radial and angular parameters, creating a new visual pattern.

## Audio

The experience uses a local `song.mp3` file.

Audio starts after the first user interaction to comply with browser autoplay restrictions.

For the best experience, use headphones or speakers and interact with the screen.

## Project Structure

```text
prato_de_areia_touch/
│
├── index.html
└── song.mp3
