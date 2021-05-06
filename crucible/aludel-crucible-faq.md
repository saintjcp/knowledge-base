# Aludel/Crucible FAQ

## **Molim vas da pogledate ovaj Video na Impermanent loss-u pre nego što nastavite**

{% embed url="https://youtu.be/8XJ1MSTEuU0" %}

**Kako da učestvujem u Aludel-u / Kako da kreiram \(mint\) Crucible NFT?**

Da bi učestvovao u Aludelu, moraš da kreiraš \(mintuješ\) Crucible NFT i položiš depozit u vidu ⚗️$mist/ETH Uniswap LP tokena u njega \(razmišljaj o njemu kao o virtuelnom novčaniku\). Crucible će onda da pripremi nagradu iz Aludel programa proporcionalno količini i trajanju LP tokena koji su sastavni deo pretplate. Troškovi kreiranja Crucibla i Pretplate zavise od trenutne cene Gas-a ETH, a možete da je očekujete u rasponu od 0.1-0.2 ETH.

{% hint style="warning" %}
**Važne informacije:**

**~Ne koristite Brave browser, jer nije kompatibilan sa procesom transakcije, a ako transakcija propadne možete da ostanete bez uloga.**

**~Ne preporučujemo da koristite hardware novčanik, jer za sada mnogi od njih ne podržavaju EIP-712 potpis. Kada oni to budu popravili, mi ćemo to da primenimo.**

**~Neki korisnici prijavljuju probleme sa Trustwallet-om.**

**~Ne preporučujemo da to radite na mobilnim uređajima.**
{% endhint %}

