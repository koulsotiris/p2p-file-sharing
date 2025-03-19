# Collaborative P2P File Sharing with Distributed Downloading

## Overview

This project implements a **peer-to-peer (P2P) file sharing system** with a **collaborative downloading mechanism**. It allows peers to efficiently share and download files while a central tracker manages file distribution and peer coordination.

## Features
- Peer-to-Peer File Sharing: Peers can share and request files from other peers.
- Collaborative Downloading: Peers can download different segments of a file from multiple sources simultaneously.
- Tracker-Based Coordination: A central tracker keeps track of available files and connected peers.
- Peer Communication: Uses socket programming for real-time peer interactions.
- Concurrency: Implements multi-threading for handling multiple peer requests efficiently.
- Resilient Downloading: Retries download requests in case of failures.
- Dynamic Peer Discovery: Peers can join and leave dynamically, with tracking updates.

## Technologies Used
- Java (Core Language)
- TCP Sockets (Networking & Peer Communication)
- Threads & Concurrency (Efficient handling of multiple requests)
- File I/O (Reading/Writing files and segments)
- Data Structures:
  - HashMap (Tracking files and peers)
  - Lists (Managing file transfers and peer requests)
  - Sets (Preventing duplicate segment downloads)



