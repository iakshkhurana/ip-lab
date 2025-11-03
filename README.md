## Image Processing Lab (IP-615)

This repository contains Jupyter notebooks and assets for foundational image processing experiments. Each experiment lives in its own folder with a primary notebook and any sample outputs.

### Quick links

- **Lab manual (PDF)**: [IP 615 Lab manual or List of Experiments.pdf](https://github.com/iakshkhurana/ip-lab/blob/main/IP%20615%20Lab%20manual%20or%20List%20of%20Experiments.pdf)
- **Dataset sample**: [dataset/sample.jpg](https://github.com/iakshkhurana/ip-lab/blob/main/dataset/sample.jpg)

### Experiments index

- **Q-1: Grayscale → Binary**  
  Folder: [gray-scale-to-binary](https://github.com/iakshkhurana/ip-lab/tree/main/gray-scale-to-binary/)  
  Notebook: [grayscale-to-binary.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/gray-scale-to-binary/grayscale-to-binary.ipynb)  
  Outputs: [original_mean.jpg](https://github.com/iakshkhurana/ip-lab/blob/main/gray-scale-to-binary/original_mean.jpg) · [binary_mean.jpg](https://github.com/iakshkhurana/ip-lab/blob/main/gray-scale-to-binary/binary_mean.jpg) · [original_user.jpg](https://github.com/iakshkhurana/ip-lab/blob/main/gray-scale-to-binary/original_user.jpg) · [binary_user.jpg](https://github.com/iakshkhurana/ip-lab/blob/main/gray-scale-to-binary/binary_user.jpg)

- **Q-2: RGB → Grayscale**  
  Folder: [rgb-to-gray-scale](https://github.com/iakshkhurana/ip-lab/tree/main/rgb-to-gray-scale/)  
  Notebook: [solution.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/rgb-to-gray-scale/solution.ipynb)

- **Q-3: Add border / padding**  
  Folder: [border-around-img](https://github.com/iakshkhurana/ip-lab/tree/main/border-around-img/)  
  Notebook: [solution.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/border-around-img/solution.ipynb)

- **Q-4: Image complement**  
  Folder: [img-complement](https://github.com/iakshkhurana/ip-lab/tree/main/img-complement/)  
  Notebook: [solution.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/img-complement/solution.ipynb)

- **Q-5: Log transform**  
  Folder: [log-transform](https://github.com/iakshkhurana/ip-lab/tree/main/log-transform/)  
  Notebook: [solutions.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/log-transform/solutions.ipynb)

- **Q-6: Power / Gamma transform**  
  Folder: [power-gamma-transform](https://github.com/iakshkhurana/ip-lab/tree/main/power-gamma-transform/)  
  Notebook: [solutions.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/power-gamma-transform/solutions.ipynb)

- **Q-7: Contrast stretching**  
  Folder: [contrast-stretching](https://github.com/iakshkhurana/ip-lab/tree/main/contrast-stretching/)  
  Notebook: [solutions.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/contrast-stretching/solutions.ipynb)

- **Q-8: Histogram equalization**  
  Folder: [histogram-equalization](https://github.com/iakshkhurana/ip-lab/tree/main/histogram-equalization/)  
  Notebook: [solutions.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/histogram-equalization/solutions.ipynb)

- **Q-9: Histogram matching**  
  Folder: [histogram-matching](https://github.com/iakshkhurana/ip-lab/tree/main/histogram-matching/)  
  Notebook: [solutions.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/histogram-matching/solutions.ipynb)

- **Q-10: Image smoothing / filtering**  
  Folder: [img-smoothening](https://github.com/iakshkhurana/ip-lab/tree/main/img-smoothening/)  
  Notebook: [solutions.ipynb](https://github.com/iakshkhurana/ip-lab/blob/main/img-smoothening/solutions.ipynb)

### How to run

1. Install Python 3.9+ and Jupyter. Recommended:
   ```bash
   pip install notebook numpy matplotlib opencv-python scikit-image
   ```
2. Launch notebooks from this root directory:
   ```bash
   jupyter notebook
   ```
3. Open any notebook linked above and run the cells.

### Repo layout

- `dataset/` – input images used across experiments.
- `<experiment>/solution(s).ipynb` – the main notebook for that task.
- Additional images inside folders are example inputs/outputs.

### Notes

- All links are direct GitHub URLs (blob/tree) for one-click navigation.
- Folder names match the question topics from the lab manual for quick navigation.


