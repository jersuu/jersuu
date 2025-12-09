## Hi👋, Sultan!

```kotlin
data class jersuu(
    val pronouns: String = "he/him",
    val askMeAbout = listOf(
        "HTML5", "CSS3", "JavaScript",
        "SQL", "Linux", "Networking"
    )
    val toLearn = {
        "Java & Python" to "Future",
        "Swift" to "Fun"
    ) 
    (0..end).reduce { progress, day ->
        study(day)
        coding(day)
        sumUp(progress) + haveFun(day)
        }
)
