# FaceDetection
Face Detection in Java Using OpenCV

#Introduction

JavaCV uses wrappers from the JavaCPP Presets of commonly used libraries by researchers in the field of computer vision (OpenCV, FFmpeg, libdc1394, PGR FlyCapture, OpenKinect, CL PS3 Eye Driver, videoInput, ARToolKitPlus, and flandmark), and provides utility classes to make their functionality easier to use on the Java platform, including Android.

JavaCV also comes with hardware accelerated full-screen image display (CanvasFrame and GLCanvasFrame), easy-to-use methods to execute code in parallel on multiple cores (Parallel), user-friendly geometric and color calibration of cameras and projectors (GeometricCalibrator, ProCamGeometricCalibrator, ProCamColorCalibrator), detection and matching of feature points (ObjectFinder), a set of classes that implement direct image alignment of projector-camera systems (mainly GNImageAligner, ProjectiveTransformer, ProjectiveColorTransformer, ProCamTransformer, and ReflectanceInitializer), a blob analysis package (Blobs), as well as miscellaneous functionality in the JavaCV class. Some of these classes also have an OpenCL and OpenGL counterpart, their names ending with CL or starting with GL, i.e.: JavaCVCL, GLCanvasFrame, etc.


#Downloads

To install manually the JAR files, obtain the following archives

OpenCV: https://github.com/opencv/opencv


#System Requirements

To use JavaCV, you will first need to download and install the following software:

An implementation of Java SE 7 or newer:

OpenJDK http://openjdk.java.net/install/ or
Sun JDK http://www.oracle.com/technetwork/java/javase/downloads/ or
IBM JDK http://www.ibm.com/developerworks/java/jdk/


#Manual Installation
Simply put all the desired JAR files (opencv*.jar, ffmpeg*.jar, etc.), in addition to javacpp.jar and javacv.jar, somewhere in your class path. Here are some more specific instructions for common cases:

NetBeans (Java SE 7 or newer):

In the Projects window, right-click the Libraries node of your project, and select "Add JAR/Folder...".
Locate the JAR files, select them, and click OK.
Eclipse (Java SE 7 or newer):

Navigate to Project > Properties > Java Build Path > Libraries and click "Add External JARs...".
Locate the JAR files, select them, and click OK.
IntelliJ IDEA (Android 4.0 or newer):

Follow the instructions on this page: http://developer.android.com/training/basics/firstapp/
Copy all the JAR files into the app/libs subdirectory.
Navigate to File > Project Structure > app > Dependencies, click +, and select "2 File dependency".
Select all the JAR files from the libs subdirectory.
After that, the wrapper classes for OpenCV and FFmpeg, for example, can automatically access all of their C/C++ APIs:

1. OpenCV : http://docs.opencv.org/master/
