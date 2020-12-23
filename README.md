## Explore Imagenet/WordNet

Tiny package to easily explore the WordNet (and subsequently, ImageNet) structure.


### Usage

```
from ewn.ewn import find_class

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

