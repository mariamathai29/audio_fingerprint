this project implements an audio fingerprinting system in python, and is loosely inspired by apps like shazam, as well as reading papers on fingerprinting. it visualizes fingerprint blocks, bit error rates, and waveforms, and ultimately finds the best match from a database of songs, given some noisy clip. when testing this myself, i used Lana Del Rey's **Born to Die** as my song database. 

some visualizations for various songs:

plots for 'Born to Die'

<img width="559" height="435" alt="image" src="https://github.com/user-attachments/assets/8c8a9923-faf6-4958-a64c-41502681cb3b" />
<img width="565" height="435" alt="image" src="https://github.com/user-attachments/assets/a73a1e0f-925a-4f52-819e-dd63c808680f" />

fingerprint blocks for 'Bel Air' (original .wav vs. compressed .mp3); bit error rate was 0.137
<img width="989" height="790" alt="image" src="https://github.com/user-attachments/assets/67e0a44e-ab3f-437e-9752-20644d0ffd1d" />

