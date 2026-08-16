# Building AI Project
 
## Your idea in a nutshell
An AI-driven enhancement for VIBRAAAX BEATS, a platform tailored for dark, emotional, and cinematic trap music. The system automatically analyzes musical beats (tempo, genre, mood, key) to accurately tag them, detect copyright issues, and recommend the perfect beats to artists and content creators based on their sonic preferences.

## Background
The online music production industry is booming, but music producers struggle to get their unique beats discovered among millions of tracks. For VIBRAAAX BEATS, showcasing unique soundscapes inspired by orchestral soundtracks requires precise targeting. Artists and video creators spend hours searching for the exact emotional or aggressive "vibe". This project aims to bridge the gap by using AI to automate music tagging and provide high-accuracy music recommendations to matching artists.

## Data and AI techniques
- **Data Sources:** Digital audio files (WAV/MP3 from VIBRAAAX), user metadata (genre, BPM, keys), and historical user interaction data (likes, plays, cart additions).
- **AI Techniques:** 
  - **Audio Signal Processing & CNNs (Convolutional Neural Networks):** To analyze audio spectrograms, automatically detecting tempo (BPM), musical key, and dominant instruments.
  - **Collaborative Filtering & Content-Based Filtering:** To power the recommendation engine for buyers.
  - **Natural Language Processing (NLP):** To understand textual search queries like "dark melodic cinematic trap beat."

## How is it used
- **Music Producers / Platform Admin:** Uploads new tracks (like Requiem or Inferno); the AI handles automatic tagging, mood detection, and descriptive generation.
- **Artists & Content Creators:** Receive a personalized feed of music beats that perfectly match their style, vocal range, or video mood.

## Challenges
- **Audio Complexity:** Distinguishing between very subtle sub-genres (e.g., Cinematic Trap vs. Melancholic Orchestral Trap) can sometimes be inaccurate.
- **Data Scarcity:** A new or independent platform faces the "cold start" problem, where the recommendation engine needs initial user interaction data to become highly accurate.
- **Copyright Detection:** Differentiating between a fully original melody and one that uses heavily modified samples is technically challenging.

## What next
The project can expand into an AI voice-matching web tool directly integrated into the website. This would allow artists to hum a melody or record a quick vocal draft, and the AI would immediately generate or find a matching beat from the VIBRAAAX catalog in real-time.

## Acknowledgments
- Inspired by modern music marketplaces like Beatstars and the active VIBRAAAX BEATS platform.
- Developed as part of the *Elements of AI - Building AI* course by the University of Helsinki.

