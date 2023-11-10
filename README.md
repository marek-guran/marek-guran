<h1>Hello there! 👋</h1>

<h3>👨‍🎓 I am university student who loves to code.</h3>

```kotlin
fun main() {
    val code = listOf("Kotlin", "Python", "JavaScript", "PHP", "Bash")
    val mobile = listOf("Android")
    val currentOccupation = listOf("3rd year bachelor student", "open for part-time job opportunities [remote]")
    val onGoingProjects = listOf("Bachelor work - private project")

    aboutMe(code, mobile, currentOccupation, onGoingProjects)
}

fun aboutMe(
    code: List<String>,
    mobile: List<String>,
    currentOccupation: List<String>,
    onGoingProjects: List<String>
) {
    println("Code: ${code.joinToString()}")
    println("Technologies:")
    println("   Mobile: ${mobile.joinToString()}")
    println("Current Occupation: ${currentOccupation.joinToString()}")
    println("On Going Projects: ${onGoingProjects.joinToString()}")
    println("Wish: be able to buy bug spray to spray my codes with")
}
```
<details> 
   <summary>My Github Stats</summary> 
  
    ![Metrics](/github-metrics.svg)
  
</details>
