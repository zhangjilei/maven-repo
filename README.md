# mvn-repo

How to use
--------

Simply add the repository to your build.gradle file:

    repositories {
        maven { url 'https://raw.githubusercontent.com/zhangjilei/mvn-repo/master/' }
        jcenter()
    }

And you can use the artifacts like this:

    dependencies {
        compile 'org.blankapp:blankapp:0.0.1-alpha@aar'
    }

Notes:

- nothing

License:
--------
The licenses are provided by the individual libary owner. This "mvn-repo" utilizes these libaries and
won´t provide any support, responsibility or licenses itself.
