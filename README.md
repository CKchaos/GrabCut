A GUI program to display the result from a image segmentation algorithm named  [GrabCut](http://pages.cs.wisc.edu/~dyer/cs534-fall11/papers/grabcut-rother.pdf).

This program is a course project during my second year in university, so some functions in outdated libraries may be not supported by the newest libraries.

##### Requirements

​	python 2.7

​	matplotlib 2.0.2

​	OpenCV 3.2.0

​	scikit-learn 0.18.1

​	PIL

​	wxPython 3.0.2.0 (GUI library )

​	igraph

​	**Note**: To install igraph library , run **pip install python-igraph**. Do **not** run **pip install igraph**

##### Usage

```
#Organization
./
    |--grab.py - call the GrabCut function in OpenCV.
    |--grabcut.py - use igraph and scikit-learn to implement GrabCut function.(Not a good implementation)
    |--main.py - build the GUI architecture by wxPython.
#Run
    python main.py
```

##### Example

![1](1.gif)

![2](2.gif)