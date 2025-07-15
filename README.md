
# LoFTR Feature Matching with Kornia

This project demonstrates how to use [Kornia](https://github.com/kornia/kornia)'s deep learning-based **LoFTR** (Local Feature TRansformer) model to find feature correspondences between two images. You MUST have torch installed.

📖 **Read the full write-up on Medium:**  
[🔗 How I Built This (LoFTR Feature Matching)]([https://medium.com/@nikolaskallweit_83151/understanding-loftr-matching-image-features-without-descriptors-875d2d1780d4])

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

````````

---

## Credits

This project uses code and concepts borrowed from the Hugging Face Computer Vision course.
All credits go to the Hugging Face team and the original authors. I encourage you to check out their course: https://huggingface.co/learn/computer-vision-course/unit0/welcome/welcome
