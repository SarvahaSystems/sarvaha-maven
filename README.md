# SarvahaSystems Maven Repository

Public Maven repository for SarvahaSystems internal libraries.

## Available Libraries

| Library | Latest Version | Description |
|---------|---------------|-------------|
| `rate-limiter-core` | 1.0.0 | Core distributed rate limiting library (plain Java) |
| `rate-limiter-spring-boot-starter` | 1.0.0 | Spring Boot starter for distributed rate limiting |

## Usage

Add this repository to your `pom.xml`:

```xml
<repositories>
    <repository>
        <id>sarvaha-maven</id>
        <url>https://raw.githubusercontent.com/SarvahaSystems/maven-repo/main</url>
    </repository>
</repositories>
```

Then add the dependency:

```xml
<!-- For Spring Boot projects -->
<dependency>
    <groupId>com.ratelimiter</groupId>
    <artifactId>rate-limiter-spring-boot-starter</artifactId>
    <version>1.0.0</version>
</dependency>

<!-- For plain Java projects -->
<dependency>
    <groupId>com.ratelimiter</groupId>
    <artifactId>rate-limiter-core</artifactId>
    <version>1.0.0</version>
</dependency>
```

No authentication required.

## Documentation

See the [distributed-rate-limiter](https://github.com/SarvahaSystems/distributed-rate-limiter) repository for full documentation.
