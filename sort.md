#### sorting

* Python
```
sorted([5, 2, 3, 1, 4])
# or
a = [5, 2, 3, 1, 4]
a.sort()
#
# For more complicated cases:
# https://wiki.python.org/moin/HowTo/Sorting
sorted("This is a test string from Andrew".split(), key=str.lower)
student_tuples = [
        ('john', 'A', 15),
        ('jane', 'B', 12),
        ('dave', 'B', 10),
]
sorted(student_tuples, key=lambda student: student[2])   # sort by age
```

* Javascript
```
var a=[1, 3, 2, 4]
a.sort();
console.log(a);
a.sort(function(a, b){
	return b - a;
})
console.log(a)
```

* Golang
```
// import "sort"
a := []int{1, 3, 2}
sort.Ints(a)
```