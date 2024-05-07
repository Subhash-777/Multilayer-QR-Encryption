# QR Code Decryption Using LU and PCA

This project contains a Python script for decrypting a QR code using LU decomposition and PCA (Principal Component Analysis). The encrypted data is stored in a QR code as a matrix, and the script performs the following steps:

1. Decodes the QR code and extracts the matrix.
2. Performs LU decomposition on the matrix.
3. Applies PCA to the decomposed matrix.
4. Performs inverse LU decomposition and inverse PCA on the transformed data.
5. Decrypts the final matrix using the provided key.
6. Displays the decrypted data as a QR code.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Scipy
- QRcode

## Usage

Run the `main()` function to start the decryption process. Enter the key when prompted. The script will display the decrypted data as a QR code.
<body>
    <h2>Functions</h2>
    <ul>
        <li><code>QR_code_decoding():</code> Decodes the QR code and extracts the matrix.</li>
        <li><code>LU_decomposition(mat):</code> Performs LU decomposition on the matrix.</li>
        <li><code>pca(X, key):</code> Applies PCA to the decomposed matrix.</li>
        <li><code>matrix_to_qr(matrix, filename):</code> Converts the matrix to a QR code image.</li>
        <li><code>qr_to_matrix(filename):</code> Decodes the QR code image and retrieves the matrix.</li>
        <li><code>decryption(decoded_matrix, L1, P1, U, L, P, principle_components):</code> Performs inverse LU decomposition, inverse PCA, and decrypts the final matrix.</li>
    </ul>
    <h2>Contact</h2>
    <p>For any questions or concerns, please contact the author at <a href="mailto:subhashravichandran7432@gmail.com">subhashravichandran7432@gmail.com</a>.</p>
</body>
