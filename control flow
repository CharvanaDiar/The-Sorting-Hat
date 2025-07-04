# ------------Question 1------------

gryffindor = 0
hufflepuff = 0
ravenclaw = 0
slytherin = 0

print('Q1) Do you lick or bite your ice cream?:')

print('  1) Lick')
print('  2) Bite')

answer=int(input('Enter answer (1,2):'))

if answer == 1:
  gryffindor = gryffindor + 1
  ravenclaw = ravenclaw + 1
if answer == 2:
  hufflepuff = hufflepuff + 1
  slytherin = slytherin + 1
else:
  print('Wrong input')

#------------Question 2------------

print('\nQ2) Can ambition and kindness truly coexist?')

print(' 1) Yes')
print(' 2) No')
print(' 3) Unsure')
print(' 4) Ask Chat')

answer = int(input('Enter answer (1-4): '))

if answer ==1:
  hufflepuff = hufflepuff + 2
elif answer ==2:
  slytherin = slytherin + 2
elif answer ==3:
  ravenclaw = ravenclaw + 2
elif answer ==4:
  gryffindor = gryffindor + 2
else:
  print('Wrong input')

#------------Question 3------------

print('\nQ3) Which of the following instruments most pleases your ear?:')
print('1) The guitar')
print('2) The drums')
print('3) The piano')
print('4) The flute')

answer = int(input('Enter answer (1-4): '))

if answer ==1:
  hufflepuff = hufflepuff + 4
elif answer ==2:
  slytherin = slytherin + 4
elif answer ==3:
  ravenclaw = ravenclaw + 4
elif answer ==4:
  gryffindor = gryffindor + 4
else:
  print('Wrong input')

print("Gryffindor: ", gryffindor)
print("Ravenclaw: ", ravenclaw)
print("Hufflepuff: ", hufflepuff)
print("Slytherin: ", slytherin)

#------------Total Points------------

if gryffindor >= ravenclaw and gryffindor >= hufflepuff and gryffindor >= slytherin:
  print('🦁 Gryffindor!')
elif ravenclaw >= hufflepuff and ravenclaw >= slytherin:
  print('🦅 Ravenclaw!')
elif hufflepuff >= slytherin:
  print('🦡 Hufflepuff!')
else:
  print('🐍 Slytherin!')
