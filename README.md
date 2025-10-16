📘 Background Removal and Object Detection System
==============================================================
- Remove and Detect is an interactive image processing application designed to perform background removal and object detection with an intuitive graphical interface.

- Background removal isolates the primary subject in an image by eliminating its surroundings, while object detection identifies and locates individual objects within an image using bounding boxes and labels.

- This project integrates modern computer vision tools with a user-friendly GUI, enabling users to upload, process, and save enhanced images effortlessly.

🚀 Features
===============
1. Background Removal via rembg
- Removes the background and replaces it with a clean white or transparent layer.

2. Object Detection using YOLOv8
- Detects multiple objects in an image with bounding boxes and labels.

3. Automatic Cropping of Detected Objects
- Crops each detected object and processes it for background removal.

4. Save Processed Results
- Easily export processed images and detected object outputs.

5. Graphical User Interface (GUI)
- Built with Tkinter and CustomTkinter for a clean, modern, and interactive user experience.


🧰 Technilogies Used
======================
- Python 3.x	for Core programming language
- Tkinter & CustomTkinter	for GUI development
- rembg	for Background removal
- YOLOv8 (Ultralytics)	for Object detection
- Pillow (PIL)	for Image handling and manipulation
- OpenCV	for Image pre/post-processing (optional)

⚙️ Example Workflow
======================
1.Launch the program.

2.Click “Upload Image” and choose your image file.

3.Click “Remove Background” → see the isolated foreground.

4.Click “Detect Objects” → YOLOv8 identifies and highlights objects.

5.Optionally, save the processed and cropped results.

🏁 Future Enhancements
======================
- Add drag-and-drop support for image upload

- Enable batch image processing

- Include more YOLO model variants for faster or more accurate detection

- Allow user-selected background color or custom replacement image

- Integrate video frame processing support
