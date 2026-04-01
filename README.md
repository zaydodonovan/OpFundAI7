## OpFundAI7 (NOW DEPRECATED)
*Developed in November 2023*

A fully automated Python system for managing YouTube and social media workflows using APIs, scraping, and automation. Designed for continuous content generation with minimal input.

---

## Status

This project is **deprecated** and no longer maintained.  
It was built as an experimental automation system and may not work with current APIs.

---

## Features

- **Automated Content Pipeline**  
  End-to-end system that scrapes, processes, uploads, and cleans up video content

- **Continuous Execution Loop**  
  Runs indefinitely with scheduled delays and automation cycles

- **YouTube API Integration**  
  Uploads videos using the YouTube Data API (v3)

- **Web Scraping System**  
  Fetches recent content from public channels

- **UI Automation (PyAutoGUI)**  
  Automates browser interactions where APIs are limited

- **Cloud-Ready Design**  
  Intended for 24/7 execution on remote machines

- **Webhook Integration**  
  Sends files and updates to external services

- **Automatic Cleanup System**  
  Deletes processed files to maintain storage efficiency

- **Self-Installing Dependencies**  
  Attempts to install required Python packages if missing

- **Error Handling & Resilience**  
  Basic handling for API limits and connectivity issues

---

### Experimental Features

- Partial support for:
  - Instagram uploads
  - TikTok uploads
  - Facebook uploads
  - Kick uploads  

*(Not fully implemented)*

---

## Example Use Case

### Automated Clips-Based Content Channel

OpFundAI7 can be used to build a semi-automated content pipeline for short-form or clips-based media channels.

For example, a creator could:

1. **Source Content**  
   Automatically fetch videos from selected public channels (e.g. podcasts, interviews, news)

2. **Process & Clip Content**  
   Send long-form videos to external services (such as OpusClip) to generate short clips

3. **Enhance Metadata**  
   Automatically generate:
   - Titles  
   - Descriptions  
   - Tags & hashtags  
   - SEO-optimized metadata  

4. **Distribute Content**  
   Upload clips to one or multiple platforms in bulk

5. **Automate Workflow**  
   Handle scheduling, uploading, cleanup, and error handling with minimal input

---

### Important Note

This project is intended for educational and experimental purposes.

Users are responsible for ensuring they have the rights to use, modify, and redistribute any content processed through this system, and must comply with platform policies and copyright laws.

---

## Project Structure

- `App.py` – main entry point  
- `Scraper.py` – handles data scraping  
- `UploadVideos.py` – manages video uploads  
- `OpusClip.py` – content processing logic  
- `Google.py` – Google API integration  
- `Alert.py` – logging and alerts  
- `HookSniffer.py` – additional automation logic  

---

## Setup & Configuration

### Required Credentials

#### BrowseAI
https://www.browse.ai/  
- Robot ID: `YOUR-ROBOT-ID`  
- Monitor ID: `YOUR-MONITOR-ID` (optional)  
- API Key: `YOUR-API-KEY`  
- Webhook: `YOUR-WEBHOOK-URL` (optional)

#### Google / YouTube API  
https://developers.google.com/youtube/v3  
- Project Name: `OpFundAI7777777`  
- Project ID: `YOUR-PROJECT-ID`  
- Project Number: `YOUR-PROJECT-NUMBER`  
- Client ID: `YOUR-CLIENT-ID`  
- YouTube API Key: `YOUR-YOUTUBE-API-KEY`  
- JSON File: `Youtube.json`

---

## Environment Setup

This project is designed to run on a cloud machine.

Recommended providers:
- Linode  
- Google Cloud  

Install dependencies:
```pip install -r Assets/Packaged.txt```

---

## Author

Developed by **Zayd O'Donovan**

OpFundAI7 was originally created in November 2023 as an experimental automation project focused on building a fully autonomous content pipeline using APIs, scraping, and cloud execution.

The project was developed as part of early exploration into:
- Automation systems  
- API integration  
- Content pipelines  
- Long-running processes  

### Original Concept

OpFundAI7 was designed around a modular pipeline:

- **OpusClip Module**  
  Utility functions for file handling, system operations, and connectivity checks  

- **Scraper Module**  
  Scrapes random YouTube channels  

- **UploadVideos Module**  
  Handles uploads, webhook delivery, and file cleanup  

- **App.py**  
  Controls the automation loop, scheduling, and error handling  
