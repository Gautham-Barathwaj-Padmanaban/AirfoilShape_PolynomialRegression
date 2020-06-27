# AirfoilShape_PolynomialRegression
The aim of this project was to develop a code that could provide the best polynomial fit of a degree specified for the upper and lower surfaces of an airfoil. The user needs only to upload the .dat file (UIUC,airfoiltools etc) and provide the degree of polynomial.

The code has been written in such a way that the UIUC co-ordinate files/ those obtained from airfoiltools.com can be directly used, as there is a function to clean the data inside the code. The user needs to enter the .dat file and the degree of the polynomial needed.

The user can also input the co-ordinates directly; the last block shows the working of the same. However in this case, the user needs to ensure that the co-ordinates start from the trailing edge, move over the top surface and loops back to the trailing edge via the bottom surface (XFOIL practice). If you are uploading the .dat file the cleaning function automatically takes care of the same.

The polynomial is finally provided, with a graph depicting the fit. The co-efficients have also been shown as 'features' in the code.

The .dat files for a few airfoils have been added to the repository. The code has been run for the ag25.dat and bacxxx.dat files. The user can change it to use whatever file he or she wants to use.

The polynomial regression has been done by using the normal equation method as it allows an easier vectorized regression which is fast. 
