+++
title = "APC Injection — Resources"
date = "2026-01-06T19:30:00+00:00"
draft = false
tags = ["APC","injection","resources"]
categories = ["Security","Exploit"]
+++

APC Injection is a technique that uses Windows Asynchronous Procedure Calls to execute code inside another process. This page provides a short summary and downloadable resources (code samples, notes, and a video) to help you explore the topic.

## Summary

The original README (available for download) walks through process/thread basics, virtual memory, memory permissions, shellcode, and APC queues. It explains how attackers prepare an APC injection and the prerequisites for successful attacks, with diagrams and examples.

## Downloads

- [APC early bird 64-bit source](/downloads/apc-early-bird-64-bit.c)
- [APC Simple source](/downloads/apc-simple.c)
- [APC early bird mechanism (handwritten notes, PDF)](/downloads/apc-early-bird-mechanism.pdf)
- [APC injection prerequisites (PDF)](/downloads/apc-injection-prerequisites.pdf)
- [APC early bird demo (video)](/downloads/apc-early-bird-injection.mp4)
- [Full README (original article)](/downloads/README.md)

> Note: Files are provided as-is for study and reproduction. Use these materials responsibly and only on systems where you have explicit permission.
