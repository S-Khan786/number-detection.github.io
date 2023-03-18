<html>
  <head>
    <meta charset="UTF-8">
  </head>
  <body>
    <h1>Finger Number Detection using Mediapipe and OpenCV</h1>
    <p>This project is a Python implementation of detecting the number of fingers shown in an image or video using Mediapipe and OpenCV.</p>
    <h2>Installation</h2>
    <p>To run this project, you will need to install the following dependencies:</p>
    <ul>
      <li>OpenCV</li>
      <li>Mediapipe</li>
      <li>NumPy</li>
    </ul>
    <p>You can install these dependencies using pip:</p>
    <pre><code>pip install opencv-python mediapipe numpy</code></pre>
    <h2>Usage</h2>
    <p>To run the program, run the following command in your terminal:</p>
    <pre><code>python finger_number_detection.py [source]</code></pre>
    <p>Where <code>[source]</code> can be either an image file path or a camera device index.</p>
    <p>For example, to detect the number of fingers in an image file named <code>hand.jpg</code>, run the following command:</p>
    <pre><code>python finger_number_detection.py hand.jpg</code></pre>
    <p>To detect the number of fingers using your camera, run the following command:</p>
    <pre><code>python finger_number_detection.py 0</code></pre>
    <h2>Sample image</h2>
    <h2 align="center">
    <img src="https://github.com/S-Khan786/number-detection.github.io/blob/master/sample_photos/f0.png" alt="number_detection" width="100%">
    <img src="https://github.com/S-Khan786/number-detection.github.io/blob/master/sample_photos/f1.png" alt="number_detection" width="100%">
    <img src="https://github.com/S-Khan786/number-detection.github.io/blob/master/sample_photos/f3.png" alt="number_detection" width="100%">
    <img src="https://github.com/S-Khan786/number-detection.github.io/blob/master/sample_photos/f4.png" alt="number_detection" width="100%">
    <img src="https://github.com/S-Khan786/number-detection.github.io/blob/master/sample_photos/f5.png" alt="number_detection" width="100%">
    </h2>
  </body>
</html>
