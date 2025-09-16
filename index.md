---
marp: true
theme: gaia
paginate: false
# header: '**bold** _italic_'
style: |
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-Thin.ttf') format('truetype');
    font-weight: 100;
    font-style: normal;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-ThinItalic.ttf') format('truetype');
    font-weight: 100;
    font-style: italic;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-ExtraLight.ttf') format('truetype');
    font-weight: 200;
    font-style: normal;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-ExtraLightItalic.ttf') format('truetype');
    font-weight: 200;
    font-style: italic;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-Light.ttf') format('truetype');
    font-weight: 300;
    font-style: normal;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-LightItalic.ttf') format('truetype');
    font-weight: 300;
    font-style: italic;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-Regular.ttf') format('truetype');
    font-weight: 400;
    font-style: normal;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-Italic.ttf') format('truetype');
    font-weight: 400;
    font-style: italic;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-Medium.ttf') format('truetype');
    font-weight: 500;
    font-style: normal;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-MediumItalic.ttf') format('truetype');
    font-weight: 500;
    font-style: italic;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-SemiBold.ttf') format('truetype');
    font-weight: 600;
    font-style: normal;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-SemiBoldItalic.ttf') format('truetype');
    font-weight: 600;
    font-style: italic;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-Bold.ttf') format('truetype');
    font-weight: 700;
    font-style: normal;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-BoldItalic.ttf') format('truetype');
    font-weight: 700;
    font-style: italic;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-ExtraBold.ttf') format('truetype');
    font-weight: 800;
    font-style: normal;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-ExtraBoldItalic.ttf') format('truetype');
    font-weight: 800;
    font-style: italic;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-Black.ttf') format('truetype');
    font-weight: 900;
    font-style: normal;
  }
  @font-face {
    font-family: 'Be Vietnam Pro';
    src: url('fonts/BeVietnamPro-BlackItalic.ttf') format('truetype');
    font-weight: 900;
    font-style: italic;
  }

  section, h1, h2, h3, h4, p {
    font-family: 'Be Vietnam Pro', sans-serif;
  }

  strong, b {
    font-weight: 500; /* SemiBold instead of default 700 */
    color: var(--color-highlight);
  }

  header {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    gap: 20px;

    /* --- Adapted properties --- */
    width: 100%;                 /* Let the header span the full page width */
    padding: 15px 2%;            /* Use padding for spacing inside the header */
    box-sizing: border-box;      /* Include padding and border in the element's total width */
  }
  h1 {
    font-size: 1.2rem;
    font-weight: 500;
    color: var(--color-H1);
    text-align: left;
    margin: 0;
    padding-bottom: 2rem;
  }
  h2 {
    font-size: 1.1rem;
    font-weight: 400;
    color: var(--color-H2);
    text-align: left;
    margin: 0;
  }
  h3 {
    font-size: 0.8rem;
    font-weight: 600;
    color: var(--color-H3);
    text-align: center;
    margin: 0;
    padding-bottom: 1rem;
  }
  h4 {
    font-size: 0.9rem;
    font-weight: 500;
    color: var(--color-H4);
    text-align: right;
  }
  fn {
    font-size: 100%;
  }
  .sub {
    font-size: 75%;
    font-weight: 400;
    color: var(--color-H2);
  }
  .f90 {
    font-size: 90%;
  }
  .f90 ul, .f90 ol, .f90 li {
    font-size: 90% !important;
    line-height: 1.2;
  }
  .f80 {
    font-size: 80%;
  }
  .f80 ul, .f80 ol, .f80 li {
    font-size: 80% !important;
    line-height: 1.2;
  }
  .f70 {
    font-size: 70%;
  }
  .content-scale-105 {
    font-size: 105%;
    line-height: 1.3;
  }
  .content-scale-120 {
    font-size: 110%;
    line-height: 1.3;
  }
  .content-scale-90 {
    font-size: 90%;
    line-height: 1.2;
  }
  .content-scale-80 {
    font-size: 80%;
    line-height: 1.2;
  }
  .content-scale-85 {
    font-size: 85%;
    line-height: 1.2;
  }
  .content-scale-95 {
    font-size: 95%;
    line-height: 1.2;
  }
  .content-scale-90 ul, .content-scale-90 ol, .content-scale-90 li {
    font-size: 90% !important;
    line-height: 1.2;
  }
  .content-scale-80 ul, .content-scale-80 ol, .content-scale-80 li {
    font-size: 80% !important;
    line-height: 1.2;
  }
  .content-scale-85 ul, .content-scale-85 ol, .content-scale-85 li {
    font-size: 85% !important;
    line-height: 1.2;
  }
  .content-scale-95 ul, .content-scale-95 ol, .content-scale-95 li {
    font-size: 95% !important;
    line-height: 1.2;
  }
  .content-scale-105 ul, .content-scale-105 ol, .content-scale-105 li {
    font-size: 105% !important;
    line-height: 1.3;
  }
  .content-scale-120 ul, .content-scale-120 ol, .content-scale-120 li {
    font-size: 110% !important;
    line-height: 1.3;
  }
  .scale-105 {
    transform: scale(1.05);
    transform-origin: center;
  }
  section.scale-105 {
    transform: scale(1.05);
    transform-origin: center;
  }
  .scale-120 {
    transform: scale(1.2);
    transform-origin: center;
  }
  section.scale-120 {
    transform: scale(1.2);
    transform-origin: center;
  }
  .scale-90 {
    transform: scale(0.9);
    transform-origin: center;
  }
  section.scale-90 {
    transform: scale(0.9);
    transform-origin: center;
  }
  .scale-80 {
    transform: scale(0.8);
    transform-origin: center;
  }
  section.scale-80 {
    transform: scale(0.8);
    transform-origin: center;
  }
  .scale-85 {
    transform: scale(0.85);
    transform-origin: center;
  }
  section.scale-85 {
    transform: scale(0.85);
    transform-origin: center;
  }
  .scale-95 {
    transform: scale(0.95);
    transform-origin: center;
  }
  section.scale-95 {
    transform: scale(0.95);
    transform-origin: center;
  }
  p {
    font-size: 1rem;
    color: var(--color-foreground);
    text-align: left;
    margin: 5px 0;
  }
  ul, ol, li {
    font-size: 0.8rem;
    line-height: 1rem;
    margin: 5px 0;
    padding-left: 1.5em;
    font-weight: 300;
  }

  .image-stack {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    gap: 30px;
    max-width: 100%;
    margin: 20px auto;
  }

  .image-container {
    display: absolute;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .image-container img {
    width: 100%;
    height: auto;
    max-width: 100%;
    max-height: 100%;
    min-height: 0;
    min-width: 0;
    object-fit: contain;
  }

  .image-caption {
    font-size: 0.6rem;
    font-weight: 300;
    color: var(--color-H2);
    margin-top: 10px;
    
  }

  .flex-container {
    display: flex;
    justify-content: center;
    align-items: flex-start; /* Aligns items to the top */
    gap: 30px; /* Space between items */
    width: 100%;
  }

  .flex-item {
    text-align: center; /* Center the caption text */
  }

  .flex-item img {
    width: 100%; /* Make image fill the container */
    height: auto;
    object-fit: contain; /* Ensure image scales correctly */
    max-height: 370px; /* Optional: limit image height */
  }

  .flex-item p {
    font-size: 0.6rem;
    font-weight: 300;
    color: var(--color-H2);
    margin-top: 10px;
  }

header: '<img src="presentation_images/logo_ecris.svg" alt="logo" width="60"/> <img src="presentation_images/logo_ufmg.svg" alt="logo" width="90"/>'

---
<style>
  :root {
    --color-background: #ffffffff;
    --color-background-code: #ccc;
    --color-background-paginate: rgba(128, 128, 128, 0.05);
    --color-foreground: #345;
    --color-highlight: rgba(132, 34, 34, 1);
    --color-H1: rgba(153, 13, 36, 1);
    --color-H2: rgba(83, 37, 45, 1);
    --color-H3: rgba(155, 38, 58, 1);
    --color-H4: rgba(43, 43, 43, 1);
    --color-highlight-hover: rgba(237, 54, 54, 1);
    --color-highlight-heading: rgba(227, 42, 36, 1);
    --color-header: #ffffffff;
    --color-header-shadow: transparent;
  }
</style>

# conTorchionist: <span class="sub"> a flexible nomadic library for exploring machine listening/learning in multiple platforms, languages, and time-contexts </span>


#### José Henrique PADOVANI (UFMG)
#### Vinícius Cesar de OLIVEIRA (UNICAMP)

<br/><br/><br/><br/>

### SBCM 2025, NICS/UNICAMP, Campinas/Brazil - September 17, 2025

---
## *machine listening*: contexts and meanings

  <br/>

  -  *machine listening* in *Interactive Music Systems*: <span class="f90">initially, meaning to the process of 'listening to' MIDI parameters</span><br/>
  - in MSP/PD context: <span class="f90"> real-time audio feature extraction and analysis</span><br/>
  - 2000s: <span class="f90">increasingly influenced by the *machine listening* meaning from related fields like Music Information Retrieval (MIR), Automatic Speech Recognition (ASR), and Computational Auditory Scene Analysis (CASA)</span><br/>
  - today, in a broader context: <span class="f90">
  strongly transformed by the widespread adoption of machine learning (ML)/artificial intelligence (AI)/deep learning (DL) techniques</span><br/>
  - from a critical-exploratory-creative perspective: <span class="f90">integration of these techniques into artistic and research practices is still challenging.</span>


---

## challenges

- **pragmatic/end-user** design: <span class="f90">many tools are designed for very specific purposes (e.g., stem separation, timbre transfer, etc.) but not for general exploration.</span>
- **'black box'**: <span class="f90">many modern tools function as opaque "black boxes", limiting creative exploration and understanding, segregating people into "users"  and "developers".</span>
- **isolation** into environment/language, OS, architecture, and/or time-context: <span class="f90">many tools are tied to a specific environment/language, OS, architecture or time-context, restricting workflows (e.g.: train in non-real-time, use/apply in real-time; usage of different tools in musicological and creative contexts; etc.).</span>
- **CPU-only**: <span class="f90">most tools do not leverage **GPU** acceleration, while this is widely used in other AI/ML fields.</span>

---

## conTorchionist goals

- **flexibility**: allow for use the same machine listening/learning in different contexts (real-time/non-real-time; environments/languages; OS/architectures; CPU/GPU; etc)
- **nomadic**: allow for easy migration/integration of  workflows and models between different environments/languages (PD, Max, SC, Python, etc.)
- **transparent**: provide access/manipulation of the inner workings of the DSP/ML algorithms
- **torch-based**: take advantage of the open-source PyTorch/libtorch/torchaudio ecosystem, which is widely used in the AI/ML community
- **core/wrappers architecture**: a single C++ core shared library (relying on `libtorch`) with language-specific wrappers for different environments (PD, Max, SC, Python, etc.)


---
## remarkable and inspiring projects

<div class="f90">

-   **Librosa (Python):** The most popular Python library for Music Information Retrieval (MIR), offering a vast range of tools for audio analysis.
-   **Essentia (C++/Python):** A C++ library with Python bindings, prioritizing efficiency and scalability for both real-time and non-real-time processing.
- **timbreID (Pure Data), Zsa.Descriptors (Max), SCMIR (SuperCollider):** Real-time audio feature extraction libraries tailored to their respective environments.
- **FluCoMa (Fluid Corpus Manipulation):** A comprehensive C++ toolset for Max, Pure Data, and SuperCollider, enabling both real-time and non-real-time corpus-based workflows. **(a great inspiration for this work)**
- **nn_tilde:** A direct bridge for running pre-trained PyTorch models (inference) in real-time environments like Max and Pure Data (with a port for SC), demonstrating the demand for this specific integration.
- **PyTorch / libtorch / torchaudio:** The foundational ML ecosystem. It provides powerful tensor computation on CPU/GPU and the core C++ backend (`libtorch`) that makes **conTorchionist** possible.
</div>

---

## architecture overview

A simple, two-part structure:

- **core library (C++)**
    - Relying on `libtorch` (the C++ core of PyTorch).
    - Built as a shared library (`.dylib`, `.so`, `.dll`).
    - Contains all core algorithms (`Processors`) for audio analysis, ML, etc.
    - Platform-agnostic.

- **Wrappers**
    - Language-specific bindings for PD, Max, SC, and Python.
    - Use language-specific APIs, utilities, and auxiliary headers to interface with the core library.
    - Handles the instantiation and management of `Processors` in the target environment.

---

## core / processors

A set of modular tools for signal processing, designed for high performance and customizability.

Some implemented `Processors`:

- `RMSOverlapProcessor`: RMS with different windowing/interpolation options, using a circular buffer (actually also a processor) to handle overlapping frames.
- `RFFTProcessor` / `IRFFTProcessor`: Real and Inverse Fast Fourier Transform.
- `SpectrogramProcessor`: Real-time spectrogram computation.
- `MelSpectrogramProcessor`: Maps frequency to the Mel scale.
- `MFCCProcessor`: Extracts Mel-frequency cepstral coefficients.

---

## example 1: `torch.rfft~` and `torch.irfft~` in Pure Data

<span class="f80">
The RFFTProcessor and IRFFTProcessor exposed as the [torch.rfft~] and [torch.irfft~] objects, respectively. They allow for real-time, GPU-accelerated FFT analysis directly within the patching environment.
</span>


<div class="flex-container">
  <div class="flex-item" style="width: 65%;">
    <img src="fig/torch_rfft_irfft.png" alt="Torch RFFT in Pure Data"/>
    <p>torch.rfft~ and torch.irfft~ / Pure Data</p>
  </div>

</div>

---

## example 2: `torch.spectrogram~` in Pure Data & Max

<span class="f80">
The SpectrogramProcessor is exposed as the [torch.spectrogram~] object. It allows for real-time, GPU-accelerated spectrogram analysis directly within the patching environment.
</span>

<div class="flex-container">
  <div class="flex-item" style="width: 45%;">
    <img src="fig/torch_spectrogram.png" alt="Torch Spectrogram in Pure Data"/>
    <p>torch.spectrogram~ / Pure Data</p>
  </div>
  <div class="flex-item" style="width: 45%;">
    <img src="fig/max_torch_spectrogram.png" alt="Max Torch Spectrogram"/>
    <p>torch.spectrogram~ / Max</p>
  </div>
</div>

---

## example 3: Mel spectrogram in Pure Data

<span class="f80">
The MelSpectrogramProcessor is exposed as the [torch.melspectrogram~] object. It allows for real-time, GPU-accelerated Mel spectrogram extraction directly within the patching environment.
</span>

![bg left height:400px](fig/torch_melspectrogram.png)

---

## neural network processors

<span class="f80">

`conTorchionist` supports two main approaches for integrating neural networks:

</span>

<br/>

- **Inference:** Load and run complex, pre-trained models (from Python/PyTorch) in real-time using the `[torch.ts~]` object.

<br/>

- **Interactive Model Building:** Create, train, and explore simple neural networks directly within the environment (e.g., Pure Data) using modular objects/processors (`[torch.sequential]`, `[torch.linear]`, `[torch.activation]`, etc.).

---

## example 4: loading a pre-trained model

<br/>

<span class="f70">
The [torch.ts] object can load a TorchScript model (`.ts`) to perform tasks like real-time audio synthesis or, in this case, MFCC frame reconstruction using an autoencoder.
</span>

<div style="display: flex; justify-content: center;">

<!-- ![height:400px](fig/mfcc_reconstruction.png) -->

![bg left height:400px](fig/mfcc_reconstruction.png)

</div>

---

## example 5: building a network in pure data

<span class="f70">
The [torch.sequential] object acts as a container, allowing you to build a neural network layer by layer using other objects like [torch.linear] and [torch.activation]. This transforms the environment into an exploratory space for prototyping models.
</span>


![center height:350px](fig/torch_seq.png)


---

## conclusion and future work

<br/>

- development is at an early stage, with many features yet to be implemented (expand set of Processors, implement more wrappers, etc.) 
- the library is open-source (LGPLv3) and available at [https://github.com/ecrisufmg/contorchionist]
- binary releases to be made available when we have the current Processors wrappers implemented and documented


---

## final remarks / acknowledgments

- `conTorchionist` was made with the support of FAPEMIG, CAPES, and CNPq.
- AI agents and tools were used while sketching and writing some parts of `conTorchionist` (usually requiring a lot of corrections and adaptations)

---

## thanks!

![bg left height:300px](presentation_images/contorchionist_github.png)

<br/>

<div class="f70">
code:
<a href="https://github.com/ecrisufmg/contorchionist">https://github.com/ecrisufmg/contorchionist</a>
</div>
<br/>

<div class="f70">
examples:
<a href="https://www.youtube.com/watch?v=4R0uCS_r9QA">https://www.youtube.com/watch?v=4R0uCS_r9QA</a>
</div>

<div class="f70">
<a href="https://www.youtube.com/watch?v=0PbWdBhGKzk">https://www.youtube.com/watch?v=0PbWdBhGKzk</a>
</div>

<div class="f70">
<a href="https://www.youtube.com/watch?v=AbU6onIZAO8">https://www.youtube.com/watch?v=AbU6onIZAO8</a>
</div>
<br/>

<div class="f70">
contact:<br/>
<a href="mailto:jhp@ufmg.br">jhp@ufmg.br</a>
<a href="mailto:oviniciuscesar@gmail.com">oviniciuscesar@gmail.com</a>
</div>