# HULK - HTTP Unbearable Load King (DDoS Script)

A Python script designed for educational purposes to demonstrate and understand certain types of Denial of Service (DDoS) attacks, specifically those targeting web servers with a high volume of unique HTTP GET requests.

## 📜 Overview

### What Is A DDoS Attack?

A Distributed Denial of Service (DDoS) attack is a malicious attempt to disrupt the normal traffic of a targeted server, service, or network by overwhelming the target or its surrounding infrastructure with a flood of Internet traffic. DDoS attacks achieve effectiveness by utilizing multiple compromised computer systems as sources of attack traffic.

These attacks can target a wide array of important resources, from e-commerce sites and online banking platforms to news websites, presenting a significant challenge in maintaining the availability and accessibility of critical online services.

## 🚨 Disclaimer

**⚠️ This tool is provided for educational and research purposes ONLY.**

*   **DO NOT** use this tool for any illegal activities or to cause harm to any system or network you do not have explicit, prior, written permission to test.
*   Misuse of this tool can lead to severe legal consequences.
*   The author(s) of this tool are not responsible for any misuse or damage caused by this program. **Use at your own risk.**

## 🎓 Used in Research

This tool ("Hulk") was utilized in the following academic research for evaluating DDoS detection and prevention mechanisms:

*   **Title:** Detecting and Preventing Distributed Denial of Services (DDoS) Attacks using Machine Learning and Software Defined Networking
*   **Publication:** 2020 International Conference on Electrical, Communication, and Computer Engineering (ICECCE)
*   **Abstract/Link:** [IEEE Xplore](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9177002)

The paper mentions using HULK (HTTP Unbearable Load King) as a DDoS tool for evaluating their proposed framework.

## ⚙️ Requirements

*   Python 2.x or Python 3.x (Python 3.x is recommended as Python 2.x is end-of-life)
*   `git` (for cloning the repository)

## 🚀 How to Run

1.  **Clone the repository:**
    Open your terminal or command prompt and run:
    ```bash
    git clone https://github.com/beezanX/Hulk
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd Hulk
    ```

3.  **Run the script:**
    Execute the script using Python:
    ```bash
    python hulk.py <target_url>
    ```
    For example:
    ```bash
    python hulk.py http://example.com
    ```
    **Note:** Replace `http://example.com` with the URL of the target you have **explicit permission** to test against. Some versions of HULK might require configuring the target within the script itself if command-line arguments are not supported by your specific version.

The script is straightforward to run once Python is installed on your system.

## ℹ️ More Details

For further information, to report issues, or to contribute, please refer to this GitHub repository or contact the maintainer via their GitHub profile.

*   **Project Repository:** [https://github.com/beezanX/Hulk](https://github.com/beezanX/Hulk)
*   **Maintainer:** [beezanX](https://github.com/beezanX)

---

Consider adding a `LICENSE` file to your repository (e.g., MIT License, Apache 2.0) and then you can add a section like:

## 📄 License 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
This project is open-source and available under the MIT License. You are free to use, modify, and distribute the code, provided you include the original copyright and license notice.
