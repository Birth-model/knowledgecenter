# Audio Files for Birth Model Knowledge Center

Place your MP3 narration files in this folder using the exact naming convention below.

## Required File Names

| File Name | GIF | Description | Duration |
|-----------|-----|-------------|----------|
| `gif1-narration.mp3` | GIF 1 | Epic Integration | 18-22s |
| `gif2-narration.mp3` | GIF 2 | Patient Arrives | 10-12s |
| `gif3-narration.mp3` | GIF 3 | C-Section Arrives | 10-12s |
| `gif4-narration.mp3` | GIF 4 | Labor Unfolds | 17-20s |
| `gif5-narration.mp3` | GIF 5 | Team Mobilizes | 12-15s |
| `gif6-narration.mp3` | GIF 6 | Nursing Handoff | 45-50s |
| `gif7r-narration.mp3` | GIF 7 | Resident Handoff (SBAR) | 25-30s |
| `gif8-narration.mp3` | GIF 8 | Mobile Notification Settings | 25-30s |
| `gif9-narration.mp3` | GIF 9 | Provider Notifications | 12-15s |
| `gif10-narration.mp3` | GIF 10 | Post-Delivery Workflow | 12-15s |
| `gif11-narration.mp3` | GIF 11 | Vaginal Delivery Note | 25-30s |
| `gif12-narration.mp3` | GIF 12 | C-Section Operative Note | 25-30s |
| `gif13-narration.mp3` | GIF 13 | Mobile Delivery Note | 40-45s |
| `gif14-narration.mp3` | GIF 14 | Unit Intelligence | 10-12s |

## Important Notes

1. **Exact naming required** - The JavaScript looks for files named exactly `{gif-id}-narration.mp3`
2. **Note GIF 7** uses `gif7r` (not `gif7`) - file must be named `gif7r-narration.mp3`
3. Files should be generated using the narration scripts in `birthmodel-narration-scripts-updated.md`
4. Recommended: Generate with ElevenLabs using settings in the narration scripts document

## How Audio Works

- Audio is **ON by default** for all GIFs
- Users click the "🔊 Audio On" button to disable audio
- Audio plays automatically when animation starts
- Audio pauses when animation is paused
- Audio stops when animation is reset or completes
- **Seeking support**: When using the progress bar to seek, audio skips to the proper time

## Folder Structure

```
birthmodel-github/
├── index.html
├── images/
│   ├── BM_App_Icon.png
│   ├── BM_Icon_White.png
│   ├── Birth_Model_Logo.png
│   └── Epic_Logo.png
└── audio/
    ├── README.md (this file)
    ├── gif1-narration.mp3
    ├── gif2-narration.mp3
    ├── gif3-narration.mp3
    ├── gif4-narration.mp3
    ├── gif5-narration.mp3
    ├── gif6-narration.mp3
    ├── gif7r-narration.mp3  ← Note: gif7r, not gif7
    ├── gif8-narration.mp3
    ├── gif9-narration.mp3
    ├── gif10-narration.mp3
    ├── gif11-narration.mp3
    ├── gif12-narration.mp3
    ├── gif13-narration.mp3
    └── gif14-narration.mp3
```

## Currently Included Audio Files

The following audio files are included in this folder:
- ✅ gif1-narration.mp3
- ✅ gif2-narration.mp3
- ✅ gif3-narration.mp3
- ✅ gif4-narration.mp3
- ✅ gif5-narration.mp3
- ✅ gif6-narration.mp3
- ✅ gif7r-narration.mp3
- ❌ gif8-narration.mp3 (pending)
- ❌ gif9-narration.mp3 (pending)
- ❌ gif10-narration.mp3 (pending)
- ❌ gif11-narration.mp3 (pending)
- ❌ gif12-narration.mp3 (pending)
- ❌ gif13-narration.mp3 (pending)
- ❌ gif14-narration.mp3 (pending)
