Starter Audio Dataset (Offline, Synthetic)

All files are mono WAV, 16 kHz, ~6 seconds.

Files:
- clean_music.wav: simple chord progression (harmonics + envelope)
- clean_speechlike.wav: vowel-like synthetic speech (formant filtering)
- clean_percussive.wav: noise bursts (percussive hits)
- noisy_music_snr10.wav: clean_music + white noise (~10 dB SNR)
- noisy_speechlike_snr5.wav: clean_speechlike + white noise (~5 dB SNR)
- speechlike_with_50hz_hum.wav: speechlike + 50 Hz (and 100 Hz) hum
- speechlike_with_echo.wav: speechlike + feedback echo
- echo_far_end.wav: 'far-end' reference signal for echo cancellation
- echo_mic_mixture.wav: simulated microphone signal = echo(far_end) + near-end speech

Tip: You can also record a short voice clip on a phone and copy it as WAV for extra realism.
