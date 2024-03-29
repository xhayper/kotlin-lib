# Kotlin-Lib

Fork of [fabric-language-kotlin](https://github.com/FabricMC/fabric-language-kotlin) to Spigot / Folia / Bungeecord / Velocity

For Kotlin version below 1.9.0, please check [kotlin-stdlib](https://www.spigotmc.org/resources/kotlin-stdlib.80808/) out!

Changes can be read [here](CHANGES.md)

## Usage

Add `kotlin-lib` to your depend on list

## Bundled libraries

`org.jetbrains.kotlin` namespace:
- **`kotlin-stdlib`** 1.9.22 [Docs](https://kotlinlang.org/docs/home.html), [API docs](https://kotlinlang.org/api/latest/jvm/stdlib/), [GitHub](https://github.com/JetBrains/kotlin)
- **`kotlin-reflect`** 1.9.22 [Docs](https://kotlinlang.org/docs/reflection.html), [API docs](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/)

`org.jetbrains.kotlinx` namespace:
- **`kotlinx-coroutines-core`** 1.8.0 [Guide](https://kotlinlang.org/docs/coroutines-guide.html), [API docs](https://kotlin.github.io/kotlinx.coroutines/), [GitHub](https://github.com/Kotlin/kotlinx.coroutines)
- **`kotlinx-coroutines-jdk8`** 1.8.0 [API docs](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-jdk8/index.html)
- **`kotlinx-serialization-core`** 1.6.2 [Guide](https://github.com/Kotlin/kotlinx.serialization/blob/master/docs/serialization-guide.md), [API docs](https://kotlin.github.io/kotlinx.serialization/kotlinx-serialization-core/index.html), [GitHub](https://github.com/Kotlin/kotlinx.serialization)
- **`kotlinx-serialization-json`** 1.6.2 [API docs](https://kotlin.github.io/kotlinx.serialization/kotlinx-serialization-json/index.html)
- **`kotlinx-serialization-cbor`** 1.6.2 [API docs](https://kotlin.github.io/kotlinx.serialization/kotlinx-serialization-cbor/index.html)
- **`atomicfu`** 0.23.2 [GitHub](https://github.com/Kotlin/kotlinx.atomicfu)
- **`kotlinx-datetime`** 0.5.0 [GitHub](https://github.com/Kotlin/kotlinx-datetime)

## Updating README

- Update the readme in `templates/README.template.md`.
- Run `./gradlew processMDTemplates`.
