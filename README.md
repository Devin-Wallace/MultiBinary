# MultiBinary
A Multi-Thread Binary search written in Python3 by Devin Wallace

## Usage
```
import MultiBinary

print(MultiBinary.binary_search(somelist, someitem))

>>>[[True, 12, 'hello']]

```

## Methods

### binary_search(somelist, someitem, t_limit=100)
 * **_somelist_** this is the list you are searching through, it is set up to handle a 1-dimensional list. 
 * **_someitem_** this is the item you are searching for within the list.
 * **_t_limit_** t_limit is the thread count limit, by default it is set to 100 threads, meaning that there will be 100 searches done simultaneously. consider your machines processing power before altering
 
 
**binary_search return**
[[True, 9, 802], [True, 44, 802]]
returns a 2D list where 
  * [0][0] = boolean if found
  * [0][1] = index in list
  * [0][2] = item searched for
  
  
  ## Testing
  
  ```
import random, MultiBinary
list = []
for i in range(random.randint(20,100)):
    list.append(random.randint(300,399))

print(MultiBinary.binary_search(list, 369))

>>>[[True, 35, 369], [True, 44, 369]]
```

## Installing
```
pip instal MultiBinary
```



## Hashes
**MultiBinary-1.0.0.tar.gz**
* SHA265: 92b8cf64d6701af578275fec82ee627a20bf4b83cfbe98dcc7e77577e0c61001

**MultiBinary-1.0.0-py3-none-any.whl**
* SHA256: 92b8cf64d6701af578275fec82ee627a20bf4b83cfbe98dcc7e77577e0c61001
