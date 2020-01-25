# AndroidGuidelines

// For Java
    def dagger2_version = "2.22"
    implementation "com.google.dagger:dagger-android:$dagger2_version"
    implementation "com.google.dagger:dagger-android-support:$dagger2_version" // if you use the support libraries
    kapt "com.google.dagger:dagger-android-processor:$dagger2_version"

// For Kotlin
    implementation "com.google.dagger:dagger:$dagger2_version"
    implementation "com.google.dagger:dagger-android-support:$dagger2_version"
    kapt "com.google.dagger:dagger-compiler:$dagger2_version"
    kapt "com.google.dagger:dagger-android-processor:$dagger2_version"
