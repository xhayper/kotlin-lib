# Kotlin-Lib

Fork of [fabric-language-kotlin](https://github.com/FabricMC/fabric-language-kotlin/tree/update-versions) to Spigot / Folia / Bungeecord / Velocity

Changes can be read [here](CHANGES.md)

## Usage

Add `kotlin-lib` to your depend list

## Bundled libraries

`org.jetbrains.kotlin` namespace:
- **`kotlin-stdlib`** ${KOTLIN_STDLIB_VERSION} [Docs](https://kotlinlang.org/docs/home.html), [API docs](https://kotlinlang.org/api/latest/jvm/stdlib/), [GitHub](https://github.com/JetBrains/kotlin)
- **`kotlin-reflect`** ${KOTLIN_REFLECT_VERSION} [Docs](https://kotlinlang.org/docs/reflection.html), [API docs](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/)

`org.jetbrains.kotlinx` namespace:
- **`kotlinx-coroutines-core`** ${KOTLINX_COROUTINES_CORE_VERSION} [Guide](https://kotlinlang.org/docs/coroutines-guide.html), [API docs](https://kotlin.github.io/kotlinx.coroutines/), [GitHub](https://github.com/Kotlin/kotlinx.coroutines)
- **`kotlinx-coroutines-jdk8`** ${KOTLINX_COROUTINES_CORE_VERSION} [API docs](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-jdk8/index.html)
- **`kotlinx-serialization-core`** ${KOTLINX_SERIALIZATION_CORE_JVM_VERSION} [Guide](https://github.com/Kotlin/kotlinx.serialization/blob/master/docs/serialization-guide.md), [API docs](https://kotlin.github.io/kotlinx.serialization/kotlinx-serialization-core/index.html), [GitHub](https://github.com/Kotlin/kotlinx.serialization)
- **`kotlinx-serialization-json`** ${KOTLINX_SERIALIZATION_JSON_JVM_VERSION} [API docs](https://kotlin.github.io/kotlinx.serialization/kotlinx-serialization-json/index.html)
- **`kotlinx-serialization-cbor`** ${KOTLINX_SERIALIZATION_CBOR_JVM_VERSION} [API docs](https://kotlin.github.io/kotlinx.serialization/kotlinx-serialization-cbor/index.html)
- **`atomicfu`** ${ATOMICFU_JVM_VERSION} [GitHub](https://github.com/Kotlin/kotlinx.atomicfu)
- **`kotlinx-datetime`** ${KOTLINX_DATETIME_JVM_VERSION} [GitHub](https://github.com/Kotlin/kotlinx-datetime)

## Updating README

- Update the readme in `templates/README.template.md`.
- Run `./gradlew processMDTemplates`.