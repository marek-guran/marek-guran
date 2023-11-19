<h1>Hello there! 👋</h1>

<h3>👨‍🎓 I am university student who loves to code!</h3>

```kotlin
fun main() {
    val code = listOf("Kotlin", "Python", "JavaScript", "PHP", "Bash")
    val mobileDev = listOf("Android")
    val currentOccupation = listOf("3rd year bachelor student")
    val onGoingProjects = listOf("Bachelor work - private repository for now")

    aboutMe(code, mobileDev, currentOccupation, onGoingProjects)
}

fun aboutMe(
    code: List<String>,
    mobileDev: List<String>,
    currentOccupation: List<String>,
    onGoingProjects: List<String>
) {
    println("Code: ${code.joinToString()}")
    println("Technologies:")
    println("   Mobile Development: ${mobileDev.joinToString()}")
    println("Current Occupation: ${currentOccupation.joinToString()}")
    println("On Going Projects: ${onGoingProjects.joinToString()}")
    println("Wish: be able to buy bug spray to spray my codes with")
}
```
<details> 
   <summary>My Github Stats</summary> 
  
    ![Metrics](/github-metrics.svg)
  
</details> 
