<p align="center"><a href="https://github.com/ItsUniquePlayz/UniqueColab"><img src="https://github.com/ItsUniquePlayz/UniqueColab/blob/master/Logo.png" alt="Logo" height="80"/></a></p>

<h1 align="center">UniqueColab</h1>
<p align="center">Run Minecraft Server on Google Colab with ease</p>
<a href="https://colab.research.google.com/github/ItsUniquePlayz/UniqueColab/blob/master/UniqueColab.ipynb" target="_parent"><img align="right" src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

## 🌍 What is Google Colab?
Google Colab (Colaboratory) is a cloud-based service that allows users to run Python code and Jupyter notebooks for free. It is commonly used for machine learning, data analysis, and automation. UniqueColab leverages Colab’s computing resources to run a Minecraft server.

## 💰 Is it really free to use?
Yes, Google Colab provides free computing resources, but there are some limitations:
1. The runtime is limited to a maximum of 12 hours, after which it must be restarted manually.
2. Colab resources are shared among users, so heavy or prolonged usage may lead to restrictions.
3. If you need a permanent solution, consider renting a VPS for better stability.

## 📜 Instructions
1. Open the UniqueColab notebook in Google Colab.
2. Read through the notebook and execute the necessary cells to set up your Minecraft server.
3. Run the first cell to start the server.
4. Choose between different tunneling options: Ngrok, Playit.gg, or Cloudflare Argo.
   - **Ngrok**: Easiest to set up but may be unreliable.
   - **Playit.gg**: Provides static subdomains but has debug log spam.
   - **Cloudflare Argo**: Stable but requires additional setup.

## ⚡ How does it work?
UniqueColab automates the setup process for running a Minecraft server in Google Colab:
1. Updates system packages.
2. Installs Java (OpenJDK 16).
3. Mounts Google Drive for persistent storage.
4. Configures and starts a tunneling service to expose the server.
5. Runs the Minecraft server with optimized settings.

## 🛠 Troubleshooting & Bug Reports
If you encounter issues, try the following:
- Use a VPN if connection issues occur.
- Switch between different tunneling services.
- Restart the notebook if something fails.

If the issue persists, report a bug using [this template](https://github.com/ItsUniquePlayz/UniqueColab/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5BBUG%5D).

## 🌟 Tips & Recommendations
- Always back up your Minecraft world to Google Drive.
- Experiment with different tunneling services to find the best one.
- Avoid running intensive tasks continuously to prevent account restrictions.

[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://github.com/ItsUniquePlayz)

