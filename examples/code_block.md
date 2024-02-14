# Readme

Important aspect:

```java-policy
grant codeBase "file:${java.home}/*" {
    permission java.security.AllPermission;
};

grant codeBase "file:${java.home}/bin/lorem-ipsum.jar" {
    permission java.net.SocketPermission "*:443", "connect,resolve,listen,accept";
};
```

The code block is marked as java-policy code and
is therefore syntax highlighted.
