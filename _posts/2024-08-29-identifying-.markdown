---
layout: post
title:  "Segmenting Customers & Identifying Needs"
date:   2024-08-29 00:55:08 -0600
categories: update customers stakeholders
---

For this assignment, we had to come up with a product that would solve a customer's problem.

This involves segmenting--we can't just say "everyone." Who has the problem? Why do they have it? Why aren't existing solutions good enough?

I adapted my machine learning class final project to this assignment. There are many popular solutions for face verification using cloud-connected "doorbells" and other devices. In settings where privacy and security are important, the cloud-connectedness is a major problem.

My solution is to perform face-verification on the device itself, so that no face data leaves the device. Furthermore, the device is encrypted and the allow-list face data is stored as vector embeddings rather than full-images. This way, if the device is compromised and decrypted, the embeddings are less likely to be mapped back to the allow-list identities.