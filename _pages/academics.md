---
layout: single
title: "Academics"
permalink: /academics/
author_profile: false
classes: wide
header:
  overlay_image: /header-banner.jpg
  overlay_filter: 0.5
---

<style>
.page__content {
  max-width: 1200px !important;
}

.research-intro {
  text-align: center;
  margin-bottom: 3rem;
}

.research-intro h1 {
  font-size: 2rem;
  margin-bottom: 0.5rem;
  color: #2c3e50;
}

.research-intro p {
  color: #666;
  font-size: 1.1rem;
}

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 3rem 2rem;  /* Vertikal 3rem, Horizontal 2rem */
  margin-bottom: 3rem;
}

.research-card {
  display: grid;
  grid-template-rows: 280px auto auto;  /* Feste Höhen für Alignment */
  text-align: center;
}

.research-card-image {
  width: 100%;
  height: 280px;  /* Feste Höhe */
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1.5rem;
  background: transparent;
}

.research-card img {
  max-width: 100%;
  max-height: 100%;
  width: auto;
  height: auto;
  object-fit: contain;
  display: block;
  margin: 0 auto;
}

.research-card h3 {
  font-size: 1.4rem;
  font-weight: 600;
  color: #1a1a1a;
  margin: 0 0 1rem 0;
  line-height: 1.3;
  min-height: 3.6em;  /* Platz für 2-3 Zeilen */
  display: flex;
  align-items: center;
  justify-content: center;
}

.research-card p {
  color: #555;
  line-height: 1.6;
  font-size: 0.95rem;
  margin: 0 0 0.5rem 0;
}

.research-card ul {
  list-style: none;
  padding: 0;
  margin: 0.5rem 0 0 0;
  font-size: 0.9rem;
  text-align: center;
}

.research-card li {
  margin: 0.3rem 0;
  color: #666;
}

.research-card a {
  color: #0066cc;
  text-decoration: none;
}

.research-card a:hover {
  color: #004499;
  text-decoration: underline;
}

@media (max-width: 768px) {
  .research-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }
  
  .research-card-image {
    height: 240px;
  }
  
  .research-card h3 {
    min-height: auto;
  }
}
</style>

<div class="research-intro">
  <h1>Academic projects showcase</h1>
  <p>Projects developed by undergrad students using neuromorphic sensing, algorithms, and processing hardware.</p>
</div>

<div class="research-grid">

<!-- Project 1 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/SpikingDQN.jpg" alt="SpikingDQN">
  </div>
  <h3>Spiking DQN Agents to learn control states</h3>
  <p>This project replicates the brain’s ability to infer motion without explicit speed data by training a spiking neural network (SNN) agent—deprived of velocity inputs—to internally reconstruct missing environmental physics using its membrane potentials as short-term memory. Through Backpropagation Through Time, the SNN-based Deep Q-Network learned to encode velocity in its hidden layers, effectively developing internal "speedometers" from spike timings alone.</p>
  <p><strong>Team:</strong></p>
  <ul>
    <li>Robin Feldmann - <a href="mailto:feldmannro80685@th-nuernberg.de">feldmannro80685@th-nuernberg.de</a></li>
    <li>Maximilian Arnold - <a href="mailto:arnoldma80620@th-nuernberg.de">arnoldma80620@th-nuernberg.de</a></li>
  </ul>
</div>

<!-- Project 1 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/ANN YOLO DVS Datastream.jpg" alt="EventBasedYolo">
  </div>
  <h3>YOLO Deep Neural Conv Net on Event-based Camera Traffic Tracking</h3>
  <p>The Neuromorphic Traffic Training project aims to compare various approaches for obtaining event-based data—including self-recording, sensor-based capture, and conversion/simulation methods—by training Artificial Neural Networks (ANNs) and converting them into Spiking Neural Networks (SNNs). The focus is on developing models that can effectively track diverse traffic actors, such as pedestrians, cars, and motorcycles.</p>
  <p><strong>Team:</strong></p>
  <ul>
    <li>Mark Franz - <a href="mailto:franzma84803@th-nuernberg.de">franzma84803@th-nuernberg.de</a></li>
    <li>Laurin Kerntke - <a href="mailto:kerntkela84836@th-nuernberg.de">kerntkela84836@th-nuernberg.de</a></li>
    <li>Jonathan Pohl - <a href="mailto:pohljo85440@th-nuernberg.de">pohljo85440@th-nuernberg.de</a></li>
  </ul>
</div>


<!-- Project 1 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/Hybrid-ArtificialNN.jpg" alt="Hybrid-ArtificialNN">
  </div>
  <h3>Hybrid ArtificialNN and SpikingNN for closed-loop motor control</h3>
  <p>Using the <a href="https://github.com/giant-axon/lu.i-neuron-pcb">LuI silicon neurons</a> in a spiking neural network converting the sound processing output of an ANN into spike trains to move a servo motor. Another ANN classifies the spike trains to determine the motor direction.</p>
  <p><strong>Team:</strong></p>
  <ul>
    <li>Selin Schmitt - <a href="mailto:schmittse79503@th-nuernberg.de">schmittse79503@th-nuernberg.de</a></li>
    <li>Timon Löwl - <a href="mailto:loewlti80780@th-nuernberg.de">loewlti80780@th-nuernberg.de</a></li>
    <li>Sven Remy - <a href="mailto:remysv80967@th-nuernberg.de">remysv80967@th-nuernberg.de</a></li>
  </ul>
