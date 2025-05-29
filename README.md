# Final Project: End-to-End Planning for Autonomous Driving
# by Milica Vukasinovic, Antoine Dávid
# Team Bubamara
## File
- `DLAV_Phase3.ipynb` – contains our final Jupyter Notebook for Milestone 3 (Sim-to-Real Generalization) of the Deep Learning for Autonomous Vehicles project (CIVIL-459)
- `https://drive.google.com/file/d/1V6bMEs64L3SltI6OoVOrl9qqe3w7vv9o/view?usp=drivesdk` - contains the final model achieving our best result. it os too big for uploading on GitHub. please find it with this link.

## Overview
We implement an end-to-end trajectory planning model for autonomous driving, designed to generalize from simulated to real-world domains.

## Objective
Predict the future trajectory (`[x, y, heading]`) of a self-driving car directly from the data.
## Data
- Training Set: 5,000 samples
- Validation Set: 1,000 samples
- Past ego-motion history (`sdc_history_feature`)
- RGB camera input (`camera`)
- Driving command (`driving_command`)

## Environment Setup
>Recommended: Run on Google Colab with GPU
>1st upload the notebook to google colab
>2nd connect to a runtime
>3rd run all cells (mounts your google drive unless adapted)
before running: adjust the dataset paths (not needed with Colab)

### Alternative
> 1. Clone repository (if using GitHub)
```bash
git clone https://github.com/vita-student-projects/DLAV-project-Bubamara.git
cd your-project-name
```
> 2. open with jupyter:
```bash
jupyter notebook your/path/to/DLAV_Phase3.ipynb
```
> 3. adjust the paths to your data and run all cells

### Expected Results:
Please read CIVIL_459_Bubamara_poster.pdf for a more detailed overview of the project and it's results.





