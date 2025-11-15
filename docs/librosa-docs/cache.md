Source: https://librosa.org/doc/latest/cache.html

Excerpt (Caching):

- Enable cache via LIBROSA_CACHE_DIR env var or os.environ prior to importing librosa
- Cache is implemented with joblib.Memory; can configure LIBROSA_CACHE_MMAP, LIBROSA_CACHE_COMPRESS, LIBROSA_CACHE_LEVEL, etc.
- Cache levels: 10 filter bases, 20 low-level features, 30 high-level features, 40 post-processing
- NOTE: cache has no eviction policy; call librosa.cache.clear() to purge
