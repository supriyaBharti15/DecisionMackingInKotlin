# DecisionMackingInKotlin
Simple IF | IF-Else | When | Nested IF | IF and When

## Simple IF
```kotlin
    private fun ifElseExample() {
        var grade = 98
       if (grade in 95..100){
           println("Grage A")
       }
    }
```
## IF-Else
```kotlin
 private fun ifElseExample(grade: Int) {
        if (grade in 95..100) {
            println("Grage A")
        } else if (grade in 60..94)
            println("Grage B")
        else if (grade in 40..59)
            println("Grade C")
        else
            println("FAIL")
    }
```
## When loop
```kotlin
private fun whenLoopTest(weekDayID: Int) {
        when (weekDayID) {
            1 -> {
                println("Sunday")
                println("Its Weekend")
            }
            2 -> {
                println("Monday")
                println("Its WeekDays")
            }
            3 -> {
                println("Tuesday")
                println("Its WeekDays")
            }
           else -> {
                println("Invalid Input")
            }
        }
    }
```

