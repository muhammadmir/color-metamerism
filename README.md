# Color Metamerism
Informally, color metamerism is the concept that two or more colors can be perceptually equivalent (but fundamentally different in composition) to another color. For example, we can mix certain proportions of red light and yellow light together such that the resulting color will be green light.

This repo summarizes some exploratory in color metamerism with Mathematica as part of DSSI during Summer 2023, mentored by Dr. Steve Kass.

## Method Overview
A color can be formally described with its ___spectral power distribution___, or [SPD](http://hyperphysics.phy-astr.gsu.edu/hbase/vision/spd.html). Color metamerism is the concept that a linear combination of two or more SPDs is equivalent to a single target SPD. Mathematically, there are an infinite number of color metamers.

We limit our experiments to monochromatic SPDs, which would be equivalent to light (in the visible spectrum) of exactly one specific wavelength. We ask, given the target SPD and a specified number of input SPDs, what are the SPDs (and their intensities) necessary to match the target SPD? We use the CIE 1931 colorimetry model for our calculations and show two approaches: exact and approximate.

Please see the PDF file attached for more information. Note that the actual Mathematica notebook file was too large, so a compressed version was uploaded.

## Academic Resources
If you find colorimetry--the field of mathematics behind human color perceptron--interesting, check out [this blog](https://medium.com/hipster-color-science/a-beginners-guide-to-colorimetry-401f1830b65a), or the following resoruces below:
1. Fairchild, M. D. (2005). Colorimetry. In *Color Appearance Models* (2nd ed., pp. 53–82). John Wiley & Sons. [PDF](https://scis.uohyd.ac.in/~chakcs/cipclass/lecs/ColourAppearance.pdf).
2. Schanda, J. (Ed.). (2007). *Colorimetry: Understanding the CIE System*. Wiley-Interscience. [Wiley Online Library](https://onlinelibrary.wiley.com/doi/book/10.1002/9780470175637).

3. Wyman, C., Sloan, P.-P., & Shirley, P. (2013). Simple analytic approximations to the CIE XYZ color matching functions. *Journal of Computer Graphics Techniques*, 2(2), 1–11. [PDF](https://jcgt.org/published/0002/02/01/paper.pdf).
