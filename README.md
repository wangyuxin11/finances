# finances

spring boot 的父级配置必需，而且maven项目群需要这个配置指定项目关系。两者不可兼容啊，只有另外封装容器了，如jetty
    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>1.5.3.RELEASE</version>
        <relativePath />
    </parent>
