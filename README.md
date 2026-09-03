## Beep Timer — Offline Interval Timer
A highly customizable, responsive, and privacy-focused interval timer web application. It allows you to build custom fitness routines with tailored work windows, recovery breaks, and audio cues, keeping your workout data entirely local to your machine.
Live App Link: artbit.github.io/beep-timer
------------------------------
## 🌟 Key Features

* Dynamic Workout Configurator: Define individual movements, attach descriptions (form tips, equipment requirements), and configure custom work/rest durations down to the second.
* Persistent Local Storage: Session structures and user customizations auto-save seamlessly using browser LocalStorage. Enjoy zero user registration, instant reloading, and total offline readiness.
* Advanced Audio Signaling:
* Main Alerts (🔊): Audio notifications to signal interval changes and upcoming blocks.
   * Text-to-Speech (🗣): Native browser speech synthesis reads the workout name and description aloud as it initiates, eliminating the need to watch your screen.
   * Sub-Beeps: Pacing indicators configured to sound halfway through an interval or at quarterly checkpoints.
* Interactive Visual Themes: Switch backgrounds on the fly using native canvas/CSS shaders, featuring: Off, Plasma, Waves, Aurora, Orbs, Gradient, Sunset Pop, Cotton Candy, Ocean Deep, and Forest Moss.
* Global Keyboard Navigation: Accelerate setup and management inside the gym using native shortcuts.

------------------------------
## ⌨️ Keyboard Shortcuts
Speed up operations using direct hotkeys while using the application:

| Key | Action |
|---|---|
| Space | Play / Pause tracking. |
| R | Reset session parameters back to initial state. |
| L | Skip the current tracking block. |
| M | Mute or unmute peripheral sounds. |
| V | Toggle text-to-speech voice narration engine. |
| B | Cycle backwards and forwards through dynamic layouts. |
| F | Toggle Fullscreen distraction-free mode. |
| E | Open / Close session configuration interface. |

------------------------------
## 🛠️ Tech Stack

* HTML5 Semantic Elements: Delivers a fully native layout structure accessible for assistive readers.
* CSS3 Custom Properties: Powers fluid layout sizing across ultra-wide desktops and mobile displays alongside rich, interactive dynamic shader profiles.
* Vanilla JavaScript API: Native processing utilizing the Web Audio API for synthetic audio generations, Speech Synthesis engines for voice overlays, and LocalStorage for application states.

------------------------------
## 🚀 Deployment & Installation
Because this application relies exclusively on standard frontend technologies, there are zero server environments, dependencies, or compilers required.
## Local Development

   1. Download or clone this public directory source:
   
   git clone https://github.com
   
   2. Navigate directly into the local repository target:
   
   cd beep-timer
   
   3. Boot the environment up by opening index.html inside your choice browser.

------------------------------
## 📜 License
Distributed under the open-source MIT License. Check out LICENSE for structural context.
------------------------------
If you'd like to scale your README further, let me know if I should detail how to write custom background presets or draft an architecture breakdown for the Web Audio API generator architecture.

