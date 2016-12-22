# Gradle Scripts

this example repo is just another bunch of exmaples for gradle for java and android. fork it and learn this useful gradle basics.

## installations

I assume you have java already installed on your machine so Please follow the instructions to start with gradle scripts.
first as usual download the gradle package or zip from below link 
https://github.com/spring-guides/gs-gradle/archive/master.zip
or if you are an android developer then u already have that in this location 
C:\Program Files\Android\Android Studio\gradle\gradle-2.14.1 
or somewhere you choose to install the setup. so 
go ahead and set the environment variable first here 
Control Panel\System and Security\System - >advance system settings->environment variable->
in the system variables choose "path" and click on edit and paste the gradle install location in the end
okeh I know you guys have did this before but still i gotta tell you.
now check if gradle is installed or not 
simple type in cmd "gradle" and you will see this
________________________________________________________


E:\courses\gradle\gradle programs\hello world>gradle
:help


Welcome to Gradle 2.14.1.


To run a build, run gradle <task> ...


To see a list of available tasks, run gradle tasks


To see a list of command-line options, run gradle --help


To see more detail about a task, run gradle help --task <task>


BUILD SUCCESSFUL
______________________________________________________________
and yes now you are really good to go.

## example

To run your first program  choose your favorite editor, mine is notepad++.
create a file and paste this hello script.
_____________________________________________________________


task hello{


description "your first task"
group "hello world"
doLast{
println "this is going to be my first program"


}


}


_______________________________________________________________________
and save as build.gradle always, now open the cmd from the same directory where you have saved this build.gradle file by pressing shift+ right click and type gradle tasks
_____________________________________________________________________________


E:\courses\gradle\gradle programs\hello world>gradle tasks
:tasks


------------------------------------------------------------
All tasks runnable from root project
------------------------------------------------------------


Build Setup tasks
-----------------
init - Initializes a new Gradle build. [incubating]
wrapper - Generates Gradle wrapper files. [incubating]


Hello world tasks
-----------------
hello - your first task


Help tasks
----------
buildEnvironment - Displays all buildscript dependencies declared in root projec
t 'hello world'.
components - Displays the components produced by root project 'hello world'. [in
cubating]
dependencies - Displays all dependencies declared in root project 'hello world'.


dependencyInsight - Displays the insight into a specific dependency in root proj
ect 'hello world'.
help - Displays a help message.
model - Displays the configuration model of root project 'hello world'. [incubat
ing]
projects - Displays the sub-projects of root project 'hello world'.
properties - Displays the properties of root project 'hello world'.
tasks - Displays the tasks runnable from root project 'hello world'.


To see all tasks and more detail, run gradle tasks --all


To see more detail about a task, run gradle help --task <task>


BUILD SUCCESSFUL


Total time: 3.141 secs


______________________________________________________________________________


you can see our Hello world task group above. now lets run this by typing gradle <task name here> . 


E:\courses\gradle\gradle programs\hello world>gradle hello
:hello
this is going to be my first program


BUILD SUCCESSFUL


okeh now you have successfully completed your first script. congratulations!!!!

## Usage

fork project or clone it and start working. 

## Contributing

if there is something you would like to add, you are welcome.
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

version 1.0

## Credits

udacity: https://udacity.com
gradle : https://gradle.org
android: https://developer.android.com/index.html

## License

Openlicensing

