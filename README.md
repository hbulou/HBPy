# Bibliothèque python de mes fonctions : HBPy

# Installation
* choisir un répertoire où sytocker HBPy et s'y placer
* cloner HBPy
```sh
git clone git@github.com:hbulou/HBPy.git
````
* en principe un répertoire HBPy a été créé. Aller dans HBPy
```sh
cd HBPy
```
* charger l'environnement ATOMOD
```sh
source ~/venv/ATOMOD/bin/activate
```
Rq : sur les serveurs de calculs tels que hpc il peut être nécessaire de charger le module python
```sh
module load python
```
* Installer le package Molecule
```sh
pip install -e .
```
