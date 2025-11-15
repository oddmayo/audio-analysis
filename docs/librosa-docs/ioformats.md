Source: https://librosa.org/doc/latest/ioformats.html

Excerpt (Advanced I/O Use Cases):

- librosa uses soundfile (pysoundfile) by default and falls back to audioread for unsupported codecs (audioread deprecated as of 0.10)
- Recommend using soundfile for advanced I/O and file-like objects
- Streaming interface: librosa.stream for blockwise reading
- Examples for reading zip files and URL downloads using soundfile
- Writing audio via soundfile: sf.write(..., format='flac')
