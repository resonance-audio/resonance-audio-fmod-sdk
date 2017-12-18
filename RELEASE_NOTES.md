# Release notes

## Resonance Audio SDK for FMOD v1.1.1

### Bug fixes
* Fixed a bug in stereo deinterleaving input buffer conversion that could lead
  to a crash.

## Resonance Audio SDK for FMOD v1.1.0

### Behavioral Changes
* The reverb brightness and time modifiers in `RoomProperties` adjust the room
  effects more accurately now for long reverb tails.

## Resonance Audio SDK for FMOD v1.0.0

This is the initial release of Resonance Audio SDK for FMOD, which includes:
* 3D audio spatialization
* Ambisonic soundfield rendering
* Room effects rendering with custom surface materials
* Occlusion
* Sound directivity controls
* Source spread controls
* Distance attenuation
