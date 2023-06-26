# Guided-Filter-by-Matlab

## Introduce 简介
1. source code about the guided filter using matlab.
使用matlab编写的引导滤波源码
2. Reference:He K, Sun J, Tang X. Guided image filtering[J]. IEEE transactions on pattern analysis and machine intelligence, 2012, 35(6): 1397-1409.
参考文献：Kaiming，He等论于2012年在IEEE上的论文《Guided image filtering》

## Instructions for use 使用说明
1. The mlx file format is a real-time rendering file, which can be run directly in Matlab.
mlx文件格式为Matlab实时渲染文件格式，直接用Matlab运行即可
2. We have used Gaussian filtering and guided filtering for comparison, highlighting the edge preserving effect of guided filtering.
先后用了高斯滤波和引导滤波进行对比，突出引导滤波的保边效果。
3. If you need to replace the image, just change the filepath at input_p and input_q.
如果需要更换图片，只需要在input_p和input_q处更改文件位置即可。
4. Strictly following the mathematical derivation in Kaiming He's paper without any optimization, the efficiency may be low, but it is easy to understand.
严格按照Kaiming He的论文中的数学推导实现，没有使用任何优化，因此效率可能较低，但是便于理解。

## Effect Description 效果说明
Mainly highlighting the efficiency of guided filtering in both edge preservation and denoising. Minimize noise as much as possible while ensuring clear edges of the image.For specific effects, please refer to the attachment "Effect Showcase_效果展示"The left image is the original image, the middle image shows the Gaussian filtering effect, and the right image shows the guided filtering effect.
主要突出引导滤波在保边和去噪两方面的高效性。在保证图片边缘清晰的情况下，尽可能降低噪声。具体效果见附件“Effect Showcase_效果展示”。左图为原图，中间的图片为高斯滤波效果，右边的图片为引导滤波效果图。

## Contact Me 联系我
please contact me @ fromthefox@icloud.com if you have any question.