1. Za kreiranje \(mintovanje\) Crucibla idite na website, [alchemist.farm](https://alchemist.farm/)
2. Konektujte MetaMask novčanik.
3. Unesite količinu LP tokena koji želite da stavite u Crucible. 
4. Kliknite “Mint Crucible and Subscribe LP to Aludel”. Dobićete dve potvrde preko  MetaMask pop up-a, potpišite to i sačekajte na kompletiranje.
5. Sledeće što će se dogoditi je to da ćete biti pitani da potvrdite transakciju, što obično košta oko 0.1-0.2 Eth za kreiranje Crucible-a, ako ste zadovoljni cenom GAS-a, pritisnite _confirm_ i sačekajte da transakcija prođe.
6. Kada se transakcija kompletira, pojaviće se nov Crucible u vašem Erc721 tokens tab-u na Etherscan-u.

**Zašto ne mogu da vidim svoj ⚗️Mist u svom novčaniku?**

Možete da dodate contract adresu **`0x88acdd2a6425c3faae4bc9650fd7e27e0bebb7ab`** ``da biste ga učinili vidljivim.

**Zašto ne mogu da vidim svoj LP u svom novčaniku?**

Možete da dodate contract adresu **`0xcd6bcca48069f8588780dfa274960f15685aee0e`** ``da biste ga učinili vidljivim.

**Zašto ne mogu da vidim svoj Crucible u svom novčaniku?**

Možete da dodate contract adresu **`0x54e0395CFB4f39beF66DBCd5bD93Cca4E9273D56`** ``da biste učinili vidljivim vaš crucible \(ili više njih\).

**Koja je nagrada za pretplatu na Aludel?**

Nagrada se distribuira iz nagradnog fonda, proporcionalno količini i trajanju pretplate. Što više ⚗️$mist/ETH Uniswap LP tokena stavite na pretplatu i što duže stoji na računu, akumuliraće se veća nagrada. Nagradni program Aludel je dizajniran tako da nagrađuje članove na duže staze.

Nagradni fond možete da pogledate [ovde.](https://etherscan.io/address/0x04108d6e9a51bec5170f8fd953a156cf754ba541)

**Kako da postanem setifikovani Alhemičar u Discord-u?**

* Molim vas da pogledate ovaj [vodič.](https://hackmd.io/@alchemistcoin/H1qJBNwLO)
* Pridružite se Discord-u.
* Idite na Welcome channelType !join
* Dobićete poruku od Collab.Land operatera.
* Konektujte vaš novčanik, koji sadrži vaš ⚗️$mist.
* Operater će vam poslati poruku ~ Updating roles, molim vas da proverite i potpišete pravila koja važe u Alchemist-u.
* Isključite operatera i vratite se  na glavni alhemi kanal i od sada ste sertifikovani Alhemičar!

**Kako da pokupim svoje nagrade?**

Sve nagrade se prikupljaju kada se ode na "Claim Rewards and Unsubscribe LP". Budite pažljivi, to će takođe resetovati vaš nagradni multiplikator. Potrebno je da koristite Taichi mrežu kada to radite da bi ste sprecili botove da preduhitre vase nagrade. Pogledajte to u [vodiču](https://hackmd.io/@alchemistcoin/Hye-_bjUd).

**Da li je važno koliko LP tokena ide u Crucible?**

Što više LP tokena stavite, time uvećavate likvidacionu masu, a time dobijate veći nagradni procenat iz nagradnog fonda. Ne postoji minimalna količina LP tokena koju možete da stavite, ali vam savetujemo da u obzir uzmete cenu Eth GAS-a kada o tome razmišljate.

**Da li je bolje imati više Crucibla sa manjim iznosima ili staviti veći iznos na jedan Crucible?**

Gotovo uvek je bolje imati jedan Crucible sa većim iznosom, jer to smanjuje Eth Gas troškove.

Samo u situaciji kada želite da prenesete ili prodate Crucible sa aktivnom pretplatom možete da koristite višestruke Curcible.

**Kako "Claim Rewards and Unsubscribe LP" utiče na nagradni multiplikator?**

Svaki put kada stavite LP tokene u nagradni program Aludel, on prati koliko dugo su vaši tokeni u pretplati. Aludel koristi nagradni multiplikator tako što počinje sa uvećanjem 1x i povećava se 10x svakih 60 dana. Kada pokupite deo količine tokena, Aludel skine sa pretplate traženu količinu sa najmanjom multiplikacijom, po principu što je poslednje stavljeno, prvo se skida \(Last In, First Out\).

**Da li postoji način da vidim koliku nagradu sam prikupio u međuvremenu?**

Možete da pogledate prikupljenu nagradu za vaš crucible, koristeći UI na [alchemist.farm](https://alchemist.farm) i akumulirani Uniswap LP zaradu koristeći [apy.vision](https://apy.vision/) or [croco.finance](https://croco.finance/)

**Mogu li da dodam još LP tokena na postojeći Crucible?**

Da. Gas troškovi za dodavanje LP tokena na postojeći Crucible biće dosta niži nego kada mintujete početni Crucible. Svaka posebna pretplata je nezavisna od predhodnih i količina LP tokena biće multiplikovana nezavisno od drugih pretplata.

**Da li “Claim Rewards and Unsubscribe LP” briše moj LP & nagrade sa Crucible?**

Ne. On samo skida nagradu koju ste zaradili, a vaš LP ostaje u Crucible-u sve dok ne iskoristite “Withdraw Unsubscribed LP”.

**Da li “Withdraw Unsubscribed LP” briše moj Crucible?**

Ne, samo ga isprazni. Vama ostaje prazan Crucible.

**Mogu li da prebacim Crucible NFT na neki drugi novčanik?**

Da, vlasništvo nad NFT-om \(kao i pretplaćenim LP tokenima\) mogu da budu prebačeni na bilo koji ERC721 kompatibilni novčanik. To može da se uradi preko "Transfer Crucible" dugmeta na [alchemist.farm](https://alchemist.farm/)

**Ako prebacim svoj Crucible sa jednog na drugi novčanik, da li će to resetovati moj nagradni multiplikator?**

Ne, sve dok se ne povuče nagrada sa Aludela.

