# Stable Filters Image Collection

This repository holds the high-resolution PNGs for the Stable Filters blog posts:

[Stable Filters - Part 1](https://caseymuratori.com/blog_0035)

[Stable Filters - Part 2](https://caseymuratori.com/blog_0036)

The images are named as follows:

name_original.png - the input image

name_filter_iterations_result.png - the output image, where:

- name identifies the input image to which this output corresponds
- filter is the name of the filter, as given in the listing below
- iterations is the number of iterations before converging or diverging
- result is either "stable" if the filter converged, or "unstable" if diverged

| Name | Kernel |
|------|--------|
| Muratorif8 | -0.010547f, 0.052344f, -0.156641f, 0.614844f, 0.614844f, -0.156641f, 0.052344f, -0.010547 |
| Muratorif6 | 0.000000f, 0.027617f, -0.130815f, 0.603198f, 0.603198f, -0.130815f, 0.027617f, 0.000000f |
| Muratori32 | 0.0f, 1.0f / 32.0f, -4.0f / 32.0f, 19.0f / 32.0f, 19.0f / 32.0f, -4.0f / 32.0f, 1.0f / 32.0f, 0.0 |
| Lanczos8 | -0.01263f, 0.05976f, -0.16601f, 0.61888f, 0.61888f, -0.16601f, 0.05976f, -0.01263f |
| Lanczos6 | 0.0f, 0.02446f, -0.13587f, 0.61141f, 0.61141f, -0.13587f, 0.02446f, 0.0f |
| HEVC | -1.0f / 64.0f, 4.0f / 64.0f, -11.0f / 64.0f, 40.0f / 64.0f, 40.0f / 64.0f, -11.0f / 64.0f, 4.0f / 64.0f, -1.0f / 64.0f |
| H264 | 0.0f, 1.0f / 32.0f, -5.0f / 32.0f, 20.0f / 32.0f, 20.0f / 32.0f, -5.0f / 32.0f, 1.0f / 32.0f, 0.0f |
| Bilinear | 0.0f, 0.0f, 0.0f, 0.5f, 0.5f, 0.0f, 0.0f, 0.0f |
| Blackman | -0.00133, 0.02190, -0.11765, 0.59708, 0.59708, -0.11765, 0.02190, -0.00133 |
| SincCos | -0.00345, 0.03918, -0.14626, 0.61053, 0.61053, -0.14626, 0.03918, -0.00345 |
| Lagrange7 | -0.0024414, 0.0239258, -0.1196289, 0.5981445, 0.5981445, -0.1196289, 0.0239258, -0.0024414 |
| Lagrange5 | 0, 0.011719, -0.097656, 0.585938, 0.585938, -0.097656, 0.011719, 0 |
| Gunderson | 0, 0.052519, -0.152582, 0.600063, 0.600063, -0.152582, 0.052519, 0 |
| Kensler | 0, 0.02172546, -0.12042216, 0.5986967, 0.5986967, -0.12042216, 0.02172546 |
