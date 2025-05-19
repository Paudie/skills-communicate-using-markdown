# This is H1
### This is H3
###### This is H6

... and this is the rest of my index md

``` python
from collections import defaultdict
#merge two or more dicts using the collections module
def merge_dicts(*dicts):
  mdict = defaultdict(list)
  for d in dicts:
    for key in d:
      mdict[key].append(d[key])
  return dict(mdict)
```

<img src="https://upload.wikimedia.org/wikipedia/en/thumb/5/54/Leeds_United_F.C._logo.svg/800px-Leeds_United_F.C._logo.svg.png" alt="Image of lufc badge" width="200"/>

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [X] Introduce myself to the world

![Image of lufc badge](https://upload.wikimedia.org/wikipedia/en/thumb/5/54/Leeds_United_F.C._logo.svg/800px-Leeds_United_F.C._logo.svg.png)
