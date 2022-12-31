# Automatic1111 Stable Diffusion Pickle Scanner

## Introduction

This script is designed to scan a directory and its subdirectories for pickle files. When a pickle file is found, it will be logged to a file called `scan_output.txt`.

This script is the [Stable Diffusion Pickle Scanner](https://github.com/zxix/stable-diffusion-pickle-scanner) by [zxix](https://github.com/zxix).

## Running the script

To run the script, follow these steps:

1. Place the script in the `automatic1111` folder.
2. Run `scan.bat`.
3. Check the `scan_output.txt` file for the results of the scan.

## Additional notes

- Make sure you have the necessary dependencies installed to run the script (e.g. the `pickle` module).
- The script may take some time to run, depending on the size of the directory and the number of files present.
- The `scan_output.txt` file will be created in the same directory as the script, if it does not already exist.
