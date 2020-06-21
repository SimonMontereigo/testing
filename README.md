
<p align="center">
  <img width="174" height="215" src="https://drive.google.com/uc?export=view&id=1_8y9jYwp1cFnVYDLkO34DEEdf_cipICh">
    <h1 align="center">Compass</h1>
</p>


<p align="center">
  
  <img src="https://badges.frapsoft.com/os/mit/mit.svg?v=102)](https://github.com/ellerbrock/open-source-badge/"/>

  <img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/"/>

  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com"/>

  <img src="https://badge.fury.io/js/badge-list.svg"/>
  
  
  <img src="https://travis-ci.org/boennemann/badges.svg?branch=master"/>
</p>



         
<h2 align="center">Quickly Pinpoint Errors in your Kubernetes Deployment</h2>
 
FREEZE FRAME 


### Code Snippet
```javascript
if (await pod.isRunContainerError()) {
    console.log(
      colors.green(`The issue is likely to be with Mounting Volumes`)
    );
  }
```

#### :heavy_check_mark: Simple (Y/N) Questions :heavy_plus_sign: Step by Step Visibility

GIF 

#### :heavy_check_mark: Checkpoints for Error Isolation

GIF

#### :heavy_check_mark: Works on the Pod level all the way up to the Ingress level

GIF

<h2 align="center"> :white_check_mark: Debug Checklist First, :sob: Search Overload Later </h2>

Compass auto-runs kubectl commands & questions based on this popular troubleshooting guide until the error is found.
Credits to XXXXXX for this awesome guide (PDF).


<p align="center">
  <img width="997" height="1308" src="https://drive.google.com/uc?export=view&id=1lzXyq1RY1QFExFK7rWCCLwBNP83Lw7DA">
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

Huge Thanks to the Kubernetes Open Source Community for the Support. If you found this interesting or helpful at all, feel free to drop a :star2: star :star2: on this project to show your support!


Got a suggestion, issue or feedback? Shoot me an email at kubecompass@gmail.com and I'll respond within the day. 



