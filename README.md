This is some simple code in a Juypter Notebook that compares LIDAR CHM tree height estimates vs. insitu measurements of tree height in the SJER study site in California.

The code opens up a file containing locations of sites where tree heights were measured.  The code creates a buffer around each of these sites and it is these buffers from which the lidar estimated tree heights will be pulled.

The code plots up a comparison of both max & mean tree height values/estimates between the lidar and insituu measurements.

The data used in the analysis comes from Earth Py:
https://earthpy.readthedocs.io/en/latest/
