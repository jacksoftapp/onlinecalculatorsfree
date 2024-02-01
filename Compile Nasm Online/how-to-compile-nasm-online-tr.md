Nasm Online Derleyici Nasıl Kullanılır?
=======================================

Bugün size Nasm Online Derleyici adlı çevrimiçi bir araçtan nasıl yararlanabileceğinizi anlatacağım. Bu araç, Assembly dilinde yazılmış programları derlemek ve çalıştırmak için kullanılabilir. İster yeni başlayan biri olun, ister deneyimli bir programcı, bu araç size çok yardımcı olacaktır.

### Temel Bilgiler

Nasm, Assembly dilinde yazılmış programları derlemek için kullanılan bir derleyici asamblerdir. Assembly dilini kullananlar, doğrudan bilgisayarın işlemcisi tarafından anlaşılabilen düşük seviye bir dil kullanır. Nasm ile yazılan programlar, daha sonra herhangi bir bilgisayarda çalıştırılabilir.

Bu online araç, Nasm derleyicisini çevrimiçi olarak kullanmanıza olanak tanır. Böylece herhangi bir indirme veya kurulum yapmanıza gerek kalmadan, sadece tarayıcınızı kullanarak kodunuzu derleyebilir ve çalıştırabilirsiniz.

### Araç Kullanımı

Şimdi, Nasm Online Derleyici aracını kullanmanın adımlarını açıklayacağım:

1. İlk olarak, tarayıcınızı açın ve aşağıdaki bağlantıya gidin: [Nasm Online Derleyici](https://www.onlinecalculatorsfree.com/tr/tools/compile-nasm-online.html).
2. Aracı kullanmaya başlamak için, sayfanın ortasında yer alan "Kod" bölümüne tıklayın. Burada Assembly dilinde yazılmış programınızı gireceksiniz.
3. Ardından, kodunuzu girin veya yapıştırın. Örneğin, basit bir "Merhaba Dünya" programı yazalım:

```
<div class="code-block-header">
<span class="code-block-header__lang"></span><span class="code-block-header__copy">Copy Code</span>
</div>```
<span class="hljs-meta">section</span> .data
    msg <span class="hljs-built_in">db</span> <span class="hljs-string">'Merhaba Dunya!'</span>,<span class="hljs-number">0</span>

<span class="hljs-meta">section</span> .text
    <span class="hljs-meta">global</span> _start
<span class="hljs-symbol">
_start:</span>
    <span class="hljs-keyword">mov</span> <span class="hljs-built_in">eax</span>, <span class="hljs-number">4</span>
    <span class="hljs-keyword">mov</span> <span class="hljs-built_in">ebx</span>, <span class="hljs-number">1</span>
    <span class="hljs-keyword">mov</span> <span class="hljs-built_in">ecx</span>, msg
    <span class="hljs-keyword">mov</span> <span class="hljs-built_in">edx</span>, <span class="hljs-number">14</span>
    <span class="hljs-keyword">int</span> <span class="hljs-number">0x80</span>

    <span class="hljs-keyword">mov</span> <span class="hljs-built_in">eax</span>, <span class="hljs-number">1</span>
    <span class="hljs-keyword">xor</span> <span class="hljs-built_in">ebx</span>, <span class="hljs-built_in">ebx</span>
    <span class="hljs-keyword">int</span> <span class="hljs-number">0x80</span>

```
```

4. Kodunuzu girdikten sonra, "Derle ve Çalıştır" düğmesine tıklayın. Arka planda Nasm derleyicisi çalışacak ve kodunuzun çıktısını sağlayacaktır.
5. Çıktı, aşağıdaki "Çıktı" bölümünde görünecektir. Bu bölümde, derlenmiş programınızın çalıştırılması sonucunda elde edilen çıktıyı göreceksiniz.
6. İsterseniz, kodunuzu düzenleyebilir ve tekrar derleyebilirsiniz. Bunun için, "Kod" bölümündeki metni değiştirin ve tekrar "Derle ve Çalıştır" düğmesine tıklayın.

Nasm Online Derleyici aracını kullanarak, Assembly dilinde yazılmış programlarınızı hızlı bir şekilde derleyebilir ve çalıştırabilirsiniz. Bu araç, yeni başlayanlar için öğrenme sürecini kolaylaştırırken, deneyimli programcılar için de pratiklik sağlar.

### Sonuç

Bu makalede, Nasm Online Derleyici aracının nasıl kullanılacağını anlattık. Bu araç sayesinde Assembly dilinde yazılmış programlarınızı çevrimiçi olarak derleyebilir ve çalıştırabilirsiniz. Başlamak için verilen bağlantıyı kullanarak araca erişebilirsiniz.

Unutmayın ki, Assembly dilinde programlama yaparken dikkatli ve özenli olmanız önemlidir. Doğru syntax ve mantığı kullanmak, hatasız bir program oluşturmanızı sağlar.

Umarım bu makale size yardımcı olmuştur. İyi çalışmalar!