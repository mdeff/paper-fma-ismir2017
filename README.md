# FMA: A Dataset For Music Analysis

[Michaël Defferrard](https://deff.ch),
[Kirell Benzi](https://www.kirellbenzi.com),
[Pierre Vandergheynst](https://people.epfl.ch/pierre.vandergheynst),
[Xavier Bresson](https://www.ntu.edu.sg/home/xbresson), \
International Society for Music Information Retrieval Conference (ISMIR), 2017.

> We introduce the Free Music Archive (FMA), an open and easily accessible dataset suitable for evaluating several tasks in MIR, a field concerned with browsing, searching, and organizing large music collections.
> The community's growing interest in feature and end-to-end learning is however restrained by the limited availability of large audio datasets.
> The FMA aims to overcome this hurdle by providing 917 GiB and 343 days of Creative Commons-licensed audio from 106,574 tracks from 16,341 artists and 14,854 albums, arranged in a hierarchical taxonomy of 161 genres.
> It provides full-length and high-quality audio, pre-computed features, together with track- and user-level metadata, tags, and free-form text such as biographies.
> We here describe the dataset and how it was created, propose a train/validation/test split and three subsets, discuss some suitable MIR tasks, and evaluate some baselines for genre recognition.
> Code, data, and usage examples are available at https://github.com/mdeff/fma.

```
@inproceedings{fma_dataset,
  title = {{FMA}: A Dataset for Music Analysis},
  author = {Defferrard, Micha\"el and Benzi, Kirell and Vandergheynst, Pierre and Bresson, Xavier},
  booktitle = {18th International Society for Music Information Retrieval Conference (ISMIR)},
  year = {2017},
  archiveprefix = {arXiv},
  eprint = {1612.01840},
  url = {https://arxiv.org/abs/1612.01840},
}
```

## Resources

PDF available at [arXiv], [ISMIR], [EPFL].

Related: [poster], [slides], [data], [code].

[arXiv]: https://arxiv.org/abs/1612.01840
[ISMIR]: https://archives.ismir.net/ismir2017/paper/000075.pdf
[EPFL]: https://infoscience.epfl.ch/record/227512
[poster]: https://doi.org/10.5281/zenodo.1035847
[slides]: https://doi.org/10.5281/zenodo.1066119
[data]: https://github.com/mdeff/fma
[code]: https://github.com/mdeff/fma

## Compilation

Compile the latex source into a PDF with `make`.
Run `make clean` to remove temporary files and `make arxiv.zip` to prepare an archive to be uploaded on arXiv.

## Figures

All the figures are in the [`figures`](figures/) folder.

## Peer-review

The paper got a [metareview](ismir_review_4.txt) based on three reviews ([#1](ismir_review_1.txt), [#2](ismir_review_2.txt), [#3](ismir_review_3.txt)).
