# HASH CRACKER TP4

## Description

Projet Python utilisant SHA-256 et une attaque par dictionnaire.

Le programme :
- génère des hashes ;
- compare les empreintes ;
- tente de retrouver un mot de passe.

---

# Fonctionnement

Le script :
1. Lit les mots du dictionnaire ;
2. Génère leur hash SHA-256 ;
3. Compare avec le hash cible ;
4. Affiche le mot trouvé.

---

# Fichiers

| Fichier | Description |
|---|---|
| cracker.py | Script principal |
| dico.txt | Dictionnaire de mots |
| README.md | Documentation |

---

# Exécution

python3 cracker.py

---

# Pourquoi utiliser SHA-256 plutôt que MD5 ?

SHA-256 est plus sécurisé que MD5.

MD5 :
- ancien ;
- vulnérable aux collisions ;
- cassé en cybersécurité moderne.

SHA-256 :
- plus robuste ;
- plus difficile à casser ;
- utilisé dans HTTPS, blockchain et sécurité moderne.

---

# Exemple de hash SHA-256

:contentReference[oaicite:0]{index=0}

---

# Auteur

LUNAISON
