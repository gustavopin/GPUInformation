# GPU Specs And Prices
Data obtained through [Kaggle](https://www.kaggle.com/datasets/alanjo/graphics-card-full-specs?resource=download) and [Tom's Hardware](https://www.tomshardware.com/news/gpu-pricing-index)

# Analysis

## Objective
This work was developed to compare and observe the development of Graphic Cards from the three major manufacturers: AMD, Nvidia and Intel (recently added to the group).
With the intentition of comparing series of graphic unit I used boxplots to better see minimum, maximuns and other central tendency measures.

## Overall
Graphics Cards have a vastly number of uses, but their focus on gaming machines are probably the most well known. Companies like Nvidia and AMD are the most prominent nowdays, both producing units for decades, Intel on the other hand just joined the maket with the realease of the Arc Series in late 2022.
Nvidia has the upper hand in the industry for many years, using their architecture and features to overpower the competition, specially after the launch of the new 4000 series, bringing the excidenly powerful (and costly) RTX 4090 and their introduction to the DLSS 3.
AMD still manufactures good products to compete with other models like the 4080 and below.
Intel and their super new architecture wasn't able to compete with the high-end models from AMD nor Nvidia but they had their uses as you can see more specifically in channels that tested them as [Tom's Hardware](https://www.tomshardware.com/reviews/intel-arc-a770-limited-edition-review) and [Linus Media Group](https://www.youtube.com/watch?v=j6kde-sXlKg&ab_channel=LinusTechTips).

Looking at the production on those units the graph below shows the number of launches of each company for each year since 2014 (this data only aplies to the "gaming" category of GPUs, so onboard graphics and hard image processing like the Quadro series from Nvidia).

![GPUs since 2014](Graphs/GPUS_over_year.png 'GPUs since 2014')

### VRAM
Starting with the VRAM (Video Random-Access Memory) we can see from the graph below how the latest series from the company (RTX 4000) stands out from the rest and the growth between each series.

![Nvidia GPU VRAM](Graphs/nvidia_vram.png 'Nvidia GPU VRAM')

For AMD and Intel recent units(RX 7000 and Arc Series), the VRAM capacity of the GPUs can be compared mostly to the RTX 3000 series from Nvidia and cards like RTX 4070.

![AMD and Intel GPU VRAM](Graphs/amd_intel_vram.png 'AMD and Intel GPU VRAM')

### Memory Bus Width

For the memory bus Nvidia maintained the same level since the GTX 900 series.

![Nvidia GPU Memory Bus](Graphs/nvidia_bus.png 'Nvidia GPU Memory Bus')

From the graph above, we can see the discrepancy within the 2000 series, having models with 64 bits and and 352 bits (both lower and upper outliers). The lowest amounts can be linked to the mobile GPUs, for the 2000 example it's the 2050 Mobile version, and the highest can be linked to Ti version (a acronym for Titanium, a plus series for GPUs from Nvidia). The same can be seen below for AMD and Intel units (AMD uses XT for the "plus" version of their cards).

![AMD and Intel GPU Memory Bus](Graphs/nvidia_bus.png 'AMD and Intel GPU Memory Bus')

## Clock
For both Memory and GPU Clock speeds (frequency in which both the GPU processor and Memory work) we can notice that every 3 generations, Nvidia boots the the clock speed for both memory and GPU while AMD has a more linear growth, until the more recent RX 7000 series, which has the same clock speed for their GPUs.
THe outliers withing the graphs are relative to Ti and XT versions of the GPUs. Here you can havea look at the Nvidia (First Graph) and AMD/Intel (Second Graph) GPU Clock speeds:

![Nvidia GPU Clock Speed](Graphs/nvidia_gpu_c.png 'Nvidia GPU Clock Speed')

![AMD and Intel GPU Clock Speed](Graphs/amd_intel_gpu_c.png 'AMD and Intel GPU Clock Speed')

Here are the graphs for Memory Clock Speed:

Nvidia:

![Nvidia Memory CLock Speed](Graphs/nvidia_mem_c.png 'Nvidia Memory CLock Speed')

AMD/Intel:

![AMD and Intel Memory Clock Speed](Graphs/amd_intel_mem_c.png 'AMD and Intel Memory Clock Speed')

## Summary
There are many variables to GPU performace: VRAM, clock speeds, architecture, memory bus width, and more. But with these data we can see clearly the that the newest unit for Nvidia, the RTX 4090 crushes the competition, but it crushed the prices too, with a MSRP of US$1599.00.
This do not say that AMD is a bad choice, it IS a good option with relative lower prices.
Intel has yet to grow, but it was a good start. It is not a exceptionally good card, but it can do a good job and, by it's price, it is a nice option.