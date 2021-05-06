# FAQ Aludel / Crucible

## Prenez le temps de regarder cette vidéo sur les pertes impermanentes avant de continuer

{% embed url="https://youtu.be/8XJ1MSTEuU0" %}

**Comment participer à l'Aludel / Comment minter un NFT Crucible ?** Pour participer à l'Aludel, vous devez minter un Crucible et déposer des LP tokens ⚗️ $MIST/ETH Uniswap dans celui-ci \(envisagez le comme un coffre virtuel\). Dès lors, le Crucible accumulera les récompenses issues du programme Aludel, proportionnellement au montant de jetons LP souscrits et à la durée de la souscription. Les frais exacts pour minter un Crucible et souscrire au programme dépendent des prix actuels du gaz du réseau ethereum. Vous pouvez vous attendre à un coût total d'environ 0,1-0,2 ETH.

{% hint style="warning" %}
**Information importante:** 

N'utilisez pas le navigateur Brave car il n'est actuellement pas compatible avec le processus. Votre transaction échouera et vous devrez payer les frais de transaction. 

Pour le moment, nous ne recommandons pas l'utilisation des portefeuilles matériel car beaucoup ne supportent pas, à ce jour, la signature EIP-712. Dès lors que celle-ci sera mise en place, nous pourrons l'implémenter. 

Certains utilisateurs ont signalé des problèmes avec Trustwallet. 

Nous vous déconseillons d'effectuer le processus sur un mobile.
{% endhint %}

