---
layout: page
title:  "TI Embedding - Tungsten Film ✨"
categories: jekyll update
---
Available on: [Hugging Face 🤗](https://huggingface.co/fzbuzz/TungstenDispo-embedding-sd-v2-768) & [CivitAI](https://civitai.com/models/3447) (600+ Downloads)


![]({{ site.url }}/media/people_highqual.jpeg)
Textual Inversion Embedding on Stable Diffusion v2 trained using Cinestill 800T photographs. Meant to replicate tungsten film, somewhat achieved. Is able to create more _artistic_ style and realistic portraits than base SD v2. Bokeh, Colors, Realism, Lens Flare, and posing is improved.

The TungstenDispo embedding were trained for 1000 epochs with a gradient batch size of 50. A total of ~100 training images of tungsten photographs taken with CineStill 800T were used. The split was around 50/50 people landscapes.

![]({{ site.url }}/media/tungsten_dataset.png)


The effect isn't quite the tungsten photo effect I was going for, but creates very nice, artistic portraits of people. For some of the people, I used SoCalGuitarist's Negative FaceLift as a negative embedding. I used it on 0.3 strength, and it seems like it makes the eyes slightly less wonky. Unclear extent of effect.

![]({{ site.url }}/media/people_sample.png)

Landscapes haven't been experimented with much and are WIP.

![]({{ site.url }}/media/background_sample.png)