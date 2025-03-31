# Kanji in (Vector) Space

---

[![Open in gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ryancahildebrandt/radicals)  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ryancahildebrandt/radicals/HEAD)  
[![This project contains 0% LLM-generated content](https://brainmade.org/88x31-dark.png)](https://brainmade.org/)

## *Purpose*
This is a little mini project looking at different embedding techniques used on kanji, partially to see what happens and partially to brush the dust off my julia lang skills. Here, I use kanji radicals and readings to construct simple embedding vectors, and overlay them with FastText semantic embeddings. This project is not intended to produce useful techniques for representing meaning in Japanese, so take the results with a grain of salt.

---

## Dataset
The dataset used for the current project was pulled from the following:
- [Kanji](https://github.com/ryancahildebrandt/yoji/blob/master/outputs/kj_df.csv) dataframe for radicals, meanings, readings, etc

---

## Outputs
- The [Pluto.jl](https://github.com/ryancahildebrandt/radicals/blob/master/radicals_pl.jl) notebook for the full code and clustering results
- The main interactive [plot](https://github.com/ryancahildebrandt/radicals/blob/master/plot.html) of the novel embeddings overlaid
