<p align="center">
  <img src="assets/banner-city.svg" alt="Hamza Demir - Machine Learning Engineer" width="100%">
</p>

<p align="center">
  Machine learning, deep learning and data science, done as focused and measured work:<br>
  clear baselines, honest evaluation, results you can reproduce.<br>
  <b>Open to internships, junior ML roles and collaborations.</b>
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-0b0a1f?style=for-the-badge&logo=python&logoColor=22e3ff">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-0b0a1f?style=for-the-badge&logo=pytorch&logoColor=22e3ff">
  <img alt="PyTorch Geometric" src="https://img.shields.io/badge/PyG-0b0a1f?style=for-the-badge&logo=pyg&logoColor=22e3ff">
  <img alt="Weights and Biases" src="https://img.shields.io/badge/W%26B-0b0a1f?style=for-the-badge&logo=weightsandbiases&logoColor=22e3ff">
  <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-0b0a1f?style=for-the-badge&logo=opencv&logoColor=22e3ff">
  <img alt="Go" src="https://img.shields.io/badge/Go-0b0a1f?style=for-the-badge&logo=go&logoColor=22e3ff">
  <img alt="C" src="https://img.shields.io/badge/C%20%2F%20ESP--IDF-0b0a1f?style=for-the-badge&logo=espressif&logoColor=22e3ff">
</p>

<img src="assets/divider-city.svg" width="100%" height="10" alt="">

## Latest work

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/wHamza/modelParamControl">modelParamControl</a> &nbsp;<img alt="bit-identical reruns" src="https://img.shields.io/badge/reruns-bit--identical-ff2d95?style=flat-square&labelColor=0b0a1f"> <img alt="Nov 2026" src="https://img.shields.io/badge/Nov%202026-6d28d9?style=flat-square"></h3>
      Experiment tracking and reproducibility study around a small CNN on CIFAR-10. Every run logs its config, seed, git commit, torch version and GPU to W&amp;B, and the same commit + config + seed reproduces the result exactly. A 5-seed run sets the noise floor (0.745 – 0.752 test accuracy); a 20-run random sweep then shows learning rate matters, weight decay does not, and no config beats the baseline beyond that noise.<br><br>
      <img alt="" src="https://img.shields.io/badge/Reproducibility-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/W%26B%20Sweeps-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/Multi--seed%20evaluation-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/PyTorch-2a1458?style=flat-square">
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/wHamza/commaOwnTry">comma Video Compression Challenge</a> &nbsp;<img alt="score 0.33 to 0.240" src="https://img.shields.io/badge/score-0.33%20%E2%86%92%200.240-ff2d95?style=flat-square&labelColor=0b0a1f"> <img alt="Oct 2026" src="https://img.shields.io/badge/Oct%202026-6d28d9?style=flat-square"></h3>
      My own HNeRV-style implicit decoder (~243K params) trained with 7-bit quantization-aware training, an entropy penalty and task losses through frozen SegNet / PoseNet evaluators. Reproduced the public #128 submission exactly (0.18796) and showed why cheap post-hoc fixes cannot pay for their bytes. Full research log, negative results included.<br><br>
      <img alt="" src="https://img.shields.io/badge/Video%20Compression-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/Implicit%20Neural%20Representation-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/QAT-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/PyTorch-2a1458?style=flat-square">
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/wHamza/cattle-anomaly-mmcows">Cattle Behaviour Anomaly Detection</a> &nbsp;<img alt="84% detection at about 1 alarm per cow per week" src="https://img.shields.io/badge/84%25%20detection-~1%20alarm%2Fcow%2Fweek-ff2d95?style=flat-square&labelColor=0b0a1f"> <img alt="Oct 2026" src="https://img.shields.io/badge/Oct%202026-6d28d9?style=flat-square"></h3>
      Label-free detection of lethargy-like behaviour in dairy cows from hourly wearable-sensor data (MMCOWS), the same cadence a LoRaWAN collar reports at. Herd-relative robust z-scores, an alarm budget instead of an arbitrary threshold, and evaluation through a physiological proxy plus synthetic drills.<br><br>
      <img alt="" src="https://img.shields.io/badge/Anomaly%20Detection-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/Time%20Series-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/IoT%20Sensors-2a1458?style=flat-square">
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>ING Hubs Türkiye Datathon &nbsp;<img alt="21st in Türkiye" src="https://img.shields.io/badge/21st%20in%20T%C3%BCrkiye-ff2d95?style=flat-square&labelColor=0b0a1f"></h3>
      Customer churn prediction on a heavily imbalanced dataset (about 95% / 5%). Individual entry, ensemble model, October 2025.<br><br>
      <img alt="" src="https://img.shields.io/badge/Churn%20Prediction-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/Ensemble-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/Imbalanced%20Data-2a1458?style=flat-square">
    </td>
  </tr>
</table>

<img src="assets/divider-city.svg" width="100%" height="10" alt="">

## More projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/wHamza/readbuddy-rag">ReadBuddy RAG</a></h3>
      Spoiler-safe reading companion: hybrid retrieval over a book that only uses what you have already read.<br><br>
      <img alt="" src="https://img.shields.io/badge/RAG-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/ChromaDB-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/NLP-2a1458?style=flat-square">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/wHamza/routeOptimGNN">Route Optim GNN</a></h3>
      Vehicle routing with graph attention and reinforcement learning, with benchmark scripts and route plots.<br><br>
      <img alt="" src="https://img.shields.io/badge/GNN-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/RL-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/PyTorch%20Geometric-2a1458?style=flat-square">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/wHamza/gnn-steam-2021-turkish">Steam Game Recommender</a></h3>
      Heterogeneous GNN on Turkish Steam reviews; users and games are nodes, recommendation is link prediction.<br><br>
      <img alt="" src="https://img.shields.io/badge/RecSys-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/Hetero%20GNN-2a1458?style=flat-square">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/wHamza/line-recog">Underwater Route Recognition</a></h3>
      YOLO-based line detection with vehicle-control experiments over PyMAVLink.<br><br>
      <img alt="" src="https://img.shields.io/badge/YOLO-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/Robotics-2a1458?style=flat-square">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/wHamza/Voice-control-with-hand">Hand-Controlled Volume</a></h3>
      Touch-free Windows volume control with MediaPipe hand landmarks.<br><br>
      <img alt="" src="https://img.shields.io/badge/MediaPipe-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/OpenCV-2a1458?style=flat-square">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/wHamza/TensorTonic-Solutions">TensorTonic Solutions</a></h3>
      ML fundamentals implemented from scratch with NumPy: losses, activations, closed-form regression.<br><br>
      <img alt="" src="https://img.shields.io/badge/NumPy-2a1458?style=flat-square"> <img alt="" src="https://img.shields.io/badge/Fundamentals-2a1458?style=flat-square">
    </td>
  </tr>
</table>

<img src="assets/divider-city.svg" width="100%" height="10" alt="">

## On the workbench

- **Edge herd monitoring** &mdash; LoRaWAN neck collars, a Raspberry Pi gateway and an on-farm server that keeps working with no internet; anomaly detection first, estrus detection next.
- **Neural video compression** &mdash; distilling a stronger HNeRV model into my own decoder, aiming below 0.2.
- **Post-training open language models** (Gemma 4).
- **MLOps habits** &mdash; experiment tracking, sweeps, multi-seed comparisons, small deployed demos.

<p align="center">
  <a href="https://github.com/wHamza?tab=repositories"><img alt="All repositories" src="https://img.shields.io/badge/All%20repositories-0b0a1f?style=for-the-badge&logo=github&logoColor=22e3ff"></a>
</p>
