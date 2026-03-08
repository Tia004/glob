# Glob

[![License: Non-Commercial](https://img.shields.io/badge/License-Non_Commercial-blue.svg)]()
[![Version](https://img.shields.io/badge/version-1.0.0-lightgrey.svg)]()
[![Platform](https://img.shields.io/badge/platform-Web%20%7C%20iOS%20%7C%20Android-lightgrey.svg)]()

Glob is a scalable, source-available communication platform designed for communities and businesses. It provides high-quality voice, video, and text chat. 

Unlike standard peer-to-peer applications, Glob is built on a Selective Forwarding Unit (SFU) architecture, allowing it to handle hundreds of concurrent users in a single channel with minimal latency and bandwidth usage.

## Features

* **Real-Time Messaging:** Persistent text channels powered by WebSockets.
* **Media Channels:** Low-latency voice and video rooms via WebRTC/LiveKit.
* **Access Control:** Granular permission system and role management.
* **Cross-Platform:** Unified codebase supporting Web, iOS, and Android clients.

## Architecture & Tech Stack

* **Frontend:** React Native / Expo
* **Backend:** Python (FastAPI) / Node.js
* **Database:** PostgreSQL
* **Video Engine:** LiveKit (SFU)

## Getting Started

### Hosted Service
For production use without managing infrastructure, use the official managed service at [Glob Cloud](#).

### Self-Hosting (Personal Use Only)
Glob can be self-hosted using Docker. Ensure Docker and Docker Compose are installed on your system.

```bash
git clone [https://github.com/your-username/glob.git](https://github.com/your-username/glob.git)
cd glob
docker-compose up -d
