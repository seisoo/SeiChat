# SeiChat
## EARLY STAGES

A WebRTC-based C# project (WPF client + ASP.NET Core backend) for secure real-time communication using DTLS-SRTP (transport encryption) plus encrypted file and data transfer. It supports voice/video calls, webcam calling, and screen sharing, with connectivity via P2P with RELAY fallback or RELAY-only, powered by coturn (TURN/STUN) with rotation-key login. Features include TOFU, 2FA, roles/permissions, servers and channels (voice & text), 18+ channels, invite/admin-authorized joins, and open registration via email + CAPTCHA. Audio bitrate is configurable from 8 kbps to 320 kbps.

## Client
![img](https://github.com/seisoo/SeiChat/blob/main/screenshot_1_3_5.png?raw=true)


## Server
Is currently hosted via docker compose and custom image
