# VirusDetta

This repository contains the source code for detecting different type of malwares using Deep learning based on Feature Extraction and Wraper based on Feature Selection Technique. 

Two major approaches used for virus classification:
1. Image representation of byte file
    -  Independent of the platform
    - Requires no knowledge of domain like assembly instructions
2. Hybrid feature space using both ASM and byte file.
This approach is platform dependent but gives a better performance that using byte file. Requires huge resources and processing time.

The data used here can be found on the Hybrid(Final) folder of following drive link:

https://drive.google.com/drive/folders/1s7EC4s_-hP9q5vEhs-3vAubspcZbBADK?usp=sharing

After downloading the required dataset, following is the sequence of files in the hybrid folder whose execution will lead to results. Use Google Colab for more efficiency.

1. "Creating hybrid dataset"

2. "Min-max normalization(hybrid dataset)"

3. "ANN-Results"
