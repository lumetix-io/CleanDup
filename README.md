# CleanDup
A fast, privacy‑first duplicate file finder for macOS and Windows.  
Designed for users who demand accuracy, performance, and complete local data processing.

---

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [How It Works](#how-it-works)
- [Technology](#technology)
- [Performance](#performance)
- [Privacy](#privacy)
- [Screenshots](#screenshots)
- [Roadmap](#roadmap)
- [Changelog](#changelog)
- [FAQ](#faq)
- [Support](#support)
- [License](#license)

---

## Overview
CleanDup is a high‑performance duplicate file finder built for macOS and Windows.  
It uses a hybrid scanning engine combining metadata analysis and cryptographic hashing to deliver fast, accurate results — without uploading any data to the cloud.

CleanDup is built for:
- Users who want to reclaim disk space safely  
- Professionals who manage large media libraries  
- Privacy‑conscious users who prefer offline tools  
- Anyone who needs a reliable, modern duplicate finder

---

## Key Features
- **Fast scanning engine**  
  Optimized for SSDs, HDDs, and external drives. Handles large folders and multi‑TB volumes.

- **Accurate duplicate detection**  
  Uses multi‑stage comparison: size → metadata → hash → optional deep verification.

- **Privacy‑first architecture**  
  All operations run locally. No telemetry, no cloud upload, no background processes.

- **Safe deletion workflow**  
  Preview duplicates, auto‑select rules, and undo‑friendly deletion.

- **Cross‑platform native performance**  
  - macOS: Universal binary (Intel + Apple Silicon)  
  - Windows: Native 64‑bit build

- **Minimal, distraction‑free UI**  
  Clean, modern interface designed for clarity and speed.

---

## How It Works
CleanDup uses a multi‑phase scanning pipeline:

1. **Directory traversal**  
   Efficient file enumeration with OS‑level optimizations.

2. **Candidate grouping**  
   Files are grouped by size and type to reduce unnecessary hashing.

3. **Hashing**  
   Uses fast, collision‑resistant hashing (xxHash / SHA‑256 depending on mode).

4. **Deep comparison (optional)**  
   Byte‑level verification for edge cases.

5. **Result presentation**  
   Duplicates are grouped visually for easy review.

6. **Safe deletion**  
   Files are moved to system trash/recycle bin unless permanently removed.

---

## Technology
CleanDup is built with a focus on performance and reliability:

- **Native codebase** for macOS & Windows  
- **Optimized hashing pipeline**  
- **Memory‑efficient file grouping**  
- **Asynchronous scanning** for smooth UI responsiveness  
- **Zero cloud dependencies**  

---

## Performance
Internal benchmarks (MacBook Air M2, 16GB RAM):

| Dataset | File Count | Size | Scan Time |
|--------|------------|------|-----------|
| Photos Library | 32,418 | 118 GB | 14.2s |
| Video Archive | 4,912 | 512 GB | 27.8s |
| Mixed Documents | 58,201 | 42 GB | 11.6s |

Performance varies by storage type and file distribution.

---

## Privacy
CleanDup follows strict privacy principles:

- No data leaves your device  
- No analytics or telemetry  
- No cloud scanning  
- No background services  
- No hidden network requests  

All processing happens locally on your machine.

---

## Screenshots
_Add screenshots here once available._

---

## Roadmap
- Smart auto‑selection rules  
- Folder exclusion lists  
- Enhanced reporting  
- Multi‑language support  
- Dark mode  
- Command‑line interface (CLI)  
- Plugin system for custom rules  

---

## Changelog
See the full changelog in:  
`CHANGELOG.md`

---

## FAQ

### **Does CleanDup upload my files?**  
No. All processing is 100% local.

### **Is deletion reversible?**  
Yes. Files are moved to Trash/Recycle Bin unless you choose permanent deletion.

### **Does it support external drives?**  
Yes — USB, SSD, HDD, and network‑mounted drives.

### **Does CleanDup modify my files?**  
No. It only reads file metadata and content for hashing.

### **Is there a command‑line version?**  
Planned in the roadmap.

---

## Support
Open an issue for bug reports or feature requests:  
https://github.com/lumetix-io/CleanDup/issues

---

## License
This repository contains documentation and assets only.  
The CleanDup application is proprietary software.
