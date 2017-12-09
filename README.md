# lidar-align
Lidar align source code using LabVIEW version 7 or 8. This code uses new focus pico-motors to steer a dielectric mirror
so that the exiting laser can be beam steered into the sky, into the field of view of the telescope. The program checks
the alignment by performing a sweep in the X and Y directions and the alignment is set using a laser pointer onto
a graticule on the wall bounced off the same mirror. During alignment the range resolved signals are captured with photo
hamamatsu HH5783 miniature multipliers and the data is collected by Licel transient recorder for all channels.
