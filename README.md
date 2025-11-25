# Realtime Visuals Using Reaper Touchdesigner

## Melodic D&B Track With Real-Time Reactive Visuals  
**By:** David Cendejas Rodríguez & Rafael Vilches Hernández  

## Project Overview
This project consists of composing a melodic Drum & Bass track and creating real-time audio-reactive visuals.  
The song follows a typical D&B structure with a strong drums + bass foundation, enriched with a melodic line that distinguishes it from more conventional D&B styles.  
It is written in C Minor, and the chorus mainly follows a VI – VII – VI – i progression.

The production includes:
- Reverb routing (ReaVerb) on the choir and flute  
- Delay with Ping-Pong effect (ReaDelay) on the main melody  
- Drums created using both Sitala and Vital  
- A slightly 8-bit inspired aesthetic, achieved by tweaking Vital’s default preset (attack, low-pass filter, etc.)

## Visual Effects
For the visuals, we used TouchDesigner, chosen over Reaper’s scripting or Blender due to its power and flexibility.

The visuals react to different musical elements:
- Drums: modify the noise level of a procedural grid  
- Choir: generate an advancing waveform made of animated squares  
- Main melody: drives a cloud of organic particles  
- Bass: controls the intensity of a blue global filter effect

Design decisions were guided by experimentation, tutorials, and programming concepts (automation, data types, functions).

## Tools & Technologies
### Audio
- Reaper for composition, mixing, and mastering  
- Plugins: Vital, Sitala, ReaDelay, ReaVerb, ReaPlugs  
- ReaPlugs was essential for routing audio output into other programs  

### Visuals
- TouchDesigner for node-based real-time graphics (noise, particles, geometry, effects)

## Contributions
- Rafael: Full musical composition (structure, harmony, instrumentation)  
- David: Visual effects and integration between Reaper and TouchDesigner  

## Future Improvements
- Automating the audio-to-TouchDesigner routing via script  
- Creating more complex and polished visual effects as experience increases

The initial code structure for the visual effects was inspired by the tutorial available at [YouTube Tutorial](https://www.youtube.com/watch?v=7tiYVq143gE). Modifications and additions were made to fit the specific needs of this project.
