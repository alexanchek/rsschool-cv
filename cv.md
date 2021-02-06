# Alexander Khudyakov #

## Personal Information ##
dreamtheater@list.ru

Hello, I'm Alexander from Moscow. I'm 29 years old. 
I'm working as a it teacher at school. At the moment I learnt basic python, basic java, basic go. 
I like to learn and i'm intend to study hard.

## My skills. ##

+Python *(basic)*
+Java *(basic)*
+Go *(basic)*
+Git
+Html
+CSS. 
+Bash / linux.
+Docker

## Code Examples. ##

There is a solution of task: 
Some guy made an app for a robot. Possible commands: S - move forward, L - turn left, R - turn right.
Does a robot get back to a start position? Please, write -1 if it's so, otherwise write "yes"

```data = 'SLSRSRSRSS'
point = [0, 0]
directions = [0, 1, 2, 3]
cur_direction = 0

dx = [0, -1, 0, 1]
dy = [1, 0, -1, 0]

for i in range(len(data)):
    print('current position -', point)
    if data[i] == 'S':
        point[0] += dx[cur_direction % 4]
        point[1] += dy[cur_direction % 4]
        print('move to ', point)

    elif data[i] == 'R':
        cur_direction += 3
        cur_direction %= 4
        print(cur_direction)

    elif data[i] == 'L':
        cur_direction += 1
        cur_direction %= 4
if point == [0,0]:
    print('Вернулся')
else:
    print(-1)
```

Python allows to draw nice patterns. Me and my students do this with python like this

```
import turtle
import random

t = turtle.Pen()
colors = ["black","orange","red", "blue"]
bgColors = ["blue","red", "orange", "black"]
for x in range(100):
    # randomColor = random.randint(0, len(colors)-1)
    turtle.bgcolor(bgColors[x%len(bgColors)-1])
    t.pencolor(colors[x%len(colors)-1])
    t.forward(x)
    t.left(91)
```

## Experience ##
I didnt have exeprience, so I'm going to get it from online courses and self-study.

2011-2021
School 1995 - IT Teacher

## Education ##
Moscow State University of Sholokhov (2007-2012)

## Qualificiations ##
Machine learning for IT teachers (2020)

