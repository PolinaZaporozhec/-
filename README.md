x = float(input())
y = float(input())
if not x % 2 and not y % 2:
  print('NO')
elif x % 2 and y % 2:
  print('NO')
elif not x % 2 and y % 2:
  print('YES')
elif x % 2 and not y % 2:
  print('YES')
