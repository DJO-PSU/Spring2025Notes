_Lab VM password:_ Behrend25!
## 1/13/2025 (lecture 1)
- New structured class 
- went over [Syllabus](Game450-Syllabus.pdf)
- Icebreaking stuff 
- [Markdown Cheat Sheet | Markdown Guide](https://www.markdownguide.org/cheat-sheet/)
- Homework: 
	- Python training course 
## 1/15/2025 (lecture 2)
 ```python
import this
#gives you a poem 

# hack for imports
from pathlib import Path 
import sys
sys.path.append(str(Path(__file__).parents[1]))
import lab01

#for loops
for i in [0,1,2,3]:
	print(1)

colors = ['red','green','blue','yellow']
for i in range (len(colors)):
	print(i,'-->',colors[i])
#0 --> red
for color in reversed (colors):
	print(color)
#red

for color in sorted(colors, key = len)
	print(color)
#strings

name = 'John'
age = 30.01
print('My name is {name} and I am {age} years old')
#My name is John and I am 30.01 years old

squared = [x**2 for x in range(10)]
# [0,1,4,9.....81]

#dict
Sample_dict = ['apple': 1, 'bannanna': 2, 'blueberry': 3]
```
