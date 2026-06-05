1. **Apache Up** – Indique si l’exporter peut contacter Apache (1 = OK, 0 = hors ligne).  
2. **Uptime (seconds)** – Temps écoulé depuis le dernier démarrage d’Apache. Une baisse soudaine signale un redémarrage.  
3. **Total Accesses** – Nombre total de requêtes traitées depuis le dernier restart (volume cumulé).  
4. **Total Sent (KB)** – Volume total de données envoyées (cumul).  
5. **Requests Per Second** – Taux de requêtes par seconde (trafic actuel).  
6. **Throughput (KB/s)** – Débit sortant en Ko/s (bande passante utilisée).  
7. **Avg Request Duration (ms)** – Temps moyen de traitement d’une requête (latence).  
8. **Busy Workers** – Nombre de workers (threads/processus) actuellement occupés à servir des requêtes.  
9. **Idle Slots (Scoreboard)** – Slots inactifs disponibles ; plus le nombre est bas, plus le serveur est saturé.  
10. **Total Connections** – Nombre total de connexions TCP actives à l’instant T.  
11. **Apache CPU Load** – Charge CPU utilisée par Apache (0 = inactif, 1 = 1 cœur à 100%).