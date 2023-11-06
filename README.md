# camera_calibration

## Purpose and background of this repo
**Purpose**: calibrate camera using Charuco board within a rotating cylinder.

**Background**: we collected 72/360 frames/images with a rotating cylinder and a 
telecentric lens. We'd like to generate the camera intrinsic and extrinsic parameters.


## Installation

1. **Clone the repository**:  
   ```
   git clone https://github.com/Salk-Harnessing-Plants-Initiative/camera_calibration.git
   ```
2. **Navigate to the cloned directory**:  
   
   ```
   cd camera_calibration
   ```
3. **Create a new conda environment**:
   ```
   conda env create -f environment.yml
   ```
4. **Activate the environment**
   ```
   conda activate calib
   ```
5. **Add the environment to Jupyter notebook kernel (only for the first time of this environment)**:
   ```
   ipython kernel install --user --name=calib
   ```
6. **Open jupyter notebook(s)**
   ```
   jupyter notebook
   ```
