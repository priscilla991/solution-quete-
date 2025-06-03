# solution-quete-

| Élément                        | Description                              |
| ------------------------------ | ---------------------------------------- |
| `192.168.0.12`                 | Adresse IP du client                     |
| `- -`                          | Identifiants utilisateur (souvent vides) |
| `[03/Jun/2025:22:59:29 +0200]` | Date et heure de la requête              |
| `"GET / HTTP/1.1"`             | Méthode HTTP, ressource, version         |
| `200`                          | Code de réponse (succès)                 |
| `3460`                         | Taille de la réponse en octets           |
| `"-"`                          | Référent HTTP                            |
| `"Mozilla/5.0 ..."`            | Navigateur ou client utilisé             |

**Conclusion**   

Le serveur Apache fonctionne correctement    

Les accès sont bien enregistrés dans les logs  

Les commandes grep et awk permettent une analyse rapide  

Il est possible d’identifier les erreurs et les utilisateurs les plus actifs  
