Source: https://librosa.org/doc/latest/core.html

Excerpt (Core IO and DSP):

Audio loading
- load(path, [sr, mono, offset, duration, ...]) — Load an audio file as a floating point time series.
- stream(path, *, block_length, frame_length, ...) — Stream audio in fixed-length buffers.
- to_mono(y) — Convert an audio signal to mono by averaging channels.

Spectral representations
- stft(y, [n_fft, hop_length, ...]) — Short-time Fourier transform (STFT).
- istft(stft_matrix, ...) — Inverse STFT.
- cqt, icqt, pseudo_cqt, vqt, fmt, magphase, griffinlim

Time / frequency / pitch utilities (frames_to_time, time_to_frames, hz_to_mel, note conversions, etc.)
