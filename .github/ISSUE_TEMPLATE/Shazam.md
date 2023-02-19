
### How does Shazam work? Music Recognition Algorithms, Fingerprinting, and Processing

### URL 
(https://www.toptal.com/algorithms/shazam-it-music-processing-fingerprinting-and-recognition#:~:text=The%20Shazam%20algorithm%20distills%20samples,each%20other%20within%20a%20song)

### Summary
This article covers the main step of music information retrieval to be used for shazam. The five steps included are initial song, Capturing, Conversion to Frequency Domain, Fingerprinting, and Storage.

### Key Points 
- Music recognition programs identify songs from small snippits of the song (known as samples)
- MIR turns audio into digital graphs of the sound wave with time on the x-axis and frequency on the y-axis
- The algorithm creates fingerprints from these spectrograms, which are essentially a condensed representation of the audio data. These fingerprints are created by taking a small window of the spectrogram and hashing the values into a compact code.
- All fingerprints are stored in a database, when a program is trying to identify a song, it will find the various fingerprints that match most and gives the user the song with the highest relevency.
- Some key algorithms and methods are covered including the Discrete Fourier Transform, Fast Fourier Transform, Cooley-Tukey algorithm, and the Nyquist-Shannon Theorem

### Citation
Jovanovic, Jovan. “How Does Shazam Work? Music Recognition Algorithms, Fingerprinting, and Processing: Toptal®.” Toptal Engineering Blog, Toptal, 2 Feb. 2015, www.toptal.com/algorithms/shazam-it-music-processing-fingerprinting-and-recognition#:~:text=The%20Shazam%20algorithm%20distills%20samples,each%20other%20within%20a%20song. 


