# OOAD-WEEK10
Sequence Diagram

ภาพที่ 1


@startuml
mook -> toon: call
toon --> mook: receive
@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUBYoitFprRGjLCeoS_Fir98Jip9uG8n5NI1OY0vAuMYrEJKpB9KBYw7rBmKe2O0)


ภาพที่ 2


@startuml
me -> cake : make
cake -> cakeshop : sale
@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuSfDLT2rKqXEp4vLi5B81L9SO3PKh3WZlm0eNfoOayh5vP2QbmBK0W00)


ภาพที่ 3

@startuml
hide footbox
people -> fan: open
fan -->people: cooling
@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuSh8J4bLIClFBqdAh-0gICqlo4bLqBLJI4lCirB8BqZDumAo57HrxI1ILWh9-VavcNdfN0wfUIb0_G00)


ภาพที่ 4


@startuml
costomer -> owner: Buy musical instruments
costomer -> owner: payment
owner --> costomer:Receipt
owner --> costomer:Receive product
@enduml


![](http://www.plantuml.com/plantuml/img/TSwv3O0m44JHVAlO1cZ00KAKG0UMlO4bV6WFaBl78951E7e_c4NKirhU0K8LhPaOfndhMOWThjOncwJWTqn5b2rJKVbAc--tmJDn6l16RgD0gVtJGTYuHWiAi529uyq5)


ภาพที่ 5


@startuml
people -> switch: open
switch -> lamp: semaphore
lamp --> people:Bright
@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuIf8pI_8ILNGjLCeBiyiISwmKiWlICtZWd10mZc9kGLM2iMfkOa56Vb5gLmWle8kK0AYqygfA3CzeuJB8JKl1MWU0000)



README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
