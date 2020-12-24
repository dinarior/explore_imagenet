## Explore Imagenet/WordNet

Tiny package to easily explore the WordNet (and subsequently, ImageNet) structure.


### Usage

```
pip install exin
```
```
from exin.exin import find_class

find_class('n02356798')
```
=>
```
('n00015388', 'animal, animate being, beast, brute, creature, fauna'),
 ('n01466257', 'chordate'),
 ('n01471682', 'vertebrate, craniate'),
 ('n01861778', 'mammal, mammalian'),
 ('n01886756', 'placental, placental mammal, eutherian, eutherian mammal'),
 ('n02329401', 'rodent, gnawer'),
 ('n02355227', 'squirrel'),
 ('n02355477', 'tree squirrel'),
 ('n02356798', 'fox squirrel, eastern fox squirrel, Sciurus niger'),
 'fox squirrel, eastern fox squirrel, Sciurus niger']
```

This package basically turn the `structure_released.xml` of WordNet to a python dictionary (this was not made with efficiency in mind...) then given a class, say `n02356798`, returns the path from the root, with all the classes id's and descriptions. <br>

You can also access the whole dictionary by using

```
from exin.exin import whole_dict
```

And play with it as you will.


### Alternative
If you dislike installing packages, you can just play with the attached [notebook](https://github.com/dinarior/explore_imagenet/blob/main/explore_imagenet.ipynb) as well for the same functionality.
