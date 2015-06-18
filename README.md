# Default Gradle Build Script

If you want to create project with gradle, then you must use build.gradle.
You just run `gradle task` then you can see below.

> ------------------------------------------------------------
> All tasks runnable from root project
> ------------------------------------------------------------
>
> Build Setup tasks
> -----------------
> **init** - _Initializes a new Gradle build. [incubating]_  
> **wrapper** - _Generates Gradle wrapper files. [incubating]_
>
> Help tasks
> ----------
> **components** - _Displays the components produced by root project 'gradle'._  
> **dependencies** - _Displays all dependencies declared in root project 'gradle'._  
> **dependencyInsight** - _Displays the insight into a specific dependency in root project 'gradle'._  
> **help** - _Displays a help message_  
> **projects** - _Displays the sub-projects of root project 'gradle'._  
> **properties** - _Displays the properties of root project 'gradle'._  
> **tasks** - _Displays the tasks runnable from root project 'gradle'._  
>
> Template tasks
> --------------
> **createGradlePlugin** - _Creates a new Gradle Plugin project in a new directory named after your project._  
> **createGroovyClass** - _Creates a new Groovy class in the current project._  
> **createGroovyProject** - _Creates a new Gradle Groovy project in a new directory named after your project._  
> **createJavaClass** - _Creates a new Java class in the current project._  
> **createJavaProject** - _Creates a new Gradle Java project in a new directory named after your project._  
> **createScalaClass** - _Creates a new Scala class in the current project._  
> **createScalaObject** - _Creates a new Scala object in the current project._  
> **createScalaProject** - _Creates a new Gradle Scala project in a new directory named after your project._  
> **createWebappProject** - _Creates a new Gradle Webapp project in a new directory named after your project._  
> **exportAllTemplates** - _Exports all the default template files into the current directory._  
> **exportGroovyTemplates** - _Exports the default groovy template files into the current directory._  
> **exportJavaTemplates** - _Exports the default java template files into the current directory._  
> **exportPluginTemplates** - _Exports the default plugin template files into the current directory._  
> **exportScalaTemplates** - _Exports the default scala template files into the current directory._  
> **exportWebappTemplates** - _Exports the default webapp template files into the current directory._  
> **initGradlePlugin** - _Initializes a new Gradle Plugin project in the current directory._  
> **initGroovyProject** - _Initializes a new Gradle Groovy project in the current directory._  
> **initJavaProject** - _Initializes a new Gradle Java project in the current directory._  
> **initScalaProject** - _Initializes a new Gradle Scala project in the current directory._  
> **initWebappProject** - _Initializes a new Gradle Webapp project in the current directory._  
>
> To see all tasks and more detail, run with --all.

You can choose project template task which you want to create.
Normally, if you want to create web application, then just run `gradle createWebappProject`. It will start the wizard for your project.
If you want to create normal java application, then just run `gradle createJavaProject`.

And also if you want to version control with the git or github, then you must manage your project resources. So, you must find out the resources that will whether synchronize or not with git server and specify it into .gitignore file.

Let's happy coding.
