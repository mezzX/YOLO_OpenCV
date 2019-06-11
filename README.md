# YOLO_OpenCV
An OpenCV implementation of YOLOv3. This was repo contains the material that was covered during the Vancouver School of AI's Object Detection Workshop. The Workshop's slides can be viewed [here](https://docs.google.com/presentation/d/1Z4Pvyp2DMZ-go_SOcDDZNVFwn4TnKNq9k2iFsfGjk2k).

### Getting Started
1. Make sure you have [Python 3.6](https://www.python.org/) installed.

2. Clone the repository
    ```bash
    git clone https://github.com/mezzX/YOLO_OpenCV.git
    ```
    
3. Use [Conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) to create a new environment and install dependencies. <br>[Click Here](https://nbviewer.jupyter.org/github/johannesgiorgis/school_of_ai_vancouver/blob/master/intro_to_data_science_tools/01_introduction_to_conda_and_jupyter_notebooks.ipynb) if you need a detail guide on using conda.

    - __Linux__ or __Mac__: 
    ```bash
    conda create --name connect4 python=3.6
    source activate connect4
    conda install numpy
    conda install opencv
    conda install jupyter notebook
    ```
  
    - __Windows__: 
    ```bash
    conda create --name connect4 python=3.6 
    activate connect4
    conda install numpy
    conda install opencv
    conda install jupyter notebook
    ```

4. Download the [YOLOv3-416 weights file](https://pjreddie.com/darknet/yolo/) and place it in the project directory
