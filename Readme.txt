USB-UNCENSORED-LLM (fork)
=========================

This repository is a fork. Its upstream README states the project is deprecated and that
active development moved to https://github.com/techjarves/Uncensored-Local-Studio.

WHAT IT IS
----------
A portable, offline local-AI environment that runs large language models from a hard drive
or a USB/SSD on Windows, macOS, Linux and Android (Termux). It bundles portable Python and a
local Ollama engine, serves a dark-mode chat web UI on your network, and installs curated
GGUF models (for example Gemma 2 2B and Qwen 3.5 9B variants) or any GGUF from Hugging Face.

FOLDERS
-------
  Windows/, Mac/, Linux/, Android/   Per-OS installers and launchers
  Shared/                            Models, binaries, chat data and Python shared by all OSes

QUICK START
-----------
  1. Run the installer for your OS (Windows/install.bat, Mac/install.command,
     bash Linux/install.sh, bash Android/install.sh).
  2. Download a model through the installer, or place a .gguf file in Shared/models.
  3. Run the start script (Windows/start-fast-chat.bat, Mac/start.command, Linux/start.sh,
     Android/start.sh). The chat UI opens in your browser.

Requirements: at least 8 GB of free storage (16 GB recommended) and 8 GB of RAM (16 GB for
the larger models).

Note: the models are described as unfiltered. Use them responsibly. See README.md for
troubleshooting and the Android guide.
