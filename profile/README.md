# Combined MatMul & FFT Systolic Array

This page serves as the home for all repositories used in the Senior Design Project for the MatMul & FFT Systolic Array project. 

## 0. [Prerequisites](https://github.com/ECE-Senior-Project-Systolic-Array/etc)

Download the scaffolding used for the rest of the repos for easy and automated operation of Git and Vivado.

> **Note**: One copy of the etc repository in the parent folder is sufficient for all repos.

## 1. [MatMul Systolic Array](https://github.com/ECE-Senior-Project-Systolic-Array/MatMul_Systolic_Array)

This repository contains the HDL for a standalone MatMul Systolic Array. The repository here serves as the MatMul control to compare with the combined FFT & MatMul Systolic Array.

## 2. [FFT Systolic Array](https://github.com/ECE-Senior-Project-Systolic-Array/FFT_Systolic_Array)

This repository contains the HDL for a standalone FFT Systolic Array. The repository here serves as the FFT control to compare with the combined FFT & MatMul Systolic Array.

## 3. [MatMul & FFT Systolic Array](https://github.com/ECE-Senior-Project-Systolic-Array/FFT_MatMul_Systolic_Array)

This repository contains the HDL for the combined FFT & MatMul Systolic Array. Processing Elements (PEs) are designed to maximize the overlap between the FFT and MatMul logic, thus reducing he overall logic needed and enabling flexible hardware for acceleration purposes.
