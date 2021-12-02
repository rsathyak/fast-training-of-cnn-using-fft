### Content Blog

[Fast — CNN : Subsitution of Convolution layers with FFT layers](https://medium.com/analytics-vidhya/fast-cnn-substitution-of-convolution-layers-with-fft-layers-a9ed3bfdc99a)

### Resources

[FCNN: Fourier Convolutional Neural Networks](http://ecmlpkdd2017.ijs.si/papers/paperID11.pdf)

[How Fourier Transform Can Speed Up Training CNNs](https://towardsdatascience.com/how-fourier-transform-speeds-up-training-cnns-30bedfdf70f6)

### Code

[fft-conv-pytorch](https://github.com/fkodom/fft-conv-pytorch)

[Main Paper Code with CUDA implementation](https://github.com/abhinav-vaishya/Fast-Training-of-Convolutional-Networks-through-FFTs)

[Processing Brain MRI's using FFT CNN](https://github.com/pushkar-khetrapal/Fast-CNN)

## Plan (as of now)

1. Lets start with the proposal architecture and implement that using fft convolution for cifar 10. We will use pytorch fft functions.
2. acquire statistics and check for improved runtime.
3. Run the same implementation with different architecture. The paper mentions that the fft implementation is largely useful only for larger kernels. lets test for the same on different architecture.
4. acquire statistics for these architectures.
5. if we have time, lets work on CUDA implementation for these architectures and gather results as well
6. Report all the experiments and results and add to the existing proposal