# 1. Escolhe uma imagem base com Java 21
FROM eclipse-temurin:21-jdk

# 2. Define o diretório de trabalho dentro do container
WORKDIR /app

# 3. Copia o JAR gerado pelo Maven para dentro do container
COPY target/api-gateway-*.jar app.jar

# 4. Define o comando de inicialização
ENTRYPOINT ["java", "-jar", "app.jar"]