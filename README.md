                                      QUADTREE DECOMPOSITION OF IMAGE

This program uses quadtree decomposition - a technique which involves subdividing an image into homogeneous blocks as a step in
compression algorithms and image edge detection. The quadtree decomposition works by dividing an image, in this example, a square image
into four equal blocks and then checking if each block meets some homogeneity criterion (e.g., if all of the pixels in the block are
within a specified range). If a block meets a specified threshold, it is not divided any further. Else, it is divided again into four
blocks and the homogeneity test is applied again. This process stops when each block meets the criterion or when it cannot be divided
any further (it is a single pixel). The process eventually results in blocks of different sizes.
