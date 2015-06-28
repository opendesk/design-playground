Developer Notes
===


2015-06-27 ~ Theo

First Post!

Several types of scripts seem to be developing in a somewhat natural progression, including:

### DXF readers
These scripts read 2D DXF files downloaded from [OpenDesk](http://opendesk.cc] and transform the data into 3D.

Reading of DXF files is progressing, but still can only read polylines that are only made up of straight line segments.
Still cannot read arc segments. Thus only reading AtFAB projects for the moment.

Positioning the assembled components still has to be done by a human.
In the first attempt - rotational table R1 - components are roughly positioned by eye.
In later models data from the bounding box of each component is used to position the component accurately.  

The AtFAB DXF files have quite odd dimensions - such as 3.14961 x 3.14961. It looks as if inches were somewhat converted to centimeters using some odd factor.

### Apps
These scripts attempt to create the 3D models using code with user-entered parameters.

These are created on the basis of the understanding of the DXF files.

Input from the original designers would be really helpful here.




 