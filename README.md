# Streamlitbot

## Groupe:
    * ADJALLA Mylena
    * GNAMBLOHOU Audrey

## Les commandes à suivres pour récupérer le code sur un pc et comment l'exécuter

## 1ère étape :
 
Vérifiez que git est correctement installé sur votre ordinateur avec la commande suivante
  
  git --version

Si git n'est pas installé sur votre ordinateur, vous pouvez vous référez au cours sur la partie git https://github.com/atifrani/mgt_opl_env_dev/blob/main/GIT.md.

## 2eme étape :
Lancez un terminal et exécutez la commande ci dessous :
    git clone https://github.com/MyleADJ/Streamlitbot.git

## 3eme étape:

Verifiez que Python est correctement installé sur votre ordinateur, si ce n'est pas le cas vous pouvez suivre la documentation suivante pour installer Python. https://github.com/atifrani/mgt_opl_env_dev/blob/main/STREAMLIT.md

## 4eme étape :

Exécutez cette commande pour verifiez l'installation:

    python --version

    ou 

    python3 --version

## 5eme étape :


Vérifiez que pip est installé correctement en utilisant les commandes suivantes.

    pip --version

    ou

    pip3 --version

## 6eme étape :

Pour créer un nouvel environnement virtuel avec Python placez vous à l'intérieur du projet avec la commande :

    cd streamlitbot

Ensuite exécutez la commande suivante pour créer un environnement virtuel:

    python -m venv stenv

    ou 

    python3 -m venv stenv

## 7eme étape :
Pour utiliser un environnement python que nous venons de créer et qui s'appelle stenv, entrez ce qui suit dans la ligne de commande :

    source stenv/bin/activate 

    ou 

    source stenv/Scripts/activate 

## 8eme étape : Installation des bibliothèques python:

Lancez la commande :
    pip install -r requirements.txt

## 9eme etape:

Pour exécuter les chatbots, lancez les commandes :

    streamlit run chatbot.py

    ou 

    streamlit run chatbotgpt.py