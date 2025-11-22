---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
classes: about-page
---

<div class="intro-section">
  <div class="typed-intro">
    <span id="typed-intro"></span>
  </div>

  <p>
  Hi, I'm Mengyu. I completed my master’s degree in Mechatronics and Robotics at the Technical University of Munich. During my studies, I followed the guidance of <a href="https://hucaofighting.github.io" target="_blank" rel="noopener">Dr. Hu Cao</a> on neuromorphic vision for autonomous driving and was supervised by <a href="https://scholar.google.de/citations?user=-CA8QgwAAAAJ" target="_blank" rel="noopener">Prof. Alois Knoll</a> at the <a href="https://www.ce.cit.tum.de/air/home/" target="_blank" rel="noopener">Lehrstuhl für Robotik, Künstliche Intelligenz und Echtzeitsysteme</a>. I also took part in the <a href="https://disrupt-projekt.de" target="_blank" rel="noopener">DISRUPT project</a> with <a href="https://www.thi.de/personen/klaus-kefferpuetz-prof-dr-ing/" target="_blank" rel="noopener">Prof. Klaus Kefferpütz</a> and worked with Longfei Han at <a href="https://www.ivi.fraunhofer.de/" target="_blank" rel="noopener">Fraunhofer IVI</a>.
  </p>

  <p>
  My academic interests center on multi-modal fusion for scene understanding, especially within autonomous driving and robotics. I am also curious about how large language models (LLMs) can support more reliable and safer scene analysis. I am currently looking for a PhD position where I can continue exploring multi-modal fusion and contribute to advancing research in scene understanding.
  </p>
</div>

<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
<script>
document.addEventListener('DOMContentLoaded', function () {
  if (window.Typed && !document.body.dataset.typedIntroInitialized) {
    document.body.dataset.typedIntroInitialized = 'true';
    new Typed('#typed-intro', {
      strings: [
        "Hi!^600 I'm Mengyu.",
        "Hi!^600 I'm passionate about neuromorphic vision and multi-modal fusion.",
        "Hi!^600 I'm exploring how LLMs can make scene understanding safer."
      ],
      typeSpeed: 45,
      backSpeed: 25,
      backDelay: 1100,
      loop: true,
      smartBackspace: true,
      cursorChar: '|'
    });
  }
});
</script>

Research
======

<div class="research-item research-item--medium">
  <div class="research-image research-image--medium">
    <img src="/images/SegRGBX.png" alt="RGB-X Fusion">
  </div>
  <div class="research-content">
    <h3>Multimodal Fusion of RGB and Complementary Modalities for Semantic Segmentation</h3>
    <div class="authors"><strong>Mengyu Li</strong> et al.</div>
    <div class="venue">Preprint, submitted to ICLR 2026 (under review)</div>
    <p>
      Multi-modal semantic segmentation augments RGB imagery with an auxiliary sensing stream X (RGB-X)—such as thermal, depth, LiDAR, event, polarization, or light field—to enhance robustness under adverse illumination and motion blur. However, sensor heterogeneity often leads to misaligned features and unstable fusion.
    </p>
    <p>
      To alleviate these issues, we propose a bidirectional polarity-aware cross-modality fusion (BPCF) module that effectively captures complementary cues while enhancing feature alignment. We evaluate the framework on six modality pairings—RGB-Thermal, RGB-LiDAR, RGB-Depth, RGB-Event, RGB-Polarization, and RGB-Light Field—and achieve state-of-the-art results on eight public datasets, including MFNe, KITTI-360, DELIVER, DDD17, DSEC, MCubeS, ZJU, and UrbanLF.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="/images/mfnet_compar1.png" alt="Master's Thesis">
  </div>
  <div class="research-content">
    <h3>Multi-Modal Fusion of Image Sequences for Dense Prediction with RGB and Event Cameras in Autonomous Driving</h3>
    <div class="authors"><strong>Mengyu Li</strong></div>
    <div class="venue">Master's Thesis, Technical University of Munich</div>
    <div class="links">
      <a href="https://github.com/MengyuLi982/RGB-E-Segmentation" target="_blank" rel="noopener">Code</a>
      <a href="https://docs.google.com/presentation/d/1a2isDWwUEuJyFn9VIvA9gUrYdCAh3KPrWyDsUgil-Js/edit?usp=sharing" target="_blank" rel="noopener">Slides</a>
    </div>
    <p>
      This work unifies RGB and event streams for dense prediction, with semantic segmentation as the primary downstream task. RGB sensors provide texture-rich spatial cues, whereas event cameras excel at capturing micro-motion and high dynamic range.
    </p>
    <p>
      I designed a hybrid encoder that aligns asynchronous event spikes with frame-based cues through temporal attention and mutual-information guided consistency terms. The fusion strategy yields more stable segmentation under extreme lighting, fast egomotion, and motion blur.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="/images/TUMTraf-EMOT.png" alt="TUMTraf EMOT">
  </div>
  <div class="research-content">
    <h3>Event-Based Multi-Object Tracking Dataset and Baseline for Traffic Scenarios</h3>
    <div class="authors"><strong>Mengyu Li</strong></div>
    <div class="venue">Semester Thesis, Technical University of Munich</div>
    <div class="links">
      <a href="https://huggingface.co/datasets/BigmouthFish/EMOT" target="_blank" rel="noopener">Dataset</a>
    </div>
    <p>
      I curated TUMTraf EMOT, the first event-based ITS dataset with synchronized vehicle and pedestrian sequences across diverse weather, illumination, and traffic densities. The benchmark includes calibrated RGB, event, and IMU streams plus fine-grained 3D bounding boxes.
    </p>
    <p>
      Building on the dataset, I proposed a tracking-by-detection pipeline with a dual-head feature extractor that handles sparse event voxels and dense frame crops jointly. The baseline outperforms frame-only trackers under low-light conditions while remaining computationally efficient.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="/images/Disrupt.png" alt="Internship">
  </div>
  <div class="research-content">
    <h3>Decentralized Tracking in the Context of the DISRUPT Project</h3>
    <div class="authors"><strong>Mengyu Li</strong></div>
    <div class="venue">Internship, Fraunhofer IVI</div>
    <div class="links">
      <a href="https://docs.google.com/presentation/d/1qIjcYz6HSf-YfD0dsEUprSEe7qI4foa0PkE5VCItgBI/edit?usp=sharing" target="_blank" rel="noopener">Slides</a>
      <a href="https://disrupt-projekt.de/index.php" target="_blank" rel="noopener">Website</a>
    </div>
    <p>
      I explored decentralized multi-object tracking on a heterogeneous sensor network that couples event-based edge devices with RGB-lidar hubs. Emphasis was placed on covariance-intersection fusion and low-bandwidth hypothesis exchange.
    </p>
    <p>
      Beyond the perception stack, I implemented an MQTT-based telemetry layer, ROS2 wireless protocols, and Dockerized deployment units so that partners could reproduce the tracking stack on both automotive-grade hardware and cloud simulators.
    </p>
  </div>
</div>
