# Udacity Self Driving Car Nanodegree
## Advanced Lane Finding

### Overview

This is a project for Udacity's Self Driving Car Nanodegree. The objective is to create a software pipeline to identify the lane boundaries from video stream of a front-facing camera on a car.

![Screenshot](/images/Capture.JPG)

### Video demo

You can see the video demo of the final outcome at [here](https://vimeo.com/).

### Final report

You can view the final report of this project at [writeup.pdf](https://github.com/).

### Dependencies

- python==3.5.2
- numpy
- matplotlib
- opencv3
- ffmpeg
- moviepy

### Installation

**Install Anaconda:**

Follow the instructions on the [Anaconda download site](https://www.continuum.io/downloads).

**Create environment:**

For users with CPU only, running this command will create a new `conda` environment that is provisioned with all libraries you need to run the codes.

```
$ conda env create -f environment.yml
```

**Uninstall environment:**

To uninstall the environment:

```
$ conda env remove -n advanced-lane-finding
```

**Activate environment:**

In order to use the environment, you will need to activate it. This must be done **each** time you open a new terminal window. 

```
$ source activate advanced-lane-finding
```

To exit the environment, simply close the terminal window or run the following command:

```
$ source deactivate advanced-lane-finding
```

### How to run

You can step through the Jupyter Notebook at [notebook.ipynb](https://github.com/).