1. Pour créer un Crucible, allez sur le site, [alchemist.farm](https://alchemist.farm/)
2. Connectez votre portefeuille MetaMask 
3. Renseignez la quantité de LP que vous souhaitez mettre dans le Crucible.
4. Appuyez sur "Mint Crucible and Subscribe LP to Aludel". Deux demandes d'approbation doivent apparaître via le pop-up MetaMask; signez-les et attendez la finalisation du processus.
5. Vous devez ensuite confirmer la transaction. Le prix doit être d'environ ~ 0,1-0,2 Eth pour la création d'un Crucible. Si vous êtes satisfait du prix du gas, appuyez sur “confirm” et attendez que la transaction soit validée.
6. Une fois la transaction validée, vous devriez voir votre nouveau Crucible dans votre onglet de jetons Erc721 sur Etherscan.

**Pourquoi ne puis-je pas voir mon ⚗️$MIST dans mon portefeuille?** Vous pouvez ajouter l'adresse du contrat **`0x88acdd2a6425c3faae4bc9650fd7e27e0bebb7ab`** pour les rendre visibles.

**Pourquoi ne puis-je pas voir mon LP dans mon portefeuille?** Vous pouvez ajouter l'adresse du contrat **`0xcd6bcca48069f8588780dfa274960f15685aee0e`** pour les rendre visibles.

**Pourquoi ne puis-je pas voir mon Crucible dans mon portefeuille?** Vous pouvez ajouter l'adresse du contrat **`0x54e0395CFB4f39beF66DBCd5bD93Cca4E9273D56`** pour rendre vos Crucible\(s\) visibles.

**Quelles sont les récompenses liées à la souscription à l'Aludel?** Les récompenses sont distribuées depuis le pool de récompenses proportionnellement au montant et à la durée de chaque abonnement. Plus votre contribution en jetons LP ⚗️ $MIST/ETH Uniswap est importante, et plus la durée de contribution est importante, plus les récompenses accumulées seront importantes. Le programme de récompenses Aludel est conçu pour récompenser les participants de longue durée. Le pool de récompenses est visible [ici](https://etherscan.io/address/0x04108d6e9a51bec5170f8fd953a156cf754ba541).

**Comment devenir “certified Alchemist” sur Discord?**

* Utilisez ce [guide](https://alchemist-docs.gitbook.io/alchemist/crucible/how-to-become-a-certified-alchemist-on-discord)
* Rejoignez Discord
* Accédez au canal “Welcome” et tapez “!join”
* Vous recevrez alors un message du bot Collab.Land
* Connectez votre portefeuille contenant vos Crucible / ⚗️$MIST
* Le bot vous enverra alors un message: “Updating roles, Please check assigned roles in Alchemist. Close bot and return to the main alchemy channel and you will now be a certified Alchemist!”
* Fermez le bot et revenez au canal principal “Alchemy” et vous serez désormais un alchimiste certifié!

**Comment puis-je réclamer les récompenses?** Vous pouvez récupérer toutes vos récompenses en appuyant sur “Claim Rewards and Unsubscribe LP”. Attention, cela réinitialise également votre multiplicateur de récompense. Vous devrez utiliser le Taichi Network pour empêcher les bots de “front-run” vos récompenses. Consultez ce [guide](comment-reclamer-des-recompenses-et-desabonner-votre-lp-de-laludel-en-utilisant-le-reseau.md).

**Le nombre de jetons LP mis dans le Crucible importe-t-il?** Plus vous mettez de jetons LP, plus vous avez fourni de liquidité, vous recevrez donc un pourcentage plus grand du pool de récompenses. Il n'y a pas de montant de LP minimum requis, mais nous vous suggérons de faire attention aux coûts de gas ethereum.

**Est-il plus avantageux d'avoir plus de Crucibles ou une souscription plus élevée dans un seul Crucible?** Il est généralement préférable d’accumuler des LP dans un seul Crucible pour minimiser les coûts en gas. Le seul cas où vous pourriez être amené à utiliser plusieurs Crucibles est la cas où vous souhaiteriez transférer ou vendre un Crucible avec une souscription active.

**Quel est l'impact de “Claim Rewards and Unsubscribe LP” sur le multiplicateur de récompenses?** Chaque fois que vous mettez des jetons LP dans le programme de récompense Aludel, celui-ci garde en mémoire la durée d'abonnement de ces jetons. L'Aludel applique un multiplicateur de récompense qui débute à 1x et augmente jusqu’à 10x après 60 jours. Lorsque vous réclamez un montant partiel, l'Aludel réclame prioritairement la souscription avec le multiplicateur le plus bas \(“First in, First Out”\).

**Puis-je voir d'une manière ou d'une autre le montant de récompenses que j'ai acquises entre-temps?** Vous pouvez voir les récompenses accumulées par votre Crucible en utilisant l’interface utilisateur [alchemist.farm](https://alchemist.farm/) et les frais Uniswap LP accumulés en utilisant [apy.vision](https://apy.vision/) ou [croco.finance](https://croco.finance/)

**Puis-je ajouter des LP à un Crucible existant?** Oui. La quantité de gas pour ajouter des LP à un Crucible existant sera beaucoup moins élévée que ce que vous avez pu initialement payer pour créer votre Crucible. Chaque événement de Souscription est indépendant. Chaque LP ajouté initialisera son propre multiplicateur.

**Est-ce que “Claim Rewards and Unsubscribe LP” supprime mon LP et mes récompenses du Crucible?** Non. Cela ne fait que réclamer les récompenses gagnées, vos LP resteront dans le Crucible jusqu'à ce que vous appuyiez sur “Withdraw Unsubscribed LP. ”

**Est-ce que “Withdraw Unsubscribed LP” détruit le Crucible?** Non, cela ne fait que le vider. Vous conservez le Crucible vide.

**Puis-je transférer le Crucible NFT vers un autre portefeuille?** Oui, la propriété du NFT \(et des jetons LP souscrits\) peut être transférée vers n'importe quel portefeuille compatible avec ERC721. Cela peut être fait via le bouton “Transfer Crucible” sur [alchemist.farm](https://alchemist.farm/)

**Si je transfère mon Crucible d'un portefeuille à un autre, cela réinitialisera-t-il le multiplicateur?** Non, tant que les récompenses ne sont pas rétirées de l'Aludel.

