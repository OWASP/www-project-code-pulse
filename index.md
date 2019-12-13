---

layout: col-sidebar
title: OWASP Code Pulse
tags: code-pulse
level: 4
type: tool

---


## About Code Pulse

The OWASP Code Pulse Project is a tool that provides insight into the real-time code coverage of black box testing activities. It is a cross-platform desktop application that runs on most major platforms.

## How it works

Code Pulse does its magic by monitoring the runtime of the target application using an agent-based approach. Code Pulse currently supports Java programs, up to Java 11, and .NET Framework programs for CLR versions 2 and 4. It can track code coverage details at the method or source code level to show what's being called and when. Although Code Pulse works for desktop applications, our current focus is on providing the best experience for web application testing. Code Pulse 2.6 incorporates the OWASP Attack Surface Detector and helps you see code coverage details for the endpoints of a web application.

## Why Code Pulse?

Whereas in the past it’s been very difficult to understand which parts of an application a DAST or manual penetration test covered, Code Pulse automatically detects the coverage information while the tests are being conducted and will even make it possible to understand the overlaps and boundaries of the different tools’ coverage.

Code Pulse presents the coverage information in a visual form to make it easy to understand at-a-glance which parts of an application have been covered, and how much. The real-time coverage feedback makes it easy to adjust testing activity based on the observed coverage. In addition for testing activities relying on multiple techniques (a variety of dynamic analysis tools for instance), it’s fairly easy to split up the recorded activity to understand which code was covered by each tool independently or to view where the coverage overlaps between multiple tools.

## Licensing

OWASP Code Pulse project is free to use. It is licensed under the Apache 2.0 License.
