FROM  python:3.12.3-alpine

# Executer une commande
# RUN mkdir /test

# Copier un dossier ou fichier
COPY app /python-unc

# Changer de dossier
WORKDIR /python-unc
LABEL description="Ceci est une image custom"
LABEL author.name="Boubacar Diallo"
LABEL author.email="bsdiallo07@gmail.com"

# exposer un port
EXPOSE 8080 

# Remplacer la commande de demarrage du container
CMD python -m http.server 8080

