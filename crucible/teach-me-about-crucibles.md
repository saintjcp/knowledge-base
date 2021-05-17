# Dites m'en plus sur les Crucibles

## Qu'est-ce qu'un Crucible ?

Il s'agit d'un NFT représentant le LP que vous avez souscrit. L'acte de sa création est appelé "minting".

Lorsqu'un Crucible a un LP souscrit à l'Aludel le détenteur gagne des ⚗️ et des ETH. Le nombre de récompenses disponibles représente 50% des ⚗️ créés par l'inflation de 1% qui a lieu tous les 14 jours, et par les ETH levés durant la pool initiale Balancer. Les Crucibles avec des LP souscrits reçoivent un fraction du total des récompenses basée sur la fraction que représente leur LP souscrit par rapport au total de LP souscrits, et sur la durée durant laquelle leur LP a été souscrit par rapport aux autres LP.

### Qu'est ce qu'un NFT ?

Cela signifie Token Non-Fongible \(Non-Fungible Token\). Si ce mot est trop obscur pour vous, vous pouvez considérer que "Non-Fongible" signifie "unique".

Les NFT sont à l'opposé des coins :

* Coins : 1⚗️ est 1⚗️, ils sont équivalent en valeur et en usage
* NFTs: 1 Crucible NFT n'est pas un autre 1 Crucible NFT et il est très improbable que deux Crucibles aient une valeur équivalente.

C'est un point important à comprendre, car des personnes ont [déjà commencé à mettre en vente](https://opensea.io/assets/0x54e0395cfb4f39bef66dbcd5bd93cca4e9273d56/620479970925497750675476517677400441094103376596) leurs Crucibles sur des plateformes telles que OpenSea.

Il convient de mentionner par souci de clarté que si vous mintez un Crucible, vous stakez également du ⚗️ dans la pool de liquidité Uniswap-V2. Vous vous engagez efficacement dans les 3 façons de gagner potentiellement de l'argent.

## Comment minter un Crucible ?

Initialement, la seule méthode était de se familiariser avec l'outil officiel CLI. Heureusement, des membres de la communauté ont depuis créé des web-apps qui permettent de rendre le processus beaucoup plus simple. En raison du risque accru de faire des erreurs en utilisant l'outil CLI, il n'est plus recommandé d'adopter cette approche.

Veuillez utiliser le guide suivant pour minter un Crucible:

* [Minter un Crucible sur crucible.alchemist.wtf](guides-crucible.alchemist.wtf/)

## Que vaut un Crucible ?

La valeur d'un Crucible est difficile à déterminer. La nature NFT du Crucible pourrait potentiellement lui donner une valeur spéculative au-delà de sa valeur immédiate, mais certains Crucibles peuvent être considérés comme plus spéciaux que d'autres.

Cependant, mise à part la spéculation, ce que nous savons c'est qu'un Crucible est créé avec un montant variable de token LP à l'intérieur, ce qui lui donne une valeur mesurable immédiate.

A minima, vous pouvez évaluer la valeur d'un Crucible sur la base de ce que vous recevriez en retour du désengagement de son contenu en LP suivi de l'échange de ce dernier contre votre monnaie fiat.

Se référer à [la section](teach-me-about-crucibles.md#how-can-i-check-how-many-lp-tokens-someone-elses-crucible-is-worth) ci-dessous pour les méthodes de vérifications du contenu d'un Crucible.

## Devriez-vous minter un Crucible?

C'est à vous de décider. Assurez vous de comprendre ce que vous avez à y gagner ou à y perdre, puis peser le pour et le contre pour faire votre choix.

#### Le coût du minting

Quand vous avez affaire à des tokens et des contrats basés sur Ethereum vous êtes confrontés à des frais de gas à presque toutes les étapes.

Les prix du gas fluctuent en permanence, ce qui joue un rôle majeur dans le montant de gas que vous êtes censé payer, pour cette raison, nous ne pouvons pas donner d'indication.

Nous pouvons néanmoins dire que vous devrez prendre en compte la valeur de vos LP tokens vis à vis du coût en gas au moment de soumettre votre transaction pour minter un Crucible.

#### Les outils

Nos guides se sont basés sur notre wallet de prédilection, MetaMask ![](../.gitbook/assets/metamask-fox.svg). Si vous avez besoin de conseils vis à vis de l'utilisation d'autres wallets, rejoignez notre channel [discord](http://discord.alchemist.wtf) et la communauté sera heureuse de vous répondre.

{% hint style="warning" %}
MetaMask ne reconnaîtra pas ou n'affichera pas vos tokens Crucibles tant que vous n'aurez pas [ajouté les adresses des tokens](faq.md#why-cant-i-see-my-mist-in-my-wallet) à l'application. 
{% endhint %}

## Quels wallets puis-je utiliser pour stocker mon Crucible ?

Les Crucibles sont des tokens ERC-721 et les signatures de ces transactions ne sont pas supportées par toutes les applications de Wallet.

Se référer à notre [guide de compatibilité des wallets.](wallet-compatibility.md)

##  De combien de LP tokens ai-je besoin pour créer un Crucible ?

Les membre de la communauté ont minté avec succès des Crucibles allant jusqu'à 0.1 LP tokens seulement.

Bien évidemment, un Crucible a toujours un coût en gas, prenez donc en considération ce coût avant d'en créer un avec peu de LP.

Souvenez vous, vous gagnez des récompenses proportionnelles à votre part de LP par rapport au nombre total de LP stakés dans l'Aludel.

## Puis-je créer plusieurs Crucibles ?

Oui. Beaucoup d'utilisateurs dans la communauté ont déjà minté plusieurs Crucibles.

Que cela soit bénéfique ou non, c'est à vous de décider.

## Comment puis-je vérifier combien de tokens LP contient un Crucible ne m'appartenant pas ?

Vous pouvez prendre l'ID du token du Crucible, le convertir en héxadécimal \(s'il est en décimal\) puis chercher l'adresse sur [etherscan.io](https://etherscan.io).

Cela affichera ce qu'il contient ainsi que l'historiques des transactions qui ont eu lieu.

Si vous ne voyez aucun token affiché, c'est qu'il est très certainement vide.

## Comment puis-je voir mes tokens sur MetaMask ![](../.gitbook/assets/metamask-fox.svg) ?

Se référer à [notre FAQ ](faq.md#why-cant-i-see-my-mist-in-my-wallet)pour les adresses que vous devez ajouter à votre wallet pour pouvoir voir le token.

