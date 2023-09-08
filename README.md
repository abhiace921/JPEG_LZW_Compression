# JPEG_LZW_Compression
LZW and JPEG compression of grayscale and RGB Images

JPEG (Joint Photographic Experts Group) compression is a widely used method for reducing the size of digital images while preserving acceptable visual quality. It works by dividing the image into small blocks, transforming them into the frequency domain using the Discrete Cosine Transform (DCT), quantizing the resulting coefficients, and then applying entropy coding like Huffman coding. This process discards some image data, leading to lossy compression. The degree of compression can be adjusted by varying the quantization levels. JPEG compression is effective for photographs and images with smooth color gradients, making it a standard format for web and digital photography.

<p align = "center"> <img src="jpg_comp.jpg"> </p>
