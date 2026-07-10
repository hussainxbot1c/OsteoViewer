<div align="center">

# OsteoViewer
### Clinical DICOM Viewer for iOS & Android

A professional-grade mobile DICOM imaging app built for radiologists,
dentists, and orthopaedic specialists multi-plane review, precise
measurements, panoramic reconstruction, and AWS cloud storage.

[![Platform](https://img.shields.io/badge/Platform-iOS%20%26%20Android-blue?style=flat-square)]()
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)]()
[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white)]()
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=flat-square)]()

</div>

---
<div align="center">
<img src="https://github.com/hussainxbot1c/OsteoViewer/blob/main/screen%202.png.jpg" width="200"/>
<img src="https://github.com/hussainxbot1c/OsteoViewer/blob/main/screen%201.png.jpg" width="200"/>
<img src="https://github.com/hussainxbot1c/OsteoViewer/blob/main/Screenshot_2026-05-05-22-49-37-18_68e5f902fd7177246c998d894d511aa1.jpg" width="200"/>
<img src="https://github.com/hussainxbot1c/OsteoViewer/blob/main/Screenshot_2026-05-05-22-51-02-17_68e5f902fd7177246c998d894d511aa1.jpg" width="200"/>
</div>

## Overview

OsteoViewer is a production-grade DICOM viewer built for clinical
professionals on mobile. Clinicians can upload DICOM scans, navigate
axial, coronal, and sagittal planes, place precise measurements and
markers, and store studies securely in the cloud all from iOS or
Android without requiring desktop software.

---

## Key Features

### Imaging & Viewing
- Native DICOM scan upload and rendering on mobile
- Multi-plane navigation: axial, coronal and sagittal with synchronised scrubbing
- Smooth frame-by-frame scan navigation with gesture controls

### Measurement & Annotation
- Linear, angular and area measurement tools
- On-image markers, targets and label placement
- Case review annotations saved per study

### Panoramic & Implant Planning
- Panoramic reconstruction mode for dental workflows
- Cross-sectional views for orthopaedic implant planning
- Export-ready views for reporting

### Cloud & Security
- AWS S3 cloud storage with per-account subscription quotas
- OAuth 2.0 secure and federated authentication
- Tiered storage plans gating advanced features
- HIPAA-aligned data handling architecture

---

## Tech Stack

| Layer | Technology |
|---|---|
| Mobile Frontend | Flutter, Dart |
| Backend API | Python, FastAPI |
| Cloud Storage | AWS S3 |
| Authentication | OAuth 2.0 |
| Database | PostgreSQL |
| Imaging | DICOM native rendering |
| Deployment | iOS, Android |

---

## Architecture

```
User uploads DICOM scan
        ↓
FastAPI backend receives and validates file
        ↓
DICOM parsed and stored securely on AWS S3
        ↓
Flutter app renders scan natively on device
        ↓
Clinician navigates planes, places measurements
        ↓
Annotations and markers saved per study in PostgreSQL
        ↓
Panoramic reconstruction computed and rendered
```

---

## Target Users

- Radiologists reviewing scan studies on mobile
- Dentists planning implant procedures
- Orthopaedic specialists reviewing patient imaging
- Clinical teams needing cloud-backed study access

---

## Status

Currently under active development. App Store and Google Play
launch upcoming after QA completion.

---

## Developer

**HUSSAIN AHMED**
Senior Flutter and Mobile AI Developer
8 years experience, 30+ production apps shipped

- Upwork: https://www.upwork.com/freelancers/~01364d92ed7bc15724
- Email: hussainxbot1c@gmail.com
- NourishDoc: https://apps.apple.com/us/app/nourishdoc-midlife-wellness/id6743374362
- MixerCloud: https://apps.apple.com/us/app/mixercloud/id6740339899
- Beautora: https://apps.apple.com/us/app/beautora/id6745489516

---

<div align="center">
Built with Flutter · FastAPI · AWS · OAuth 2.0
</div>
