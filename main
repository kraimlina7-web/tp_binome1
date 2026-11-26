taches = []
def ajouter_tache():
    t = input("Titre de la tâche : ")
def afficher_taches():
    if len(taches) == 0:
        print("Aucune tâche enregistrée.")
    else:
        print("\n=== LISTE DES TACHES ===")
        for i, t in enumerate(taches, start=1):
            print(i, "-", t)

def rechercher_tache():
    mot = input("Mot-clé à rechercher : ")
    trouve = False

    for i, t in enumerate(taches, start=1):
        if mot.lower() in t.lower():
            print(i, "-", t)
            trouve = True

    if not trouve:
        print("Aucune tâche trouvée.")
print("Application mise à jour avec succès !")
while True:
    print("GESTION DES TACHES ")
    print("1. Ajouter une tâche")
    print("2. Afficher les tâches")
    print("3. Rechercher une tâche")
    print("0. Quitter")

    choix = input("Votre choix : ")

    if choix == "1":
        ajouter_tache()
    elif choix == "2":
        afficher_taches()
    elif choix == "3":
        rechercher_tache()
    elif choix == "0":
        print("Au revoir !")
        break
    else:
        print("Choix invalide ")
