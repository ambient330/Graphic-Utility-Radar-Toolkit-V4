# Graphic-Utility-Radar-Toolkit-V
GURT V (the V stands for vispy)


A graphical interface built on ARM PyART & VisPY that emulates NCAR's SOLO3 program.

-----------------------------USAGE------------------------------------------

**execute the main.py file**
**Controls**: 
1. Left/Right arrows: Change sweep/volume
2. Up/Down arrows: Change tilt
3. 2-finger scroll: Zoom in/out

Aesthetics:
Scaler/offset for colormap
(PLACEHOLDER) In-app background color selector, although users can just change the BG color in the code.
Azimuth/range rings(km)/tick marks(km)

Data editing:

    User selected unfolding with PyART region dealias and KDP processing
    Unfolding/deglitching brush (adennison2009)
    Boundary-guided deletion tool (adennison2009)
    Gate averaging brush/boundary tool (adennison2009)

PREREQUISITE PACKAGES FOR V4:

    vispy
    numpy
    scipy
    PyART

Data recovered from gate averaging should be considered subjective

Certain code was taken or referenced from these sources: lrose-colette, 2025: DeHart, J., Dixon, M., Javornik, B., Bell, M., Cha, T.-Y., DesRosiers, A., & Lee, W.-C. (2025). nsf-lrose/lrose-releases: lrose-colette-20250105 (lrose-colette-20250105). Zenodo. https://doi.org/10.5281/zenodo.14624762

Lee, W.-C., Walther, C., & Oye, R. (2010). National Center for Atmospheric Research NCAR Earth Observing Laboratory EOL DORADE Doppler Radar Exchange Format DORADE Originally. https://www.eol.ucar.edu/sites/default/files/files_live/private/files/field_project/EMEX/DoradeDoc.pdf

Helmus, J.J. & Collis, S.M., (2016). The Python ARM Radar Toolkit (Py-ART), a Library for Working with Weather Radar Data in the Python Programming Language. Journal of Open Research Software. 4(1), p.e25. DOI: http://doi.org/10.5334/jors.119
