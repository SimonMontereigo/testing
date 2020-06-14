
![image](https://drive.google.com/uc?export=view&id=1_8y9jYwp1cFnVYDLkO34DEEdf_cipICh)


[![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
[![star this repo](http://githubbadges.com/star.svg?user=boennemann&repo=badges&style=flat)](https://github.com/boennemann/badges)
[![Build Status](https://travis-ci.org/boennemann/badges.svg?branch=master)](https://travis-ci.org/boennemann/badges)
[![NPM version](https://badge.fury.io/js/badge-list.svg)](http://badge.fury.io/js/badge-list)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)

MIT LICENSE BADGE, OPEN SOURCE, npm version, prs welcome, build passing travis ci 

## Highlights

:rocket:  **FAST** - debugs from Pod level to Ingress level in seconds, not hours

:mag_right: **Visible** - auto-runs kubectl commands at major steps giving you eyes on the process

:vertical_traffic_light: **Lazy-Friendly** - Simple Y/N Questions, Color Highlights (Red / Green) 

:page_facing_up: **Lightweight** - No bulk files, just the essentials

:compass: **Predictable** - Navigation follows this popular troubleshooting guide

## Installation

To install the latest version:

```sh
npm install kcompass
```

## How to Use


#### One Command

```sh
kcompass debug <pod-name>
```

#### Simple Y/N Questions That Quickly Pinpoint Your Errors


```javascript
if (await pod.isRunContainerError()) {
    console.log(
      colors.green(`The issue is likely to be with Mounting Volumes`)
    );
  }
```

## Inspiration

For the Kubernetes war stories: 
https://k8s.af/

For the awesome guide: 



