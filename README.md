# Hi there 👋

My name is Pavel Kotsko, and I'm an ML engineer in computer vision, working in Python and C++. I take models from the first experiment
to a service that people rely on every day. I hold a degree in spacecraft flight dynamics, and my thesis applied neural
networks and computer vision to autonomous spacecraft docking, the same mix
of ML and aerospace I work with today.

Saint Petersburg, Russia · UTC+3

**Portfolio:** [epochspace.github.io](https://epochspace.github.io)


<p>
  <a href="https://en.wikipedia.org/wiki/Python_(programming_language)" title="Python — programming language"><img src="https://skillicons.dev/icons?i=python" width="48" alt="Python" title="Python — programming language"></a>
  <a href="https://en.wikipedia.org/wiki/C%2B%2B" title="C++ — programming language"><img src="https://skillicons.dev/icons?i=cpp" width="48" alt="C++" title="C++ — programming language"></a>
  <a href="https://en.wikipedia.org/wiki/PyTorch" title="PyTorch — deep learning framework"><img src="https://skillicons.dev/icons?i=pytorch" width="48" alt="PyTorch" title="PyTorch — deep learning framework"></a>
  <a href="https://en.wikipedia.org/wiki/TensorFlow" title="TensorFlow — machine learning framework"><img src="https://skillicons.dev/icons?i=tensorflow" width="48" alt="TensorFlow" title="TensorFlow — machine learning framework"></a>
  <a href="https://en.wikipedia.org/wiki/OpenCV" title="OpenCV — Open Source Computer Vision Library"><img src="https://skillicons.dev/icons?i=opencv" width="48" alt="OpenCV" title="OpenCV — Open Source Computer Vision Library"></a>
  <a href="https://en.wikipedia.org/wiki/Linux" title="Linux — operating system"><img src="https://skillicons.dev/icons?i=linux" width="48" alt="Linux" title="Linux — operating system"></a>
  <a href="https://en.wikipedia.org/wiki/CMake" title="CMake (Cross-platform Make) — build system"><img src="https://skillicons.dev/icons?i=cmake" width="48" alt="CMake" title="CMake (Cross-platform Make) — build system"></a>
  <a href="https://en.wikipedia.org/wiki/Flask_(web_framework)" title="Flask — Python web framework"><img src="https://skillicons.dev/icons?i=flask" width="48" alt="Flask" title="Flask — Python web framework"></a>
  <a href="https://en.wikipedia.org/wiki/SQLite" title="SQLite — embedded SQL database"><img src="https://skillicons.dev/icons?i=sqlite" width="48" alt="SQLite" title="SQLite — embedded SQL database"></a>
  <a href="https://en.wikipedia.org/wiki/Git" title="Git — version control system"><img src="https://skillicons.dev/icons?i=git" width="48" alt="Git" title="Git — version control system"></a>
</p>


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
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pavel_Kotsko-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6TTcuMTE5IDIwLjQ1MkgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMHoiLz48L3N2Zz4K)](https://www.linkedin.com/in/pavel-kotsko-920891451/)

