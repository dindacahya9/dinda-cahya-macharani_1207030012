# dinda-cahya-macharani_1207030012
from sklearn import tree
x = [[1,1,1],[1,1,2],[1,2,1],[2,1,1],[2,2,2],[1,2,3],[2,2,3],[2,3,2],[3,2,2],[3,3,3]]
y = [0,1,1,1,0,3,2,2,2,0]

clf = tree.DecisionTreeClassifier()
clf = clf.fit(x,y)

print("Logika AND Metode Decision Tree")
print("Logika = Prediksi")
print("1 1 1 =",clf.predict([[1,1,1]]))
print("1 1 2 =",clf.predict([[1,1,2]]))
print("1 2 1 =",clf.predict([[1,2,1]]))
print("2 1 1 =",clf.predict([[2,1,1]]))
print("2 2 2 =",clf.predict([[2,2,2]]))
print("1 2 3 =",clf.predict([[1,2,3]]))
print("2 2 3 =",clf.predict([[2,2,3]]))
print("2 3 2 =",clf.predict([[2,3,2]]))
print("3 2 2 =",clf.predict([[3,2,3]]))
print("3 3 3 =",clf.predict([[3,3,3]]))
