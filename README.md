# Engineering Foundations: The Math-to-Systems Sprint 🚀

> **Note:** This repository is a living technical document. It is updated periodically as I bridge new mathematical concepts into high-level engineering applications. Stay tuned for updates.

## 📌 Project Overview
This repository documents my journey of mastering the mathematical DNA that powers modern global infrastructure. My goal is to move beyond abstract theory by building **"Professional Bridges"** between core mathematics and the actual systems we build, secure, and scale.

## 🛠️ The "Full-Stack" Methodology
I don't just solve equations; I implement them across the entire engineering spectrum:

* **Mathematics:** From Signed Operations and Absolute Value to Calculus, Linear Algebra, and Discrete Math.
* **Systems Engineering:** High-level bridges involving SLA Monitoring, Anomaly Detection, Cloud Billing, and AI/ML Optimization.
* **Implementation (The Polyglot Approach):**
    * **Now:** Python (Jupyter Labs), Matplotlib.
    * **Coming Soon:** Bash Scripting, SQL Database Logic, Assembly (Low-Level Optimization), and C.
* **Domain Focus:** Linux Kernel Architecture, Cybersecurity Protocols (Encryption/XOR), and DevOps Infrastructure.

## 🗺️ Learning Roadmap
I am currently bridging the gap between professional systems engineering and foundational mathematics.

### 🛡️ [CyberSecurity](./2.%20CyberSecurity/)
* **Linux 100 Fundamentals** | **Status: 100% Completed** ✅
* *Click the heading above to view the CyberSecurity Master Index.*

### 📐 [Mathematics](./1.%20Mathematics/)
* **Fundamentals of Math** | **Status: In Progress** ⏳
* *Click the heading above to view the Mathematics Master Index.*

## ⚙️ Environment Setup & Infrastructure
This repository utilizes a "Sovereign Lab" configuration to ensure cross-language execution and reproducibility.
<details>
   
   <summary><b> 1. Manual Software Downloads (Web-Based) (Click to expand) </b></summary>
   
   * CMDER: Download 'Full' version from https://cmder.app/ (Unzip and add to System PATH)
   * PYTHON: Download 3.10+ from https://www.python.org/downloads/ (Check "Add Python to PATH")
   * NODE.JS/NPM: Download LTS version from https://nodejs.org/ (Includes NPM)
</details>

<details>
<summary><b> 2. Virtual Environment Creation (Click to expand) </b></summary>
   
   * Creating the isolated 'studyenv' to house all dependencies.
```bash
python3 -m venv studyenv
```
</details>

<details>
<summary><b> 3. Environment Activation (Cross-Platform) (Click to expand) </b></summary>
   
   *Activating the 'studyenv' virtual environment. Use the appropriate command for your current OS context.*

* For Windows (PowerShell/CMD):
```bash
.\studyenv\Scripts\activate
```

*  For Linux/macOS (Bash/Zsh):
```bash
source studyenv/bin/activate
```
</details>

<details>
<summary><b> 4. Python Core Configuration - SSL Global Bypass (Click to expand) </b></summary>

   *Configures PIP to trust official repositories globally to avoid SSL handshake errors.*
```bash
pip config set global.trusted-host "pypi.org files.pythonhosted.org pypi.python.org"
```
</details>

<details>
<summary><b> 5. Jupyter Lab & Language Server Protocol (LSP) Setup (Click to expand) </b></summary>

   *Installing Jupyter Lab and the LSP extensions for intelligent code completion.*
```bash
pip install jupyterlab --trusted-host pypi.org --trusted-host files.pythonhosted.org
pip install jupyterlab-lsp --trusted-host pypi.org --trusted-host files.pythonhosted.org
pip install 'python-lsp-server[all]' --trusted-host pypi.org --trusted-host files.pythonhosted.org
```
</details>

<details>
<summary><b> 6. Jupyter Lab Bash Kernel Setup (Click to expand) </b></summary>
   
* Installing the Bash Kernel to enable native Linux command execution within 

   *Jupyter Lab—critical for the "Sovereign Lab" (Phase 3) documentation.*
```bash
pip install bash_kernel --trusted-host pypi.org --trusted-host files.pythonhosted.org
python -m bash_kernel.install
```
</details>

<details>
<summary><b> 7. Global Libraries for Engineering Bridges (Click to expand) </b></summary>
   
```bash
pip install pandas numpy matplotlib --trusted-host pypi.org --trusted-host files.pythonhosted.org
```
</details>

<details>
<summary><b> 8. Node.js Security Bypass & Language Server Installations (Click to expand) </b></summary>
   
* Temporarily disable SSL/TLS security to install global language servers
   
```bash
npm config set strict-ssl false
export NODE_TLS_REJECT_UNAUTHORIZED=0
```
* Install Bash Language Server (For Linux 100 Sprint)
  
```bash
sudo npm install -g bash-language-server
```

* Install SQL Language Server (For Database Bridges)
  
```bash
sudo -E npm install -g sql-language-server --unsafe-perm=true --allow-root
```

</details>

<details>
<summary><b> 9. Re-Enabling Security (Post-Installation) (Click to expand) </b></summary>
   
* IMPORTANT: Reset security variables once installations are finished
  
```bash
export NODE_TLS_REJECT_UNAUTHORIZED=1
npm config set strict-ssl true
```
</details>

<details>
<summary><b> 10. Disabling SSL for NPM (Persistent Config if needed) (Click to expand) </b></summary>

   *Only use if you are in a permanent restricted-network environment*
```bash
npm config set strict-ssl false
```
</details>

<details>
<summary><b> 11. Essential Export Utilities (Python Native) (Click to expand) </b></summary>
   
*Replacing 'notebook-export' (deprecated/404) with the official nbconvert.  This allows exporting notebooks to Markdown, PDF, and HTML via terminal.*

```bash
pip install nbconvert --trusted-host pypi.org --trusted-host files.pythonhosted.org
```
</details>

<details>
<summary><b> 12. Launching the Lab (Click to expand) </b></summary>

*Navigate to your 'Engineering-Foundations' folder and run:*

```bash
jupyter lab
```
</details>

### 🔗 Connected Writing
* [Follow me on LinkedIn](https://www.linkedin.com/in/mohamed-abdelhamied)
* [Follow me on Medium](https://medium.com/@mohamed_abdelhamied)
