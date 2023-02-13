# OpenPTV v2.0 

This project is an attempt to merge between two open source 3D-PTV software packages: OpenPTV+PyPTV and MyPTV

## Introduction

OpenPTV core library `liboptv` is written in ANSI C and contains very useful ideas, the central one is multi-media calibration model. 
PyPTV is a Python GUI based on a flexible but somewhat cumbersome libraries of `chaco`, `enable`, and it is binded to C library using Cython. 

MyPTV is a pure Python and with Tk GUIs by @ronshnapp. 

@Roi-Feldenkreis master thesis is to merge these software packages, all in Python. The main idea is to either translate one system into another, or to create Python 
copies for all `liboptv` objects.



## Authors
- @alexlib
- @ronshnapp
- @Roi-Feldenkreis
