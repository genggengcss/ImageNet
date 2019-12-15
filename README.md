# ImageNet
ImageNet Dataset Description

### Dataset Split  
**Filtered**: removing the classes without word embedding  

|Split|Original  (index)|Filtered|
|:------:|:------:|:------:|
|**2012 1k**|1000  (1~1000)|1000|
|2011 2-hops|1549  (1001~1549)|1509|
|2011 3-hops|6311  (2550~8860)|6169|
|2011 rest|12982  (8861~21842)|12667|
|all|21842|21345|

### Dataset Category
**7 categories**: Plant, Geological, Natural, Sport, Artifact Fungus, Person, Animal

### Dataset Features
**Semantic features**: word embedding (21842x500)  
**Image features**: Resnet101 pretrained embedding (21842x2048)

### Exp1
**Seen Classes**: 249 classes (1300 images per class)  
**Unseen Classes**: 361 classes (800 images per class)

