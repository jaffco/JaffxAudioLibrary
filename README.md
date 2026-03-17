# JaffxAudioLibrary

A Jaffx Audio Module (`.jam`) is a compiled WebAssembly (WASM) binary that exports two functions:

1. `init(samplerate)`
2. `processAudio(float** inputs, float** outputs, unsigned int numSamples)`
