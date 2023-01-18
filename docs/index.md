Denoising Diffusion Probabilistic Models (DDPM) have been used extensively with great success in the vision field, with many models showing particularly high-quality results in image inpainting. We propose applying similar diffusion methods to the speech domain, with the goal of performing super-resolution on speech samples. We believe that an analogous method to image inpainting can be performed on low resolution speech samples to retrieve a target high-resolution sample. Throughout this study, we compare super-resolution results from multiple baseline models with an unconditional diffusion-based approach.

## Listening samples for evaluation

We recommend using headphones for this section.

|            | 196-122150-0000                                                                          | 196-122150-0001                                                                        |
|------------|------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
|            | ![](new/target/196-122150-0000.png)                                                  | ![](new/lstm/196-122150-0000.png)                                                  |
| Input      | <audio src="new/target/196-122150-0000.wav" controls="" preload=""></audio>          | <audio src="new/lstm/196-122150-0000.wav" controls="" preload=""></audio>          |
|            | ![](new/target/196-122150-0000.png)                                                  | ![](new/target/196-122150-0001.png)                                                  |
| Target      | <audio src="new/target/196-122150-0000.wav" controls="" preload=""></audio>          | <audio src="new/target/196-122150-0001.wav" controls="" preload=""></audio>          |
|            | ![](new/lstm/196-122150-0000.png)                                              | ![](new/lstm/196-122150-0001.png)                                              |
| LSTM    | <audio src="new/lstm/196-122150-0000.wav" controls="" preload=""></audio>      | <audio src="new/lstm/196-122150-0001.wav" controls="" preload=""></audio>      |
|            | ![](new/u-net/196-122150-0000.png)                                           | ![](new/u-net/196-122150-0001.png)                                           |
| U-Net  | <audio src="u-net/196-122150-0000.wav" controls="" preload=""></audio>   | <audio src="new/u-net/196-122150-0001.wav" controls="" preload=""></audio>   |
|            | ![](new/nuwave2/196-122150-0000.png)                                                  | ![](new/nuwave2/196-122150-0001.png)                                                  |
| NU-wave2      | <audio src="new/nuwave2/196-122150-0000.wav" controls="" preload=""></audio>          | <audio src="new/nuwave2/196-122150-0001.wav" controls="" preload=""></audio>          |
|            | ![](new/repaint/196-122150-0000.png)                                          | ![](new/repaint/196-122150-0001.png)                                          |
| Repaint   | <audio src="new/repaint/196-122150-0000.wav" controls="" preload=""></audio>  | <audio src="new/repaint/196-122150-0001.wav" controls="" preload=""></audio>  |

