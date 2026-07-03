# SoundStat (soundstat)

SoundStat is an independent audio analysis API that returns detailed per-track features - tempo (BPM), key, mode, energy, danceability, valence, instrumentalness, acousticness, loudness, plus segment and beat structure - for music tracks referenced by Spotify track ID. Launched in early 2025 as an alternative after Spotify deprecated its public audio-features and recommendations endpoints, SoundStat has analyzed several million tracks and layers a rich recommendation engine (similar, feature-target, mixed-seed, mood, activity, time-of-day, cross-genre, DJ-compatible, contrast, hidden-gems, and more) plus genre-and-feature search on top of its analysis corpus. The REST API is authenticated with an `x-api-key` header and billed per unique track analyzed.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/soundstat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/soundstat/refs/heads/main/apis.yml)

## Tags

- Music
- Audio Analysis
- Audio Features
- Recommendations
- Track Analysis
- Spotify Alternative

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### SoundStat Track Analysis API

Retrieve the full audio analysis for a track by its Spotify track ID - tempo, key, mode, key confidence, energy, danceability, valence, instrumentalness, acousticness, loudness, and segment/beat structure - alongside track metadata (name, artists, genre, popularity, duration). Includes a per-track analysis status endpoint (Server-Sent Events over HTTP) for tracks still being processed.

- **Human URL:** [https://soundstat.info/api/v1/docs](https://soundstat.info/api/v1/docs)
- **Base URL:** `https://soundstat.info/api/v1`

#### Tags

- Track Analysis
- Audio Features
- Tempo
- Key

#### Properties

- [Documentation](https://soundstat.info/api/v1/docs)
- [API Reference](https://soundstat.info/api/v1/docs)
- [OpenAPI](openapi/soundstat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundstat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundstat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SoundStat Search & Discovery API

Search the analyzed track corpus by genre with pagination, filter on audio-feature ranges (tempo, energy, danceability, valence, instrumentalness, acousticness, popularity, key, mode), list the available genres, and read corpus-wide analysis statistics such as the total number of tracks analyzed.

- **Human URL:** [https://soundstat.info/api/v1/docs](https://soundstat.info/api/v1/docs)
- **Base URL:** `https://soundstat.info/api/v1`

#### Tags

- Search
- Discovery
- Genres
- Statistics

#### Properties

- [Documentation](https://soundstat.info/api/v1/docs)
- [API Reference](https://soundstat.info/api/v1/docs)
- [OpenAPI](openapi/soundstat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundstat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundstat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SoundStat Recommendations API

A recommendation engine built on the analysis corpus, exposing fifteen strategies - similar tracks, feature-target, mixed multi-seed, harmonic progression, DJ-compatible, contrast, cross-genre, time-of-day, hidden gems, beat-structure, duration, mood, activity, instrumental, and acoustic - each returning ranked tracks with a genre filter and result limit. The similar, feature-target, and mixed endpoints are documented as free to call.

- **Human URL:** [https://soundstat.info/api/v1/docs](https://soundstat.info/api/v1/docs)
- **Base URL:** `https://soundstat.info/api/v1`

#### Tags

- Recommendations
- Similarity
- Mood
- Playlisting

#### Properties

- [Documentation](https://soundstat.info/article/New-Horizons-in-Music-Recommendations.html)
- [API Reference](https://soundstat.info/api/v1/docs)
- [OpenAPI](openapi/soundstat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundstat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundstat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://soundstat.info)
- [Documentation](https://soundstat.info/api/v1/docs)
- [Sign Up](https://soundstat.info/auth.html)
- [Terms of Service](https://soundstat.info/terms.html)
- [Plans](plans/soundstat-plans-pricing.yml)
- [Rate Limits](rate-limits/soundstat-rate-limits.yml)
- [Fin Ops](finops/soundstat-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
