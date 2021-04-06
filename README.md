# demo-spring-boot-bug-4.2.2
https://github.com/spring-projects/spring-boot/issues/25885

# Run with

```sh
$ ./mvnw spring-boot:run
```

# Using 2.4.4 process never ends

```
	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>2.4.4</version>
		<relativePath /> <!-- lookup parent from repository -->
	</parent>
```

# Using 2.4.0 process finished ok

```
	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>2.4.0</version>
		<relativePath /> <!-- lookup parent from repository -->
	</parent>
```