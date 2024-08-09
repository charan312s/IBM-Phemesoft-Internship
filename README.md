<!DOCTYPE html>
<html lang="en">
<head>

</head>
<body>
    <h1>Glasses Overlay Project</h1>

  <div class="section">
      <h2>Overview</h2>
      <p>This project demonstrates a real-time application of computer vision techniques to overlay a glasses image onto a user's face using a webcam. The key features and steps involved are:</p>
      <ul>
          <li><strong>Face Detection:</strong> The system uses a pre-trained Haar Cascade classifier to detect faces in the webcam feed.</li>
          <li><strong>Eye Detection:</strong> Once a face is detected, the system further detects eyes within the face region to accurately position the glasses.</li>
          <li><strong>Glasses Resizing:</strong> The glasses image is resized according to the detected distance between the eyes to ensure a natural fit.</li>
          <li><strong>Overlay Process:</strong> The resized glasses image is then overlaid onto the detected face, creating a realistic effect by blending it with the original image.</li>
      </ul>
      <p>The application utilizes OpenCV for image processing and real-time video capture. The result is displayed in a window where the user can see their face with the overlayed glasses.</p>
  </div>
</body>
</html>
