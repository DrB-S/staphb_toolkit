# StaPH-B ToolKit
[![Build Status](https://travis-ci.org/StaPH-B/staphb_toolkit.svg?branch=master)](https://travis-ci.org/StaPH-B/staphb_toolkit)  
A python library designed to make programs held within the StaPH-B Docker repository more accessible to public health scientists.

## Summary
The StaPH-B ToolKit is a Python library of commonly used bioinformatics tools that help to inform public health action. The StaPH-B ToolKit utilizes the [StaPH-B Docker Images](https://github.com/StaPH-B/docker-builds) to enable easy access of open-source software without the need of local installation and/or dependency maintenance.

## Motivation
Public health bioinformatics is dependent on open-source software that require carefully curated computational environments and various software dependencies. Setting up and maintaining such environments requires a skill set and expertise absent in most public health laboratories. The [StaPH-B Docker Images](https://github.com/StaPH-B/docker-builds) have helped generate reproducible computational environments through the use of containerization. However, access to these images is dependent on a working understanding of containerization, which is not available in most laboratories. The ToolKit addresses this issue through the handling of the StaPH-B docker images allowing users to interact with bioinformatis programs without needing to interact directly with mounted file systems and running containers. The goal of the Toolkit is it increase usability while mirroring the functionality of a locally-installed tool.

## Installing and Usage
The ToolKit requires **either** singularity or docker nad Python 3.6 or greater.  
The documentation for installing the dependencies can be found here: [https://staph-b.github.io/staphb_toolkit](https://staph-b.github.io/staphb_toolkit/install).  
The ToolKit itself can be installed using pip or git:

To install using pip:
```
pip install staphb_toolkit
```

To install using git:
```
`git clone https://github.com/StaPH-B/staphb_toolkit.git`
`./staphb_toolkit/setup.py`
```

Test the pipeline with the following command:  
```
staphb-tk test
```
