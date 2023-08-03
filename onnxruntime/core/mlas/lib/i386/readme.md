contains files that implement the kernels for the single precision matrix/matrix multiply operation (SGEMM) using AVX and SSE2 instructions. These files provide macros and structures for efficient computation of blocks of the output matrix, handling different row counts, multiplying by a scalar alpha, and accumulating the result into the output matrix. Additionally, the directory includes a file with common kernel macros and structures for the Machine Learning algebra subprogram library, which conditionally emits statements based on variable comparisons.