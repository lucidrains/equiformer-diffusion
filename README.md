## Equiformer Diffusion (wip)

Implementation of denoising diffusion for protein design in the same vein as <a href="https://www.biorxiv.org/content/10.1101/2022.12.09.519842v1">RFDiffusion</a>, with the pretraining and <a href="https://arxiv.org/abs/2208.04202">newly discovered self-conditioning technique</a>, but using the new <a href="https://github.com/lucidrains/equiformer-pytorch">Equiformer</a> with some improvements (negative of euclidean distance for attention in higher types).

## Citations

```bibtex
@article{Liao2022EquiformerEG,
    title   = {Equiformer: Equivariant Graph Attention Transformer for 3D Atomistic Graphs},
    author  = {Yi Liao and Tess E. Smidt},
    journal = {ArXiv},
    year    = {2022},
    volume  = {abs/2206.11990}
}
```

```bibtex
@article{Watson2022,
    author  = {Watson, Joseph L. and Juergens, David and Bennett, Nathaniel R. and Trippe, Brian L. and Yim, Jason and Eisenach, Helen E. and Ahern, Woody and Borst, Andrew J. and Ragotte, Robert J. and Milles, Lukas F. and Wicky, Basile I. M. and Hanikel, Nikita and Pellock, Samuel J. and Courbet, Alexis and Sheffler, William and Wang, Jue and Venkatesh, Preetham and Sappington, Isaac and Torres, Susana Vazquez and Lauko, Anna and De Bortoli, Valentin and Mathieu, Emile and Barzilay, Regina and Jaakkola, Tommi S. and DiMaio, Frank and Baek, Minkyung and Baker, David},
    title   = {Broadly applicable and accurate protein design by integrating structure prediction networks and diffusion generative models},
    year    = {2022},
    doi     = {10.1101/2022.12.09.519842},
    publisher = {Cold Spring Harbor Laboratory},
    url     = {https://www.biorxiv.org/content/early/2022/12/10/2022.12.09.519842},
    eprint  = {https://www.biorxiv.org/content/early/2022/12/10/2022.12.09.519842.full.pdf},
    journal = {bioRxiv}
}
```
