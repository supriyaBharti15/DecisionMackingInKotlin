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
```kotlin
 private fun whenLoopTest(grade: Int) {
        when {
            grade in 80..100 -> println("Grade A")
            grade in 50..79 -> println("Grade B")
            grade in 30..49 -> println("Grade C")
            else -> println("FAIL")
        }
    }
```
```kotlin
 private fun whenLoopTest(GPA: Int) {
        val result: Boolean = when (GPA) {
            4 -> true
            else -> false
        }
        println(result)
    }
```
## ####################################################################
## Simple for loop
```kotlin
 private fun simpleLoop(){
       for( i:Int in 1..10)
           println("Number is :: $i")
       //Output : 1,2,3,4,5,6,7,8,9,10
   }
```
//print Odd no in range 1 to 10
```kotlin
private fun simpleLoop(){
       for( i:Int in 1..10 step 2)
           println("Number is :: $i")
       //Output : 1,3,,5,7,9
   }
   ```
   //print even number
   ```kotlin
   private fun simpleLoop(){
       for( i:Int in 2..10 step 2)
           println("Number is :: $i")
       //Output : 2,4,6,8,10
   }
   ```
// print number 1 to 10 in decremented order 
```kotlin
 private fun simpleLoop() {
        for (i: Int in 10 downTo 0)
            println("Numbre is : $i")
        //Output 10,9,8,7,6,5,4,3,2,1,0
    }
```
## while and do-while loop
```kotlin
 /*
    while loop to print 1 to 10
     */
    private fun simpleWhileLoop() {
        var i = 1
        while (i <= 10) {
            println(i)
            i++
        } //Output : 1,2,3,4,5,6,7,8,9,10
    }
```
## do-while loop
```kotlin
 private fun doWhileLoop() {
        var i = 1
        do {
            println("Output is : $i")
            i = i + 2
        } while (i < 10)//Output : 1,3,5,7,9
    }
```
## continue and break in kotlin
```kotlin
private fun breakContinue() {
       for (i : Int in 1..10){
           if(i==6) // 6 will not print 
               continue
           println("number : $i")
       } // Output  :: 1,2,3,4,5,7,8,9,10
    }
```
//break
```kotlin
 private fun breakContinue() {
       for (i : Int in 1..10){
           if(i==6) // 6 will not print
               break
           println("number : $i")
       } // Output  :: 1,2,3,4,5,
    }
```


