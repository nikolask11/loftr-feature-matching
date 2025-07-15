
# LoFTR Feature Matching with Kornia

This project demonstrates how to use [Kornia](https://github.com/kornia/kornia)'s deep learning-based **LoFTR** (Local Feature TRansformer) model to find feature correspondences between two images.

📖 **Read the full write-up on Medium:**  
[🔗 How I Built This (LoFTR Feature Matching)](https://medium.com/@yourusername/your-post-slug)

It uses `kornia.feature.LoFTR`, along with OpenCV and Matplotlib, to detect, match, and visualize keypoints without requiring traditional descriptors like SIFT or ORB.

---

## 🖼️ Example

Input images:

- `image1.jpeg`
- `image2.jpeg`

Result:

- Matched keypoints displayed in green between the two images.

---

## 📦 Requirements

Install the required Python packages:

```bash
pip install kornia torch opencv-python matplotlib kornia_moons
