This repository has the codebase for my Medium article: https://levelup.gitconnected.com/how-to-integrate-elastic-apm-java-agent-with-spring-boot-7ce8388a206e
分别起terminal 运行：
` mvn spring-boot:run -Dspring-boot.run.profiles=predev`
`mvn spring-boot:run -Dspring-boot.run.profiles=dev`
`mvn spring-boot:run -Dspring-boot.run.profiles=staging`
`mvn spring-boot:run -Dspring-boot.run.profiles=prod`




另外一个参考：https://github.com/elastic/opbeans-java



