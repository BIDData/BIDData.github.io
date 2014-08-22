---
title: Setting Up Your Environment
layout: default
---

# Setting Up Your Environment

In this class, we will all be using the same Virtual Machines to complete assignments and class exercises. We have configured a Virtual Machine Image with a recent version of Linux, Python 2.7, and several libraries we’ll be using throughout the class. 

*Note: While you should also be able to set up a similar environment on your machine without needing a Virtual Machine, the course staff will not support such configurations - so you’re on your own if you choose to go that route!*

To create a VM using our [disk image](https://www.eecs.berkeley.edu/~charles/datascience-fa14-images/image-amd64.vdi.zip):

1.   Download and install [VirtualBox](https://www.virtualbox.org).
2.   Download and unzip our VirtualBox disk image [here](https://www.eecs.berkeley.edu/~charles/datascience-fa14-images/image-amd64.vdi.zip).
3.   Open VirtualBox and click the 'New' button.
4.   Select the following options in the VM creation wizard that appears:
     *    _Name and operating system_:
          *    Type: Linux
          *    Version: Ubuntu (64-bit)
     *    Memory size: at least 1024 MB
     *    _Hard drive_:
          *    Use an existing virtual drive file, and select the disk image you unzipped.

Then, start the VM by selecting it and pressing the 'Start' button at the top of the VirtualBox VM Manager window.

## Credentials

The VM should automatically log you into an account called `datascience`. The password for this account is
`datascience`. If you need to run commands with root (adminstrator) privalleges, you can use `sudo`.

## Information you should not need

### No 64-bit support? 

In the unlikely event that your machine cannot support a 64-bit virtual machine, we also have a [32-bit image](https://www.eecs.berkeley.edu/~charles/datascience-fa14-images/image-i386.vdi). Configuration instructions are the same, except that you should select _Version: Ubuntu (32-bit)_ instead of _Version: Ubuntu (64-bit)_.

We believe that machines that cannot support a 64-bit VM are *extremely* rare, so please inform the course staff if you need this.

### Software installed in the VM

The virtual machine image we supplied is setup using [this script](https://github.com/woggle/datascience-vm-scripts/blob/master/post-build-script.sh), which should also work on a Ubuntu-like system (but this is not supported by the course staff, so use it _at your own risk_). The notable pieces of software this installs are:

*   [ipython](http://ipython.org/)
*   [pandas](http://pandas.pydata.org/)
*   [OpenRefine](https://github.com/OpenRefine/OpenRefine/)
*   [Spark](https://spark.apache.org/)
*   [R](http://www.r-project.org/)
*   [numpy](http://www.numpy.org/)
*   [scipy](http://www.scipy.org/)
*   [matplotlib](http://matplotlib.org/)
*   [scikit-learn](http://http://scikit-learn.org/stable/)
*   [python-levenshtien](https://pypi.python.org/pypi/python-Levenshtein/)
*   [graphviz](http://www.graphviz.org/) and [pydot](https://pypi.python.org/pypi/pydot)
*   [BIDMach](http://bid2.berkeley.edu/bid-data-project/download/)
