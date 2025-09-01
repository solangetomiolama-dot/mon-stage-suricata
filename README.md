# Mes Règles et Scripts pour Suricata

Ce dossier contient mon travail sur Suricata réalisé pendant mon stage.

## 📁 Que contient ce projet ?

*   Le dossier `rules` a mes règles personnalisées.
*   Le dossier `scripts` a mes scripts pour les différentes règles.

## 🚀 Comment installer ?

1.  Copiez les fichiers .rules dans le dossier de Suricata :
    ```bash
    sudo cp rules/*.rules /etc/suricata/rules/
    ```
2.  Redémarrez Suricata :
    ```bash
    sudo systemctl restart suricata
    ```

Réalisé par Solange TOMI durant mon stage à FINANACIAL HOUSE SA en 2024.