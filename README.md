# even-fibonacci

l = []
k = []
(x, y) = (1, 2)
while x < 4000000:
    k.append(x)
    k.append(y)
    x += y
    y += x
for i in k:
    if i % 2 == 0:
        l.append(i)
print(sum(l))
