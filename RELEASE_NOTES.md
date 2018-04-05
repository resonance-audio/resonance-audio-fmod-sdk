# Release notes

## Resonance Audio SDK for FMOD v1.2.1

### Bug fixes
* Fixed a bug where the near-field effect modifiers were assigned to a wrong UI index.
* Minor bug fixes and performance optimizations.

## Resonance Audio SDK for FMOD v1.2.0 (2018-02-20)

### Additions
* Added advanced near-field effect for sound sources less than 1 meter from the listener. Introduced Near-Field Effect toggle and gain adjustment in `Resonance Audio Source` to simulate the effect of sound sources being very close to the listener's ears. Note that this effect could result in up to ~9x gain boost on the source input. Therefore, it is advised to set smaller gain values or reduce the input gain for louder sound sources to avoid clipping of the output signal.

### Behavioral Changes
* Significant CPU performance improvement for reverb times more than 0.6 seconds (thanks to a new spectral reverb implementation under the hood). Also, delivers a slightly brighter sounding reverb.

## Resonance Audio SDK for FMOD v1.1.1 (2017-12-18)

### Bug fixes
* Fixed a bug in stereo deinterleaving input buffer conversion that could lead to a crash.

## Resonance Audio SDK for FMOD v1.1.0 (2017-12-15)

#Behavioral Changes
* The reverb brightness and time modifiers in `ResonanceAudioRoom` adjust the room effects more accurately now for long reverb tails.

## Resonance Audio SDK for FMOD v1.0.0 (2017-12-07)

This is the initial release of Resonance Audio SDK for FMOD, which includes:
* 3D audio spatialization
* Ambisonic soundfield rendering
* Room effects rendering with custom surface materials
* Occlusion
* Sound directivity controls
* Source spread controls
* Distance attenuation
