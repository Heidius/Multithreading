# Multithreading
Java multithreading


Application that simulates the downloading of a number of images from a (very slow) server. 
It does not, in fact, download anything, instead it reads the images
from files on the local drive, with the reading process artificially slowed down to simulate a slow
download. As this application is only demonstration for learning purposes, the files it pretends to
download are hard coded into the application and provided with this assignment.
On launching, the program displays a GUI which shows three progress bars, one for each image to be
downloaded, and a "Start" button to start the downloading process. Each progress bar has an
associated cancel button marked with an "X". The developer intended that the progress bars should
advance as the images download, and that each download could be individually cancelled if
necessary by pressing the associated "X" button. Once each image has been downloaded a new
window is opened and the image is displayed in it.
