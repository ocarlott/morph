#morph.js
========


###Morphological image processing for javascript.

The purpose of morph.js is to make the low level image processing and computer vision functions defined by mathematical morphology available for use with preproccessed input from the webcam via window.getUserMedia(). Morph.js deals with binary images, in other words, all operations are done on arrays of ones and zeroes. 


###Mathematical Morphology as described by wikipedia:

Mathematical morphology (MM) is a theory and technique for the analysis and processing of geometrical structures, based on set theory, lattice theory, topology, and random functions. MM is most commonly applied to digital images, but it can be employed as well on graphs, surface meshes, solids, and many other spatial structures.
Topological and geometrical continuous-space concepts such as size, shape, convexity, connectivity, and geodesic distance, were introduced by MM on both continuous and discrete spaces. MM is also the foundation of morphological image processing, which consists of a set of operators that transform images according to the above characterizations.
MM was originally developed for binary images, and was later extended to grayscale functions and images. The subsequent generalization to complete lattices is widely accepted today as MM's theoretical foundation.


##Usage

To initialize a morph object:
    
    var height = 200
    var width = 270
    var morph = new Morph(height, width, bits)

where bits is an array of 1s and 0s with length 54,000, usually derived from some image.

Basic functionality in Morphological image processing (MIP) is defined by the dilate and erode operations.



Example usage: http://somatostat.in/swarmSandbox.html






