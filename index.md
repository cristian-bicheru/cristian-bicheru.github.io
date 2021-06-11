---
layout: default
---

<style>
    body {font-family: Arial, Helvetica, sans-serif;}
    .modal {
      display: none; /* Hidden by default */
      position: fixed; /* Stay in place */
      z-index: 1; /* Sit on top */
      padding-top: 100px; /* Location of the box */
      left: 0;
      top: 0;
      width: 100%; /* Full width */
      height: 100%; /* Full height */
      overflow: auto; /* Enable scroll if needed */
      background-color: rgb(0,0,0); /* Fallback color */
      background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
    }
    .modal-content {
      position:relative;
      background: #252525;
      background-attachment: fixed !important;
      background: linear-gradient(#2a2a29, #1c1c1c);
      margin: auto;
      padding: 20px;
      border: 1px solid #888;
      width: 80%;
      overflow: auto;
    }
    .close {
      color: #aaaaaa;
      float: right;
      font-size: 28px;
      font-weight: bold;
    }
    .close:hover,
    .close:focus {
      color: #000;
      text-decoration: none;
      cursor: pointer;
    }
    .image-left {
      width: 50%;
      margin-right: 10px;
      float: left;
    }
    .description {
      margin: 10px;
    }
    .tools {
      position: relative;
      left: 20px;
    }
    .view-github {
      position:absolute;
      bottom:15px;
      font-family: 'OpenSansLight', "Helvetica Neue", Helvetica, Arial, sans-serif;
      font-weight: normal;
      list-style: none;
      display: inline;
      color: white;
      line-height: 50px;
      text-shadow: 0px 1px 0px rgba(0,0,0,.2);
      font-size: 14px;
    }
    .view-github-link {
      color: white;
      border: 1px solid #5d910b;
      background: linear-gradient(#93bd20, #659e10);
      border-radius: 2px;
      box-shadow: inset 0px 1px 0px rgba(255,255,255,.3), 0px 3px 7px rgba(0,0,0,.7);
      background-color: #93bd20;
      padding: 10px 12px;
      margin-top: 6px;
      line-height:14px;
      font-size:14px;
      display:inline-block;
      text-align:center;
    }
    .view-github-link:hover {
      background: linear-gradient(#749619, #527f0e);
      background-color: #659e10;
      border: 1px solid #527f0e;
      box-shadow: inset 0px 1px 1px rgba(0,0,0,.2), 0px 1px 0px rgba(0,0,0,.0);
    }
    .data-cell {
      vertical-align: top;
      height: 20vh;
    }
    .cell-image {
      display:block;
      max-height: 18vh;
      max-width: 80%;
      margin:auto;
    }
    table td {
      width: 50%;
    }
</style>

# About Me
{: style="text-align: center;"}
I'm a passsionate, aspiring Mechanical Engineer from Waterloo, Ontario in my first year at the University of Waterloo. I'm currently seeking an internship or employment to gain practical experience and to expand my skillset.

<div style="height:50px;"></div>

# Tools and Technologies
{: style="text-align: center;"}

<table border="" style="vertical-align: top;">
  <tbody>
    <tr>
      <td class="data-cell">C <br /> <img src="assets/images/c.png" alt="C" class="cell-image" /></td>
      <td class="data-cell">C++ <br /> <img src="assets/images/cpp.png" alt="C++" class="cell-image" /></td>
    </tr>
    <tr>
      <td class="data-cell">Python <br /> <img src="assets/images/python.png" alt="Python" class="cell-image" /></td>
      <td class="data-cell">PyTorch <br /> <img src="assets/images/pytorch.png" alt="PyTorch" class="cell-image" /></td>
    </tr>
    <tr>
      <td class="data-cell">TensorFlow <br /> <img src="assets/images/tensorflow.png" alt="TensorFlow" class="cell-image" /></td>
      <td class="data-cell">Node.js <br /> <img src="assets/images/nodejs.png" alt="Node.js" class="cell-image" /></td>
    </tr>
    <tr>
      <td class="data-cell">Java <br /> <img src="assets/images/java.png" alt="Java" class="cell-image" /></td>
      <td class="data-cell">Google Cloud Platform <br /> <img src="assets/images/gcloud.png" alt="Google Cloud Platform" class="cell-image" /></td>
    </tr>
  </tbody>
</table>

# Projects
{: style="text-align: center;"}

<div id="fast-ta-modal" class="modal">
  <div class="modal-content">
    <span class="close" id="fast-ta-closebtn">&times;</span>
    <img class="image-left" src="assets/images/kama.svg" alt="KAMA Indicator Relative Speedup">
    <div class="description">
        <h2>Description:</h2>
        <p>Fast TA is an optimized, high-level technical analysis Python library used to compute technical indicators on financial datasets. It is written entirely in C, and uses SIMD vectorization as well. Fast TA is built with the Python and NumPy C APIs.</p>
        <h2>Tools and Technologies:</h2>
        <ul class="tools">
            <li>C</li>
            <li>Intel SIMD Intrinsics</li>
            <li>Python C API</li>
            <li>NumPy C API</li>
            <li>Travis CI</li>
            <li>Bazel</li>
            <li>Google Test (GTest)</li>
        </ul>
        <span class="view-github"><a href="https://github.com/cristian-bicheru/fast-ta" class="view-github-link" target="_blank">View on GitHub</a></span>
    </div>
  </div>
</div>

<div id="arith-modal" class="modal">
  <div class="modal-content">
    <span class="close" id="arith-closebtn">&times;</span>
    <img class="image-left" src="assets/images/arith.png" alt="Arithmetic Encoder Diagram">
    <div class="description">
        <h2>Description:</h2>
        <p>Arith is a simple C++ Huffman/Arithmetic Codec library for compressing data.</p>
        <h2>Tools and Technologies:</h2>
        <ul class="tools">
            <li>C++</li>
        </ul>
        <span class="view-github"><a href="https://github.com/cristian-bicheru/arith" class="view-github-link" target="_blank">View on GitHub</a></span>
    </div>
  </div>
</div>

<div id="tippe-modal" class="modal">
  <div class="modal-content">
    <span class="close" id="tippe-closebtn">&times;</span>
    <iframe src="https://drive.google.com/file/d/18MQ3AtuQT2Z1k9QhuBENRCZ1aoh2wO1d/preview" width="640" height="480" class="image-left"></iframe>
    <div class="description">
        <h2>Description:</h2>
        <p>This software simulates a <a href="https://en.wikipedia.org/wiki/Tippe_top" target="_blank">Tippe Top</a> spinning. It implements state-of-the-art ODE solvers such as the Dormand-Prince and Runge-Kutta Methods. Euler's method was found to be too unstable for the problem. The software was written as part of an energy and momentum lab analysis for Grade 12 AP physics. The only conserved quantity was found to be angular momentum dotted with the position vector. </p>
        <h2>Tools and Technologies:</h2>
        <ul class="tools">
            <li>Processing 3</li>
            <li>G4P</li>
            <li>Java Matrix Package (JAMA)</li>
        </ul>
        <span class="view-github"><a href="https://github.com/cristian-bicheru/tippe-top-simulation" class="view-github-link" target="_blank">View on GitHub</a></span>
    </div>
  </div>
</div>

<div id="electro-modal" class="modal">
  <div class="modal-content">
    <span class="close" id="electro-closebtn">&times;</span>
    <img class="image-left" src="assets/images/electrostatics.png" alt="Simulation of Two Coils">
    <div class="description">
        <h2>Description:</h2>
        <p>This software displays the magnetic vector field for a given input scene of current-carrying wires. It uses <a href="https://en.wikipedia.org/wiki/Biot%E2%80%93Savart_law" target="_blank">Biot-Savart Law</a> to compute the resulting field. Scenes are stored as files with a human-readable syntax, see example files in the GitHub repository. This software was written as part of an assignment for Grade 11 AP Physics. </p>
        <h2>Tools and Technologies:</h2>
        <ul class="tools">
            <li>Processing 3</li>
            <li>G4P</li>
        </ul>
        <span class="view-github"><a href="https://github.com/cristian-bicheru/modeling-electrostatics" class="view-github-link" target="_blank">View on GitHub</a></span>
    </div>
  </div>
</div>

|:-:|:-:|
| Fast-TA <br> ![Fast-TA](assets/images/kama.svg "Fast-TA Speedup vs Other Library"){: style="cursor: pointer;" #fast-ta} | Arith <br> ![Arith](assets/images/arith.png "Arithmetic Encoding Diagram"){: style="cursor: pointer;" #arith} |
| Tippe Top Simulation <br> ![Tippe Top Simulation](assets/images/tippe.png "Tippe Simulation in Action"){: style="cursor: pointer;" #tippe} | Modeling Electrostatics <br> ![Modeling Electrostatics](assets/images/electrostatics.png "Simulation of Two Coils"){: style="cursor: pointer;" #electro} |
{: border=""}

<script>
    const ids = ["fast-ta", "arith", "tippe", "electro"];
    ids.forEach(function(id) {
        const modal = document.getElementById(id+"-modal");
        const closebtn = document.getElementById(id+"-closebtn");
        const img = document.getElementById(id);
        img.onclick = function() {
          modal.style.display = "table-cell";
        };
        closebtn.onclick = function() {
          modal.style.display = "none";
        };
        window.addEventListener('click', function(event) {
          if (event.target == modal) {
            modal.style.display = "none";
          }
        });
    });
</script>
