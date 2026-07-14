<div align="center">

# Carl Kuhligk

### From PCB to firmware to backend to AI — I build the whole chain.

<sub>Practical automation across software and hardware, aimed at real problems.</sub>

[![califana.com](https://img.shields.io/badge/califana.com-4ade80?style=for-the-badge&labelColor=060807)](https://califana.com)
[![GitHub](https://img.shields.io/badge/@theautomatist-e9e3d1?style=for-the-badge&logo=github&logoColor=060807&labelColor=060807&color=e9e3d1)](https://github.com/theautomatist)
![Germany](https://img.shields.io/badge/Germany-060807?style=for-the-badge&labelColor=060807&color=3a4640)

</div>

<br>

<div align="center">

### 🌱 Currently building — **[Califana](https://califana.com)**

**Open, local-first hardware for plant care.**

</div>

It starts with **Flora**, a soil sensor that measures what actually matters, right at the root: no cloud, no subscription, no throwaway batteries. Solar-powered where it makes sense, and the software is yours to keep. **Cura** — the agentic plant-care assistant (RAG, live sensor data, vision) — becomes the brain on top of it.

<div align="center">

`no cloud` · `no subscription` · `built to last` · `open source`

</div>

---

<table>
<tr>
<td width="33%" valign="top">

### Embedded / IoT

![C](https://img.shields.io/badge/C%2FC%2B%2B-060807?style=flat-square)
![ESP32](https://img.shields.io/badge/ESP32-060807?style=flat-square)
![KiCad](https://img.shields.io/badge/KiCad-060807?style=flat-square)

Firmware in C/C++, sub-GHz radio (wM-Bus/OMS), PCB design — from schematic to a board that ships.

</td>
<td width="33%" valign="top">

### AI / Data

![Python](https://img.shields.io/badge/Python-060807?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-060807?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA-060807?style=flat-square)

B.Sc. Data Science (2026). RAG agents for the bachelor thesis, local-first AI on my own hardware.

</td>
<td width="33%" valign="top">

### Ops

![Proxmox](https://img.shields.io/badge/Proxmox-060807?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-060807?style=flat-square)
![nginx](https://img.shields.io/badge/nginx-060807?style=flat-square)

A Proxmox homelab running the family cloud behind SSO. Running things yourself is the fastest way to understand them.

</td>
</tr>
</table>

---

## Selected work

<table>
<tr>
<td width="50%" valign="top">

#### [OMS-Gateway](https://github.com/theautomatist/OMS-Gateway) <sub>⭐ 4</sub>

Firmware for a W-MBus/OMS meter gateway on ESP32-C3 + CC1101. Captures meter telegrams, decodes the link layer, forwards frames to a backend.

<sub>`C` · `ESP32-C3` · `CC1101`</sub>

</td>
<td width="50%" valign="top">

#### [KiCad-Parts-Importer](https://github.com/theautomatist/KiCad-Parts-Importer) <sub>⭐ 4</sub>

Chrome extension plus a local backend that turns EasyEDA/LCSC components into proper KiCad libraries on your own machine.

<sub>`JavaScript` · `FastAPI`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [whisper-dictation](https://github.com/theautomatist/whisper-dictation)

Push-to-talk dictation that never leaves the machine. Hold a key, speak, the text lands at your cursor — an offline Wispr Flow.

<sub>`faster-whisper` · `CUDA`</sub>

</td>
<td width="50%" valign="top">

#### [whz-lora](https://github.com/theautomatist/whz-lora)

Self-hosted LoRaWAN base station with a field-measurement cockpit, built for sensor coverage tests at the university.

<sub>`ChirpStack` · `Docker`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [homelab](https://github.com/theautomatist/homelab)

The family cloud on a single Proxmox node — a sanitized mirror of the real thing, with deep-dive guides.

<sub>`Proxmox` · `Docker` · `SSO`</sub>

</td>
<td width="50%" valign="top">

#### [OMS-Bridge](https://github.com/theautomatist/OMS-Bridge)

The gateway's counterpart: decodes OMS telegrams and publishes them to MQTT, with a small UI for key management.

<sub>`FastAPI` · `MQTT`</sub>

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>

<br>

| Project | What it is |
| :--- | :--- |
| [ShellShock-Live-Mod](https://github.com/theautomatist/ShellShock-Live-Mod) | Reverse-engineering study in C++: pattern scanning, memory analysis, code injection internals |
| [ESP32C3-RGB-M](https://github.com/theautomatist/ESP32C3-RGB-M) | 6+2 channel RGB/CCT controller board for LED strips, runs Tasmota |
| [Chickengate](https://github.com/theautomatist/Chickengate) | ESP32 coop gate that opens and closes with the sun, via Node-RED + MQTT |
| [ATtiny85-Fan-Controller](https://github.com/theautomatist/ATtiny85-Fan-Controller) | USB-to-PWM fan controller for GPU passthrough setups where the host can't read the sensors |
| [Moodle-All-in-One](https://github.com/theautomatist/Moodle-All-in-One) | Nginx + PHP-FPM + MariaDB in one Alpine image, for quick Moodle demos |

</details>

---

<div align="center">
<sub><b>📍 Germany</b> · Open to Embedded/IoT and AI engineering roles</sub>
</div>
