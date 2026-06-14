+++
date = '2025-05-03'
draft = false
title = 'My First Production Issue: what I could and couldn’t do as a new Developer 💥'
tags = ['career', 'learning', 'reflection']
toc= true
readTime= true
showTags = true
+++

## Introduction

I’ve been working at ExxonMobil for about six months now as a new graduate developer. I’m currently the sole developer maintaining our team’s services. For most of that time, things had been running smoothly. There were no incidents, and I felt fairly confident keeping everything stable. That changed when a production issue occurred—one that didn’t directly involve my part of the system, but it still put me in a position where I had to step up. It was a moment that made me realise just how much I didn’t know—and pushed me to grow.

## My Role During the Incident

The issue occurred on May 1, 2025, ironically, on Workforce Day—when business data stopped reaching our services. The root cause turned out to be a certificate issue in the central API gateway, a critical component for routing traffic across all services. As a result, none of the business applications were usable.

## What I Realised

During the incident, I had a humbling realisation:
* I knew far less about the overall system architecture than I thought.
* I couldn’t confidently explain how some of the services I was “responsible” for actually worked.
* When the Business Analyst asked which customers and what kind of data were affected, I couldn’t give a clear answer.
* I hadn’t explored beyond my day-to-day tasks enough to be prepared for unexpected issues.
It was a wake-up call—not because I made mistakes, but because I saw the gaps I hadn’t noticed before.

## What I’m Doing Differently Now

After the incident, I took some steps to level up:
* Mapped out the architecture of all our services—not just the ones I touch daily.
* Documented what I learned, so I have a reference next time.
* Scheduled weekly learning time to read logs, configs, and unfamiliar code paths.

## Conclusion

This was a wake-up call. Production issues have a way of revealing hidden gaps, and I’m grateful I had the chance to discover mine in a relatively low-pressure situation. Next time something breaks, I want to be more than “just available” as I want to be helpful.
