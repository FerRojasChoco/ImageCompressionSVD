SVD Image Compressor

This repository contains the implementation of an image compressor utilizing the Singular Value Decomposition (SVD) theory. The project demonstrates how linear algebra concepts can be applied to reduce image sizes effectively while maintaining visual quality. It was developed as part of a university project for the Linear Algebra course at Universidad Politécnica Taiwán Paraguay.

Features
- Compression Modes:
  - Compress grayscale versions of images.
  - Compress RGB images while retaining color fidelity.
- User Interface:
  - Upload and compress images via a graphical user interface (GUI).
  - Preview and download compressed versions.
- Efficiency:
  - Significant file size reduction without major loss of quality.
  - Supports popular formats such as JPG, PNG, and JPEG.

Repository Contents
- `SVD_Image_compression.pdf`: Project report detailing the theory, implementation, and results of the image compression.
- `funtionsvd.py`: Python script handling the image processing and SVD logic for compression.
- `interfaceGUI.py`: Python script providing the graphical user interface for interacting with the program.

Theory Behind the Project
Singular Value Decomposition is a mathematical approach to factorizing a matrix into three components: two orthogonal matrices (U and V^T) and a diagonal matrix (Σ). In the context of image compression:
- Images are treated as matrices of pixel values.
- By truncating less significant singular values, we reduce the amount of data while preserving the most critical image features.
- Adjusting the rank of approximation (“k”) allows control over the balance between compression and quality.

Further details on the mathematical foundation are provided in the report (`SVD_Image_compression.pdf`).


Collaborators
This project was a collaborative effort between:
- [Fernando Rojas](mailto:frrm04@gmail.com)
- [Nicolás Vega](https://github.com/NicoVegaPortaluppi)  

License
This project is open source. Feel free to use, modify, and distribute the code with proper attribution.

---

For any questions or suggestions, please refer to the report or contact the authors via the provided emails.

