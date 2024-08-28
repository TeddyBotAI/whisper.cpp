## Prerequisites

### Whisper gguf

```sh
./models/download-ggml-model.sh large-v3   
```

### Tinydiarize

```sh
./models/download-ggml-model.sh small.en-tdrz
```

## Starting the server

Command being:

```sh
./server -m models/ggml-large-v3.bin 
```