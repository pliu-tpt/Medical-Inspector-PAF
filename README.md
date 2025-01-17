# Medical Inspector 3D - PAF Télécom Paris
Graphical User Interface to visualize 3D medical images in NIfTI format. There are also several integrated segmentation and graph clustering methods.

Main Interface|Segmentation Plugin|User Manual
:---:|:---:|:---:
![](/Screenshots/app.png)|![](/Screenshots/segmentation.png)|![](/Screenshots/manual.png)

Visualization Demo
:---:
![](/Screenshots/demo.gif)

Here is the required list of libraries (for python3):
- tkinter
- nibabel
- matplotlib
- PIL
- numpy
- networkx
- scikit-image
- scipy
- scikit-learn
- opencv (cv2)

This GUI was originally coded for Windows and Linux, but the version on this repository has been sligthly modified to better function on macOS. This may cause some incoherences when pressing buttons.

This project was done in a group of 7 during a two-week full-time project in Télécom Paris under the supervision of Isabelle Bloch, Pietro Gori and Mateus Riva.

## Setup instructions (compatible with Apple Silicon)

Install python 3.8:

```
conda create -y -n paf python=3.8
```

Install dependencies:

```
pip install -r requirements.txt
```

To run the app:

```
cd Medical-Inspector
python main.py
```

## Authors

Members of the project:

Anna Audit - Clément Galaup - Hugo Queinnec - Nicolas Wittmann - Philippe Liu - Pierre Piovesan - Thomas Poyet