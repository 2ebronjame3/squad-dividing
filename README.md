I want to divide squad of 16 people to 4 randomally teams based on level of quality, it represented in the code as level_a,level_b,level_c and level d
who can I make the whole team be in the same parenthesis? (one person from each level)


import random
a= list(range(1,4))
b= random.randint(1,4)
level_a = ['yuval', 'moshe', 'yonatan', 'harel']
level_b = ['omer', 'oded', 'yoav', 'shahaf']
level_c = ['michael', 'tal', 'rotem', 'david']
level_d = ['yahav', 'matan', 'dan', 'dvir']
squad = [level_a,level_b,level_c,level_d]

for i in range(4):
  random.shuffle(level_a)
  random.shuffle(level_b)
  random.shuffle(level_c)
  random.shuffle(level_d)

print(level_a)
print(level_b)
print(level_c)
print(level_d)
