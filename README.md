# MARS-task-2
Aim:
to make an object counter which uses an IR sensor to count the number of passing objects and display the count on LCD Screen 
Thought proccess and Applications :
since the object detection and counting is the aim,only an ir sensor and lcd display is needed .the ir helps in object detection, the out pin of the irsensor is connected to the digital pin of aurdino .
application it is  used to detect objects  
The basic idea of code is we use prev and current varibles to keep track of the movemnet of the object .according to this code only when the object reaches right infront of the irsensor the count will increase .later the prev and current values are reset such that the coount will not increase after .the printing s done on first row 0th coloumn of the lcd display 
procedure and pin selctons :
the ir sensor is conncetd to pin 6 of aurdino and rest is conncted to 5v of aurdino and GND 
liquid crystal library I2C is installlled for the lcd display to work
the lcd display is connect to the lcd backpack module .VCC to 5V ,GND to GND of aurdino ,SDA,SCL are coonected to respective pins of the aurdino .`
resources :
https://www.youtube.com/watch?v=KMQtyRayEEs
https://www.youtube.com/watch?v=u2c5-TMQWuM
https://www.youtube.com/watch?v=EAeuxjtkumM
