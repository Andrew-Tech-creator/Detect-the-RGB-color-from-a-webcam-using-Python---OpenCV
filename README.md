 🎨 Real-Time Dominant Color Detection Using OpenCV

This project captures real-time video from your webcam and detects the most **dominant primary color** (Red, Green, or Blue) in the video feed based on the average intensity of each color channel. The result is printed to the console every frame.



 📸 Features

* Real-time webcam feed using OpenCV
* Analyzes the intensity of **Blue**, **Green**, and **Red** color channels
* Prints the most dominant color live in the terminal
* Exit anytime by pressing `q`


 🧰 Technologies Used

* Python
* OpenCV (`cv2`)
* NumPy

🖥️ Demo

![Demo GIF or Image Placeholder](https://via.placeholder.com/800x400.png?text=Demo+Coming+Soon)



📦 Installation

1. Clone this repository

   ```bash
   git clone https://github.com/yourusername/color-detection-opencv.git
   cd color-detection-opencv
   ```

2. Create a virtual environment (optional but recommended)

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. Install required libraries

   ```bash
   pip install opencv-python numpy
   ```

---

 🚀 Run the Program

```bash
python color_detector.py
```

* A webcam window will pop up.
* The dominant color in the current frame will be printed to the console.
* Press `q` to quit.

 🧠 How It Works

1. Captures a video stream from your webcam.
2. Extracts the Blue, Green, and Red channels of each frame.
3. Calculates the **mean value** of each channel.
4. Compares the means to determine the **dominant color**.
5. Displays the video frame and prints the detected color.

 📌 Notes

* Make sure your webcam is properly connected.
* Accuracy can vary based on lighting conditions and image content.
* This script uses simple mean calculations; for more accurate color detection, consider using HSV or clustering (like K-Means).

📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


 🙌 Acknowledgements

* [OpenCV Documentation](https://docs.opencv.org/)
* [NumPy Documentation](https://numpy.org/)

