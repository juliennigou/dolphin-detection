# 🐬 Dolphin Fin Detection and Identification Project


|                                                                                 |                                                                                                |
| ------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **Figure A - Dolphin in the Wild** Original field image before model inference. | **Figure B - Fin Detection Result** Model output with dolphin fin localized by a bounding box. |




A computer vision project designed to support dolphin monitoring and conservation from photo datasets.
The work is organized in two stages:

- Stage 1: detect dolphin fins in images.
- Stage 2: identify individual dolphins from detected fins.

## Project Snapshot


| Item              | Details                                                            |
| ----------------- | ------------------------------------------------------------------ |
| Domain            | Marine computer vision                                             |
| Primary Goal      | Build an end-to-end dolphin monitoring workflow from raw photos    |
| Stage 1           | Fin detection (completed)                                          |
| Stage 2           | Individual identification (in progress)                            |
| Data Source       | Dolphin image dataset prepared from field collections and Roboflow |
| Human-in-the-loop | Yes, via review workflow for prediction validation                 |


## Context

Field campaigns can generate thousands of dolphin images.
Manual review alone is slow and difficult to scale.

This project helps teams move faster by pre-detecting fins, organizing candidate images, and preparing data for expert validation.
The final objective is to make long-term dolphin tracking more reliable by combining model assistance with human expertise.

## What Has Been Done

- Built and validated a dolphin fin detection stage with strong results.
- Generated visual outputs and prediction artifacts for review.
- Set up the foundation for an active-learning style loop with human validation.

## Current Focus

The active phase is individual dolphin identification.
The goal is to connect each detection to a specific dolphin identity over time, enabling stronger ecological monitoring and research insights.