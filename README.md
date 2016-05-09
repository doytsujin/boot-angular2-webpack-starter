# Spring Boot and Angular2 Webpack Starter (from AngularClass)
An Angular 2 starter kit using [Spring Boot](http://projects.spring.io/spring-boot/) and the [Angular2 Webpack Starter from @AngularClass](https://github.com/AngularClass/angular2-webpack-starter).

##[Spring Boot](http://projects.spring.io/spring-boot/)
A Gradle-based Spring boot project with:
- Groovy
- spring-cloud-starter-config
- spring-boot-devtools
- spring-boot-starter-security
- spring-boot-starter-web
- 2 Gradle tasks ([dev](#dev) and [prod](#prod)) to the default build.
 

### <a id="dev">Development Build</a> ###
```
./gradlew dev
```
- builds the client resources using the Angular2 webpack starter's `build:dev` task 
- puts the resources into the resources directory 
- sets the `springProfilesActive` to `development`
- calls the `bootRun` task.

### <a id="prod">Production Build</a> ###
```
./gradlew prod
```
- builds the client resources using the Angular2 webpack starter's `build:prod` task
- puts the resources into the resources directory
- sets the `springProfilesActive` to `production`
- calls the `bootRun` task.

> Note: To minimize the changes between this project and the Angular2 Webpack Starter, the default `src/main/groovy` and `src/main/resources` directories have been changed to `srv/main/groovy` and `srv/main/resources` respectively.

<a href="https://angularclass.com"><img src="https://cloud.githubusercontent.com/assets/1016365/9863770/cb0620fc-5af7-11e5-89df-d4b0b2cdfc43.png" alt="Angular Class" style="width: 150px;"></a>
##[AngularClass](https://angularclass.com)
> Learn AngularJS, Angular 2, and Modern Web Development from the best.
> Looking for corporate Angular training, want to host us, or Angular consulting? patrick@angularclass.com

# License
 [MIT](/LICENSE)