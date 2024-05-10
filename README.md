To use this is to add all of these files into a folder then "Opening a project" on Android Studio, after that running the build.gradle
After that is run and set, you will have to navitage to app/build.gradle then before the dependencies {
Add this line of code: 

task wrapper(type: Wrapper){
   gradleVersion = '7.2'
}

task prepareKotlinBuildScriptModel {

}


which will update it then reload it, then the application can be run.
