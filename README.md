
paper - you only cache once
---------
https://arxiv.org/pdf/2405.05254

github official
-----------
https://github.com/microsoft/unilm/blob/master/YOCO/yoco/models/decoder/yoco.py![image]

![image](https://github.com/jinuk0211/yoco_-youonlycacheonce-/assets/150532431/feb6e010-eabc-4f18-a59f-432099755c81)

![image](https://github.com/jinuk0211/yoco_-youonlycacheonce-/assets/150532431/90bfe805-903c-43f7-a2d5-432e2854dcb0)

![image](https://github.com/jinuk0211/yoco_-youonlycacheonce-/assets/150532431/ad3c547f-9ccb-4fdf-8946-7ef5cadeea3b)

self 디코더
------------
cross 디코더를 위한 global kv cache 생성
![image](https://github.com/jinuk0211/yoco_-youonlycacheonce-/assets/150532431/5ccfd4d3-5d75-4663-97c7-f35f545b74cd)

cross 디코더 
--------------------
![image](https://github.com/jinuk0211/yoco_-youonlycacheonce-/assets/150532431/7625824a-7e62-4b5c-b231-c8f7327d34e1)

The Parallel Representation The gated retention is defined as:
---------------------

![image](https://github.com/jinuk0211/yoco_-youonlycacheonce-/assets/150532431/a8dd0773-fed5-4445-9f64-1454fe2de539)

chunkwise representation
---------
![image](https://github.com/jinuk0211/yoco_-youonlycacheonce-/assets/150532431/9dc1215c-30de-4233-b756-855fa9f1cc90)

