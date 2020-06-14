

<p align="center">
  <img width="249" height="307" src="https://drive.google.com/uc?export=view&id=1_8y9jYwp1cFnVYDLkO34DEEdf_cipICh">
    <h1 align="center">Compass</h1>
</p>




[![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
[![Build Status](https://travis-ci.org/boennemann/badges.svg?branch=master)](https://travis-ci.org/boennemann/badges)
[![NPM version](https://badge.fury.io/js/badge-list.svg)](http://badge.fury.io/js/badge-list)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
         
<h2 align="center">A way to quickly pinpoint errors in your Kubernetes Deployment.</h2>
 



GIF


### Code Snippet
```javascript
if (await pod.isRunContainerError()) {
    console.log(
      colors.green(`The issue is likely to be with Mounting Volumes`)
    );
  }
```

#### :heavy_check_mark: Simple (Y/N) Questions :heavy_plus_sign: Step by Step Visibility

#### :heavy_check_mark: Checkpoints for Error Isolation

#### :heavy_check_mark: Works on the Pod level all the way up to the Ingress level


#### Troubleshooting Checklist First, Search Overload Later 

Questions follow this popular troubleshooting guide. Credits to XXXXXX for this awesome guide (PDF).


<p align="center">
  <img width="1500" height="1962" src="https://drive.google.com/uc?export=view&id=1lzXyq1RY1QFExFK7rWCCLwBNP83Lw7DA">
</p>

## Installation

To install via npm:

```sh
npm install kcompass
```

## How to Use


#### One Command

```sh
kcompass debug <pod-name>
```


## Highlights

:rocket:  **FAST** - debugs from Pod level to Ingress level in seconds, not hours

:mag_right: **Visible** - auto-runs kubectl commands at major steps giving you eyes on the process

:vertical_traffic_light: **Lazy-Friendly** - Simple (Y/N) Questions, Color Highlights (Red / Green) 

:page_facing_up: **Lightweight** - No bulk files, just the essentials

:compass: **Predictable** - Navigation follows this popular troubleshooting guide


## Contributors

Contributors Welcome!

Huge Thanks to the Kubernetes Open Source Community for the Support. If you found this interesting or helpful at all, feel free to drop a star on this project to show your support!

Got a suggestion, issue or feedback? Shoot me an email at kubecompass@gmail.com and I'll respond within the day. 



