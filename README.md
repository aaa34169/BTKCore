BTKCore
=======

Introduction
------------

Core of the project Biomechanical-ToolKit (BTK) to represent biomechanical data, file formats and data processing

BTK is an open-source and cross-platform library for biomechanical analysis. BTK read and write acquisition files and can modify them. All these operations can be done by the use of the C++ API or by the wrappers included (Matlab, Octave, and Python).

All the informations to build the C++ libraries and bindings are provided in file 'Readme.html' which is located in the root of the source code.

APIs Documentation and tutorials are proposed on the main website of the project: http://b-tk.googlecode.com

Continuous integration
----------------------

To test the implemented features as well as to verify the modification in the code, hundreds of cases representing standard usages of the project are tested at each revision of the project.
The following list shows the status of the tests for different operating systems as well for the different supported languages (C++, Matlab/Octave, and Python):

 * [![Build Status](https://travis-ci.org/Biomechanical-ToolKit/BTKCore.png?branch=master)](https://travis-ci.org/Biomechanical-ToolKit/BTKCore) MacOS X (C++, Python)
 * [![Build Status](https://drone.io/Biomechanical-ToolKit/b-tk.core/status.png)](https://drone.io/Biomechanical-ToolKit/b-tk.core/latest) Linux (C++, Python, Octave)

**Note**: The continuous integration is realized on the `master` branch which corresponds to the *development* version of the code.