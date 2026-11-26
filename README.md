<div align="center">

<img src="assets/header.svg" alt="Gabriel Paludeto — Ad astra per aspera" width="100%" />

<br/>

[![Email](https://img.shields.io/badge/Email-paludeto%40alunos.utfpr.edu.br-0F172A?style=for-the-badge&logo=gmail&logoColor=38BDF8)](mailto:paludeto@alunos.utfpr.edu.br)
[![GitHub](https://img.shields.io/badge/GitHub-%40Paludeto-0F172A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Paludeto)
[![Papers](https://img.shields.io/badge/Publications-2_Papers-0F172A?style=for-the-badge&logo=googlescholar&logoColor=34D399)](#-publications)
<!-- Uncomment whenever you want to add social / academic links:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gabriel_Paludeto-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_HANDLE)
[![Lattes](https://img.shields.io/badge/Lattes-CNPq-1B4F72?style=for-the-badge)](http://lattes.cnpq.br/YOUR_ID)
-->

</div>

---

### 👋 About

Computer Engineering undergrad at **UTFPR** (Apucarana, PR — Brazil). Most of my projects revolve around **reinforcement learning**, **embedded systems**, **signal processing**, and **numerical methods** — usually exploring topics by implementing drivers, simulators, and experiments on my own.

- 🎓 B.S. in Computer Engineering @ **UTFPR** *(2023–2028)*
- 🔬 Undergraduate researcher
- 🤖 Founder & mentor at **RoboAP**, a competitive robotics and STEM outreach initiative
- 🌍 Portuguese *(native)* · English *(C1)*

---

### 📌 Pinned Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎮 <a href="https://github.com/Paludeto/megaman-ppo-ga">megaman-ppo-ga</a></h3>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
        <img src="https://img.shields.io/badge/PPO_%7C_Deep_GA_%7C_OL--GA-7C3AED?style=flat-square" alt="RL & GA" />
      </p>
      <p>Controlled comparison of <strong>PPO</strong> (<code>CnnPolicy</code>), <strong>Deep GA</strong>, and <strong>Open-Loop GA</strong> on <em>Mega Man (NES)</em> Robot Master fights from raw <code>84×84×4</code> grayscale frames, under one unified step budget, custom <code>stable-retro</code> integration, sticky-action evaluation, and 95% Wilson intervals.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🎯 <a href="https://github.com/Paludeto/pico-aim">pico-aim</a></h3>
      <p>
        <img src="https://img.shields.io/badge/RP2040_Dual--Core-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white" alt="RP2040" />
        <img src="https://img.shields.io/badge/C11_%7C_Pico_SDK-00599C?style=flat-square&logo=c&logoColor=white" alt="C11" />
        <img src="https://img.shields.io/badge/PID_Q16.16_@_1_kHz-059669?style=flat-square" alt="1 kHz PID" />
      </p>
      <p>Closed-loop 3D visual cursor tracker running at <strong>1 kHz</strong> on a Raspberry Pi Pico acting as a composite <strong>USB CDC + HID mouse</strong> — dual-core zero-float <code>Q16.16</code> PID with a 128-step Smith predictor (<strong>0.0% overshoot</strong>, <strong>86 ms</strong> settling, <strong>2,165</strong> native C checks).</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📡 <a href="https://github.com/Paludeto/esp32-station">esp32-station</a></h3>
      <p>
        <img src="https://img.shields.io/badge/ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP-IDF" />
        <img src="https://img.shields.io/badge/C11-555555?style=flat-square&logo=c&logoColor=white" alt="C11" />
        <img src="https://img.shields.io/badge/nRF24L01%2B_2.4GHz-00897B?style=flat-square" alt="nRF24L01+" />
      </p>
      <p>Datasheet-compliant <strong>nRF24L01+</strong> driver component and wireless base station in C11 over hardware-managed SPI, with Enhanced ShockBurst, 8-byte <code>CRC-8/SMBUS</code> frames, a live <strong>2.4 GHz RF spectrum scanner</strong>, and a stateful mock-SPI host test suite.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🖥️ <a href="https://github.com/Paludeto/mips-on-c">mips-on-c</a></h3>
      <p>
        <img src="https://img.shields.io/badge/C11-00599C?style=flat-square&logo=c&logoColor=white" alt="C11" />
        <img src="https://img.shields.io/badge/ISA-MIPS32-4E9A06?style=flat-square" alt="MIPS32" />
        <img src="https://img.shields.io/badge/Zero_Deps-1F2937?style=flat-square" alt="Zero Dependencies" />
      </p>
      <p>Zero-dependency <strong>MIPS32</strong> two-pass assembler, 32-bit binary encoder/disassembler, and MARS/SPIM-compatible big-endian simulator with an interactive step debugger (<code>.text</code>, <code>.data</code>, stack, 18 pseudo-instructions, and syscalls) in portable C11.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💡 <a href="https://github.com/Paludeto/arduino-optical-link">arduino-optical-link</a></h3>
      <p>
        <img src="https://img.shields.io/badge/Arduino_Uno-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Arduino" />
        <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
        <img src="https://img.shields.io/badge/DPLL_%7C_CRC--8-D97706?style=flat-square" alt="DPLL & CRC-8" />
      </p>
      <p>Visible-light digital communication link (<strong>LED → LDR</strong>) on Arduino Uno with <code>NRZ-L</code>, <code>NRZ-I</code>, and <code>Manchester</code> line coding, Schmitt-trigger auto-threshold, 8-pulse preamble sync, rising-edge <strong>DPLL</strong> clock recovery, and <code>CRC-8</code> 1-bit syndrome correction (<strong>168</strong> host checks).</p>
    </td>
    <td width="50%" valign="top">
      <h3>🫀 <a href="https://github.com/Paludeto/ecg-wavelet-analysis">ecg-wavelet-analysis</a></h3>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/MIT--BIH_Database-2E7D32?style=flat-square" alt="MIT-BIH" />
        <img src="https://img.shields.io/badge/Morlet_CWT-0284C7?style=flat-square" alt="Morlet CWT" />
      </p>
      <p>Open-source time–frequency ECG characterization pipeline comparing regular sinus beats against PVCs on the <strong>MIT-BIH Arrhythmia Database</strong> via Morphology, FFT, STFT, and <strong>Morlet CWT</strong> scalograms, with XQRS alignment, PhysioNet auto-download, and <code>pytest</code> suite.</p>
    </td>
  </tr>
</table>

---

### 🔬 Research & STEM Outreach

- **📈 Macroeconomic Forecasting with ML** — *PIBIC/CNPq Research Fellow, UTFPR*  
  End-to-end modeling pipeline (acquisition, preprocessing, feature selection, training, and out-of-sample validation) forecasting Brazil's monthly GDP from regional industrial production time series, benchmarking linear baselines against neural networks under uncertainty.

- **🔥 3D Transient Simulation of Ohmic Heating** — *Undergraduate Researcher, UTFPR*  
  High-performance finite-difference solvers implemented from scratch in **Fortran** for Laplace, Poisson, and heat equations, solving 3D coupled nonlinear thermo-electrical PDEs over uniform meshes.

- **🤖 RoboAP — Competitive Robotics & STEM Outreach** — *Founder, Mentor & Developer*  
  Built a competitive robotics team and local STEM outreach initiative from zero — securing sponsorships with local companies, teaching robotics fundamentals to high school students, and co-supervising a regional **OBR** (Brazilian Robotics Olympiad) winner.

---

### 📄 Publications

> **Analysis of Premature Ventricular Contractions and Regular Heartbeats via the Wavelet Transform** *(First Author)*  
> *Revista Mundi Engenharia, Tecnologia e Gestão*, v. 11, n. 2 (2026) · Presented at VI SIMECA (IFPR, 2025)  
> [![DOI](https://img.shields.io/badge/DOI-10.21575%2F25254782rmetg2026vol11n22551-2563EB?style=flat-square)](https://doi.org/10.21575/25254782rmetg2026vol11n22551) [![Code](https://img.shields.io/badge/Code-ecg--wavelet--analysis-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Paludeto/ecg-wavelet-analysis)

> **Three-Dimensional Numerical Simulation of Ohmic Heating in Food** *(Co-author)*  
> *REMUNOM — Revista Multidisciplinar do Nordeste Mineiro*, v. 2, n. 2 (2026) · Presented at SICITE (UTFPR)  
> [![DOI](https://img.shields.io/badge/DOI-10.66104%2F6965rv11-2563EB?style=flat-square)](https://doi.org/10.66104/6965rv11)

---

### 🧰 Toolbox & Domains

<div align="center">

**Languages**  
![C](https://img.shields.io/badge/C11-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-004482?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Fortran](https://img.shields.io/badge/Fortran-734F96?style=for-the-badge&logo=fortran&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge)
![MIPS32](https://img.shields.io/badge/MIPS32_Assembly-4E9A06?style=for-the-badge)

**AI, Vision & Scientific Computing**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-1F2937?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

**Embedded, Robotics & Systems**  
![ESP-IDF](https://img.shields.io/badge/ESP32_%7C_ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![RP2040](https://img.shields.io/badge/RP2040_%7C_Pico_SDK-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-2E7D32?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Protocol Buffers](https://img.shields.io/badge/Protocol_Buffers-4285F4?style=for-the-badge)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

<div align="center">

<img src="assets/footer.svg" alt="Ad astra per aspera" width="100%" />

</div>
