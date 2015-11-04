# HAMR 2015: DeepDreamEffect

## Author

* Christian Dittmar
* Stefan Balke

## Description

I used Google's DeepDream processing as an audio effect. Therefore, I export music magnitude spectrogram as RGB channels of PNG images and apply so-called 'Gradient Ascent' with pre-trained networks to these images. Afterwards, I convert the resulting images to spectrograms again and resynthesize them using Griffin and Lim's method.

More information and further demos can be found here:
http://labrosa.ee.columbia.edu/hamr_ismir2015/proceedings/doku.php?id=deepdreameffect


## Installation

You need to have a running version of caffe (http://caffe.berkeleyvision.org) on your machine
There are hundreds of tutorials describing how to install it (it takes some time...).
Anyhow, the notebook with an example is best viewed here:
http://nbviewer.ipython.org/github/stefan-balke/deepdreameffect/blob/master/dream.ipynb

## Music Copyright

The used music is copyright free to our best knowledge.
However, we want to thank the creator. If any legal problems occur, please contact us.
