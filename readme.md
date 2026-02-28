Partie 1

Dans cette première partie, vous allez devoir implémenter les deux fonctions suivantes, buy et sell, pour une mini-plateforme en ligne permettant à des particuliers de vendre des objets d'occasion dont ils ne veulent plus.

sell(user_login, item_title, min_price) permet à un vendeur d’ajouter un article en vente, en indiquant le prix minimum qu'il en demande. Le rôle de cette fonction est uniquement de mémoriser les articles en vente.
buy(user_login, item_title, max_price) permet à un acheteur d’acheter un article si:
Un article avec ce titre exact est disponible à la vente;
    Le prix proposé par l'acheteur, max_price, est supérieur ou égal au prix demandé par le vendeur.
    Si ces deux conditions ne sont pas réunies, l’ordre d’achat échoue. Dans le cas contraire, l'article est vendu.
    L'implémentation demandée fonctionne uniquement en mémoire : pas de fichiers ni de base de données.

Points importants
Lors de l’évaluation, nous attacherons une importance particulière aux points suivants:

    La performance de l'algorithme, sa complexité O().
    L'absence de bugs. Il y a des scénarios non-évidents qui causeraient des bugs.
    La simplicité de la solution.
Dans le souci de vous faire gagner du temps, nous n'attacherons pas d'importance à l'élégance du code ou son architecture, au choix des noms de variables, aux commentaires.

Inutile de vérifier que les arguments des deux fonctions sont raisonnables, vous pouvez supposer que c'est fait en amont, avant que buy et sell soient appelées. Les chaînes ne sont pas vides, les prix sont positifs etc.


Parti 2

Les navigateurs internet répètent parfois les requêtes, de ce fait, les fonctions que vous avez implémentées en première partie risquent d'être appelées plusieurs fois pour une action unique de l'utilisateur, avec des effets indésirables.

Dans cette deuxième partie, vous devez imaginer une solution à ce problème et modifier le code en conséquence. La solution doit fonctionner en pratique pour des duplications réalistes, il n'est pas nécessaire qu'elle résolve des cas irréalistes. Elle doit fonctionner sur une machine dont les ressources sont suffisantes, mais pas illimitées. Vous pouvez modifier la liste d'arguments des fonctions implémentées dans la première partie si vous en avez besoin, en supposant que vous recevez des informations supplémentaires.
