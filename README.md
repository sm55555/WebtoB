# WebtoB

enviroment : window7, webtob

## How to control webtob

If you are using normal cmd, you should turn it on an administrator cmd

Turn on cmd and change directory webtob config folder

#### [backup]

~~~

http.m - >  (copy) http.m.yyyy.mm.dd
http.m.working -> http.m

~~~~

#### GUI Version [compile && restart]

~~~

wscfl -i http.m (compile)

GUI version (Recommend)
window taskmanger -> service -> webtob(right click restart)

~~~

#### cmd Version [compile && restart]

~~~

wscfl -i http.m (compile)

wsdown

wsboot

~~~

#### restore

~~~
http.m.yyyy.mm.dd - > http.m
~~~


repeat [compile && restart]


#### [check]

~~~
you have to test after deleting cookies

[chrome]

ctrl + shift + delete -> cookie delete click
~~~
