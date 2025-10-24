# SoundLens

SoundLens brings intelligent audio focus management to Linux, automatically pausing background audio when new sounds play. Experience seamless audio handling just like on your smartphone.

## The Problem

How many times have you been listening to music only to have a video drown it out? Or missed notification sounds because media was playing? Manually pausing and resuming apps is frustrating and disruptive to your workflow.

## Our Solution

SoundLens acts as an intelligent audio conductor for your desktop. It automatically manages your audio applications using a smart focus system:

- **Music playing** → You open a video → Music pauses, video plays
- **Video playing** → You get a call → Video pauses, call rings
- **Call ends** → Video automatically resumes
- **Video pauses** → Music automatically resumes

No more manual audio juggling. SoundLens understands context and prioritizes what you're actively listening to.

## How It Works

1. **Monitors** audio streams through PulseAudio or PipeWire
2. **Detects** when new applications start playing sound
3. **Pauses** background applications automatically
4. **Maintains** a smart stack of audio sources
5. **Resumes** previous audio when current sound stops

## Perfect For

- Developers who constantly switch between music, videos, and calls
- Anyone tired of manually managing multiple audio sources
- Linux users wanting a smarter desktop audio experience
- People who appreciate automated, context-aware computing

## Getting Started

SoundLens is currently in active development. Star this repository to stay updated on our release progress and be notified when the first version is ready.

## Contributing

We welcome contributors! Whether you're interested in audio engineering, daemon development, or UI design, there are plenty of opportunities to help build the future of Linux audio management.

---

**SoundLens**: Stop managing your audio. Start experiencing it.