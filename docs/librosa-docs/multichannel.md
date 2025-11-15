Source: https://librosa.org/doc/latest/multichannel.html

Excerpt (Multi-channel):

- By default librosa loads multichannel signals and averages to mono; use mono=False to preserve channels.
- Multi-channel arrays shape conventions: leading dims = channels, trailing dim = time
- Some detectors (beat/onset) return sparse outputs that don't generalize to multi-channel unless sparse=False
- Many functions now accept multi-channel inputs; see doc for exceptions and advanced caveats
