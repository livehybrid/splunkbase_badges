# Introduction
So you've built a great Splunk app and uploaded to Splunkbase, but the app's Github repo doesnt really show how popular the app is or which versions it supports. 
If you are a fan of using Badges/Shields to show attributes of your projects then this repo will show you how to add Splunkbase badges to them!

Note: This is a personal development and is not supported by, or endorsed by Splunk. 

# Example
<img width="933" alt="Screenshot 2021-03-04 at 07 51 19" src="https://user-images.githubusercontent.com/5527349/109929491-6a100f80-7cbe-11eb-9b9d-73916a61598d.png">

# Code 
| Info | Example | Link |
| ---- | ------- | ---- |
| Splunkbase Downloads | ![Splunkbase Downloads](https://img.shields.io/endpoint?url=https%3A%2F%2Fsplunkbasebadge.livehybrid.com%2Fv1%2Fdownloads%2F4207) | `![Splunkbase Downloads](https://img.shields.io/endpoint?url=https%3A%2F%2Fsplunkbasebadge.livehybrid.com%2Fv1%2Fdownloads%2F<YOUR_APP_ID>)` |
| Splunk Cloud Compatible | ![Splunk Cloud Compatible](https://img.shields.io/endpoint?url=https%3A%2F%2Fsplunkbasebadge.livehybrid.com%2Fv1%2Fsplunkcloud%2F4207) | `![Splunkbase Installs](https://img.shields.io/endpoint?url=https%3A%2F%2Fsplunkbasebadge.livehybrid.com%2Fv1%2Fsplunkcloud%2F<YOUR_APP_ID>)` |
| AppInspect Status | ![Splunkbase AppInspect](https://img.shields.io/endpoint?url=https%3A%2F%2Fsplunkbasebadge.livehybrid.com%2Fv1%2Fappinspect%2F4207) | `![Splunkbase AppInspect](https://img.shields.io/endpoint?url=https%3A%2F%2Fsplunkbasebadge.livehybrid.com%2Fv1%2Fappinspect%2F<YOUR_APP_ID>)` |
| Compatibility | ![Splunkbase Compatibility](https://img.shields.io/endpoint?url=https%3A%2F%2Fsplunkbasebadge.livehybrid.com%2Fv1%2Flatest_compat%2F4207)  | `![Splunkbase Compatibility](https://img.shields.io/endpoint?url=https%3A%2F%2Fsplunkbasebadge.livehybrid.com%2Fv1%2Flatest_compat%2F<YOUR_APP_ID>)` |

# Advanced

# How it works 
tbc 

# ToDo
* Add additional Splunkbase metrics/data points (CIM Compliance, Splunk Enterprise/Cloud compatibility, etc)
* Publish Lambda code to create badges in this repo
* Submit PR to shields.io to incorporate as a supported OOTB endpoint
