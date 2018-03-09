#### Concatenate two arrays
* Python
```Python
[1, 2].extend([3, 4])
```

* Javascript
```Javascript
[1, 2].concat([3, 4])
```

* Golang
```Golang
append([]int{1, 2}, []int{3, 4})
```

#### Split a string
* Python
```Python
"a b c".split(" ")
```

* Javascript
```Javascript
"a b c".split(" ")
```

* Golang
```
// https://golang.org/pkg/strings/#Split
// import "strings"
strings.Split("a b c", " ")
```

#### Join a slice of string into a string

* Python
```Python
" ".join(["a", "b", "c"])
```

* Javascript
```Javascript
["a", "b", "c"].join(" ");
```

* Golang
```Golang
// https://golang.org/pkg/strings/#Join
// import "strings"
strings.Join([]string{"a", "b", "c"}, " ")
```