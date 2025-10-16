# Flux - P2P File Sharing 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Introduction
Flux = P2P File Sharing is a peer-to-peer file sharing application written in Python. It allows users to share files directly with each other without the need for a centralized server. This project aims to provide a decentralized and efficient way of sharing files among multiple users. <br>

Supported Operating Systems: <br>
- Windows ✅<br>
- macOS&nbsp;&nbsp;&nbsp; ✅<br>
- Linux&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✅


## Features
- Peer-to-peer file sharing without a central server.
- Efficient file transfer using TCP/IP sockets.
- Simple and intuitive command-line interface.

## Requirements
To run this application, you need the following:

- Python (version 3.7+)
- Install requirement.txt

## Installation
1. Clone the repository:

```bash
git clone https://github.com/your-username/P2P-File-Sharing.git
```

2. Change into the project directory:
```bash
cd P2P-File-Sharing
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Start the application by running these scripts:
```python
python Chunk_Uploader.py
```
```python
python Chunk_Announcer.py
```
```python
python Chunk_Discovery.py
```
```python
python Chunk_Downloader.py
```

