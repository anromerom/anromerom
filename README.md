<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" width="100%" alt="Nicolai Romero — software engineer, C++ systems, moving into graphics and computer vision">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/nicolai-romero/"><img src="assets/link-linkedin.svg" height="30" alt="LinkedIn"></a>&nbsp;
  <a href="#experience"><img src="assets/link-experience.svg" height="30" alt="Experience"></a>&nbsp;
  <a href="#selected-projects"><img src="assets/link-projects.svg" height="30" alt="Projects"></a>
</p>

I'm a software engineer from Colombia with **four years of production C++**, from passenger-data services at Amadeus to the cross-platform endpoint agent at Wazuh. I'm now pointing that systems background at **visual computing**: real-time graphics, image processing and computer vision.

<!--
=====================================================================
  WORK IN PROGRESS: uncomment this block once the piano repo is public.
  Put a short GIF of the live overlay at assets/projects/piano-fingering.gif (~560×280).
=====================================================================

<a name="now-building"></a>

## <img src="assets/penrose-mark.png" height="22" alt="">&nbsp; Now building

<table>
<tr>
<td width="48%" valign="top">
  <a href="https://github.com/anromerom/REPO-NAME"><img src="assets/projects/piano-fingering.gif" width="100%" alt="Live overlay: detected hand landmarks and the finger assigned to each pressed key"></a>
</td>
<td valign="top">
  <img src="assets/wip.svg" height="22" alt="Work in progress">
  <h3><a href="https://github.com/anromerom/REPO-NAME">Piano Fingering Tracker</a></h3>
  <sub>Personal project · 2026 – now</sub>
  <p>Watches a pianist's hands through a camera and labels which finger plays each key, with a live overlay as real-time feedback for learners.</p>
  <p><code>C++</code> <code>Python</code> <code>OpenCV</code></p>
</td>
</tr>
</table>
-->

<a name="selected-projects"></a>

## <img src="assets/penrose-mark.png" height="22" alt="">&nbsp; Selected projects

<table>
<tr>
<td width="50%" valign="top">
  <a href="https://github.com/anromerom/unal-vc-water-shaders"><img src="assets/projects/water-shaders.gif" width="100%" alt="Animated lake that reflects and refracts a terrain with a palm tree, with moving ripples"></a>
  <h3><a href="https://github.com/anromerom/unal-vc-water-shaders">Water Shaders</a></h3>
  <sub>Visual Computing · UNAL · 2020 · team of 3</sub>
  <p>Real-time lake water. Each frame renders the scene three times (mirrored camera for reflection, main camera for refraction, final view); a scrolling DuDv map adds ripples and a Fresnel term blends the two. <b>My part:</b> the water texturing and reflection demo.</p>
  <p><code>GLSL</code> <code>Processing</code> <code>Java</code> <code>nub</code></p>
</td>
<td width="50%" valign="top">
  <a href="https://github.com/anromerom/unal-vc-ascii-art"><img src="assets/projects/ascii-art.png" width="100%" alt="A photo of an apple next to the same image rendered as coloured ASCII characters"></a>
  <h3><a href="https://github.com/anromerom/unal-vc-ascii-art">ASCII Art &amp; Image Processing</a></h3>
  <sub>Visual Computing · UNAL · 2020 · team of 3</sub>
  <p>Filters for images and live video (luma, threshold, blur and edge-detection convolutions) plus an ASCII renderer that ranks glyphs by pixel coverage. Built on the CPU first, then again as GLSL fragment shaders.</p>
  <p><code>GLSL</code> <code>Processing</code> <code>Java</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <!-- TODO: link to a curated copy (e.g. anromerom/unal-pdc-parallel-blur) once it exists, like the other unal-* repos -->
  <a href="https://github.com/Equipo-alfa-super-mega-dinamita/Paralela-y-distribuida"><img src="assets/projects/parallel-blur.png" width="100%" alt="A cat photo split into vertical bands, each blurred with a larger convolution kernel, from the input to k=41"></a>
  <h3><a href="https://github.com/Equipo-alfa-super-mega-dinamita/Paralela-y-distribuida">Parallel Image Blur</a></h3>
  <sub>Parallel &amp; Distributed Computing · UNAL · 2020 · team of 3</sub>
  <p>A box-blur convolution in C, parallelized four ways: POSIX threads, OpenMP, CUDA and MPI. Benchmarked on 720p, 1080p and 4K images with kernels from 3 to 15, reaching up to 3.2× speed-up on a 4-core i7. <b>My part:</b> the original blur kernel, the benchmark script and analysis notebook, and per-channel parallelism in the CUDA version.</p>
  <p><code>C</code> <code>pthreads</code> <code>OpenMP</code> <code>CUDA</code> <code>MPI</code></p>
