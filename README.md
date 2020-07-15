# H-Mish

*Code will be released soon. Currently in validation for ImageNet.*

#### Updates:

- Faster variants for Mish and H-Mish by [Yashas Samaga](https://github.com/YashasSamaga) can be found here - [ConvolutionBuildingBlocks](https://github.com/YashasSamaga/ConvolutionBuildingBlocks)
- Alternative (experimental improved) variant of H-Mish developed by [Páll Haraldsson](https://github.com/PallHaraldsson) can be found here - [H-Mish](https://github.com/PallHaraldsson/H-Mish/blob/master/README.md) (Available in Julia)

Formula - *(x/2).min(2, max(0, x+2))*

<div style="text-align:center"><img src ="assets/hard_mish_graph.png"  width="450"/></div>
<p>
    <em>Figure 1. Hard Mish Activation Function</em>
</p>

### CIFAR-10: 

|Architecture|Swish|H-Mish|Mish|ReLU|
|:---:|:---:|:---:|:---:|:---:|
|ResNet-20|90.42%|92.57%|**92.68%**|91.8%|
