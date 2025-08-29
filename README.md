# Isolated Black Hole Detection Project

This repository contains my contribution to a team project aimed at developing methods for detecting **local isolated black holes** through gravitational microlensing in night-sky images from the Vera C. Rubin Observatory (LSST).  

The project involved three main components:  
1. **Microlensing algorithm implementation** — applying black hole microlensing to telescope images (Raymond Shao).  
2. **Noise cancellation** — manually stacking and denoising telescope images to improve signal quality (Yunki Yau).  
3. **Dynamic modelling** — applying the microlensing algorithm to simulated black hole distances, masses, and velocities (Jaime Pryor).  

This repository contains the code and files from my portion of the project, which focused on **denoising telescope images** by stacking multiple exposures to reduce background noise and prepare the data for microlensing analysis.  

## Folder Structure
- `src/Noise_cancellationLSST.ipynb` — Jupyter notebook implementing the image stacking / noise cancellation workflow.  
- `data/` — telescope image files used for stacking.  
- `project_outcomes/` — group presentation slides, example telescope image, and example microlensing video.  

## Requirements
- Python 3.10+  
- Jupyter Notebook  
- numpy, matplotlib, opencv-python  

Install with:
```bash
pip install numpy matplotlib opencv-python jupyter
```

## Usage
1. Place telescope image files into the `data/` folder.  
2. Launch the Jupyter notebook:  
   ```bash
   jupyter notebook src/Noise_cancellationLSST.ipynb
   ```  
3. Run all cells to stack and denoise the telescope images.  

## Author
Noise cancellation / image stacking code developed by **Yunki Yau**.  
GitHub: [yunkiyau](https://github.com/yunkiyau)  
Email: yunki.yau@gmail.com  

## Acknowledgements
Developed as part of a collaborative project with **Raymond Shao** and **Jaime Pryor**.  

---
