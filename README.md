# Voynich Semitic‑Root Analysis – Dataset Package

This archive contains all raw data used to reproduce the results in the pre‑print *“Voynich Manuscript as a Semitic‑Root Ritual Text”*.

| File | Description |
|------|-------------|
| `EVA_v4_transliteration.pdf` | Full Zandbergen–Landini EVA v4 transliteration corpus (≈ 58 k tokens). |
| `arabic_roots_raw.txt` | 7 504 Arabic triliteral + quadriliteral roots (GPL‑licensed list by T. Zerrouki). |
| `maltese_pilot_roots.txt` | 25 Old‑Maltese roots extracted from *Il‑Kantilena* (c. 1470). |
| `control_italian_sample.txt` | Italian control wordlist sample. |
| `control_korean_sample.txt` | Korean control wordlist sample. |
| `control_nahuatl_sample.txt` | Classical Nahuatl control wordlist sample. |

## Usage

1. Unzip this archive in the same folder as `root_match.ipynb` (see Appendix B of the manuscript).  
2. Open the notebook and run all cells – paths are relative (`./`).  
3. The final precision line should read **≈ 0.88** for the top‑200 evaluation.

## License

* **Arabic roots list** is GPL‑licensed per original repository <https://github.com/linuxscout/arabic-roots>.  
* All other plain‑text lists (Maltese pilot, control wordlists) are released under the MIT License (see `LICENSE`).  
* The EVA PDF is © R. Zandbergen & G. Landini – redistributed here under fair‑use for scholarly analysis.

---
Generated 2025-06-17.
