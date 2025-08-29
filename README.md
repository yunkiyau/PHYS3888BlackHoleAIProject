# Isolated Black Hole Detection Project

This repository contains my contribution to a Senior Physics team project at USYD. Under the supervision of Prof. Peter Tuthill, Prof. Geraint Lewis, Dr. David Sweeney and Dr. Alison Wong, we conducted work neccessary to develop an AI training model for detecting local isolated black holes. Black holes change the light that we receive on Earth from outer space due to a phenomenon called gravitational microlensing. Our group primarily applied gravitational microlensing effects on simulated night-sky images that will come from the Vera C. Rubin Observatory (LSST).  

The project involved three main components:  
1. **Microlensing algorithm implementation** — applying black hole microlensing to telescope images (Raymond Shao).  
2. **Noise cancellation** — manually stacking and denoising telescope images to improve signal quality (Yunki Yau).  
3. **Dynamic modelling** — Taking the microlensing algorithm and extending it to a variety of black hole distances, masses, and velocities (Jaime Pryor).  

This repository contains the code and files from my portion of the project, which focused on denoising telescope images by stacking multiple exposures to reduce background noise and prepare the data for microlensing analysis. There was significant complication due to the multitude of orientations images could take over a time-series due to the rotation of Earth. Please feel free to reach out if you are interested in this work - only my small (generalisable) portion of this project is presented here as it is an ongoing study within the Sydney Institute for Astronomy.

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
Email: yunki.yau@gmail.com, yyau2516@uni.sydney.edu.au

## Acknowledgements
My excellent teammates for this project were Jaime Pryor and Raymond Shao.
We were supervised by Prof. Peter Tuthill, Prof. Geraint Lewis, Dr. David Sweeney, and Dr. Alison Wong at the University of Sydney, School of Physics.

---
