# Kanji in (Vector) Space

---

[*Open*](https://gitpod.io/#https://github.com/ryancahildebrandt/radicals) *in gitpod*
[*Open*]() *in binder*

## *Purpose*

This is a little mini project looking at different embedding techniques used on kanji, partially to see what happens and partially to brush the dust off my julia lang skills. Here, I use kanji radicals and readings to construct simple embedding vectors, and overlay them with FastText semantic embeddings. This project is not intended to produce useful techniques for representing meaning in Japanese, so take the results with a grain of salt.
---

## Dataset
The dataset used for the current project was pulled from the following: 
- [Kanji](https://github.com/ryancahildebrandt/yoji) dataframe for radicals, meanings, readings, etc

---

## Outputs
- The [Pluto.jl]() notebook for the full code and clustering results
- The main interactibe [plot]() of the novel embeddings overlaid
