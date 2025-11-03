# 🖼️ Image Processing Lab (UCS-615)

> A collection of image processing experiments implemented in Jupyter Notebooks.

---

## 📋 Quick Links

| Resource | Link |
|----------|------|
| 📄 **Lab Manual** | [UCS-615 Lab manual or List of Experiments.pdf](https://github.com/iakshkhurana/ip-lab/blob/main/IP%20615%20Lab%20manual%20or%20List%20of%20Experiments.pdf) |
| 🖼️ **Dataset Sample** | [sample.jpg](https://github.com/iakshkhurana/ip-lab/blob/main/dataset/sample.jpg) |

---

## 📊 Experiments Table

| # | Question | Topic | Solution Notebook |
|---|----------|-------|-------------------|
| **Q-1** | Convert Grayscale to Binary Image | Binary Image Conversion | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/gray-scale-to-binary/grayscale-to-binary.ipynb) |
| **Q-2** | Convert RGB to Grayscale Image | Grayscale Conversion | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/rgb-to-gray-scale/solution.ipynb) |
| **Q-3** | Draw Border Around Image | Image Padding | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/border-around-img/solution.ipynb) |
| **Q-4** | Image Complement | Image Inversion | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/img-complement/solution.ipynb) |
| **Q-5** | Log Transform | Intensity Enhancement | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/log-transform/solutions.ipynb) |
| **Q-6** | Power Law / Gamma Transform | Gamma Correction | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/power-gamma-transform/solutions.ipynb) |
| **Q-7** | Contrast Stretching | Intensity Level Slicing | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/contrast-stretching/solutions.ipynb) |
| **Q-8** | Histogram Equalization | Histogram Processing | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/histogram-equalization/solutions.ipynb) |
| **Q-9** | Histogram Matching | Histogram Specification | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/histogram-matching/solutions.ipynb) |
| **Q-10** | Image Smoothing / Filtering | Filtering Techniques | [📓 Open Notebook](https://github.com/iakshkhurana/ip-lab/blob/main/img-smoothening/solutions.ipynb) |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher
- Jupyter Notebook

### Installation

```bash
pip install notebook numpy matplotlib opencv-python scikit-image
```

### Running the Notebooks

1. Clone the repository:
   ```bash
   git clone https://github.com/iakshkhurana/ip-lab.git
   cd ip-lab
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Click on any notebook link from the table above to open it directly on GitHub, or navigate to the folder and open the notebook locally.

---

## 📚 Experiment Details

### Q-1: Grayscale to Binary Image
- **Case 1:** Use mean intensity as threshold
- **Case 2:** User-defined threshold value

### Q-2: RGB to Grayscale Image
- **Case 1:** Mean average of R, G, B planes
- **Case 2:** Custom weightages for R, G, B (sum = 1)

### Q-3: Border Around Image
- User inputs border width (pixels) and color
- Works for both binary and grayscale images

### Q-4: Image Complement
- Implementation for both binary and grayscale images

### Q-5: Log Transform
- Enhancement using logarithmic transformation
- Constant c = 1

### Q-6: Power Law / Gamma Transform
- Enhancement using gamma correction
- Constant c = 1
- User inputs gamma value

### Q-7: Contrast Stretching
- User inputs original and target intensity ranges
- Example: Stretch 80-120 → 50-150

### Q-8: Histogram Equalization
- Automatic contrast enhancement using histogram processing

### Q-9: Histogram Matching
- Match histogram of input image with reference image

### Q-10: Image Smoothing / Filtering
- **1.** Averaging filter (un-weighted)
- **2.** Weighted filter: h(x,y) = max(|x|,|y|)
- **3.** Gaussian filter

---

## 📝 Notes

- All notebooks contain complete solutions with explanations
- Click on the notebook links in the table above to view solutions directly on GitHub
- Dataset sample images are available in the `dataset/` folder

---

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements.

---

## 📄 License

This project is for educational purposes.
