# Podcastle (podcastle)

Podcastle is an AI audio and podcast creation platform whose developer engine, Async, exposes a low-latency Voice API for human-like text-to-speech, a browsable voice library, and instant voice cloning from a short audio sample. The API is served from https://api.async.com and authenticated with an x-api-key header plus a version header. Transcription is a Podcastle platform feature; no standalone transcription endpoint is documented in the public Voice API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/podcastle/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/podcastle/refs/heads/main/apis.yml)

## Tags

- AI
- Audio
- Text to Speech
- Voice Cloning
- Podcasting

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Podcastle Text-to-Speech API

Low-latency, human-like speech synthesis via the Async engine. Batch (/text_to_speech), streaming (/text_to_speech/streaming), word-timestamped (/text_to_speech/with_timestamps), and WebSocket (/text_to_speech/websocket/ws) generation across async_pro_v1.0 and async_flash models.

- **Human URL:** [https://docs.async.com/welcome-to-async-voice-api-990330m0](https://docs.async.com/welcome-to-async-voice-api-990330m0)
- **Base URL:** `https://api.async.com`

#### Tags

- Text to Speech
- Audio
- Streaming

#### Properties

- [Documentation](https://docs.async.com/text-to-speech-18760785e0)
- [API Reference](https://docs.async.com/welcome-to-async-voice-api-990330m0)
- [OpenAPI](openapi/podcastle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/podcastle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/podcastle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Podcastle Voices API

Browse the voice library of predefined and custom voices via POST /voices, with filters for model, language, accent, gender, and style plus cursor-based pagination.

- **Human URL:** [https://docs.async.com/list-voices-16699698e0](https://docs.async.com/list-voices-16699698e0)
- **Base URL:** `https://api.async.com`

#### Tags

- Voices
- Voice Library
- Catalog

#### Properties

- [Documentation](https://docs.async.com/list-voices-16699698e0)
- [OpenAPI](openapi/podcastle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/podcastle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/podcastle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Podcastle Voice Cloning API

Instant voice cloning via POST /voices/clone. Upload a short audio sample (wav, mp3, flac, aiff) as multipart/form-data to produce a production-ready custom voice with no training step.

- **Human URL:** [https://docs.async.com/clone-voice-16699697e0](https://docs.async.com/clone-voice-16699697e0)
- **Base URL:** `https://api.async.com`

#### Tags

- Voice Cloning
- Custom Voices
- Revoice

#### Properties

- [Documentation](https://docs.async.com/clone-voice-16699697e0)
- [OpenAPI](openapi/podcastle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/podcastle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/podcastle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Podcastle Transcription

Transcription and speech-to-text are Podcastle platform features (multi-language transcription with speaker identification) available in the product, console, and credit-based plans. A standalone transcription endpoint is not documented in the public Async Voice API as of the catalog date; this entry is documented as accurately as the public material allows.

- **Human URL:** [https://help.podcastle.ai/en/articles/9903954-generating-and-converting-text-to-speech](https://help.podcastle.ai/en/articles/9903954-generating-and-converting-text-to-speech)
- **Base URL:** `https://api.async.com`

#### Tags

- Transcription
- Speech to Text
- Captions

#### Properties

- [Documentation](https://async.com/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/podcastle-ai)
- [Website](https://podcastle.ai)
- [Documentation](https://docs.async.com)
- [Plans](plans/podcastle-plans-pricing.yml)
- [Rate Limits](rate-limits/podcastle-rate-limits.yml)
- [Fin Ops](finops/podcastle-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
