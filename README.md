# Band-Structure-Plot-QE
Plotting of band structure generated by quantum espresso calculations using python.

This python code draw the band structures generated by quantum espresso with the following description:
  The bands are shifted according to the Fermi energy of the considered system, so the Fermi energy represent the origin of the energy axis.
  Vertical lines at the high symmetry points of according to the choosen path are added to the figure
  The symbole of the high symmetry points are added at the x-axis after importing them by the user.
  
The files needed to run this code are:
  File generated by the pw.x scf calculation; this file must be named 'scf.out'.
  File generated by the bands.x calculation; this file must be named 'bandx.out'.
  File containing the bands to draw in the gnu format, this file must be named 'bands.gnuplot.gnu'.
  
The user can decide the range of energy.

The high symmetry points given by the user should be separated by a space.

This program transform the 'G' letter into Gamma greek letter automatically.
