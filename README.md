# Functions Exit Ticket

Fork and clone this repo. On your fork, answer and commit the follow questions. When you are finished, submit the link to your repo on Canvas.

## Question 1

```swift
func a(x, y) {
    return x + y
}

func b(integer x, integer y) -> sum: Int {
    return x + y
}

func c(x: Int, y: Int) -> Int {
    return x + y
}

func d(firstAddend x: Int, withSecondAddenend y: Int) -> Int {
    return x + y
}
```

Select which of the above functions will return the sum of two integers x and y:
- A
- B
- C
- D


## Question 2

```swift
//a)
func squareA(a: Int) -> Int {
    return a * a
}
squareA(a: 3)

//b)
func squareB(b: Int) -> Int {
    return b * b
}
print( squareB(3) )

//c)
func squareC(Int: c) -> Int {
    return c * c
}
print(squareC(Int: 3))

//d)
func squareD(d: Int) {
    print(d * d)
}
squareD(d: 3)

//e)
func squareE(e: Int) -> Int {
    return e * e
}
print(squareE(e: 3))
```

Which of the above blocks of code will print 9:
- a
- b
- c
- d
- e


## Question 3

```swift
func defaultValues(x: Int = 4, y: Int = 8, z: Int = 2) -> Int {
 return x + y + z
}

let a = defaultValues(2, z: 1)
print(a)
```

What will the code above print?
- 3
- 5
- 11
- 12
- 14
- 17
- It will give an error


## Question 4

```swift
//a
func buildADoorA(withMaterial s: String, andHeight x: Int) {
    print("I built a door with \(s) of height \(x) feet!")
}
buildADoorA(withMaterial: "wood", andHeight: 7)

//b
func buildADoorB(withMaterial s: String, andHeight x: Int) {
    print("I built a door with \(withMaterial ) of height \(andHeight) feet!")
}
buildADoorB(withMaterial: "wood", andHeight: 7)

//c
func buildADoorC(s withMaterial: String, x andHeight: Int) {
    print("I built a door with \(withMaterial ) of height \(andHeight ) feet!")
}
buildADoorC(withMaterial: "wood", andHeight: 7)

//d
func buildADoorD(s withMaterial: String, x andHeight: Int) {
    print("I built a door with \(s) of height \(x) feet!")
}
buildADoorD(withMaterial: "wood", andHeight: 7)
```

Select which of the above will print `"I built a door with wood of height 7 feet!"`:
- a
- b
- c
- d


## Question 5

```swift
func optionals(x: Int?) -> Int? {    //Line 1
    if let y = x {                   //Line 2
        return y + 3                 //Line 3
    }                                //Line 4
    return nil                       //Line 5
}                                    //Line 6

let problemOne = optionals()         //Line 7
print(problemOne)                    //Line 8
```

What will happen when the above code is run?
- It will give you an error on line 1
- It will give you an error on line 2
- It will give you an error on line 6
- It will give you an error on line 7
- It will print nil
- It will print 3


## Question 6

```swift
var myValue = 3

func myFunction(x: Int) -> Int {
    var myValue = 4
    myValue += 2
    return myValue
}

print(myValue)
```

What will happen when the code above is run?
- It will give an error because two variables can't ever have the same name
- It will print 3
- It will print 4
- It will print 6
