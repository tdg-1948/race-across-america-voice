# Race Across America voice pack

Offline speech-recognition model used by the "Talk & type" mode of
[Race Across America: The 50 State Road Trip](https://northcurrenttech.com/roadtrip).

- `voice-pack-1.bin` + `voice-pack-2.bin` concatenated = one `.tar.gz` Vosk model (28,336,580 bytes).
- Based on [vosk-model-small-en-us-0.15](https://alphacephei.com/vosk/models) by Alpha Cephei Inc., Apache License 2.0.
- Modified: the general language-model graph (`graph/Gr.fst`) is replaced with an empty graph that keeps the word list,
  because the game always uses its own small grammar (states, capitals, letters). Recognition results are unchanged.

No personal data. Served via jsDelivr.
