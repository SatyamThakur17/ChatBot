# Android ChatBot

Built using Android Studio and Java , the app integrates the ChatGPT API to provide operational resources for chatbots. 
Users can chat in real time with the chatbot and get answers to their questions.

# Libraries Used
* OkHttp for handling HTTP requests and responses
(You can also use java.net.http package if you are using JAVA 11 or higher)
* Gson for parsing JSON data

Add these dependencies in your build.gradle
```
dependencies {
implementation 'com.squareup.okhttp3:okhttp:4.9.3'
implementation group: 'com.google.code.gson', name: 'gson', version: '2.10.1' 
}  
```
# Important Points

* Try to use Oreo or higher (SDK version 26 or higher) version of Android.
