def guess(a, b):
  m = (a + b) // 2
  print(m)
  s = input()
  if s == "CORRECT":
    return
  elif s == "TOO_SMALL":
    a = m + 1
  else:
    b = m - 1
  guess(a, b)

T = int(input())
for i in range(T):
  a, b = map(int, input().split())
  n = int(input())
  guess(a + 1, b)
