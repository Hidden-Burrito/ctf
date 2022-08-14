# Alien Communication (Forensics)

## The Challenge

![challenge](images/challenge.png)

We are given a .wav file to download. Given that this is a challenge in the Forensics category, I assume we're going to be looking for something hidden within the file itself rather than trying to decode some alien language.

## Examining the File

![waveform](images/alienAudacity.png)

I opened the file in Audacity and play it, but nothing really stands out. My first guess anytime I'm given a CTF challenge with an audio file is to examine the spectrogram.

![navigation](images/alienMenu.png)


## The Flag

The first guess was correct! The flag was hidden in the spectrogram.

![flag](images/alienSpectrogram.png)
