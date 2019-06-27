# Control Flow Lab

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit

## Question 1

What will be printed when the code below is run?  Select all that apply.

```swift
let conditionOne = !(4 < 5) || !(3 > 8)
let conditionTwo = !(!true)

if conditionOne {
 print("A")
} else if conditionTwo {
 print("B")
}

if conditionTwo {
 print("C")
}

print("D")
```

- A (PRINTED)
- B (will not be printed)
- C (PRINTED)
- D (PRINTED)

***
## Question 2

What will the code block below print?  Select all that apply:

```swift
let appInfo = (name: "myCoolApp", version: 0.4)

switch appInfo {
    case (_, 0.0..<1.0):
        print("\(appInfo.0) hasn't released yet")
    case ("myCoolApp", _):
        print("Thanks for looking at myCoolApp!")
    default:
        print("I'm not quite sure what you are looking at")
}
```

- appInfo.0 hasn't released yet (will not be printed)
- myCoolApp hasn't released yet (PRINTED)
- Thanks for looking at myCoolApp! (will not be printed)
- I'm not quite sure what you are looking at (will not be printed)
- It will give a compile-time error (will not be printed)

***
## Question 3

What will be printed to the console when the code below is run?  Select all that apply.

```swift
let x: Int = 4

switch x {
    case 0..<4:
        print("A")
    case 5..<10:
        print("B")
    case is Double:
        print("C")
    default:
        print("D")
}
```

- A
- B
- C
- D  (PRINTED)

***
## Question 4

What are the errors in the code below for the switch statement? Select all that apply.

```swift
let candyType: String = "skittles"

switch candyType {
    case "mAndM":
        print("Melts in your mouth, not in your hand")
    case "skittles":
        print("Taste the rainbow")
    case "snickers":
        print("Hungry? Grab a Snickers")
}
```

- No parentheses around the conditions (error not present)
- No opening and closing brackets in each of the cases (error not present)
- No default case in the switch statement (ERROR PRESENT)
- No print statement right outside the switch statement (error not present)

***
## Question 5

Given the current weather conditions (rain, sunny, snow), use a switch statement to print an appropriate message to the user

```swift
let currentWeather = "rain"

// enter code below


switch currentWeather {
    case "rain":
        print ("bring your umbrella")
    case "snow":
        print ("get your snow shovel")
    case "sunny":
        print ("wear sunscreen")
    default:
        print ("just another day")
}

```

***
## Question 6

Given the first name and last name of a Fellow, declare `fullName` variable and use string interpolation to concatenate the Fellow's full name and print to the console e.g The Fellow's full name is John Appleseed

```swift
let firstName = "John"
let lastName = "Appleseed"

// enter code below

var fullName = firstName + " " + lastName
print ("The Fellow's full name is \(fullName)")
```

***
