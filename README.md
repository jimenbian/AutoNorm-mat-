AutoNorm-mat-
=============

This is a python library,it can denoise the mat and make the mat auto-normal.

function:

DenoisMat(mat)-make the mat denoise

AutoNorm(mat)-autonorm the mat
    
example:
 
 mat=[[1,42,512],[4,5,6],[7,8,9],[2,2,2],[2,10,5]]
 
 AutoNorm(mat)=[[0.0, 1.0, 1.0], [0.5, 0.075, 0.00784313725490196], [1.0, 0.15, 0.013725490196078431], [0.16666666666666666, 0.0, 0.0], [0.16666666666666666, 0.2, 0.0058823529411764705]]
    
