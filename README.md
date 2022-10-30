# Parallel-Algorithms

## How to start
1. Login to Grace Cluster
```bash
ssh <NetID>@grace.tamu.edu
```
2. Load module
```bash
module load intel/2020b
```
3. Compile source file 
```bash
mpiicc -o main.exe main.c
```
4. Start batch job
```bash
sbatch main.grace_job
```
