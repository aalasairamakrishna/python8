# python8
set operations
se={1,2,3,4,5,6}
print(se)
print("add and remove values")
se.add(9)
print(se)
se.remove(1)
print(se)
se.discard(10)
print(se)
print("membership check")
print("1" in se)

#8b
print("union")
a={1,2,3,4}
b={5,6,7,9}
print("union="a.union(b))
print("intersection="a.intersection(b))
print("difference="a.difference(b))
print("symm_diff="a.symmetric_difference(b))

#remove dupilicate num
num=[1,2,3,3]
unique=set(num)
print(unique)
