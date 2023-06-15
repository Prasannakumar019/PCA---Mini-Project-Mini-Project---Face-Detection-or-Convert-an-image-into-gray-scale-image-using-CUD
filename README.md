# CUDA Grayscale Conversion

## Aim:
The aim of this project is to demonstrate how to convert an image to grayscale using CUDA programming without relying on the OpenCV library. It serves as an example of GPU-accelerated image processing using CUDA.

## Procedure:
1. Load the input image using the `stb_image` library.
2. Allocate memory on the GPU for the input and output image buffers.
3. Copy the input image data from the CPU to the GPU.
4. Define a CUDA kernel function that performs the grayscale conversion on each pixel of the image.
5. Launch the CUDA kernel with appropriate grid and block dimensions.
6. Copy the resulting grayscale image data from the GPU back to the CPU.
7. Save the grayscale image using the `stb_image_write` library.
8. Clean up allocated memory.

## Output:

### Input file:

![photo-1503023345310-bd7c1de61c7d](https://github.com/212220230020-Grahamstanes/PCA---Mini-Project-Mini-Project---Face-Detection-or-Convert-an-image-into-gray-scale-image-using-CUD/assets/75235150/fe8987d3-a7b6-4d07-9d00-566ebaca52cf)



### Output file:
![photo-1503023345310-bd7c1de61c7d1](https://github.com/212220230020-Grahamstanes/PCA---Mini-Project-Mini-Project---Face-Detection-or-Convert-an-image-into-gray-scale-image-using-CUD/assets/75235150/b95be550-80ca-49b7-b92e-715bb1e966e3)


## Result:
The CUDA program successfully converts the input image to grayscale using the GPU. The resulting grayscale image is saved as an output file. This example demonstrates the power of GPU parallelism in accelerating image processing tasks.
