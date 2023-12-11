# Readme

Important aspect:

```java-policy
grant codeBase "file:${java.home}/*" {
    permission java.security.AllPermission;
};
```
