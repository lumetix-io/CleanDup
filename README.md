# CleanDup
A high‑performance, privacy‑first duplicate file finder for macOS and Windows.  
Built for professionals who manage large datasets and users who demand accuracy, speed, and complete local processing.

---

## Official Pages

- **Brand Homepage:** https://lumetix.io  
- **CleanDup Product Page:** https://lumetix.io/cleandup  

These pages provide product details, screenshots, download links, and additional information about the Lumetix software suite.

---

## Table of Contents
- [Overview](#overview)
- [Why CleanDup](#why-cleandup)
- [Key Features](#key-features)
- [Architecture](#architecture)
- [Scanning Pipeline](#scanning-pipeline)
- [Performance](#performance)
- [Privacy & Security](#privacy--security)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Roadmap](#roadmap)
- [FAQ](#faq)
- [Support](#support)
- [License](#license)

---

## Overview
CleanDup is a modern duplicate file finder designed for speed, accuracy, and privacy.  
It uses a multi‑stage scanning engine combining metadata analysis, hashing, and optional deep verification to identify duplicate files with high precision — without uploading anything to the cloud.

CleanDup is ideal for:

- Photographers & videographers managing large media libraries  
- Knowledge workers with years of documents  
- Developers with large project folders  
- Anyone who wants to reclaim disk space safely and efficiently  

---

## Why CleanDup
Most duplicate finders fall into two categories:

1. Slow but accurate  
2. Fast but unreliable  

CleanDup is engineered to deliver both:

- Fast scanning on large datasets  
- High‑accuracy detection with minimal false positives  
- Zero data transmission  
- A clean, modern UI that stays out of your way  

---

## Key Features
- **High‑performance scanning**  
  Optimized for SSD/HDD/external drives. Handles large folders with ease.

- **Hybrid detection engine**  
  Multi‑stage comparison: size → metadata → hash → optional byte‑level verification.

- **Privacy‑first architecture**  
  No telemetry, no cloud upload, no background processes.

- **Safe deletion workflow**  
  Preview duplicates, auto‑select rules, and reversible deletion.

- **Cross‑platform native performance**  
  - macOS: Universal binary (Intel + Apple Silicon)  
  - Windows: Native 64‑bit build  

- **Minimal, distraction‑free UI**  
  Designed for clarity, speed, and reliability.

---

## Architecture
CleanDup is built on a modular, high‑performance architecture:

### 1. File Enumeration Layer
- Multi‑threaded directory traversal  
- OS‑level optimizations for APFS, NTFS, exFAT  
- Efficient memory usage for large datasets  

### 2. Candidate Grouping Layer
- Groups files by size and type  
- Reduces unnecessary hashing  
- Minimizes I/O operations  

### 3. Hashing Layer
- Fast hashing (xxHash) for large datasets  
- Secure hashing (SHA‑256) for verification mode  
- Optional deep byte‑level comparison  

### 4. Result Aggregation Layer
- Groups duplicates visually  
- Provides safe deletion options  
- Supports export for auditing  

---

## Scanning Pipeline
CleanDup uses a deterministic multi‑phase pipeline:

1. Directory traversal  
2. Size‑based grouping  
3. Metadata comparison  
4. Hashing (fast or secure mode)  
5. Optional deep verification  
6. Duplicate grouping  
7. Safe deletion or export  

This pipeline ensures both speed and accuracy.

---

## Performance
CleanDup’s performance depends on multiple factors, including:

- Storage type (SSD / HDD / external drives)  
- File count and size distribution  
- File types (many small files → slower)  
- System load and available memory  
- Whether deep verification is enabled  

On modern SSDs, CleanDup can scan large folders efficiently, but actual performance varies significantly based on environment.

---

## Privacy & Security
CleanDup follows strict privacy principles:

- No data leaves your device  
- No telemetry or analytics  
- No cloud scanning  
- No background services  
- No hidden network requests  

All processing happens locally.

---

## Usage
1. Launch CleanDup  
2. Select a folder or drive  
3. Review detected duplicates  
4. Confirm deletion or export results  

---

## Screenshots
_Add screenshots here once available._

---

## Roadmap
- Smart auto‑selection rules  
- Exclusion lists  
- Enhanced reporting  
- Multi‑language support  
- Dark mode  
- Command‑line interface (CLI)  
- Plugin system for custom rules  

---

## FAQ

### Does CleanDup upload my files?
No. All processing is 100% local.

### Is deletion reversible?
Yes. Files are moved to Trash/Recycle Bin unless permanently deleted.

### Does it support external drives?
Yes — USB, SSD, HDD, and network‑mounted drives.

### Does CleanDup modify my files?
No. It only reads metadata and content for hashing.

### Is there a CLI version?
Planned in the roadmap.

---

## Support
Open an issue for bug reports or feature requests:  
https://github.com/lumetix-io/CleanDup/issues

---

## License
This repository contains documentation and assets only.  
The CleanDup application is proprietary software.
