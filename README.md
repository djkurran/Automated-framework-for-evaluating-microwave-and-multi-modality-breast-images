# Automated-workflow-for-evaluating-microwave-and-multi-modality-breast-images

***

## Abstract
The emergence and subsequent expansion of the field of medical microwave imaging has resulted in numerous approaches to image reconstruction. This includes microwave tomography, radar imaging, and more recently, multi-modality approaches. However, there is an absence of a standardized and widely accepted process that is proficient at extracting information from these images and employing this knowledge to conduct a thorough quantitative evaluation of images and regions within images. This shortcoming may interfere with a researcher’s ability to make reliable and consistent inferences from experiments and to interpret results. This, in turn, complicates comparison of results obtained by different research groups, which is of interest given the development of standardized test phantoms. To remedy this deficiency, an automated workflow has been developed with the objective to standardize the processing and analysis of images acquired from a range of modalities. Processing images in a consistent manner to extract quantitative information about an experiment assists researchers to make inferences and to report consistent and reliable results that can be compared across research groups. Images are first segmented into regions dominated by a tissue type. Quantitative information is then evaluated from these regions. The effectiveness of the workflow is demonstrated with multiple examples that focus on quantifying changes to images due to enhancements of the reconstruction algorithm or perturbations of a parameter used by the reconstruction operator. 

## Overview and take-home messages

![](https://github.com/djkurran/Automated-framework-for-evaluating-microwave-and-multi-modality-breast-images/blob/main/overview.png)

Figure 1. Overview of automated workflow for evaluating microwave and multi-modality breast images.

### Overview

The objective is to furnish a workflow that standardizes the processing and analysis of images to allow researchers to make inferences from experiments and to report consistent and reliable results that can be compared across research groups. The workflow is applied to pairs of images: a test, and a reference image.  The test image is a reconstruction, but the reference image may be another version of the reconstruction or a ground truth model. Images are segmented into regions dominated by a tissue type. Quantitative information is then evaluated from these regions. This is accomplished by comparing the test image to the reference. Discrepancies are measured by comparing regions based on shape, size, and location within an image. This is carried out by the *Tissue interface analysis*, and the *geometric analysis*. Moreover, properties within segmented regions of the test image are compared to the corresponding reference region to evaluate a change in response or the ability of an algorithm to reconstruct a tissue type. This is prescribed by the *Analysis of properties* stage of the workflow. The properties contained within the segmented regions may be dielectric properties associated with a tissue type (microwave tomography), backscattered energy related to a dominant scatterer (microwave radar), or scattering that may arise due to a change of propagation speed of a sound wave due to the presence of dense tissue (qualitative ultrasound).

### Take-home messages

1. An automated image analysis workflow is presented that extracts qualitative and quantitative information from regions, objects, and responses within images.
Images, acquired from a range of modalities, are processed in a consistent manner to extract quantitative information about an experiment conducted by a researcher.
2. The workflow is applied to pairs of images: a test, and a reference image.  The images are then partitioning into regions. Differences between image pairs are evaluated by comparing regions based on shape, size, and location within an image. 
3. Properties within segmented regions of the test image are compared to the corresponding reference region to measure a change in response or the ability of an algorithm to reconstruct a tissue type. 
4. The quantitative information extracted from results assists researchers to make inferences related to a variable change, a data acquisition modification, or a reconstruction algorithm enhancement, and to facilitate the comparison of results obtained by different research groups.

### Supplementary Materials

[Support documentation](https://github.com/djkurran/Automated-framework-for-evaluating-microwave-and-multi-modality-breast-images/wiki/0.-Introduction) provides detailed results for all cases presented in the paper.

## Citing Manuscript

D. Kurrant, M. Omer, E. Fear. Automated framework for evaluating microwave and multi-modality breast images. IEEE Journal of Electromagnetics, RF and Microwaves in Medicine and Biology, 2022 (Submitted for review).

***
