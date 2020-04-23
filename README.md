# Quarkus Ngrok Extension

[![Maven Central](https://img.shields.io/maven-central/v/com.github.quarkus-extension/ngrok?color=green)](https://search.maven.org/artifact/com.github.quarkus-extension/ngrok)
![Issues](https://img.shields.io/github/issues/quarkus-extension/quarkus-ngrok-extension)



##### What is Ngrok?
Ngrok can create a http tunnel and give you a public URL with redirection to 
specified port on your local machine, which in our case will be a standard springs `http://localhost:8080` 
or whatever you set as `server.port`. For simply usage account is not needed. Tunnels created with 
free version will be available for 8 hours, so it is great tool for development and testing purposes! 
For more details you can check out their [site](https://ngrok.com/).

![](https://github.com/previousdeveloper/quarkus-ngrok-extension/raw/master/image.png)

### Dependency
- maven:

```xml
<dependency>
      <groupId>com.github.quarkus-extension</groupId>
      <artifactId>ngrok</artifactId>
      <version>0.0.1</version>
</dependency>
```
### Configuration
```xml
ngrok.enabled=true
ngrok.windowsBinaryUrl=string
ngrok.linuxBinaryUrl=string
ngrok.osxBinaryUrl=string
ngrok.binaryCustom=string
ngrok.directory=string
ngrok.http.url=string

```
