3 Non-Code Production Performance Improvements For Developers
=============================================================

How I turned broken into working without changing my code.

*This is for a talk given at the January 2013 [Unified Diff](http://unifieddiff.co.uk/) meetup. This is a combination of the slides and the notes in text-only form.*

## The Developer Problem-Solving Mindset

You're a developer, you write code. You write code all day long.

You write code to build solutions to problems. You modify code to fix problems with your solutions to problems.

You use code to solve your problems.

I fixed major system-wide performance problems without touching a line of code. The results were orders of magnitude greater than any code change.

## SimlpyTestable.com Test Lifecycle

Simply Testable is a distributed test task management system where each task is a specific test carried out against a specific URL.

It consists of 7 applications communicating over HTTP:

- web interface where the user inputs the site to test, views progress and views results
- core application which breaks down a full-site test into tasks, assigns tasks to workers and recieves results from workers
- 5 workers; a worker performs an assigned task and reports results back to the core application

## Nginx Instead of Apache

content

## Let MySQL Use Tons of Memory

content

## Use `/run/shm` For Non-Permanent File Storage

content
