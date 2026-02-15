# Acoustic Phonetics

Analysis of acoustic phonetic features using Praat, covering dysarthric speech therapy evaluation and cross-language vowel formant analysis.

## Project Structure
```
AcousticPhonetics/
├── Task1/   # Cross-language vowel formant analysis (English, French, Japanese)
└── Task2/   # Dysarthric speech analysis before and after therapy
```

## Task 1 — Cross-Language Vowel Formant Analysis

**Languages:** English, French, Japanese

Audio files (`ENG.wav`, `JP.wav`, `FR.wav`) were analyzed using Praat to create phonemic vowel charts for each language. For each vowel sound, the F1 and F2 formant frequencies were calculated by segmenting vowel intervals using Praat annotation tools. Results were recorded in tables and used to construct F1/F2 vowel space charts, enabling cross-language phonetic comparison.

**Key measurements:** F1 (vowel height) and F2 (vowel backness) formant frequencies across all vowel categories in each language.

## Task 2 — Dysarthric Speech Analysis

**Domain:** Clinical speech therapy evaluation

This task involves phonetic analysis of speech samples from patients diagnosed with dysarthria following traumatic brain injuries. Audio recordings capture speech **before and after speech therapy**, enabling acoustic comparison of therapy outcomes.

**Analysis pipeline:**
- Segmentation of utterances into words, syllables, and phonemes using Praat
- Phonetic transcription of selected sentence pairs
- Spectrogram and pitch contour analysis
- Calculation of rhythmic characteristics: articulation rate, speech rate, and pause-to-speech time ratio
- Comparison and interpretation of acoustic changes before and after therapy

Full analysis, spectrograms, graphs, and conclusions are available inside the `Task2/` folder.

## Tools

- **Praat** — phonetic analysis, segmentation, spectrogram generation, formant extraction
- **Audio formats:** WAV files
