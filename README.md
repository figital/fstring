# fstring

"find string" 

Make searching for text strings easier on Linux.

The following example will search the current directory (and below) for the string "hello".

`fstring ./ hello`

![](http://farm7.static.flickr.com/6147/5940191146_65b0be8a2b_m.jpg)

(thanks to @rwaldron for the pick)

**Installation**

```
wget https://raw.github.com/figital/fstring/master/fstring
sudo cp fstring /usr/local/bin
```
 **Example**
 
 The following command will find all instances of the phrase "python3" in the current directory (recursively):
 
 ```bash
 >> fstring ./ python3
 ./groups.py:#!/usr/bin/env python3
./next.py:#!/usr/bin/env python3
./getusers.py:#!/usr/bin/env python3
