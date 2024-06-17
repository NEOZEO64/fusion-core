# Roadmap FUSION CORE

- Kein Ziel, nur ausprobieren, schauen, wie weit ich komme
    - Arbeiten mit Schaltplänen
        - Was ist möglich mit analogen Schaltungen
    - Designen von Front-Plates mit Fusion 360
- Lernen, lernen, lernen
- Projekt zu groß, Aufteilung in Einzelprojekte nötig
- Grundsätzlich:

- Nebenbei: 
    - Make Bücher durchlesen
    - The Art of Electronics durchlesen
    - Schaltpläne testen

- Kompetenzen:
    - Überblick über alle bekannten elektronischen Bauteile kriegen
    - Was ist mit ihnen möglich? Was sind Edge-Cases?
    - Schaltplan-Design
    - Großes Projekt laufen lassen

## Spezifikationen

- ±12V, 5V Modul-Power-Supply 
- 16cm hoch, breit: n * 2cm

- PCBs:
    - Standard-Grün
- Frontplate Material
    - Holz, lasergecuttet, Eingravierungen
- Knobs: Angeschlossen über Stecker an die Platine
	- Krimp-Zange bestellen


# Level 1: Basic Synth

## Kapitel 1: Gehäuse

<img src="img/Synth Case.jpg"  width=500>

## Kapitel 2: Netzteil

## Kapitel 3: 3x VCO 

Knobs:
- Big Frequency Knob
- Fine Frequency Knob
- PWM Knob

Inputs:
- PWM
- 1V/Oct
- Hard Sync
- Soft Sync

Outputs:
- Triangle
- Sawtooth
- Rectangle

## Kapitel 4: 2x VCF
Knobs:
- Cutoff
- Resonance
- Drive

Inputs:
- Cutoff
- Resonance
- Drive

Output:
- Low Pass
- Band pass
- High Pass

## Kapitel 5: 4x VCA

VU Meter!

Knobs:
- Volume

Inputs:
- Audio in
- CV in

Outputs:
- Audio out

## Kapitel 6: 2x 4-channel Mixer
Knobs:
- Channel 1 Volume
- Channel 2 Volume
- Channel 3 Volume
- Channel 4 Volume

Inputs:
- Audio Channel 1
- Audio Channel 2
- Audio Channel 3
- Audio Channel 4

Output
- Audio Sum

## Kapitel 7: 1x Teensy Reverb / Echo / DISTORTION

Knobs:
- Mode
- Mod 1 (Reverb Room Size    / Echo Clock Speed)
- Mod 2 (Reverb Decay Length / Echo Feedback)

Input:
- Left Audio In
- Optional Right Audio In
- Mod 1 (Reverb Room Size    / Echo Clock Speed)

Output:
- Left Audio Out
- Right Audio Out


## Kapitel 8: Audio Out (Kopfhörer, direkt Boxen)
- Trennung Input / Output durch OpAmp?

- Dual Mono to Stereo
- Headphone Out
- Volume Knob
- Vu Meter

# Level 3: LMNC AAAPPPCCC Module

# Level 4: Triangle to Sine Wave Conversion

# Level 5: Beat Extension

## Kapitel 1: Splitter

## Kapitel 2: Clock

## Kapitel 3: Clock Divider

## Kapitel 4: Counter

## Kapitel 5: ADSR

## Kapitel 6: Manual Trigger / Gate

## Kapitel 7: Sample & Hold

## Kapitel 8: LFO

## Kapitel 9: Constant voltage source

## Kapitel 10: Signal voltage offset