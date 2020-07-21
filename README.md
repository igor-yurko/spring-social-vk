### Spring Social VKontakte
[![Build Status](http://fugru.com/jenkins/buildStatus/icon?job=spring-social-vkontakte)](http://fugru.com/jenkins/job/spring-social-vkontakte/)

To check out the project and build from source, do the following:

```
git clone git://github.com/vkolodrevskiy/spring-social-vkontakte.git
cd spring-social-vkontakte
./gradlew build
```

To generate Eclipse metadata (.classpath and .project files), do the following:

```
./gradlew eclipse
```

Once complete, you may then import the projects into Eclipse as usual:
 `File -> Import -> Existing projects into workspace`

To generate IDEA metadata (.iml and .ipr files), do the following:

```
./gradlew idea
```

To build the JavaDoc, do the following from within the root directory:

```
./gradlew :docs:api
```

The result will be available in `'docs/build/api'`.

For more details go to project wiki https://github.com/vkolodrevskiy/spring-social-vkontakte/wiki
