# Single-Query Person-Centric Bimanual Hand-Object Interaction Detection

This repository contains the project page for:

> **Single-Query Person-Centric Bimanual Hand-Object Interaction Detection**
> Jonghyun Kim*, Junho Roh*, Yubin Yoon, Hyotae Lee, Jongkuk Park, Taehwan Hwang, Jaechul Kim†, and Jungho Lee†
> ECCV 2026
> *Equal contribution
> †Corresponding authors

## Project Page

The project page is available at:

```text
https://LGECTO-AIL-VIL.github.io/SingleQuery-BHOI/
```

## Overview

This project introduces **person-centric bimanual hand-object interaction detection**.

Given an input image, the goal is to detect each person and jointly predict:

* Human bounding box
* Body keypoints
* Left and right hand boxes
* Left and right hand contact states
* Left and right interaction targets

Unlike hand-centric approaches that treat each hand independently, our method represents each person with a single query and predicts the full bimanual interaction structure under the corresponding human instance.

## Resources

| Resource     | Link                                                | Status      |
| ------------ | --------------------------------------------------- | ----------- |
| Project page | `https://LGECTO-AIL-VIL.github.io/SingleQuery-BHOI/`         | Available   |
| Paper        | Coming soon                                         | Coming soon |
| Code         | Coming soon                                         | Coming soon |
| Dataset      | `https://github.com/LGECTO-AIL-VIL/SingleQuery-BHOI-Dataset` | Available   |
| arXiv        | Coming soon                                         | Coming soon |

## Dataset

The dataset repository provides COCO Panoptic-style annotations, example files, and an executable-based visualization tool.

Dataset repository:

```text
https://github.com/LGECTO-AIL-VIL/SingleQuery-BHOI-Dataset
```

The full dataset is based on COCO images.
We do not redistribute the full COCO image dataset. Users should download the original images from the official COCO dataset website and follow the corresponding image licenses and terms of use.

## Repository Structure

```text
SingleQuery-BHOI/
├── index.html
├── README.md
└── static/
    └── images/
        ├── teaser.png
        ├── architecture.png
        ├── dataset_examples.png
        ├── company_logo.png
        └── favicon.png
```

## Local Preview

This is a static HTML project page.
To preview it locally, open `index.html` in a browser.

Alternatively, run a simple local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{kim2026singlequery,
  title     = {Single-Query Person-Centric Bimanual Hand-Object Interaction Detection},
  author    = {Jonghyun Kim and Junho Roh and Yubin Yoon and Jaechul Kim and Jungho Lee and Hyotae Lee and Jongkuk Park and Taehwan Hwang},
  booktitle = {European Conference on Computer Vision},
  year      = {2026}
}
```

## Acknowledgement

This project page is adapted from the Academic Project Page template.

## License

The website source is released for research and academic project-page use.
Please refer to the original template license if reusing the page template.
