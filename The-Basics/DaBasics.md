# [🔊 What is Sound ?](/The-Basics/What-Is-Sound.md)

## Basic Audio Concepts

### Sound Waves and Frequency

Sound is a pressure wave. Its pitch is determined by frequency (cycles per second, Hz), and its loudness by amplitude. Humans hear roughly 20 Hz–20 kHz ￼. For example, deep bass is near 20–60 Hz, vocals and guitars occupy midrange, and cymbals and sibilance are in the upper range. Modern audio workstations and speakers are designed around this range ￼ (see diagram below).

![The human audible spectrum spans ~20 Hz–20 kHz](/The-Basics/Audio-Spectrum.png)

### Analog vs. Digital Audio

Analog audio is a continuous waveform that directly represents sound (captured by microphones, tape machines, vinyl, etc.) ￼. Digital audio converts sound into discrete numbers by sampling: at each instant (sampling rate) the waveform’s amplitude is measured and stored in binary ￼. Common sampling rates are 44.1 kHz (CD quality) and 48 kHz (video standard), with higher rates (96–192 kHz) for high-resolution audio ￼. Bit depth (e.g. 16-bit, 24-bit) determines resolution and dynamic range ￼. Higher bit depth and sampling rate capture more detail and dynamic range, at the cost of larger file size.

### Signal Path (Flow)

A clean signal path is crucial. An audio signal flows from source (e.g. mic or guitar) through preamps, processors, and into the DAW, then back out to monitors. For example: Mic → Preamp (gain boost) → EQ/Compression → Audio Interface → Computer/DAW → Monitors. Every device can introduce noise or distortion, so cables should be good quality and gain staged properly ￼ ￼. Engineers must check each connection and level to preserve clarity.

### Decibels (dB) and Levels

Audio levels are measured in decibels (dB), a logarithmic unit expressing a ratio of power or amplitude ￼. In audio engineering, we use dB to compare signal strengths and adjust gain. A 10 dB increase corresponds to a tenfold power increase. Because it’s logarithmic, decibels mirror human hearing: a +10 dB change sounds about twice as loud. Correct gain staging (avoiding both noise floor and clipping) relies on understanding dB levels.

### Equalization (EQ)

Equalization is the process of boosting or cutting specific frequency bands ￼ ￼. Since each instrument occupies different frequency ranges, EQ balances the mix. For example, if two instruments mask each other, an engineer might cut one’s frequency region and boost the other’s to reduce masking. EQ can be:
	•	High-pass/Low-cut: remove unwanted rumble (low frequencies).
	•	Shelving: boost/cut all frequencies above or below a cutoff (like a bass or treble control).
	•	Parametric Bands: precise boosts/cuts at chosen frequencies with adjustable width (Q).

EQing shapes tone: cutting muddy low-mids, adding presence (around 2–6 kHz) for clarity, or trimming harsh highs. Remember: EQ sculpts existing frequencies; it doesn’t create new ones ￼ ￼. Careful EQ use (and referencing a clear commercial mix) yields a balanced spectrum.

### Dynamics (Compression, Limiting)

Compression reduces dynamic range by attenuating loud passages and/or boosting quiet ones ￼. This makes the volume more consistent and can add “punch.” For instance, a drum compressor might reduce the peaks of a snare, allowing the overall snare level to be raised without clipping. Over-compressing can cause pumping (audible gain modulation) or a lifeless sound. A limiter is a strong compressor that prevents peaks from exceeding a set level, used to avoid clipping on the master bus. Proper use of compression controls transients (sharp attacks) and maintains fullness.

### Time Based Effects (Reverb, Delay)

Reverb simulates reflections in a space, adding a sense of depth and immersion ￼. Shorter reverb makes a vocal sit nicely in a small room, while longer reverb can give a grand, ambient feel. Delay repeats the audio after a set time, creating echo effects ￼. These effects enhance space: for example, applying reverb to drums and panned reverbs can increase perceived depth ￼. In moderation, reverb/delay glue a mix together; too much can wash out clarity.

### Monitoring and Analysis

Accurate listening is vital. Studio monitors (speakers) are designed for flat frequency response, so you hear the mix without coloration ￼. Headphones (especially high-quality closed or open-back cans) allow detailed listening, useful when speakers aren’t feasible ￼. Visual tools also help: meters and spectrograms show levels and frequency content in real-time ￼. For example, peak/RMS meters ensure you’re not clipping (exceeding 0 dBFS), and spectrograms can reveal unwanted resonances or imbalance. Together, critical listening and metering help make informed mixing decisions.