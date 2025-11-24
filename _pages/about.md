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
    <img src="/images/dsec_results.png" alt="Master's Thesis">
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
      Integrating RGB and event camera data through multi-modal fusion in autonomous driving significantly enhances
 dense prediction tasks such as depth estimation and object detection. RGB cameras provide high-resolution color
 imagery crucial for visual perception. In contrast, event cameras offer high temporal resolution and dynamic
 range, capturing pixel-level changes caused by motion even in challenging lighting conditions. 
    </p>
    <p>
      The work can construct a more comprehensive and robust representation of the environment by fusing the continuous visual stream of RGB with the asynchronous intensity changes captured by event cameras. This thesis mainly focuses on combining the multi-modal features for semantic segmentation. 
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
      In Intelligent Transportation Systems (ITS), multi object tracking is primarily based on frame-based cameras. However, these cameras tend to perform poorly under dim lighting and high-speed motion conditions. Event cameras, characterized by low latency, high dynamic range and high temporal resolution, have considerable potential to mitigate these issues. Compared to frame-based vision, there are far fewer studies on event-based vision. To address this research gap, we introduce a dataset tailored for event-based ITS, covering vehicle and pedestrian detection and tracking. 
    </p>
    <p>
      Based on this dataset, we establish a tracking-by-detection benchmark with a specialized feature extractor. The experimental results demonstrate the excellent performance of our method. We hope our work can facilitate further research on the use of event cameras for ITS.
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
      During my internship at Fraunhofer IVI, I worked on making multi camera object tracking in urban traffic more robust and scalable. I built a decentralized tracking framework that keeps object identities consistent across cameras, even when objects are occluded or leave and re enter the scene. I also improved the way information from several cameras is fused so that the system remains stable and reliable as more sensors are added.
    </p>
    <p>
      In addition, I designed the communication and deployment setup so this tracking system can run both on real vehicles and in cloud based simulations. I created a lightweight telemetry and ROS2 based communication layer that supports wireless connections between cars and the backend, and packaged the whole stack into containers for easy reuse by project partners. I then evaluated network latency in different settings to show that the architecture is suitable for real time, distributed perception research.
    </p>
  </div>
</div>
