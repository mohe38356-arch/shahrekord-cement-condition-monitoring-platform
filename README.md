Shahrekord Cement Condition Monitoring Platform

Overview

Shahrekord Cement Condition Monitoring Platform is an offline-first industrial web application designed for equipment condition monitoring, inspection management, vibration analysis, thermography records, oil analysis tracking, and predictive maintenance workflows inside Shahrekord Cement Plant.

The project aims to centralize all machine condition monitoring data into a single equipment-based platform for industrial reliability engineering.

---

Problem Statement

Currently, equipment condition monitoring data is stored in multiple disconnected formats:

- vibration analysis reports
- oil analysis PDFs
- thermography images
- handwritten inspection notes
- manual temperature measurements
- field observations
- audio recordings
- inspection checklists

There is no unified internal platform for:

- equipment-based historical records
- trend analysis
- vibration data registration
- thermography archive
- oil analysis monitoring
- offline field data collection
- synchronization after reconnecting to internal network
- future AI-assisted diagnostics

---

Main Goals

- Equipment-centered asset database
- Measurement point management
- Vibration monitoring data entry
- Oil analysis management
- Thermography image archive
- Inspection checklist workflows
- Audio upload and FFT analysis
- Trend visualization dashboards
- Alert and alarm monitoring
- Offline-first PWA support
- Internal network deployment
- Future-ready local AI integration

---

Planned Technology Stack

Frontend

- React
- TypeScript
- Vite
- Progressive Web App (PWA)

Backend

- FastAPI

Database

- PostgreSQL

Offline Storage

- IndexedDB (Dexie.js)

Charts

- Apache ECharts

Deployment

- Docker Compose

File Storage

- Local object storage / MinIO

---

Industrial Use Case

This platform is being designed specifically for real industrial condition monitoring workflows inside Shahrekord Cement Plant in Iran.

Supported monitoring methods include:

- vibration monitoring
- thermography
- oil analysis
- stroboscope inspection
- visual inspection
- temperature measurement
- audio recording analysis
- FFT spectrum analysis

---

Current Status

Active architecture and system design phase.

Work in progress.

---

Roadmap

- [x] Project scope definition
- [x] System requirements analysis
- [ ] Technology stack finalization
- [ ] Database design
- [ ] Backend API development
- [ ] Frontend development
- [ ] Offline sync engine
- [ ] Dashboard implementation
- [ ] FFT analysis module
- [ ] Internal deployment
- [ ] Future local AI integration

---

Vision

Build a robust internal industrial reliability platform for predictive maintenance and machine condition monitoring with full offline capability and future AI-assisted diagnostics support.
