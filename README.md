# Hi there 👋

My name Pavel Kotsko and i'm ML engineer in computer vision, working in Python and C++. I take models from the first experiment
to a service that people rely on every day. My degree from BSTU VOENMEH is in spacecraft navigation
and ballistics, and my thesis used neural networks and computer vision for spacecraft docking, so
aerospace keeps finding its way into my projects.

Saint Petersburg, Russia · UTC+3

<img src="https://skillicons.dev/icons?i=python,cpp,pytorch,tensorflow,opencv,linux,cmake,flask,sqlite,git" alt="Python, C++, PyTorch, TensorFlow, OpenCV, Linux, CMake, Flask, SQLite, Git" />

## What I work on

Production projects. The code stays with my employer, so I can show demos but not the source.

- **Face recognition from IP cameras.** SCRFD detection, AdaFace embeddings and tracking, with the
  decision made over a series of three or more frames. It went from first version to production in a
  week and has been running since December 2025. Operators change thresholds from a Flask web UI
  without a restart.
- **UAV visual localization without GPS.** The algorithm matches onboard frames against satellite
  maps with SuperPoint + LightGlue and RANSAC. On UAV-VisLoc, without fine-tuning, 79% of
  localizations land within 25 m, with a median error of 20.9 m. I shipped it as a C++ library on
  ONNX Runtime with a deb package and presented it in three conference talks, one of which won a
  best talk award.
- **Medical imaging.** Neural network models for medical tasks.
- **Table OCR.** Scanned PDF tables become Excel files with the same structure: computer vision finds
  the cells and a locally deployed Qwen2.5-VL reads them. I chose this setup after comparing six OCR
  approaches on real scans.

## Open source

- **[booster-landing](https://github.com/EpochSpace/booster-landing)**: propulsive landing of a rocket
  booster. Convex-optimization powered descent guidance flies closed loop through a 6-DoF rigid-body
  model, and the descent is replayed in real time as a 2D side view. Every equation is written up in
  a 16-page document. C++, Python.
- **[volt](https://github.com/EpochSpace/volt)**: HTTP load tester with an interactive terminal UI
  where you change concurrency on the fly. Python front end, C++ backend.
- **[Matching-Engine](https://github.com/EpochSpace/Matching-Engine)**: limit order book in C++17
  with price-time priority, partial fills and separate threads for the order feed, matching and
  live rendering.
- **[Universal-Chess-visual-Assistant](https://github.com/EpochSpace/Universal-Chess-visual-Assistant)**:
  finds a chessboard on the screen, recognizes the pieces with a neural network and draws the best
  move over the board. Python, OpenCV, TensorFlow.

## Contact

[![Telegram](https://img.shields.io/badge/Telegram-@rust1core-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rust1core)
[![Email](https://img.shields.io/badge/Email-tarkov3108@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tarkov3108@gmail.com)
