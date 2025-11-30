# Base image : Amazon Corretto 17 (version alpine = léger)
FROM amazoncorretto:17-alpine

# Dossier de travail dans le conteneur
WORKDIR /app

# Environment variables for database connection
# Do not hardcode credentials; use secrets or environment files instead.

ENV SPRING_DATASOURCE_USERNAME  # Database username
ENV SPRING_DATASOURCE_PASSWORD   # Database password
ENV SPRING_DATASOURCE_URL       # Database connection URL

# Copy of jar file
COPY  target/*.jar  paymybuddy.jar


EXPOSE 8080

#command for backend start
CMD ["java", "-jar", "paymybuddy.jar"]
