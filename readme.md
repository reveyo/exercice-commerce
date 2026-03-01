
  <h3>Première partie</h3>

  <p>
    Dans cette première partie, vous allez devoir implémenter les deux fonctions suivantes, <em>buy</em> et <em>sell</em>, pour une mini-plateforme en ligne permettant à des particuliers de vendre des objets d'occasion dont ils ne veulent plus.
  </p>

  <ul>
    <li><code>sell(user_login, item_title, min_price)</code> permet à un vendeur d’ajouter un article en vente, en indiquant le prix minimum qu'il en demande. Le rôle de cette fonction est uniquement de mémoriser les articles en vente.</li>
    <li><code>buy(user_login, item_title, max_price)</code> permet à un acheteur d’acheter un article si:
      <ol>
        <li>Un article avec ce titre <strong>exact</strong> est disponible à la vente;</li>
        <li>Le prix proposé par l'acheteur, <code>max_price</code>, est supérieur ou égal au prix demandé par le vendeur.
      </ol>
      Si ces deux conditions ne sont pas réunies, l’ordre d’achat échoue. Dans le cas contraire, l'article est vendu.
    </li>
  </ul>

  <p>
    L'implémentation demandée fonctionne uniquement en mémoire : pas de fichiers ni de base de données.
  </p>

  <h4>Points importants</h4>
  <p>
    Lors de l’évaluation, nous attacherons une importance particulière aux points suivants:
    <ol>
      <li>La <strong>performance de l'algorithme</strong>, sa complexité O().</li>
      <li>L'absence de bugs.  Il y a des scénarios non-évidents qui causeraient des bugs.</li>
      <li>La simplicité de la solution.</li>
    </ol>
  </p>
  <p>
  Dans le souci de vous faire gagner du temps, nous n'attacherons pas d'importance à l'élégance du code ou son architecture, au choix des noms de variables, aux commentaires.
  </p>
  <p>
    Inutile de vérifier que les arguments des deux fonctions sont raisonnables, vous pouvez supposer que c'est fait en amont, avant que <code>buy</code> et <code>sell</code> soient appelées.  Les chaînes ne sont pas vides, les prix sont positifs etc.
  </p>

  <h3>Deuxième partie</h3>

  <p>
  Les navigateurs internet répètent parfois les requêtes, de ce fait, les fonctions que vous avez implémentées en première partie risquent d'être appelées plusieurs fois pour une action unique de l'utilisateur, avec des effets indésirables.
  </p>
  <p>
 Dans cette deuxième partie, vous devez imaginer une solution à ce problème et modifier le code en conséquence.  La solution doit fonctionner en pratique pour des duplications réalistes, il n'est pas nécessaire qu'elle résolve des cas irréalistes.  Elle doit fonctionner sur une machine dont les ressources sont suffisantes, mais pas illimitées.  Vous pouvez modifier la liste d'arguments des fonctions implémentées dans la première partie si vous en avez besoin, en supposant que vous recevez des informations supplémentaires.
  </p>

  <hr>
