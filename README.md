<p align="center">
  <a href="https://desk.hsslive.cn" target="_blank">
    <img width="200" src="https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/img/logo.png?raw=true" alt="BilldDesk logo" />
  </a>
</p>

<h1 align="center">
  BilldDesk
</h1>

<p align="center">
  Remote desktop control built with Vue3 + WebRTC + Node.js + Electron
</p>

<div align="center">
  
![stars](https://img.shields.io/github/stars/galaxy-s10/billd-deskields.io/github/forks/galon](https://img.shields.io/github/package-json/v/galse](https://img.shields.io/github/license/galaxy-s10/b://img.shields.io/github/languages/top/galaxy-s10/b://img.shields.io/github/languages/top/galaxy-s10/bage](https://img.shields.io/github/languages/top/galaxy-s10/billd-desk-flutter)

</div>

## Introduction

BilldDesk is a remote desktop control software that currently implements features similar to ToDesk, Sunflower (向日葵), and other remote desktop tools.

## Comparison with ToDesk Free Personal Version
The author has used many remote software tools: TeamViewer, Sunflower, ToDesk, AnyDesk, RustDesk, UU Remote, Lianlian Control, and QQ's built-in remote assistance, etc. But uses ToDesk free personal version more often, so here is a comparison between ToDesk and BilldDesk:

| Feature | BilldDesk (Free) | ToDesk Free Personal Version |
| --- | --- | --- |
| Connection Limit | Unlimited, free | 200 times/month, max 80 hours/month connection, need pro version (¥24/month) after that |
| Image Quality Limit | Unlimited, free | Max 1080p, 30fps |
| Android Remote Control | Supported, free | Not supported, requires pro version (¥24/month) or plugin (¥15/month) |
| Multi-screen Display | Supported, free | Not supported, requires performance version (¥95/month) |
| Screen Wall | Supported, free | Not supported, requires ToDesk Enterprise (¥805/year) |
| Remote Recording | Supported, free | Not supported |
| Webpage Initiated Remote | Supported, free | Not supported, requires ToDesk Enterprise (¥805/year) |
| Remote Control Webpage (View Only) | Supported, free | Not supported |
| Multiple Controllers on Same Account | Supported, free | Supported, requires plugin (¥233/month) |
| Private Deployment / Secondary Development | Supported, open source, free | Not supported, requires ToDesk Enterprise, pricing unknown |

## Ecosystem

| Project Name | Repository | Stars & Forks | Online/Download Link |
| --- | --- | --- | --- |
| Remote Desktop Web/Client | billd-desk | [![GitHub stars](https://img.shields.io/github/stars/galaxy-s10/billd-desk?label=star&logoHub forks](https://img.shields.io/github/forks/galaxy-s10/billd-desk?label=fgithub.com/galaxy-s10/bill | https://desk.hsslive.cn |
| Remote Desktop Backend | billd-desk-admin | [![GitHub stars](https://img.shields.io/github/stars/galaxy-s10/billd-desk-admin?label=starb.com/galaxy-s10/billd-desks](https://img.shields.io/github/forks/galaxy-s10/billd-desk-admin?label=forkb.com/galaxy-s10/billd-desk | https://desk-admin.hsslive.cn |
| Remote Desktop Mobile | billd-desk-flutter | [![GitHub stars](https://img.shields.io/github/stars/galaxy-s10/billd-desk-flutter?label=starb.com/galaxy-s10/billd-desks](https://img.shields.io/github/forks/galaxy-s10/billd-desk-flutter?label=fgithub.com/galaxy-s10/bill | https://desk.hsslive.cn/#/download |
| Remote Desktop Server | billd-desk-server | [![GitHub stars](https://img.shields.io/github/stars/galaxy-s10/billd-desk-server?label=starb.com/galaxy-s10/billd-desks](https://img.shields.io/github/forks/galaxy-s10/billd-desk-server?label=forkb.com/galaxy-s10/billd-desk | https://desk-api.hsslive.cn |

## Features

- ✅ Control PC from web page
- ✅ Control Android from web page
- ✅ Control web page from web page (view only)
- ✅ Control PC from PC
- ✅ Control Android from PC
- ✅ Control web page from PC (view only)
- ⏳ Control PC from Android (TODO)
- ⏳ Control Android from Android (TODO)
- ⏳ Control web page from Android (view only, TODO)
- ✅ Multiple devices remotely controlling one device simultaneously
- ✅ One device remotely controlling multiple devices simultaneously
- ✅ Multi-screen operation
- ✅ Connection authentication
- ✅ Custom device code
- ✅ Custom interfaces (WSS/API/relay servers)
- ✅ Keyboard shortcuts
- ✅ File transfer
- ✅ Auto start on boot
- ✅ Screen lock keep-alive
- ✅ Screen wall
- ✅ Supports macOS
- ✅ Supports Windows
- ✅ Supports Linux (untested)
- ✅ Supports Android (Flutter)
- ✅ Supports iOS (Flutter)
- ✅ Backend management
- ✅ One-click Docker deployment
- ✅ Supports private deployment

More features: [features.md](features.md)

## Preview
Try it quickly: https://desk.hsslive.cn

### Web/PC controlling PC
![img](https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/readme_img/PC controlling Android)

![img](https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/read Web/PC controlling web page (view only))

![img](https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/readme_img mobile homepage)

![img](https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/readme_img/777.png?raw mobile control page)

![img](https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/readme_imgen wall)

![img](https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/read Android controlling PC [TODO])

### Android controlling Android [TODO]
### Android controlling web page (view only) [TODO]
### File transfer
![img](https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/readme_img/666.png?raws-platform support)

![img](https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/read Technology Stack)

### Frontend: Vue3 and related tech stack, Typescript, WebRTC, WebCodecs, Web Worker, Web Audio, Canvas

### Backend: Node.js and related tech stack, Koa2, Typescript, Sequelize, MySQL, Redis, Socket.io

### Desktop Client: Electron and related tech stack, WebRTC

### Mobile Client: Flutter3 and related tech stack, WebRTC

### Streaming Server: SRS, FFmpeg, Coturn

### Docker

### Deployment: Alibaba Cloud DevOps, billd-deploy

## Local Startup
https://desk.hsslive.cn/s/qk

billd-desk(pro) see [start-client.md](start-client.md)

billd-desk-server(pro) see [start-server.md](start-server.md)

billd-desk-flutter(pro) see [start-app.md](start-app.md)

## API Documentation
See [apifox](apifox)

## Performance Testing
See [benchmarking.md](benchmarking.md)

## FAQ
See [faq.md](faq.md)

## Feedback
Welcome to submit issues

## Contributions
Welcome to submit pull requests

## Private Deployment
BilldDesk is fully open source (commercial use allowed), welcome to deploy!

## Client Download
https://desk.hsslive.cn/s/bd
Backup link: https://pan.quark.cn/s/2acbf2d49603

## Official Group
![img](https://github.com/galaxy-s10/billd-desk/blob/main/src/assets/readme_img/wechat_groui-platform Support)

### Windows

### macOS

### Linux

### Android 12+ (lower versions untested)

## Contributors
<a href="https://github.com/galaxy-s10/billd-desk/graphs/contributors" target="_blank">
  <img width="200" src="https://contrib.rocks/image?repo=galaxy-s10/billd-desk" alt="BilldDesk contributors" />
</a>

## Origin
This project started as a derivative of billd-live, but later the author found remote desktop interesting and has continued to improve it.

## Vision
Although many remote software tools offer free versions, their free features are limited. For example, some ordinary personal users may only need to remotely control an Android phone temporarily but have to pay for a monthly subscription. BilldDesk improves these basic functions to make them accessible to ordinary users.
