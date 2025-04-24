1. Setup a Spring Boot project with custom context;
2. Build this project into a Docker image. The `context` can be configurated in environments;
3. Deploy these web apps in K3s but with different contexts,for example, one instance with context `/foo`, one with `/bar`, but with the same domain.