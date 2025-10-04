<h1 align="center">👋 Wait And See - AFK</h1>
<h3 align="center">💻 Android Developer | 🎯 Problem Solver | 📱 Mobile Enthusiast</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=4000&color=0095D5&center=true&vCenter=true&width=500&lines=Sometimes+waiting...;Sometimes+coding...;Always+learning+💫" />
</p>

<p align="center">
  <a href="https://t.me/WaitAndSee_5">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
  <a href="mailto:b_banni@inbox.ru">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/L_E_L_I_K/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
</p>

---

## 🚀 About Me
<p align="left">
  <img src="https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</p>
```kotlin
object Developer {
    const val NAME = "Leonid Vorobev"
    const val PREFERRED_NAME = "Lelik"
    const val ROLE = "Android Developer"
    const val STATUS = "Sometimes AFK, always learning"
    
    val TECH_STACK = listOf(
        "Kotlin", "Java", "Android SDK",
        "Retrofit", "Room", "Coroutines", 
        "MVVM", "Clean Architecture", "Git"
    )
    
    fun isAvailable(): Boolean {
        return !isAFK()
    }
    
    fun getMotivation(): String {
        return "Turning ideas into Android apps 📱"
    }
}
