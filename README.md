# maven_release_demo
Maven Multimodule Demo / jgitflow Release 

## command to do release star/finish
```
mvn -B  jgitflow:release-start jgitflow:release-finish -X -Dmaven.test.skip=true
```

## command to do release start/finish in steps
```
mvn -B  jgitflow:release-start -X -Dmaven.test.skip=true

#do some other action

mvn -B  jgitflow:release-finish -X -Dmaven.test.skip=true
```


