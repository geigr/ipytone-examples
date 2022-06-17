[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/benbovy/ipytone-examples/HEAD)

# Ipytone Demo

[Ipytone](https://github.com/benbovy/ipytone) showcase examples illustrating the powerful capabilities of Jupyter notebooks for data visualization and sonification.

## Overview

### Music teaser

<a href="https://www.youtube.com/watch?v=jMYMQFhareo" target="_blank" rel="noopener noreferrer"><img width="512" alt="music teaser yt video" src="https://user-images.githubusercontent.com/4160723/174279963-b1728f13-e814-48c1-b63c-75e5b037970c.png"></a>

### Hubble Deep Field

<a href="https://www.youtube.com/watch?v=en4MlnaQBY8" target="_blank" rel="noopener noreferrer"><img width="512" alt="hubble yt video" src="https://user-images.githubusercontent.com/4160723/174279791-e67f244e-8db6-4352-af66-e7d466120d46.png"></a>

### Global CO2 concentration vs. air temperature

<a href="https://www.youtube.com/watch?v=EGdd3wQJkHM" target="_blank" rel="noopener noreferrer"><img width="512" alt="co2 vs temp yt video" src="https://user-images.githubusercontent.com/4160723/174279666-764726d0-63a3-486b-bf55-5278175edb8b.png"></a>

### French presidential election 2022 (1st round)

<a href="https://www.youtube.com/watch?v=1EpDZMUDR8Q" target="_blank" rel="noopener noreferrer"><img width="512" alt="french election yt video" src="https://user-images.githubusercontent.com/4160723/174279530-380ee692-5885-415f-aac8-ff71d43113b3.png"></a>

### River meandering

<a href="https://www.youtube.com/watch?v=ygIFh0SkkU4" target="_blank" rel="noopener noreferrer"><img width="512" alt="river meandering yt video" src="https://user-images.githubusercontent.com/4160723/174279320-c642c51f-c4b6-43ca-b9c3-fa7db0b45907.png"></a>

### Landscape evolution model

<a href="https://www.youtube.com/watch?v=GNYDMfbU5O0" target="_blank" rel="noopener noreferrer"><img width="512" alt="landscape evolution yt video" src="https://user-images.githubusercontent.com/4160723/174280263-08abc8a3-f33e-4f85-a0d1-e4b0e308b232.png"></a>

### Earthquake data

<a href="https://www.youtube.com/watch?v=O5Y6kMlNsp8" target="_blank" rel="noopener noreferrer"><img width="512" alt="earthquake data yt video" src="https://user-images.githubusercontent.com/4160723/174280546-0d5d6b13-b338-4182-8542-0f368b61adb3.png"></a>

## Run the notebooks

### Using Binder

Although it may be sub-optimal for some of the examples, you can run the notebooks without installing
anything thanks to [binder](https://mybinder.org/). Just follow the link below or click on the
"launch binder" badge at the top of this document and it will launch remotely a new notebook server
for you:

- [Run on binder](https://mybinder.org/v2/gh/benbovy/ipytone-examples/HEAD)

### Install and run locally (Conda)

Assuming that you have `git` and [conda](https://conda.io/docs/index.html)
installed, you can install all the packages required to run the notebooks in a
new conda environment using the following commands:

```bash
$ git clone https://github.com/benbovy/ipytone-examples
$ cd ipytone-examples
$ conda env create -n ipytone-demo -f environment.yml
$ conda activate ipytone-demo
```

Note: you could use [mamba](https://github.com/mamba-org/mamba) instead of
`conda`. `mamba` is a faster alternative to `conda`.