</td>
<td width="50%" valign="top">
  <a href="https://github.com/anromerom/unal-pl-vaca"><img src="assets/projects/vaca.gif" width="100%" alt="Animated 8086 CPU in dark mode: registers, instruction queue, an ALU animation and memory cells"></a>
  <h3><a href="https://github.com/anromerom/unal-pl-vaca">VACA: Visual Assembly Code Analyzer</a></h3>
  <sub>Programming Languages · UNAL · 2019 · team of 3 · <a href="https://equipo-alfa-super-mega-dinamita.github.io/VACA-Project/">live demo</a></sub>
  <p>A web IDE that parses 8086 assembly with an ANTLR grammar, runs it step by step and animates the registers, instruction queue, ALU and memory. <b>My part:</b> the p5.js CPU visualization.</p>
  <p><code>p5.js</code> <code>ANTLR 4</code> <code>React</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <a href="https://github.com/anromerom/unal-mad-krow"><img src="assets/projects/krow.png" width="100%" alt="Three phones showing Krow: the side menu with the Krow logo, the task list with priorities and difficulty stars, and a running timer for the saving method"></a>
  <h3><a href="https://github.com/anromerom/unal-mad-krow">Krow</a></h3>
  <sub>Mobile Development · UNAL · 2020 · team of 2</sub>
  <p>Android time-management app: plan tasks on a calendar, then work through them with Pomodoro, "saving" or "marathon" clocks. Room for local data, Firebase for accounts and sync. Built alongside <a href="https://github.com/anromerom/unal-mad-challenges">11 weekly Android challenges</a>.</p>
  <p><code>Kotlin</code> <code>Java</code> <code>Room</code> <code>Firebase</code></p>
</td>
<td width="50%" valign="top">
  <a href="https://github.com/anromerom/unal-is-quiz-grille"><img src="assets/projects/quiz-grille.png" width="100%" alt="Quiz screen: a 4×4 grid of coloured cells, some marked with black or white squares"></a>
  <h3><a href="https://github.com/anromerom/unal-is-quiz-grille">Quiz Turning Grille</a></h3>
  <sub>Information Systems · UNAL · 2019 · solo</sub>
  <p>A classroom quiz whose answers form the key of a Fleissner turning-grille cipher. Answer everything correctly and the rotating grille reveals a hidden message; wrong answers give gibberish.</p>
  <p><code>p5.js</code> <code>JavaScript</code></p>
</td>
</tr>
</table>

<a name="experience"></a>

## <img src="assets/penrose-mark.png" height="22" alt="">&nbsp; Experience

<table>
<tr>
  <td valign="top" width="120"><b>2025&nbsp;–&nbsp;now</b></td>
  <td><b>C/C++ Software Developer</b> · <a href="https://github.com/wazuh">Wazuh</a> · remote<br><sub>Cross-platform endpoint agent (Linux, Windows, macOS) of an open-source security platform.</sub></td>
</tr>
<tr>
  <td valign="top" width="120"><b>2025</b></td>
  <td><b>Senior Application Software Developer</b> · RS2 Software · remote (Malta)<br><sub>Oracle PL/SQL for a payments back-office product.</sub></td>
</tr>
<tr>
  <td valign="top" width="120"><b>2022&nbsp;–&nbsp;2025</b></td>
  <td><b>Associate Software Development Engineer</b> · Amadeus · Bogotá<br><sub>C++ REST/JSON services over Oracle that send airline passenger data to customs authorities; Angular monitoring app on OpenShift.</sub></td>
</tr>
<tr>
  <td valign="top" width="120"><b>2021&nbsp;–&nbsp;2025</b></td>
  <td><b>Teaching Assistant &amp; Course Developer</b> · Universidad Nacional de Colombia<br><sub>Python MOOC, applied data analysis and visualization, and applied-AI courses for public-sector teams.</sub></td>
</tr>
</table>

<a name="education"></a>

## <img src="assets/penrose-mark.png" height="22" alt="">&nbsp; Education

**B.Sc. Systems and Computing Engineering** · Universidad Nacional de Colombia, Bogotá · 2021
<br><sub>Highlights: Visual Computing · Parallel &amp; Distributed Computing · Optimization · Intelligent Systems</sub>

<a name="toolbox"></a>

## <img src="assets/penrose-mark.png" height="22" alt="">&nbsp; Toolbox

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg">
  <img src="assets/stack-light.svg" width="100%" alt="Languages: C++, C, Python, Java, Kotlin, JavaScript, SQL and PL/SQL. Graphics: GLSL, Processing, p5.js. Parallel: POSIX threads, OpenMP, CUDA, MPI. Platforms: Linux, Android, Firebase, React, Angular, OpenShift, Git.">
</picture>

<p align="center"><sub>Spanish (native) · English (C1)</sub></p>
