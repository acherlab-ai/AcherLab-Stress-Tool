<<<<<<< HEAD
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=800&size=32&duration=2500&pause=500&color=19D7FF&center=true&vCenter=true&width=600&lines=AcherLab+Stress+Tool;FOR+AUTHORIZED+USE+ONLY;Security+Testing+Framework" alt="header" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare_Bypass-19D7FF?style=flat-square" />
</p>

---

## DISCLAIMER / TUYEN BO MIEN TRACH

> **AcherLab khong chiu trach nhiem voi bat ky viec su dung trai phep repo nay.**
> **AcherLab is NOT responsible for any misuse of this repository.**
>
> This tool is for **authorized security testing only**.
> You must own the target system or have explicit written permission.
> Unauthorized use is illegal and punishable by law.

## Usage

```bash
# Clone
git clone https://github.com/acherlab-ai/AcherLab-Stress-Tool.git
cd AcherLab-Stress-Tool

# Install
pip3 install -r requirements.txt

# Fetch proxies
python3 fetch_proxies.py

# Run
python3 Attack.py --url http://target.com --threads 500 --duration 3600
```

## GitHub Actions

1. Fork this repo
2. Go to **Actions** > **AcherLab Stress Test** > **Run workflow**
3. Enter target URL, threads, duration
4. Run

## Parameters

| Param | Default | Description |
|-------|---------|-------------|
| `--url` | required | Target URL |
| `--threads` | 500 | Number of threads |
| `--duration` | 3600 | Duration in seconds |
| `--proxy-mode` | both | tor/proxylist/both/none |
| `--no-cf` | false | Disable Cloudflare bypass |

---

<p align="center">
  <sub>&copy; 2026 AcherLab. For authorized security testing only.</sub><br/>
  <sub><b>AcrhorLab khong chiu trach nhiem voi viec su dung repo nay.</b></sub>
</p>
=======
# AcherLab-Stress-Tool
AcherLab Stress Testing Tool - ONLY for authorized security testing. AcherLab khong chiu trach nhiem voi viec su dung repo nay.
>>>>>>> 317e25987268f0248ac913fd08d8a294f94b9d3d
