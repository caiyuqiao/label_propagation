﻿Source codes for some algorithms based Label Propagation
 ---
 
Label propagation (LP) is a graph-based algorithm for multi-label classification. I upload the program I have implemented for my study. 
I have implemented the following some algorithms.
1. __Label Propagation (LP)__
2. __Dynamic Label Propagation (DLP)__
3. __Label Propagation Through Linear Neighborhoods (LNP)__
4. __Label Propagation Using Amendable Clamping (LPAC)__
  
Libraries Used
---
- Python
  1. [numpy](http://www.numpy.org/)
  2. [scikit-learn](http://scikit-learn.org/stable/)
  3. [PuLP](http://pythonhosted.org/PuLP/)
  4. [itertools](https://docs.python.org/2/library/itertools.html)
  
Usage for LP
---
~~~
>> from lp import LabelPropagation()
>> lp = LabelPropagation()
>> lp.make_par()
>> lp.metrics_lp()
~~~

Usage for DLP
---
~~~
>> from dlp import DynamicLabelPropagation()
>> dlp = DynamicLabelPropagation()
>> dlp.make_par()
>> dlp.metrics_dlp()
~~~

Usage for LNP (I am sorry, I am revisioning a file of LNP...)
---
~~~
python lnp.py
~~~

Usage for LPAC (I am sorry, I am revisioning a file of LPAC...)
---
~~~
python lpac.py
~~~

Reference
---
 X. Zhu,
 "Semi-supervised Learning with Graphs" ,
 PhD thesis, Pittsburgh, PA, USA, 2005. AAI3179046.
 [paper](http://pages.cs.wisc.edu/~jerryzhu/pub/thesis.pdf)
 
 B. Wang and J. Tsotsos,
 Dynamic label propagation for semi-supervised multi-class multi-label classiﬁcation,
 Pattern Recognition, 52:75 – 84, 2016.
 [paper](http://pages.ucsd.edu/~ztu/publication/iccv13_dlp.pdf)
 
 F. Wang and C. Zhang,
 Label propagation through linear neighborhoods,
 ICML’06, Pittsburgh, Pennsylvania, USA, June 25-29, 2006, pages 985–992, 2006.
 [paper](http://machinelearning.wustl.edu/mlpapers/paper_files/icml2006_WangZ06.pdf)

 T.Miyazaki and Y.Sumikawa,
 Label Propagation Using Amendable Clamping, WII'2018, Tokyo, Japan, March 11, 2018.
 [paper](http://ceur-ws.org/Vol-2068/wii10.pdf)
 [slide](https://www.slideshare.net/MiyazakiTatsurou/label-propagation-using-amendable-clamping?qid=1bf1dfc9-b3ca-4d4a-ae7c-eaa89427dd78&v=&b=&from_search=1)
 
License
---

The FreeBSD Copyright for Label Propagation  
Copyright (c) 2017-present, Tatsurou Miyazaki, All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met: 

1. Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.   

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution. 

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

The views and conclusions contained in the software and documentation are those
of the authors and should not be interpreted as representing official policies, 
either expressed or implied, of the FreeBSD Project.
 
Developers
---
Implementor
 - [Tatsurou Miyazaki]
