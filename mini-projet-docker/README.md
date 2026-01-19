
# PayMyBuddy - Financial Transaction Application

Ce repository contient le souce code l'application PayMyBuddy.

Pour mettre en route l'ensemble du système, il suffit d'exécuter les taches suivantes:

**Cloner le repository sur votre environnement local

**builder l'image Paymybuddy dont le dockerfile est situé dans /app

**Avant de pusher les images sur le registre privé

**tagger les images avec:  docker tag paymybuddy:latest localhost:5000/paymypuddy:latest
	
**Si tout est ok vous devriez avoir l'image dans le registry
<img width="1834" height="855" alt="image" src="https://github.com/user-attachments/assets/a3779fc9-08bb-4d52-a388-33ef6806b67f" />



**lancer le conteneur registry avec le docker compose -f docker_compose_registry.yml up --build -d

**lancer le conteneur PaMybuddy et mysql avec docker compose up docker-compose.yml --build

c'est fonctionne bien 

ouvrir sur le navigateur l'adresse http://adresse_ip_environement:8081

si tout fonctionne bien, vous deviez avoir une page comme sur cette capture d'écran

<img width="1868" height="1000" alt="Capture d&#39;écran 2025-12-04 225202" src="https://github.com/user-attachments/assets/50e266ea-982c-437e-90c8-4c431a95b59f" />

Ensuite creer un compte et se connecter
<img width="1910" height="880" alt="Capture d&#39;écran 2025-12-04 225322" src="https://github.com/user-attachments/assets/8344f19b-52f0-48e3-af33-a6774f7fab46" />








