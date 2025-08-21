# KuiSCIMA
A digital machine-readable dataset of both purely symbolic and OMR-oriented representations of the music pieces in
Baishidaoren Gequ.

The dataset KuiSCIMA (Jiang Kui Score Images for Musicological Analysis) is the first machine-readable digital OMR
dataset containing ancient Chinese *suzipu* 俗字谱 notation. It is based on five different influential editions of
Jiang Kui's 17 *suzipu* pieces in the influential collection *Baishidaoren Gequ* 白石道人歌曲. The JSON format employed in
this dataset is semantically close to the original notation and features symbol-level annotations of the textual and
musical contents with their positions.
  
## Annotation Tool
The annotation tool used for viewing, editing and exporting from the KuiSCIMA dataset is available under
[https://github.com/SuziAI/gui-tools](https://github.com/SuziAI/gui-tools).
Currently, the version of `gui-tools` needed is tagged as `v2.1`.
  
## How to Cite

KuiSCIMA `v2.0` is an updated and expanded version of KuiSCIMA `v1.0`. It contains not only the 17 *suzipu* pieces,
but all 109 pieces of *Baishidaoren Gequ*, including *lülüpu*, and *jianzipu* musical notations. For all new work, please
cite KuiSCIMA `v2.0`:

[KuiSCIMA v2.0: Improved Baselines, Calibration, and Cross-Notation Generalization for Historical Chinese Music Notations in Jiang Kui's Baishidaoren Gequ](https://doi.org/10.48550/arXiv.2507.18741) (currently only available as preprint)

```
@misc{RepoluskIcdar2025,
  author       = {Repolusk, Tristan and Veas, Eduardo},
  title        = {KuiSCIMA v2.0: Improved Baselines, Calibration, and Cross-Notation Generalization for Historical Chinese Music Notations in Jiang Kui's Baishidaoren Gequ},
  note         = {Accepted for publication at ICDAR 2025 (in press)},
  year         = {2025},
  eprint       = {arXiv:2507.18741},
  archivePrefix= {arXiv},
  primaryClass = {cs.CV},           
  url          = {https://arxiv.org/abs/2507.18741}
}
```

[comment]: <> ( ``` )
[comment]: <> ( @InProceedings{RepoluskIcdar2025, )
[comment]: <> (   author={Repolusk, Tristan and Veas, Eduardo}, )
[comment]: <> (   editor={Yin, Xu-Cheng and Karatzas, Dimosthenis and Lopresti, Daniel}, )
[comment]: <> (   title={KuiSCIMA v2.0: Improved Baselines, Calibration, and Cross-Notation Generalization for Historical Chinese Music Notations in Jiang Kui's Baishidaoren Gequ}, )
[comment]: <> (   booktitle={Document Analysis and Recognition - ICDAR 2024}, )
[comment]: <> (   year={2025}, )
[comment]: <> (   publisher={Springer Nature Switzerland}, )
[comment]: <> (   address={Cham}, )
[comment]: <> (   pages={xx--yy}, )
[comment]: <> (   doi={TODO} )
[comment]: <> ( } )
[comment]: <> ( ``` )

KuiSCIMA `v1.0` should only be cited if you refer to that specific version:
[The KuiSCIMA Dataset for Optical Music Recognition of Ancient Chinese Suzipu Notation](https://link.springer.com/chapter/10.1007/978-3-031-70552-6_3)

```
@InProceedings{RepoluskIcdar2024,
  author={Repolusk, Tristan and Veas, Eduardo},
  editor={Barney Smith, Elisa H. and Liwicki, Marcus and Peng, Liangrui},
  title={The KuiSCIMA Dataset for Optical Music Recognition of Ancient Chinese Suzipu Notation},
  booktitle={Document Analysis and Recognition - ICDAR 2024},
  year={2024},
  publisher={Springer Nature Switzerland},
  address={Cham},
  pages={38--54},
  doi={10.1007/978-3-031-70552-6_3}
}
```

## Documentation
For the details of what editions of *Baishidaoren Gequ* are contained in KuiSCIMA, preprocessing, dataset composition
etc., refer to the [chapter in my dissertation](kuiscima_documentation.pdf). See the [annotation remarks](annotation_remarks.pdf) for additional comments on annotations of unclear notation
instances in KuiSCIMA.

## Content List
See the [content list](kuiscima_contents.pdf) for a complete listing of all the contents in KuiSCIMA.

## Artificial Dataset
In addition, the folder `artificial_suzipu_dataset` contains 36 handwritten (by me) instances of all 77 *suzipu* classes,
even the ones that do not occur in the original *Baishidaoren Gequ*. This data is not yet used, since all my attempts to
train models with this artificial data included resulted in worse overall performance.