</div>

<!-- Project 2 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/Text2Morse.jpg" alt="Text2Morse">
  </div>
  <h3>Spiking Silicon Neurons for Text2Morse Conversion</h3>
  <p>Neuromorphic data encoding and decoding using <a href="https://github.com/giant-axon/lu.i-neuron-pcb">LuI silicon neurons</a> for implementing an efficient Text2Morse converter based on spike trains.</p>
  <p><strong>Team:</strong></p>
  <ul>
    <li>Tan Phat, Nguyen - <a href="mailto:phatnguyen@gmx.de">phatnguyen@gmx.de</a></li>
    <li>Paul Schmachtl - <a href="mailto:paul.schmachtl@outlook.com">paul.schmachtl@outlook.com</a></li>
  </ul>
</div>

<!-- Project 3 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/predictive-maintenance.jpg" alt="Event-clustering">
  </div>
  <h3>Event-based camera spatial and temporal clustering for predictive maintenance</h3>
  <p>Using a neuromorphic event-based camera to design and develop a spatial and temporal clustering algorithm for frequency detection used in machine state estimation and predictive maintenance.</p>
  <p><strong>Team:</strong></p>
  <ul>
    <li>Benedikt Fischer - <a href="mailto:fischerbe98484@th-nuernberg.de">fischerbe98484@th-nuernberg.de</a></li>
    <li>Felix Sixdorf - <a href="mailto:sixdorffe80095@th-nuernberg.de">sixdorffe80095@th-nuernberg.de</a></li>
    <li>David Stiegler - <a href="mailto:stieglerda78912@th-nuernberg.de">stieglerda78912@th-nuernberg.de</a></li>
  </ul>
</div>

<!-- Project 4 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/spiking-PID.jpg" alt="Spiking-PID">
  </div>
  <h3>Spiking PID Controller for Mobile Robot Trajectory Tracking</h3>
  <p>Neuromorphic PID implemented using Nengo to control a differential mobile robot trajectory tracking performance under uncertainty.</p>
  <p><strong>Team:</strong></p>
  <ul>
    <li>Adrian Stangl - <a href="mailto:stanglad98626@th-nuernberg.de">stanglad98626@th-nuernberg.de</a></li>
    <li>Bastian Wunderlich - <a href="mailto:wunderlichba98628@th-nuernberg.de">wunderlichba98628@th-nuernberg.de</a></li>
  </ul>
</div>

<!-- Project 5 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/follow_the_leader.jpg" alt="Robot-swarm">
  </div>
  <h3>Follow the leader robot swarm</h3>
  <p>Neuromorphic vision based frequency tracking algorithm and closed-loop control. Embedded processing for collaborative mini-robots.</p>
</div>

<!-- Project 6 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/Scene-understanding.jpg" alt="Scene-understanding">
  </div>
  <h3>Scene understanding for robot motion</h3>
  <p>Neuromorphic visual sensing fusion with LiDAR for scene understanding and planning for mobile robot motion control.</p>
</div>

<!-- Project 7 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/Camera-based-instruments.jpg" alt="Karaoke">
  </div>
  <h3>Camera-based instruments for karaoke</h3>
  <p>Users can accompany their favourite songs instrumentally by imitating selected instruments with gestures sensed using a neuromorphic vision sensor.</p>
  <p><strong>Team:</strong></p>
  <ul>
    <li>Selin Schmitt - <a href="mailto:schmittse79503@th-nuernberg.de">schmittse79503@th-nuernberg.de</a></li>
    <li>Kay Hartmann - <a href="mailto:hartmannka80488@th-nuernberg.de">hartmannka80488@th-nuernberg.de</a></li>
  </ul>
</div>

<!-- Project 8 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/crowd-sourced.jpg" alt="Crowd-sourced">
  </div>
  <h3>Crowd-sourced visuals</h3>
  <p>Privacy-preserving club visuals generation based on synchronized neuromorphic video sensing and sound generation.</p>
  <p><strong>Team:</strong></p>
  <ul>
    <li>Selin Schmitt - <a href="mailto:schmittse79503@th-nuernberg.de">schmittse79503@th-nuernberg.de</a></li>
    <li>Kay Hartmann - <a href="mailto:hartmannka80488@th-nuernberg.de">hartmannka80488@th-nuernberg.de</a></li>
  </ul>
</div>

<!-- Project 9 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/academics/Event-based_camera-LiDAR.jpg" alt="LiDAR-fusion">
  </div>
  <h3>Event-based camera-LiDAR fusion for clustering-based depth estimation</h3>
  <p>This project addresses the challenge of estimating depth using a single DVS (Dynamic Vision Sensor) camera and a 2D LiDAR. Built using ROS2 for communication and data processing, the system can run on various platforms, including wheeled robots with Jetson Nano or similar hardware. A custom clustering algorithm was developed to estimate the depth of objects outside the LiDAR's measurement plane, enhancing depth perception while maintaining affordability.</p>
  <p><strong>Team:</strong></p>
  <ul>
    <li>Annika Igl - <a href="mailto:aiglgg@web.de">aiglgg@web.de</a></li>
    <li>Timo Kapellner - <a href="mailto:timo.kapellner@gmail.com">timo.kapellner@gmail.com</a></li>
  </ul>
</div>

</div>
