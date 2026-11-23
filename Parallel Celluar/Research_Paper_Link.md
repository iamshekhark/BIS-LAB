
# Parallel Cellular Algorithm (PCA)

## 1. Title
Image Noise Reduction Using Parallel Cellular Algorithm.

## 2. Research Paper Details
- **Paper Title:** Modeling and Numerical Validation for an Algorithm Based on Cellular Automata to Reduce Noise in Digital Images
- **Authors:** Karen Vanessa Angulo, Danilo Gustavo Gil, Helbert Eduardo Espitia
- **Journal:** Computers
- **Volume:** 11
- **Issue:** 3
- **Article Number:** 46
- **Year:** 2022
- **DOI:** 10.3390/computers11030046

### Research Paper Links
- [Research Paper](https://www.mdpi.com/2073-431X/11/3/46)
- [DOI Link](https://doi.org/10.3390/computers11030046)
- [PDF Link](https://pdfs.semanticscholar.org/1765/9abdde7f8f6253ef6f6453b7065551d1eba3.pdf)

## 3. Problem Statement
An MRI-like image contains unwanted noise that reduces image quality. The Parallel Cellular Algorithm (PCA) is used to reduce noise by representing each pixel as a cell and updating its intensity using neighboring pixels.

## 4. Problem Objective
- Implement Parallel Cellular Algorithm using Python.
- Represent each pixel as an individual cell.
- Use neighboring pixel information to update cell values.
- Reduce image noise and improve image quality.

## 5. Algorithm Description
The Parallel Cellular Algorithm is inspired by biological cells that interact with neighboring cells and update their states.

In image processing:
- Each pixel represents a cell.
- Pixel intensity represents the cell state.
- Neighboring pixels provide information for updating the cell.
- Multiple cells are updated simultaneously.

## 6. Code Summary
1. Import NumPy and Matplotlib libraries.
2. Create a sample MRI-like image.
3. Add random noise to the image.
4. Initialize the number of iterations.
5. Represent each pixel as an individual cell.
6. Identify the eight neighboring pixels.
7. Calculate the average intensity of neighboring pixels.
8. Update all pixel values simultaneously.
9. Repeat the process for the specified iterations.
10. Display the original, noisy, and denoised images.

## 7. Output Summary
- Displays the original image.
- Displays the noisy image.
- Displays the denoised image after applying PCA.
- Reduces noise using neighborhood-based updates.
- Demonstrates cellular processing for image enhancement.

## 8. Technologies Used
- Python
- NumPy
- Matplotlib

## 9. How to Run
```bash
pip install numpy matplotlib
python PCA.py
```

## 10. Conclusion
The Parallel Cellular Algorithm uses neighboring cell interactions and simultaneous state updates to perform image processing and noise reduction.

**Note:** This implementation uses a synthetic MRI-like image for educational demonstration. The research paper discusses digital image noise reduction using cellular automata; it is not specifically an MRI study.
