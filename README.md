# Whisper Local Transcription for Mac

Free, unlimited speech-to-text running locally on your M1 Pro Mac!

## Quick Start

### 1. Run the installer:
```bash
cd ~/Mpc/whisper-docker
./install.sh
```

### 2. Use Whisper:

**Option A - Terminal (Fastest)**
```bash
# Record and transcribe
whisper

# Transcribe a file
whisper audio.mp3
```

**Option B - Menu Bar App**
- Double-click `Whisper.command` on your Desktop
- Click the 🎤 icon in menu bar
- Select "Start Recording"

## Features

- ✅ **100% Free** - No API costs
- ✅ **Private** - Everything runs locally
- ✅ **Fast** - Optimized for M1 Pro
- ✅ **Auto-clipboard** - Text copied automatically
- ✅ **Multiple formats** - MP3, WAV, M4A, MP4

## Docker Commands

```bash
# Start Whisper
cd ~/Mpc/whisper-docker
docker-compose up -d

# Check status
docker logs whisper-api

# Stop Whisper
docker-compose down
```

## Troubleshooting

**"API not running"**
```bash
cd ~/Mpc/whisper-docker
docker-compose up -d
# Wait 30 seconds for model to load
```

**Recording issues**
Install sox: `brew install sox`

## Files Created

- `whisper-transcribe.sh` - Shell script for terminal
- `whisper_menu.py` - Menu bar app
- `test_whisper.py` - Test script
- `app.py` - API server
- `Dockerfile` & `docker-compose.yml` - Container setup

## Enjoy unlimited free transcription! 🎉