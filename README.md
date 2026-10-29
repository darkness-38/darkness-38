<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=A855F7&center=true&vCenter=true&width=560&lines=Hi%2C+I'm+Hamza+Mert+Da%C5%9Fdemir+%F0%9F%91%8B;Computational+Number+Theory+%26+Experimental+Math;Pure+Rust+Systems+%26+Algorithmic+Engines;Linux+%26+Low-Level+Architecture" alt="Typing SVG" />
  </a>
</h1>

<p align="center">
  <a href="https://raseplus.com" target="_blank"><img src="https://img.shields.io/badge/Rase%2B-Streaming-FF7139?style=for-the-badge&logo=Firefox&logoColor=white" alt="Rase+"></a>
  <a href="mailto:someoneteachs@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### 🔬 Research & Key Focus

I am an independent researcher and software builder specializing in **experimental mathematics, high-precision integer relation algorithms, and low-level systems engineering**.

* 🦀 **Experimental Number Theory:** Creator of **`hyper-lll`**, an arbitrary-precision (230-digit) LLL lattice reduction and automated Wilf–Zeilberger (WZ) algorithmic proof engine built entirely from scratch in pure Rust.
* 📐 **Recent Milestones:** Discovered accelerated Calabi–Yau series for Catalan's constant $G$, $\zeta(3)$, and $\pi^4$ without harmonic numbers, endorsed by Doron Zeilberger for arXiv (`math.NT` / `math.CO`).
* 🐧 **Systems & OS:** Low-level customization on **Arch Linux / CachyOS**, kernel optimization, and modular software architectures.

---

### 🛠️ Core Stack & Tooling

<p align="center">
  <b>Systems & Computation:</b><br/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" alt="rust" width="38" height="38"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="38" height="38"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/latex/latex-original.svg" alt="latex" width="38" height="38"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="bash" width="38" height="38"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/archlinux/archlinux-original.svg" alt="archlinux" width="38" height="38"/>
</p>

<p align="center">
  <b>Web Platforms & Infrastructure:</b><br/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="typescript" width="38" height="38"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="react" width="38" height="38"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="nextjs" width="38" height="38"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="docker" width="38" height="38"/>&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="git" width="38" height="38"/>
</p>

---

### 📌 Pinned Research

```rust
// hyper-lll: 230-digit LLL lattice reduction & WZ engine
fn verify_closed_form() -> Result<ExactRelation, MotivicObstruction> {
    let lattice = LLL::reduce(scale: 10^160, precision: 230);
    lattice.find_diagonal_periods(CalabiYau::Level3)
}
