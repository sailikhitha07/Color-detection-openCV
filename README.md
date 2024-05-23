<h1>Color Detection and Bounding Box Drawing Using OpenCV</h1>
    
<h2>Overview</h2>
<p>
        This project captures video from the webcam, detects a specified color in the video feed, and draws a bounding box around the detected color using OpenCV. The specified color in this project is yellow, represented in the BGR color space.
</p>
    
<h2>Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li>OpenCV</li>
        <li>NumPy</li>
        <li>Pillow (PIL)</li>
    </ul>
    
<h2>Installation</h2>
    <p>
        Alternatively, you can install all the required libraries from the provided <code>requirements.txt</code> file:
    </p>
    <pre><code>pip install -r requirements.txt</code></pre>
    
<h2>Project Files</h2>
    <ul>
        <li><code>main.py</code>: The main script that captures video, processes each frame to detect the specified color, and draws a bounding box around the detected color.</li>
        <li><code>util.py</code>: Contains utility functions, including the <code>get_limits</code> function that calculates the HSV color range for the specified color.</li>
    </ul>
    
<h2>Usage</h2>
    <p>
        To run the project, execute the <code>main.py</code> script:
    </p>
    <pre><code>python main.py</code></pre>
    <p>
        Press <code>q</code> to exit the video capture window.
    </p>

</body>
</html>
