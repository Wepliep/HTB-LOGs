# Dom Nedir?


"DOM", HTML, XML veya bir HTML dökümanına erişim için kullanılan programlama arabirimlerini (API'lerini) temsil eden bir kısaltmadır. DOM, "Document Object Model" kelimelerinin baş harflerinden oluşur. DOM, web tarayıcıları tarafından kullanılan bir öğe ağacı veya hiyerarşik yapı sağlar ve bu yapı, bir web sayfasında bulunan her öğeyi (örneğin, başlık, paragraf, bağlantı, resim, form öğesi vb.) temsil eder.

Bir DOM ağacı, her bir HTML öğesinin bir "Node" adı verilen bir nesne şeklinde temsil edildiği bir veri yapısıdır. Bu "Node"lar, aynı zamanda "Element" (örneğin, bir başlık), "Attribute" (örneğin, bir bağlantının hedef adresi), "Text" (örneğin, bir paragrafın içeriği) vb. gibi farklı türlerde olabilir. İşte birkaç örnek:

1. Element Node: Bir HTML etiketini temsil eder. Örneğin, \<h1>Başlık\</h1> etiketi bir "h1" element node'udur.
2. Attribute Node: Bir HTML etiketinin özelliğini temsil eder. Örneğin, \<a href="https://www.google.com">Google'a Git\</a> etiketinde "href" bir attribute node'dur.
3. Text Node: Bir HTML etiketinin içeriğini temsil eder. Örneğin, \<p>Bu bir paragraf metnidir.\</p> etiketinde "Bu bir paragraf metnidir." bir text node'dur.

Web tarayıcıları, JavaScript gibi diller kullanarak DOM'a erişmeyi sağlayan API'ler sunar. Bu API'ler, belirli bir HTML öğesine erişmek, özelliklerini değiştirmek, öğeleri eklemek veya kaldırmak ve DOM ağacını manipüle etmek için kullanılabilir.

İşte DOM'a erişmek için kullanılan bazı yaygın JavaScript API'leri:

+ document.getElementById(): Bir ID'ye sahip bir öğeyi seçer.
+ document.getElementsByTagName(): Bir etiket adına sahip tüm öğeleri seçer.
+ document.getElementsByClassName(): Bir sınıf adına sahip tüm öğeleri seçer.
+ document.querySelector(): CSS seçicilerini kullanarak bir öğeyi seçer.
+ document.createElement(): Yeni bir öğe oluşturur.
+ document.removeChild(): Bir öğeyi kaldırır.