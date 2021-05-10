# FAQ 📖

## Por favor, antes de continuar ve este vídeo sobre la Pérdida Impermanente \(o Impermanent Loss\)

{% embed url="https://youtu.be/8XJ1MSTEuU0" %}

**¿Cómo participar en el Aludel? / ¿Cómo crear un NFT Crucible?**

Para participar en el Aludel, debes crear un NFT Crucible y depositar en ella algunos ⚗️mist/ETH Uniswap LP tokens \(piensa en esto como una caja fuerte virtual\). El Crucible acumula las recompensas del programa Aludel proporcionalmente a la cantidad y duración de los tokens LP suscritos. El coste por la creación de un Crucible y para hacer el deposito depende de los precios actuales del gas Ethereum, se puede suponer que la comisión sea aproximadamente 0,1-0,2 ETH.

{% hint style="warning" %}
**Informaciónes importantes :**

No utilice el navegador Brave, porque no es compatible con el proceso en este momento y su transacción fallará resultando en la pérdida de la comisión.

No recomendamos el uso de un hardware wallet en este momento porque muchos no soportan actualmente la firma EIP-712. Cuando solucionen esto, podremos implementarlo.

Algunos usuarios han reportado problemas con Trustwallet.

No recomendamos hacer esto en un móvil.
{% endhint %}

1. Para crear un Crucible ve la página web, [alchemist.farm](https://alchemist.farm/)
2. Conecta el wallet MetaMask
3. Introduce la cantidad de LP que deseas depositar en el Crucible.
4. Haz Clic en "Mint Crucible and Subscribe LP to Aludel". Obtendrá 2 aprobaciones a través del cuadro de dialoguo MetaMask, firma estos y espera a la finalización.
5. A continuación se te pedirá que confirmes la transacción, esto normalmente cuesta alrededor de 0,1-0,2 ETH para crear un Crucible, si estás contento con el precio del gas, pulsa confirmar y espera a que la transacción se realice.
6. Una vez completada, verás tu nuevo Crucible en tu pestaña de tokens Erc721 en Etherscan.

**Por qué no puedo ver mis ⚗️Mist en mi wallet?**

Puedes añadir la dirección del contrato **`0x88acdd2a6425c3faae4bc9650fd7e27e0bebb7ab`** para hacerlos visibles.

**¿Por qué no puedo ver mi token LP en mi wallet?**

Puedes añadir la dirección del contrato **`0xcd6bcca48069f8588780dfa274960f15685aee0e`** para hacerlos visibles.

**¿Por qué no puedo ver mi Crucible en mi wallet?**

Puedes añadir la dirección del contrato **`0x54e0395CFB4f39beF66DBCd5bD93Cca4E9273D56`** para hacer visibles tu Crucible.

**¿Cuáles son las recompensas por suscribirse a Aludel?**

Las recompensas se distribuyen de la bolsa de recompensas proporcionalmente a la cantidad y duración del deposito. Cuantos más ⚗️mist/ETH Uniswap LP tokens depositas y cuanto más tiempo lo dejes, más recompensas acumularás. El programa de recompensas de Aludel está diseñado para premiar a los participantes a largo plazo.

Puedes ver el conjunto de recompensas [aquí](https://etherscan.io/address/0x04108d6e9a51bec5170f8fd953a156cf754ba541).

**¿Cómo puedo convertirme en un Alquimista certificado en Discordia?**

* [Guía](https://alchemist-docs.gitbook.io/alchemist/crucible/how-to-become-a-certified-alchemist-on-discord)
* Únete al Discord
* Ve al canal de bienvenida y escribe !join
* Después recibirás un mensaje del bot de Collab.Land
* Conecta tu wallet con tu ⚗️$mist
* El bot te enviará un mensaje "Updating roles, Please check assigned roles in Alchemist"
* Cierra el bot y vuelve al canal principal \(alchemy\) y ya serás un Alquimista certificado.

**¿Cómo reclamo las recompensas?**

Todas las recompensas se reciben cuando pulse "Claim Rewards and Unsubscribe LP". Ten cuidado, esto también reinicia tu multiplicador de recompensas. Tendrás que usar la Red Taichi cuando hagas esto para evitar que los bots se adelanten \("front-run"\) a tus recompensas. Consulta esta [guía]().

**¿Importa cuántos tokens de LP entran en el Crucible?**

Cuantos más tokens de LP depósitas en el Crucible, mayor será la cantidad de liquidez que hayas proporcionado y, por tanto, mayor será el porcentaje de la bolsa de recompensas que recibirás. No se requiere un mínimo de LP, pero te sugerimos que tengas en cuenta el coste del gas Ethereum cuando lo considere.

**¿Es más ventajoso tener más Crucible o una mayor Suscripción en un Crucible?**

Casi siempre es mejor acumular tokens LP en un solo Crucible porque minimiza los costes de gas.

El único caso en el que se utilizarían varios Crucible es si se pretende transferir/vender un Crucible con alguna suscripción activa en él.

**¿Cómo afecta "Claim Rewards and Unsubscribe LP" al multiplicador de recompensas?**

Cada vez que pones tokens LP en el programa de recompensas de Aludel, este lleva la cuenta del tiempo que esos tokens están depositos. Aludel aplica un multiplicador de recompensa que comienza en 1x y aumenta hasta 10x en 60 días. Cuando reclamas una cantidad parcial, el Aludel reclama primero los tokens LP del depósito con el multiplicador más bajo \("Last In, First Out"\).

**¿Puedo ver de alguna manera cuántas recompensas he adquirido mientras tanto?**

Puedes ver la recompensa acumulada de tu Crucible usando la IU en [alchemist.farm](https://alchemist.farm/) y las cuotas de LP acumuladas de Uniswap usando [apy.vision](https://apy.vision/) o [https://croco.finance/](https://croco.finance/)

**¿Puedo añadir más LP a un Crucible existente?**

Sí. El gas para añadir más LP a tu Crucible actual será mucho menor que cuando creas inicialmente un Crucible. Cada evento de suscripción es independiente, por lo que cualquier token LP que depósitas iniciará su propio multiplicador de forma independiente.

**¿"Claim Rewards and Unsubscribe LP" retira los LP tokens y recompensas del Crucible?**

No. Esto sólo reclama las recompensas ganadas, tu token LP permanecerá en el Crucible hasta que "Withdraw Unsubscribed LP".

**¿"Withdraw Unsubscribed LP" destruye el Crucible?**

No, sólo lo vacía. Conservas el Crucible vacío.

**¿Puedo transferir el NFT del Crucible a otro wallet?**

Sí, la propiedad del NFT \(y los tokens LP depositado\) puede transferirse a cualquier wallet compatible con ERC721. Esto puede hacerse a través del botón "Transfer Crucible" en [alchemist.farm](https://alchemist.farm/)

**Si transfiero mi Crucible de un wallet a otro, ¿se reiniciará el multiplicador?**

No, siempre que no desabonas las recompensas del Aludel.

