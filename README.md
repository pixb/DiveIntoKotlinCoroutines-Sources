# 《深入理解 Kotlin 协程》 源码

*本仓库为随书源码*

本书读者 QQ 群：612797230

最新动态请访问：[本书主页](https://www.bennyhuo.com/project/kotlin-coroutines.html) 查看。

本书已经在[京东](https://item.jd.com/12898592.html)、[当当](http://product.dangdang.com/28973005.html)上架，请感兴趣的小伙伴留意。

* 第一章 ~ 第六章
  * [Kotlin 协程](Kotlin)
  * [Lua 协程](Lua)
  * [JavaScript async/await](JavaScript)
  * [Python Generator](Python)
  * [Go routine](Go)

* [第七章 Android 应用](CoroutineAndroidSample)
* 第八章
  * [IO、NIO相关](Kotlin)
  * [Spring](CoroutineSpringSample)
  * [Vert.x](CoroutineVertxSample)
  * [Ktor](CoroutineKtorSample)
* 第九章
  * [Kotlin-Js](CoroutineJavaScript)
  * [Kotlin-Native](CoroutineNative)

* [1-1 同步代码](./Kotlin/src/main/kotlin/com/bennyhuo/kotlin/coroutine/ch01/Listing01.kt)
* [3-1 创建kotlin协程](./Kotlin/src/main/kotlin/com/bennyhuo/kotlin/coroutine/ch03/Listing01.kt)
* [3-2 launchCoroutine的定义](./kotlin/DiveIntoKotlinCoroutines-Sources/Kotlin/src/main/kotlin/com/bennyhuo/kotlin/coroutine/ch03/Listing02_04.kt)
* [3-3 启动带有Receiver的协程](./kotlin/DiveIntoKotlinCoroutines-Sources/Kotlin/src/main/kotlin/com/bennyhuo/kotlin/coroutine/ch03/Listing02_04.kt)
* [3-4 限制作用域的挂起函数调用](./kotlin/DiveIntoKotlinCoroutines-Sources/Kotlin/src/main/kotlin/com/bennyhuo/kotlin/coroutine/ch03/Listing02_04.kt)
* [3-5 模拟可挂起的main函数](./DiveIntoKotlinCoroutines-Sources/Kotlin/src/main/kotlin/com/bennyhuo/kotlin/coroutine/ch03/Listing05.kt)
* [3-6 runSuspend函数的定义](./DiveIntoKotlinCoroutines-Sources/Kotlin/src/main/kotlin/com/bennyhuo/kotlin/coroutine/ch03/Listing06_RunSuspend.kt)
* [3-7 挂起函数的定义](./DiveIntoKotlinCoroutines-Sources/Kotlin/src/main/kotlin/com/bennyhuo/kotlin/coroutine/ch03/Listing07.kt)
* [3-8 不会挂起的挂起函数](./DiveIntoKotlinCoroutines-Sources/Kotlin/src/main/kotlin/com/bennyhuo/kotlin/coroutine/ch03/Listing08.kt)
