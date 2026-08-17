# Awesome-Virtual-Classroom

# Top Virtual Classroom Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Online Teaching, Live Classes, Breakout Rooms, Whiteboards, Polling, LMS Integration & Interactive Learning*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Virtual Classrooms**. These tools enable real-time video/audio, interactive whiteboards, breakout rooms, polling, screen sharing, recording, attendance tracking, and deep LMS integrations for education, training, and online tutoring.

**Examples** include Zoom, Google Meet, Microsoft Teams, BigBlueButton, Class Technologies, LearnCube, Electa Live, Adobe Connect, Engageli, and ClickMeeting (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, education-specific features, privacy, and full control — ideal for schools, universities, training organizations, and developers building transparent virtual learning environments.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Zoom](https://zoom.us/)**  
  Industry-standard video platform widely used for virtual classes, with breakout rooms, polling, whiteboard, recording, AI companion notes, and education-specific plans/add-ons.
- **[Google Meet](https://meet.google.com/)**  
  Browser-based conferencing tightly integrated with Google Workspace and Classroom. Simple joining, Drive recordings, breakout rooms (higher tiers), and strong K-12 / education adoption.
- **[Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams/)**  
  Enterprise collaboration hub with class teams, assignments, gradebook, wellbeing tools, and deep Office 365 / OneNote integration — ideal for institutions already in the Microsoft ecosystem.
- **[BigBlueButton](https://bigbluebutton.org/)**  
  Purpose-built open-source virtual classroom (also available as managed hosting) with multi-user whiteboard, breakout rooms, polling, shared notes, learning analytics, and excellent Moodle/Canvas integration.
- **[Class Technologies](https://www.class.com/)** (formerly Class for Zoom / Blackboard Collaborate lineage)  
  Virtual classroom layer optimized for active learning, engagement analytics, and institutional LMS ecosystems.
- **[LearnCube](https://www.learncube.com/)**  
  Education-focused virtual classroom designed for online tutoring and language schools, featuring interactive whiteboard, content sharing, and teaching-specific tools.
- **[Electa Live](https://www.e-lecta.com/)**  
  Virtual classroom platform oriented toward interactive online teaching with whiteboard, breakout capabilities, and content tools.
- **[Adobe Connect](https://www.adobe.com/products/adobeconnect.html)**  
  Mature enterprise virtual classroom and webinar platform with custom layouts, persistent rooms, SCORM support, strong compliance features, and high customization for corporate training and education.
- **[Engageli](https://www.engageli.com/)**  
  Active-learning virtual classroom platform emphasizing measurable participation, analytics, and pedagogical features for higher education, K-12, and corporate L&D.
- **[ClickMeeting](https://clickmeeting.com/)**  
  Webinar and virtual classroom platform with easy setup, interactive tools, branding options, and support for training/webinar-style sessions.

## Open-Source GitHub Projects
- **[BigBlueButton](https://github.com/bigbluebutton/bigbluebutton)**  
  The leading open-source virtual classroom platform (LGPL). Built specifically for education with multi-user whiteboard, breakout rooms, polling, shared notes, recording, learning analytics, and deep LMS integrations (Moodle, Canvas, etc.). Highly scalable with load balancers (Scalelite, etc.).
- **[Jitsi Meet](https://github.com/jitsi/jitsi-meet)**  
  Popular open-source (Apache 2.0) WebRTC video conferencing platform. Easy self-hosting, end-to-end encryption options, screen sharing, chat, recording (via Jibri), mobile apps, and no account required for participants. Excellent general-purpose and education use.
- **[OpenMeetings](https://github.com/apache/openmeetings)**  
  Apache open-source web conferencing and collaboration system with video/audio, whiteboard, chat, file sharing, recording, and virtual meeting rooms suitable for classrooms and group work.
- **[Nextcloud Talk](https://github.com/nextcloud/spreed)**  
  Open-source video/audio calling and chat integrated into Nextcloud. Self-hosted, privacy-focused, supports screen sharing and group calls; ideal when already using Nextcloud for files and collaboration.
- **[Galene](https://github.com/jech/galene)**  
  Lightweight, easy-to-deploy open-source videoconferencing server (MIT). Focuses on simplicity, performance, and self-hosting for smaller to medium groups.
- **[MiroTalk](https://github.com/miroslavpejic85)** (SFU / P2P variants)  
  Self-hosted open-source WebRTC video conferencing solutions with different architectures (SFU and P2P) for flexible deployment.
- **[PlugNMeet](https://github.com/mynaparrot/plugNmeet-server)**  
  Modern open-source WebRTC-based conferencing platform optimized for performance and low latency, suitable for virtual classrooms and meetings.
- **[OpenTalk](https://opentalk.eu/)** (and related European open-source efforts)  
  Privacy- and security-focused open-source conferencing solutions often used in education and public-sector deployments in Europe.
- **[eduMEET](https://github.com/)** / community instances  
  Open-source video conferencing platform supported by research/education networks (GÉANT ecosystem) for academic use.

### Additional Strong Open-Source Options
- **LMS platforms with built-in or deep virtual classroom integration**: Moodle (with BigBlueButton plugin), Canvas LMS (open core), Open edX, Chamilo, ClassroomIO, LearnHouse — all self-hostable.
- **Load balancers & frontends for BigBlueButton**: Scalelite, Greenlight, b3lb, BBBeasy, Pilos, and related tools for multi-server education deployments.
- **WebRTC stacks & media servers**: LiveKit, mediasoup, Janus, Pion, Kurento, and related libraries for building custom virtual classroom features.
- **Collaborative whiteboards and annotation tools** that pair with video platforms.
- Community **recording, analytics, attendance, and polling extensions** for education-focused deployments.
- Many smaller **self-hosted meeting tools**, **Jitsi forks** (e.g., Infomaniak kMeet), and **privacy-first European alternatives**.

**Frameworks for building custom systems**: Combine **BigBlueButton** or **Jitsi Meet** as the core real-time engine with an open-source LMS (Moodle/Canvas/Open edX), Scalelite for scaling, Greenlight or custom frontends for room management, and tools like n8n or custom scripts for attendance/recording workflows. Ideal for full data ownership, GDPR compliance, and institutional control.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Virtual classroom tools process student data and must comply with education privacy regulations (FERPA, GDPR, COPPA, etc.).
- Self-hosted open-source solutions require proper server capacity, security hardening, TURN/STUN configuration, monitoring, and operational expertise for reliable production use.

---
**Made for educators, instructional designers, schools, universities, and edtech developers.**  
Let's make virtual classrooms more open, interactive, and accessible.
