# Smartphone Accelerometer Validation Against Gold-Standard Bioplux Device

## Project Overview

This project validates the use of a **smartphone accelerometer** as a measurement tool against a gold-standard **Bioplux accelerometer** device. The study investigates whether consumer-grade smartphone sensors can produce data comparable to professional-grade biosignal acquisition hardware, supporting the broader goal of accessible and low-cost biomechanical assessment.

---

## Datasets

The data collected in this project are publicly available on Mendeley Data:

- 📦 **Version 2 (Latest):** [https://data.mendeley.com/datasets/cvfy8gtfn9/2](https://data.mendeley.com/datasets/cvfy8gtfn9/2)
- 📦 **Version 1:** [https://data.mendeley.com/datasets/cvfy8gtfn9/1](https://data.mendeley.com/datasets/cvfy8gtfn9/1)

---

## Devices Used

| Device | Role |
|---|---|
| Smartphone Accelerometer | Device under validation |
| Bioplux Accelerometer | Gold-standard reference sensor |

---


### Dataset Structure version 2
The data is organized into one folder per trial, with a visual directory tree illustrating how each trial folder contains both the smartphone and Bioplux files recorded simultaneously, and the user_data.json
| File | Description |
|---|---|
| `mobile.txt` | Raw accelerometer data from the smartphone per trial |
| `Bioplux.txt` | Raw accelerometer data from the Bioplux device per trial |
| `user_data.json` | Participant metadata and user information |

> ⚠️ All trials were recorded simultaneously across both devices. Each smartphone file corresponds directly to a matching Bioplux file for the same trial.

---
