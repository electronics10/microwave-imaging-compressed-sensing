# Microwave holographic imaging with compressed sensing (study code)

Study code from my first master's project at the NTU Antenna Lab (advisor: Prof. Shih-Yuan Chen), 2022–2023.

## Credit

The method and the original code are by **Hsin-Jung Yang (楊欣融)**, from his master's thesis
*Sparsely-Sampled Microwave and Millimeter-Wave Holographic Imaging Using Compressed Sensing*
(National Taiwan University).

- `hsin-jung-yang/`: his original code, unmodified.
- `twoD_*.py`, `threeD_*.py`, `test.py`: my rewrite of his 2D and 3D reconstruction. I wrote it to
  understand his method line by line; it does not add anything significant to his work.

## Notes

- Simulation setup (Altair FEKO): https://hackmd.io/@clement0917/imagingreadme#Simulation-Setup-using-Altair-FEKO
- Run `python twoD_Holography.py` or `python threeD_Holography.py`; settings are in `twoD_settings.py` / `threeD_settings.py`.
- A short report is provided [here](compressed-sensing-report.pdf) (credit to Hsin-Jung Yang).
