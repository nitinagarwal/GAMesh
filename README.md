# GAMesh: Guided and Augmented Meshing for Deep Point Networks
### 3DV 2020 [[Paper]](https://arxiv.org/abs/2010.09774)[[Project Page]](https://www.ics.uci.edu/~agarwal/GAMesh/index.html)

We propose a new meshing algorithm to generate a surface with correct topology for the output points of a point network. GAMesh can be used both in post-processing to mesh the output points or to train the point network to directly optimize the vertex positions of the final 3D mesh. Unlike traditional surface reconstruction techniques (like Ball-Pivot Algorithm & Screened Poisson Reconstruction), GAMesh is independent of both the density and distribution of points and gaurantees correct geometry and topology of the final surface. We show its applications in single-view shape prediction, fair evaluation of point networks and reconstructing surfaces for networks which output sparse point clouds. 

## Getting Started
coming soon

## Citation
If you find this code useful, please consider citing our paper

```
@inproceedings{agarwal2020GAMesh,
    title={GAMesh: Guided and Augmented Meshing for Deep Point Networks},
    author={Agarwal, Nitin and Gopi, M},
    booktitle={3DV},
    year={2020}}
```

## License
Our code is released under MIT license (see License file for details)

## Contact
Please contact [Nitin Agarwal](https://www.ics.uci.edu/~agarwal/) if you have questions or comments
