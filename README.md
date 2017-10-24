### ISSUES

#### it's a bug until update `gradle` to `4.3`
* question
```java

All of them match the consumer attributes:
  - Configuration 'debugApiElements':
      - Found com.android.build.api.attributes.BuildTypeAttr 'debug' but wasn't required.
      - Found com.android.build.gradle.internal.dependency.AndroidTypeAttr 'Aar' but wasn't required.
      - Found com.android.build.gradle.internal.dependency.VariantAttr 'debug' but wasn't required.
      - Found org.gradle.api.attributes.Usage 'java-api' but wasn't required.
  - Configuration 'debugRuntimeElements':
      - Found com.android.build.api.attributes.BuildTypeAttr 'debug' but wasn't required.
      - Found com.android.build.gradle.internal.dependency.AndroidTypeAttr 'Aar' but wasn't required.
      - Found com.android.build.gradle.internal.dependency.VariantAttr 'debug' but wasn't required.
      - Found org.gradle.api.attributes.Usage 'java-runtime' but wasn't required.
  - Configuration 'releaseApiElements':
      - Found com.android.build.api.attributes.BuildTypeAttr 'release' but wasn't required.
      - Found com.android.build.gradle.internal.dependency.AndroidTypeAttr 'Aar' but wasn't required.
      - Found com.android.build.gradle.internal.dependency.VariantAttr 'release' but wasn't required.
      - Found org.gradle.api.attributes.Usage 'java-api' but wasn't required.
  - Configuration 'releaseRuntimeElements':
      - Found com.android.build.api.attributes.BuildTypeAttr 'release' but wasn't required.
      - Found com.android.build.gradle.internal.dependency.AndroidTypeAttr 'Aar' but wasn't required.
      - Found com.android.build.gradle.internal.dependency.VariantAttr 'release' but wasn't required.
      - Found org.gradle.api.attributes.Usage 'java-runtime' but wasn't required.

```
* solution

[Android Studio 3.0 Compile Issue (Cannot choose between Configurations)](https://stackoverflow.com/questions/45679847/android-studio-3-0-compile-issue-cannot-choose-between-configurations)

