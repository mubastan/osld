## OSLD Dataset
Open Set Logo Detection Dataset (OSLD Dataset, formerly known as BLAC dataset) is a dataset of eCommerce product images with associated brand logo images (see [paper](https://arxiv.org/abs/1911.07440) for details). It is released under creative commons ([CC BY-NC 4.0](http://creativecommons.org/licenses/by-nc/4.0)) license to promote research in open set logo detection. The dataset can be used only for research purposes. It contains:
- 20K product images, with logo bounding box annotations (this [dataset loader](https://github.com/mubastan/voc) in PyTorch can be useful to load and evaluate)
- 12.1K logo classes with 20.8K canonical logo images
- Product image logo bounding box to canonical logo image match pair annotations


## Download
[Dropbox](https://www.dropbox.com/sh/1uz2d684hofp65m/AAB2pxO5mkv1YPt76UVeXJbAa?dl=0)

## Updates
- 30 August 2021: Initial release of the dataset

## Contact
For questions, please contact Muhammet Bastan (mubastan@gmail.com)

## References
```
@article{OSLD,
  author    = {Muhammet Bastan and
               Hao-Yu Wu and
               Tian Cao and
               Bhargava Kota and
               Mehmet Tek},
  title     = {{Large Scale Open-Set Deep Logo Detection}},
  year      = {2019},
  url       = {http://arxiv.org/abs/1911.07440}
}
```
