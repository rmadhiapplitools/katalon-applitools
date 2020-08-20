# katalon-applitools 

# Add Applitools libraries


### Option1.Using Gradle

1.Add gradle.build file to your Katalon project

2.Add Applitools dependency to the gradle.build file 

```
dependencies {
  compile ('com.applitools:eyes-selenium-java3:+')
}
```
3.Open your terminal, navigate to the root of your Katalon project, run the following command
```
 gradle katalonCopyDependencies
````
Restart Katalon Studio (**Do not skip this step**)

### option2.Manually add External libraries

1.Download the eyes-selenium-java3 package jar files [eyes-selenium-java3](https://bintray.com/applitools/Java3/eyes-selenium-java3)

2.Extract the package

4.In your katalon studio Navigate to **project** > **Settings** > **External Libraries** click on **+add** and select all the jar files



#### Tip
‘Ctrl + Shift + O’ hotkeys to automatically fill in necessary import libraries in your test cases.

