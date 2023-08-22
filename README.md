<h3>To build and run</h3>
<p>Run the following command: <br> <b>gcc <u>.c file</u> `pkg-config --cflags gstreamer-1.0` `pkg-config --libs gstreamer-1.0` -o <u>build name</u></b></p>
<br>
<h4>To install gstreamer</h4>
Official doc: <a href="https://gstreamer.freedesktop.org/documentation/">Gstreamer Doc</a>
<br>
<b>Run the following commands: </b>
<code>apt-get install libgstreamer1.0-dev libgstreamer-plugins-base1.0-dev libgstreamer-plugins-bad1.0-dev gstreamer1.0-plugins-base gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-plugins-ugly gstreamer1.0-libav gstreamer1.0-tools gstreamer1.0-x gstreamer1.0-alsa gstreamer1.0-gl gstreamer1.0-gtk3 gstreamer1.0-qt5 gstreamer1.0-pulseaudio</code>
<br>
<br>
<h4>Building applications with Gstreamer</h4>
<p>Add this to gcc command: <code>pkg-config --cflags --libs gstreamer-1.0</code></p>