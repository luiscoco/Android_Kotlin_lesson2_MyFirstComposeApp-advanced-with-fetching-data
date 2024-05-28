# How to fetch data from free API online

In this example I would explain you how to send a GET request to a public API endpoint from your Android Compose application to retrieve data from a server

This is the public API endpoint we are going to interrogate

https://jsonplaceholder.typicode.com/todos

## 1. Create a new Compose project in Android Studio






## 2. Project Folders and Files structure


![image](https://github.com/luiscoco/Android_Kotlin_lesson2_MyFirstComposeApp-advanced-with-fetching-data-/assets/32194879/a5eea515-a9c8-4f80-abe5-ebd1d8ea0aab)



## 3. Project Dependencies

**build.gradle.kts**(Module:app)

```
dependencies {

    implementation(libs.androidx.core.ktx)
    implementation(libs.androidx.lifecycle.runtime.ktx)
    implementation(libs.androidx.activity.compose)
    implementation(platform(libs.androidx.compose.bom))
    implementation(libs.androidx.ui)
    implementation(libs.androidx.ui.graphics)
    implementation(libs.androidx.ui.tooling.preview)
    implementation(libs.androidx.material3)
    implementation("org.jetbrains.kotlinx:kotlinx-serialization-json:1.7.0-RC")
    implementation("com.squareup.retrofit2:retrofit:2.11.0")
    implementation("com.squareup.retrofit2:converter-gson:2.11.0")
    implementation("androidx.lifecycle:lifecycle-viewmodel-compose:2.4.0")
    implementation("androidx.compose.runtime:runtime-livedata:1.2.0-alpha01")
    implementation(libs.androidx.runtime.livedata)
    testImplementation(libs.junit)
    androidTestImplementation(libs.androidx.junit)
    androidTestImplementation(libs.androidx.espresso.core)
    androidTestImplementation(platform(libs.androidx.compose.bom))
    androidTestImplementation(libs.androidx.ui.test.junit4)
    debugImplementation(libs.androidx.ui.tooling)
    debugImplementation(libs.androidx.ui.test.manifest)
}
```




## 4. Add Internet Permission 






## 5. Data Model





## 6. API Service





## 7. Data Repository





## 8. User Interface (UI) Screens





## 9. ViewModel





## 10. MainActivity



#
