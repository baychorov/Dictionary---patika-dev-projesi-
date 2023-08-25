# Dictionary---patika-dev-projesi-
dictionary dersi için verilen alıştırmanın çözümü

from collections import defaultdict
the_dict = defaultdict(list) 
n,m = map(int,input().split()) 
for i in range(1,n +1):
 v = input() 
 the_dict[v].append(i)
for i in range(m):
  k = input() 
  if k in the_dict:
    print(*the_dict[k])
  else: print(-1)

