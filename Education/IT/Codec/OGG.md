---
tags:
  - audio
  - openContainer
  - open-source
---
- encode with lossy compression.
- for audio, video, text (captions)
- 2-256 channels

**Multiplexing** is method by which transmission of multiple data streams at a lower speed over one communication channel



struct ogg header
    quint32 Signature;
    quint8   Version;
    quint8   Flags;
    quint64 Granule Position;
    quint32 Serial Number;
    quint32 Sequence Number;
    quint32 Checksum;
    quint8   Total Segments;