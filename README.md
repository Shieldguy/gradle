# Default Gradle Build Script

If you want to create project with gradle, then you must use build.gradle.
You just run `gradle task` then you can see below.

```------------------------------------------------------------
All tasks runnable from root project
------------------------------------------------------------

Build Setup tasks
-----------------
init - Initializes a new Gradle build. [incubating]
wrapper - Generates Gradle wrapper files. [incubating]

Help tasks
----------
components - Displays the components produced by root project 'gradle'.
dependencies - Displays all dependencies declared in root project 'gradle'.
dependencyInsight - Displays the insight into a specific dependency in root project 'gradle'.
help - Displays a help message
projects - Displays the sub-projects of root project 'gradle'.
properties - Displays the properties of root project 'gradle'.
tasks - Displays the tasks runnable from root project 'gradle'.

Template tasks
--------------
createGradlePlugin - Creates a new Gradle Plugin project in a new directory named after your project.
createGroovyClass - Creates a new Groovy class in the current project.
createGroovyProject - Creates a new Gradle Groovy project in a new directory named after your project.
createJavaClass - Creates a new Java class in the current project.
createJavaProject - Creates a new Gradle Java project in a new directory named after your project.
createScalaClass - Creates a new Scala class in the current project.
createScalaObject - Creates a new Scala object in the current project.
createScalaProject - Creates a new Gradle Scala project in a new directory named after your project.
createWebappProject - Creates a new Gradle Webapp project in a new directory named after your project.
exportAllTemplates - Exports all the default template files into the current directory.
exportGroovyTemplates - Exports the default groovy template files into the current directory.
exportJavaTemplates - Exports the default java template files into the current directory.
exportPluginTemplates - Exports the default plugin template files into the current directory.
exportScalaTemplates - Exports the default scala template files into the current directory.
exportWebappTemplates - Exports the default webapp template files into the current directory.
initGradlePlugin - Initializes a new Gradle Plugin project in the current directory.
initGroovyProject - Initializes a new Gradle Groovy project in the current directory.
initJavaProject - Initializes a new Gradle Java project in the current directory.
initScalaProject - Initializes a new Gradle Scala project in the current directory.
initWebappProject - Initializes a new Gradle Webapp project in the current directory.

To see all tasks and more detail, run with --all.```

You can choose project template task which you want to create.
Noramlly, if you want to create web application, then just run `gradle createWebappProject`. It will start the wizard for your project.
If you want to create normal java application, then just run `gradle createJavaProject'.

And also if you want to version control with the git or github, then you must manage your project resources. So, you must find out the resources that will whether synchronize or not with git server and specify it into .gitignore file.

Let's happy coding.

