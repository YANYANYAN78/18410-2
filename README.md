# 18410-2
排序


L = [('Bob', 75), ('Adam', 92), ('Bart', 66), ('Lisa', 88)]

def by_name(t):
    return t[0].lower()
    
def by_score(t):
    return -t[1]

L2 = sorted(L, key=by_name)
print(L2)
L3 = sorted(L, key=by_score)
print(L3)

>>> [('Adam', 92), ('Bart', 66), ('Bob', 75), ('Lisa', 88)]
>>> [('Adam', 92), ('Lisa', 88), ('Bob', 75), ('Bart', 66)]

