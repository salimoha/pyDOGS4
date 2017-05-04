# pyDOGS4
For Imperial Collage collaborator

# pyDOGS
A derivative-free global optimization algorithm based on Delaunay triangulation designed to solve efficiently the problems whose function evaluations process is inaccurate, but its accuracy can be improved by increasing its computational cost. This package particularly well-suited when the objective function is the infinite time-averaged value of a statistics of a stationary and ergodic process. Moreover, a new UQ method is developed to quantify the expected squared averaging error which is multiscale, meaning that it is based on an autocorrelation model that is tuned to the data to fit the statistic of interest at a large range of different timescales. In addition a transient detector scheme is developed to delete the transient part of the signal.


# output
Optimization code generetes a file called allpoints/pts_to_eval.dat which has  the format of:
flagin=1
IDin=3
Awin=0.75
lambdain=0.5
fangle=0.5

Moreover, it reads surr_J_new.dat from the current directory.
A_w is the same parameter as the current ‘Aw’ and the two other parameters would be replaced by b_1 and b_2.
 
The range for these parameters would be:
A : [0.05 ; 0.15]  (à same as current Aw)
B_1 : [0 ; 0.2]      (à in place of lambda)
B_2 : [0 ; 0.13]   (à in place of fangle)
 
