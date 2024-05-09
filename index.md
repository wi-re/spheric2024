# 18th International Smoothed Particle Hydrodynamics Research and Engineering International Community Workshop

We have two papers in the proceedings this year:

## Physically-Motivated Machine Learning Models for Lagrangian Fluid Mechanics

In this paper we talk about recent experiences and insights into machine learning for fluid mechanics, specifically Lagrangian ones. In this context we give an overview of some best practices and how we can bring CFD and ML knowledge together to build a bridge towards the future.

This paper will be presented orally in Berlin and you can find the full paper in this repository (https://github.com/wi-re/spheric2024)

## Fully Analytic Higher-Order Boundary Integrals for Two-Dimensional SPH

This is a long running result from my work on semi analytic boundary handling in SPH that was presented some years ago at SIGGRAPH Asia. Back then we only were able to analytically solve boundary integrals for planar boundaries (in 2D and 3D). In this work we extended the solutions to arbitrary triangular boundaries in 2D and added the ability to model baricentric interpolation, i.e., piece-wise linear boundary quantities. This improves on prior work that was only capable of handling piece-wise constant boundary quantities as they did not solve the integrals over the area of the boundary but instead commonly solved it over the boundary surface geometry using the Divergence Theorem. We also show how this solution can be extended to non compact Gaussian kernels highlighting some interesting future work.

This paper will only be included in the proceedings and you can find the full paper in this repository.

## General things

Please also check out our recent work at ICLR Vienna 2024 https://tum-pbs.github.io/SFBC

And our recent presentation at PMAC in Santa Fe https://pmac.fluids.dev