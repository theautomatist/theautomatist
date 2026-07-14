<div align="center">

# Carl Kuhligk

**From PCB to firmware to backend to AI — I build the whole chain.**

Practical automation across software and hardware, aimed at real problems.

[![califana.com](https://img.shields.io/badge/califana.com-4ade80?style=flat-square&labelColor=060807)](https://califana.com)
![Germany](https://img.shields.io/badge/Germany-e9e3d1?style=flat-square&labelColor=060807)
![Open to Embedded/IoT & AI roles](https://img.shields.io/badge/open_to-Embedded%2FIoT%20%26%20AI%20roles-4ade80?style=flat-square&labelColor=060807)

</div>

---

## Currently building — Califana

> **Open, local-first hardware for plant care.**
>
> It starts with **Flora**, a soil sensor that measures what actually matters, right at the root:
> no cloud, no subscription, no throwaway batteries. Solar-powered where it makes sense,
> and the software is yours to keep.
>
> **Cura** — the agentic plant-care assistant (RAG, live sensor data, vision) — becomes the brain on top of it.
>
> [**califana.com →**](https://califana.com)

---

## What I work with

|  |  |
| :--- | :--- |
| **Embedded / IoT** | ESP32 firmware in C/C++ · sub-GHz radio (wM-Bus/OMS) · PCB design in KiCad |
| **AI / Data** | B.Sc. Data Science (2026) · RAG agents with LangGraph (bachelor thesis) · local-first AI |
| **Ops** | Proxmox homelab · Docker everywhere · self-hosted services behind SSO |

## Selected work

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **[OMS-Gateway](https://github.com/theautomatist/OMS-Gateway)** | Firmware for a W-MBus/OMS meter gateway — captures telegrams, decodes the link layer, forwards frames to a backend | `ESP32-C3` `CC1101` `C` |
| **[OMS-Bridge](https://github.com/theautomatist/OMS-Bridge)** | The counterpart: decodes OMS telegrams and publishes them to MQTT, with a small UI for key management | `FastAPI` `MQTT` |
| **[KiCad-Parts-Importer](https://github.com/theautomatist/KiCad-Parts-Importer)** | Chrome extension + local backend that turns EasyEDA/LCSC parts into KiCad libraries | `JavaScript` `FastAPI` |
| **[whisper-dictation](https://github.com/theautomatist/whisper-dictation)** | Push-to-talk dictation that never leaves the machine — an offline Wispr Flow | `Python` `faster-whisper` |
| **[whz-lora](https://github.com/theautomatist/whz-lora)** | Self-hosted LoRaWAN base station with a field-measurement cockpit for coverage tests | `ChirpStack` `Docker` |
| **[homelab](https://github.com/theautomatist/homelab)** | The family cloud on a single Proxmox node — sanitized mirror with deep-dive guides | `Proxmox` `Docker` |

<div align="center">
<sub>Running things yourself is the fastest way to understand them.</sub>
</div>
