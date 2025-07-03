# Lane-Detection-using-OpenCV

This project implements a basic **lane detection pipeline** using OpenCV and Python. It processes a video frame-by-frame to detect and highlight lane lines on roads.

## 📥 Input Videos

You can access input videos here:
- 🔗 [Input Video: `lanes_clip.mp4`](https://indianinstituteofscience-my.sharepoint.com/:f:/g/personal/poornima2024_iisc_ac_in/EgYLSGjWrD1MvILchdPC3ekBq8nq1xOd4pmZj2y0zN6d8Q?e=f7857A)

Try other test videos from here:
- 🔗 [More Sample Videos](https://indianinstituteofscience-my.sharepoint.com/:f:/g/personal/poornima2024_iisc_ac_in/EnUlTamdsLNIkoh_TgiRaBEBoVPxdfL-CSm8-9yx-xdiSw?e=heKe0K)

## ⚙️ How It Works

1. Convert frame to **grayscale**
2. Apply **Gaussian blur** to reduce noise
3. Use **Canny edge detection** to find edges
4. Apply a **region of interest mask**
5. Detect lines using **Hough Transform**
6. Draw lines and **overlay** them on the original frame
7. Save the output as a processed video

## ▶️ Running the Code in Google Colab

## ✅ Results

Output frame 

![Outframe frame](https://github.com/Poornima855/Lane-Detection-using-OpenCV/blob/main/Result_frames.png)

Here are some more resulting frames and videos.

🎬 [Watch Output Video](https://indianinstituteofscience-my.sharepoint.com/:f:/g/personal/poornima2024_iisc_ac_in/ElcnE-C5rGVJiM0-4L5unj8Bde8PLf3idryMLw5zckxoUg?e=tETLmM)

## 💡 Try Enhancements

- Add **lane curvature smoothing**
- Predict **vehicle direction**
- Highlight **lane departure**

✅ Fully compatible with **Google Colab**

