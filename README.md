```kotlin
data class About(
        val name: String,
        val email: String,
        val technologies: Map<String, List<String>>,
        val interests: List<String>,
        val links: Map<String, String>
)

fun main() = print(About(
        name = "Saksham Sharma",
        email = "sakshamsh23@gmail.com",
        links = mapOf(
                "linkedIn" to "https://www.linkedin.com/in/sakshamsh/",
                "HackerRank" to "https://www.hackerrank.com/sakshamsh23",
                "Github" to "https://github.com/Sakshamoo17"),
        technologies = mapOf(
                "languages" to listOf( "Java", "Python", "C", "C++","HTML", "JavaScript", "CSS"),
                "frameworks" to listOf("Spring", "Flutter"),
                "databases" to listOf(""MySQL"),
        ),
        interests = listOf("Quantum Mechanics", "Competitive Programing", "Astrophysics")
).toString())
```
