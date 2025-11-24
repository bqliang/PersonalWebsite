---
title: "👋 About me"
---

一个小青年，热爱 Android 开发 👨‍💻，喜欢羽毛球 🏸、Burger King 🍔、欧卡2 🎮...


因为早年长期刷机，泡 XDA、酷安等论坛，对 Android 开发产生了浓厚的兴趣，从而走上了不归的 Android 开发之路......

```kotlin
object Me : AndroidDeveloper {
    val name = "bqliang"
    var age = 25
    var location = "Guangzhou"

    val languages = mutableListOf(
        "Kotlin", 
        "Java", 
        "Python",
        "Go",
    )

    val hobbies = mutableListOf(
        "Coding",
        "Reading",
        "Cola",
    )

    fun code() {
        println("Writing Android apps...")
    }
}
```