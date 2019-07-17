# Planet Hunters and PHAD

This repository contains a notebook for interacting with the [Planet Hunters API](https://planethunters.org) and the [Planet Hunters Analysis Database](https://mast.stsci.edu/phad/) (PHAD) hosted at [MAST](https://mast.stsci.edu).

## What am I looking at here?

This notebook takes as an input a `subject_id` which is the first column on the PHAD site:

![PHAD table](https://user-images.githubusercontent.com/4483/61394343-c8eefe00-a8ba-11e9-8e14-d9b8fdec752e.png)

After executing all of the cells, you should be left with a plot a little bit like this one which shows the Planet Hunters light curve together with the consensus results from the Planet Hunters site:

![Markings](https://user-images.githubusercontent.com/4483/61394457-0e133000-a8bb-11e9-8715-f30440660377.png)

## I love this - how can I make these plots?

Great! You can run this notebook on Binder without installing any software. Just click this link → [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/arfon/phad-notebook/master?filepath=notebook.ipynb)
