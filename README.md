# JDK Error
java-version: '17'
distribution: 'adopt'

 compileOptions {
        sourceCompatibility = JavaVersion.VERSION_17
        targetCompatibility = JavaVersion.VERSION_17
    }
    kotlinOptions {
        jvmTarget = "17"
    }


# gradlew: Permission Denied
git update-index --chmod=+x gradlew
git add .
git commit -m "Changing permission of gradlew"
git push origin master
