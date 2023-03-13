# multiprojgrails5
Multi project for Grails 5 

To show how to make Plugins and App inside the main project and be able to run them together (inline) 
The Official Grails.org documentation seems to be missing something for Grails 5 (and 4).  

This is a tricked version, but not too dirty. 


Based on this dicussion https://github.com/grails/grails-core/issues/11221


to run, just type:

use the wrapper included (Gradle 7.2)
./gradlew myapp:bootRun

or if you have Gradle 7.2 already in your path
gradle myapp:bootRun


