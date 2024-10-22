# Découpage Réseaux 

Le réseau est en 172.16.1.0/24

| Découpage Asymétrique | 
| -- | -- |
| Découpage | Pôle informatique (50) | Pôle administratif (20) | Pôle Technicien (15) | Pôle développement (12) |
| Formule utilisée pour IP | (2^6) - 2 = 62 | (2^5) - 2 = 30 | (2^5) - 2 = 30 | (2^4) - 2 = 14 |
| Formule utilisée pour CIDR | 32 - 6 = 26 | 32 - 5 = 27 | 32 - 5 = 27 | 32 - 4 = 28 |
| Adresse Réseau | 172.16.1.0/26 | 172.16.1.64/27 | 172.16.1.96/27 | 172.16.1.128/28 |
| Plage d'adresse disponible Début | 172.16.1.1 | 172.16.1.65 | 172.16.1.97 | 172.16.1.129 |
| Plage d'adresse disponible Fin | Fin : 172.16.1.62 | Fin : 172.16.1.94  | Fin : 172.16.1.126  | 172.16.1.142 |
| Adresse de Broadcast | 172.16.1.63 | 172.16.1.95 | 172.16.1.127 | 172.16.1.143 |
 



| Découpage Symétrique |
| -- | -- |
| Découpage | Pôle informatique (50) | Pôle administratif (50) | Pôle Technicien (50) | Pôle développement (50) |
| Formule utilisée pour IP| (2^6) - 2 = 62 | (2^6) - 2 = 62 | (2^6) - 2 = 62 | (2^6) - 2 = 62 |
| Formule utilisée pour CIDR | 32 - 6 = 26 | 32 - 6 = 26 | 32 - 6 = 26 | 32 - 6 = 26 |
| Adresse Réseau | 172.16.1.0/26 | 172.16.1.64/26 | 172.16.127/26 | 172.16.1.190/26 | 
| Plage d'adresse disponible | Début : 172.16.1.1 ; Fin : 172.16.1.62 | Début : 172.16.1.65 ; Fin : 172.16.1.125 | Début : 172.16.1.128 ; Fin : 172.16.1.188 | Début : 172.16.1.191 ; Fin : 172.16.1.251 |
| Adresse de Broadcast | 172.16.1.63/26 | 172.16.1.126/26 | 172.16.1.189 | 172.16.1.252 |
