# Rough compute performance (timing how long computation takes) benchmarks  

## for Ising GPU  

2^10 x 2^10 or 1024 x 1024 grid; 10000 trials, temperature T = 1.0, 1.01,...3. (temperature step of 0.01), so 200 different temperatures, 32 x 32 thread block, 

[topolo@localhost IsingGPU]$ ./main
 L : 1048576
 MAXGRIDSIZES : 2147483647
7419.75 ms
7419.45 ms
7409.27 ms
7416.42 ms
7421.53 ms
7432.09 ms
7425.46 ms
7439.06 ms
7425.75 ms
7443.7 ms
7425.87 ms
7438.77 ms
7433.33 ms
7447.29 ms
7432.76 ms
7449.93 ms
7430.82 ms
7448.93 ms
7439.53 ms
7465.98 ms
7445.73 ms
7470.79 ms
7444.45 ms
7479.49 ms
7452.22 ms
7472.92 ms
7461.54 ms
7466.05 ms
7456.99 ms
7476.95 ms
7452.35 ms
7470.88 ms
7454.28 ms
7459.72 ms
7441.99 ms
7473.26 ms
7446.76 ms
7457.96 ms
7450.81 ms
7460.34 ms
7449.51 ms
7462.64 ms
7444.82 ms
7456.5 ms
7441.88 ms
7470.36 ms
7448.65 ms
7458.78 ms
7458.1 ms
7471.28 ms
7444.65 ms
7458.38 ms
7457.71 ms
7461.03 ms
7461.63 ms
7458.82 ms
7452.39 ms
7454.39 ms
7445.56 ms
7456.63 ms
7444.91 ms
7461.27 ms
7438.71 ms
7456.65 ms
7441.38 ms
7460.31 ms
7443.16 ms
7466.41 ms
7442.01 ms
7433.18 ms
7447.89 ms
7453.24 ms
7444.91 ms
7466.26 ms
7448.63 ms
7461.37 ms
7441.99 ms
7455.07 ms
7438.25 ms
7453.84 ms
7450.24 ms
7466.53 ms
7440.41 ms
7453.32 ms
7460.01 ms
7450.41 ms
7437.4 ms
7457.84 ms
7452.18 ms
7461.14 ms
7444.79 ms
7466.75 ms
7440.78 ms
7467.55 ms
7447.15 ms
7457.98 ms
7443.77 ms
7463.07 ms
7459.77 ms
7461.17 ms
7444.81 ms
7458.56 ms
7443.99 ms
7458.3 ms
7447.49 ms
7468.19 ms
7454.8 ms
7457.36 ms
7441.77 ms
7463.23 ms
7445.91 ms
7537.66 ms
7447.23 ms
7541.85 ms
7528.47 ms
7555.27 ms
7527.16 ms
7514.11 ms
7446.89 ms
7466.78 ms
7446.22 ms
7470.86 ms
7446.4 ms
7460.88 ms
7459.53 ms
7467.28 ms
7452.54 ms
7475.4 ms
7442.97 ms
7466.13 ms
7448.65 ms
7451.72 ms
7448.04 ms
7461.11 ms
7449.79 ms
7456.92 ms
7446.15 ms
7457.8 ms
7446.95 ms
7457.18 ms
7444.66 ms
7470.23 ms
7452 ms
7467.82 ms
7449.81 ms
7459.82 ms
7448.29 ms
7473.13 ms
7445.94 ms
7459.05 ms
7452.75 ms
7465.6 ms
7449.71 ms
7459.72 ms
7465.57 ms
7478.86 ms
7457.34 ms
7474.84 ms
7440.85 ms
7473.66 ms
7454.92 ms
7459.24 ms
7455.56 ms
7455.47 ms
7443.57 ms
7462.5 ms
7463.27 ms
7460.2 ms
7448 ms
7465.39 ms
7444.52 ms
7466.61 ms
7446.47 ms
7471.18 ms
7464.21 ms
7458.49 ms
7446.72 ms
7459.83 ms
7452.98 ms
7473.67 ms
7452.05 ms
7467.27 ms
7444.43 ms
7460.23 ms
7448.55 ms
7457.25 ms
7454.24 ms
7465.53 ms
7458.32 ms
7467.31 ms
7445.38 ms
7460.65 ms
7450.09 ms
7468 ms
7449.84 ms
7462.4 ms
7454.93 ms
7466.83 ms
7466.45 ms
7462.82 ms
7453.37 ms
1.49942e+06 ms


