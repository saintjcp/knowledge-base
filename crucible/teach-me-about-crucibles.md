# Bana Crucible'ları öğret

## Crucible nedir?

Katılım sağlayarak elde ettiğiniz LP'yi temsil eden bir NFT'dir. Bir tane oluşturma eylemine "minting" denir.

Bir Crucible, Aludel'e LP katılımı yaptığında, sahibi ⚗️ ve ETH kazanır. Mevcut toplam ödül, her 14 günde bir meydana gelen %1'lik enflasyon ve ilk Balancer havuzu sırasında toplanan ETH'nin karşılığı olan ⚗️'in %50'sidir. Katılım sağlayan LP'ye sahip crucible, katılım sağlamış LP'nin katılım sağlamış toplam LP'nin oranına ve LP'lerinin diğer LP'lere göre katılım sağlama süresinin uzunluğuna bağlı olarak toplam ödüllerin bir kısmını alır.

### NFT nedir?

Non-Fungible Token anlamına gelir. Bu kavram sizin için anlaşılmazsa, "non-fungible" kavramını "eşsiz" anlamında düşünebilirsiniz.

NFT'ler, coinlerin doğrudan zıttıdır:

* Coinler: 1⚗️'e 1⚗️, eşdeğer ve kullanıma sahiptirler
* NFT'ler: 1 Crucible NFT, başka bir 1 Crucible NFT değildir ve herhangi iki Crucible'ın eşdeğere sahip olma olasılığı çok düşüktür.

Bu anlaşılması gereken önemli bir noktadır, çünkü insanlar Crucibleları OpenSea gibi platformlarda [satışa sunmaya](https://opensea.io/assets/0x54e0395cfb4f39bef66dbcd5bd93cca4e9273d56/620479970925497750675476517677400441094103376596) çoktan başladılar.

Açıklık getirmek adına: Bir Crucible oluşturursanız, Uniswap-V2 likidite havuzunda da ⚗️ tutarsınız. Potansiyel olarak kazanmanın 3 yolunu da etkin bir şekilde kullanıyorsunuz.

## Bir Crucible nasıl oluştururum?

Başlangıçta tek yöntem resmi CLI aracını kullanmaktı. Neyse ki, topluluk üyeleri o zamandan beri süreci çok daha kolay hale getiren web uygulamaları yarattılar. CLI aracını kullanırken fazladan hata yapma riski nedeniyle, artık bu yaklaşımı benimsemeniz önerilmez.

Bir Crucible oluşturmak için lütfen aşağıdaki kılavuzu kullanın:

* [crucible.alchemist.wtf üzerinden Crucible oluşturmak](guides-crucible.alchemist.wtf/)

## Crucible'ı değerli yapan nedir? 

Bir Crucible'ın değerini belirlemek zordur. Crucible'ın NFT doğası, potansiyel olarak onun anlık değerinin ötesinde spekülatif bir değere sahip olmasını sağlayabilir, ancak bazı Crucible'lar diğerlerinden daha özel kabul edilebilir.

Bununla birlikte, spekülasyon bir yana, bildiğimiz şey, içinde hemen ölçülebilir bir değere sahip olan bazı değişken miktarda LP tokenleri olan bir Crucible'ın oluşturulduğudur.

En azından, LP içeriklerinin katılımını iptal etmek ve itibari para biriminize geri dönüş yapmak için alacağınız tokenlara dayanarak bir crucible'a değer verebilirsiniz.

Bir Crucible içeriğini kontrol etme yöntemleri için aşağıdaki [bu bölüme](teach-me-about-crucibles.md#how-can-i-check-how-many-lp-tokens-someone-elses-crucible-is-worth) bakın.

## Bir Crucible oluşturmalı mısınız? 

Buna sen karar vereceksin. Neyin kazanabileceğini, neyi kaybedebileceğinizi anladığınızdan emin olun ve ardından bunun sizin için iyi bir seçim olup olmadığına karar verin.

#### Oluşturmanın maliyeti

Ethereum tabanlı tokenlar ve sözleşmelerle uğraşırken, hemen hemen her aşamada gaz ücretleriyle karşılaşacaksınız.

Gaz fiyatları sürekli dalgalıdır ve bu, ne kadar gaz ödemeniz beklendiğinde önemli bir rol oynamaktadır, bu nedenle bir şey söylemek oldukça zordur.

Bununla birlikte, bir crucible oluşturmak için bir işlem göndermek üzereyken LP jetonlarınızın değerini gaz maliyetine karşı hesaba katmanız gerektiğini söyleyebiliriz.

#### Araçlar

Kılavuzlarımız, tercih ettiğimiz cüzdan ![](../.gitbook/assets/metamask-fox.svg)MetaMask'a dayanıyor. Diğer cüzdanların kullanımıyla ilgili tavsiyeye ihtiyacınız varsa, [discord](http://discord.alchemist.wtf) kanalımıza katılın. Topluluk cevap vermekten mutluluk duyacaktır.

{% hint style="warning" %}
MetaMask, token [adreslerini uygulamaya ekleyene](faq.md#why-cant-i-see-my-mist-in-my-wallet) kadar Crucible jetonlarınızı tanımayacak veya görüntülemeyecektir.
{% endhint %}

## Crucible'ımı saklamak için hangi cüzdanları kullanabilirim?

Crucible'lar ERC-721 tokenlerdir ve bu işlemler tüm Cüzdan Uygulamaları tarafından desteklenmez. 

Lütfen [cüzdan uyumluluk kılavuzuna](wallet-compatibility.md) bakın.

## Crucible oluşturmak için ne kadar LP jetonuna ihtiyacım var?

Topluluk üyeleri, 0.1 LP token kadar düşük bir miktarla Crucible'ı başarıyla oluşturdu.

Tabii ki, bir Crucible belli bir komisyona ücretine mal oluyor, bu yüzden lütfen minimum LP ile oluştururken bu maliyeti dikkate alın.

Unutmayın, Aludel'de yatırdığınız toplam LP'deki LP payınızla orantılı olarak ödül kazanıyorsunuz.

## Birden fazla Crucible oluşturabilir miyim?

Evet. Topluluktaki birçok kullanıcı zaten birden fazla Crucible oluşturmuştur.

Bunun yararlı olup olmadığına karar vermek size kalmış.

## Başka birinin Crucible'ının ne kadar LP token değerinde olduğunu nasıl kontrol edebilirim?

Crucible'ın token ID'sini alabilir, eğer ondalık\(decimal\) ise onaltılık tabana\(hexadecimal\) dönüştürebilir ve ardından [etherscan.io](https://etherscan.io)'da adresi arayabilirsiniz.

Bu, Crucible'da içeriğin ne olduğunu ve gerçekleşen işlemlerin geçmişini gösterecektir.

Bunun için gösterilen herhangi bir token göremiyorsanız, büyük olasılıkla boştur.

## Tokenlarımı ![](../.gitbook/assets/metamask-fox.svg)MetaMask'ta nasıl görebilirim ?

Tokenı görebilmek için cüzdanınıza eklemeniz gereken adreslerle ilgili [SSS](faq.md#why-cant-i-see-my-mist-in-my-wallet)[ ](faq.md#why-cant-i-see-my-mist-in-my-wallet)bölümümüze bakın.

\*\*\*\*

