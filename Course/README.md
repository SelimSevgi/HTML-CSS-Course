> ## 1-giriş-kütüphaneler

```html
<!-- AÇIKLAMA SATIRI-->
<!-- 
    Kütüphane - Eklentileri eklemek için;  
    Uzantılar 
    - Live Server : statik dilleri canlı bir sunucuda kullanabilmek.
    - Prettier - Code formatter : otomotik olarak metinleri düzenlemize yarar.
    - Bracket Pair Colorizer : css için kodların renkli görülmesini sağlar.
    - indent-rainbow : kodlarının girintili olarak görülmesini sağlar
    - Highlight Matching Tag : tag oluştururken vurgulanmasını sağlar.
      Styling Examples(copy) - Settings - sağ üstte ayarları aç JSON(paste)
      "borderStyle": "solid",
      "borderColor": "yellow",
  
    Settings - Format - *Format on paste ve *Format on save kısımlarını aktif yapıyoruz 
-->

<!--
  -KAYNAKLAR
  -- https://developer.mozilla.org/en-US/
  -- https://www.w3schools.com/
-->

<!--
  Klavye Kısayolllarına gidip istediğimiz düzenlemeyi kendimize göre şekillendirebiliriz.
  (Ctrl basılı tutularak K sonra S tuşuna basılmalıdır)
-->
<!-- 
  ! Tab yaparak HTML temel öğelerini aktif hale getirebiliyoruz. 
-->

<!-- 
  (shift + alt + f) tuşu kod düzenleme yapıyor 
-->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>first webpage</title>
  </head>
  <body>
    <h1>Hello People</h1>
    <p>this is my first webpage!!!!!!!!</p>
  </body>
</html>
```

> ## 2-headingElements(Başlık 'h1'-'h2'-'h3'-'h4'-'h5'-'h6')

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Heading</title>
  </head>
  <body>
    <!-- 
        Kalın başlıktan ince başlığa doğru 
    -->
    <h1>Heading Başlık 1</h1>
    <h2>Heading Başlık 2</h2>
    <h3>Heading Başlık 3</h3>
    <h4>Heading Başlık 4</h4>
    <h5>Heading Başlık 5</h5>
    <h6>Heading Başlık 6</h6>
  </body>
</html>
```

> ## 3-paragraph-br-Elements(Metin 'p'-'br')

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Paragraph</title>
  </head>
  <body>
    <!-- 
        paragraf eklemek için p tab tuşuna basıp içine eklemek istediğimiz metni yazabiliriz. 
        Lorem tab yapıp metin belgesini ekleyebiliriz.
        (Lorem20 Lorem500) ise kelime sayısını gösteriyor
    -->

    <!-- 
        <br> komutuyla paragraf başı yada boşluk bırakılabilir
    -->
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae enim
      fugit numquam possimus porro architecto eos, neque quisquam, nesciunt
      obcaecati ad error doloribus beatae quaerat veniam in eius minima
      dignissimos quibusdam. Magnam quo officiis qui rerum itaque tempora
      facilis. Labore vel, id officiis cumque sapiente, pariatur nesciunt
      perspiciatis architecto corporis <br />
      neque quaerat placeat reprehenderit dolore consequuntur omnis excepturi?
      Odit vitae sint tempora quaerat maiores temporibus assumenda rem
      recusandae nobis deleniti nesciunt quod ipsam ipsum inventore hic pariatur
      suscipit adipisci rerum molestiae, corporis expedita error. Sunt dolorem
      debitis libero praesentium. <br />
      <br />
      <br />
      <br />
      Ducimus delectus saepe quam quos excepturi aperiam dicta voluptatum eius!
    </p>
  </body>
</html>
```

> ## 4-images(Fotoğraf 'img')

```html
<!-- 
    telif hakkı olmayan resimler için ;
    https://pixabay.com/tr/
    https://www.pexels.com/tr-tr/
    https://gratisography.com
-->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Images</title>
  </head>
  <body>
    <!-- 
        img tab tuşuna basarak resim ekleme komutunu ekliyoruz
        src kısmına resmin url yani kaynağını yazıyoruz.
        alt kısmına resme erişilememe durumunda alternatif söz dizilimi
    -->
    <h3>image of git logo</h3>
    <img src="images/./git.png" alt="" />
    <img src="images/git.jpeg" alt="git resmi" />

    <!--
        Resmi indirmek yerine resim adresini kopyalayıp scr kısmına yapıştırabiliriz
        telif hakkı olmayan resimlerde kullanılabilir
        kaynak kısmı uzun olduğu için ve başka bir resim kullanılabilir olduğu için 
        bu yöntem pek kullanılmaz
    -->
    <h3>youtube logo</h3>
    <img
      src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAilBMVEX/////AAD/vr7/l5f/k5P/kZH/2tr/4OD/xMT/mZn/+fn/4+P/qKj/r6//yMj/zc3/09P/TU3/u7v/8fH/7Oz/pKT/n5//Vlb/R0f/tbX/nJz/aWn/Ojr/LCz/jIz/9vb/fX3/Ghr/dHT/EhL/h4f/YWH/Pz//IiL/Wlr/MDD/cHD/e3v/Jyf/goL3kCEBAAAEWklEQVR4nO2c2VbiUBBFIwYIkJBAEiCCTOLUrf//e01EaYZou1KnqOvqs598vHvJyq3plucRQgghhBBCCCGEEEIIIYQQQgghhBBCCCGEEEIIIYQQQkg3zbJeO0nifhA0iigK89HoptO53uI3582mv/2j07kZ5WEYFcNGEPTjpNXLsnRhffJq0nYSFKG/WU7Hg9nqSsxqNhhPl3M/LIKknRqKZXHkrwe3cqN/8TxY+1GcXdYunk/0zU6ZLYcX+hV3O5e3+2AyvIBgaOdXctdQ9ksfbAW3jLuagi1rvTfaeoKJtds7iZZg29psT09HsGvtdYCO4ZO11gH3GoKBtdURsYLhylrqiGe8YMPa6QT8P3FgrXTCFC2YWhudgTYcWgudgf6ZvloLnXENNpxZC50xBhta+1SAFexZ61SALWy4FdDs6EMNR9Y6FeRQw7W1TgVLqKFrEU0J9mN6Z61TwQpqaG1TCVLQvai0BFnyd6PGdkoLaNi3lqkEeSEWknOopSUR0DAXnKPheRuY1BHIK38uOEfZaMjGMK0DNkDD34Jz7Fop8QtMbM8aaDgVnOOjWYRvWiGLppKG6L4d1l3C3HY8AA0lGf5Bw6+HDW+RNdNHwTmOWpoBMsBFBqaSc5w0bW9QflfQwFRyjNO29OIXStBVw22Ui2qV4wRFncOq0QJQIIebPhElT9XDEz7CEFdtE9USPxkPSe/lhrhmt6iB/+kATCIeGcMNZegYel4kNMSlwKIU/8shJllehTMUzdF8PaYlyqtwczWxnqHn9euHhLgyhqhM8+9Ru9p5Fc5Q1Jf5xjBht2aGHfwYw+2NWysDxU1iiiZNvnmMOqUgnKH+/zCtVSf5Qb/SmlEqzlD5W1o708B9S1XvQ0G2iBupUYxpUknGj4tp9OJS2csGXFyqlVs0hJU317OntrhcgzPUyPEXgPEOXI6f4Q0hAzq4Nje81gYqfQNfz2ANYe0LnCDUENiCctMQ2UYEGsJ6T4KSxTkvQMNnwTkODMHt/BnQENIDhs+KD4CGkgq8Xh8f+eRCPoshL+GfswQaSkrTb/M0Ku/emkBD4UyUZODoC0KgoaSFojfXVgAN3ZxNRL4LcnO+FPmm280ZYegSCWuZSpCCTs7qP0INXXxv8QQ1dPHNzCvUEDmNhgJ54bv3krsE+3bNnZUYfwEvVrLWqQAr+B+8A3bvLbcPNnTvPT72Q+NiZAoWdC+qwUY0Ja7diLgphT0ra6cj7vCCjj3JV1m+59KeqImGoFO7vpS2froTnGrswXrDlZ17ihsw3ai5oaOZIxb2F/+L0krBPZJn3Qg6yn4lkcKT3u/iX2jRbi+fGpQXJ3O1T2gl3VYjf50+rPTNbi2WQR+p9lrxsBjNN+v78QTRB90t9N5cmy/0/oJFuZO99b6TvYjCPH/fye43D3eyj/IwiophEPQ/lrKrrggmhBBCCCGEEEIIIYQQQgghhBBCCCGEEEIIIYQQQgghhPwQ/gCnHFmFM03ovQAAAABJRU5ErkJggg=="
      alt=""
    />

    <!--
        Yanda veya iki kelime arasında birden fazla boşluk algılanmıyor. 
        Tek boşluk olarak algılanıyor.
    -->
    <h3>laptop image of pexel site</h3>
    <img src="images/pexel-laptop.jpeg" alt="pexels laptop" />

    <!--
        Resim boyutunu bilmek için resme tıklayıp tam görüntü kısmında öğrenebiliriz.
        git resmin boyutu 910x380
        pexel-laptop resmini
        Resmin boyutunu ayarlamk için ise
        height="380" width="910" 
        bu şekilde görüntünün çözünürlüğünde sorun meydana gelebilir.
    -->
    <h3>laptop image of pexel site</h3>
    <img
      src="images/pexel-laptop.jpeg"
      alt="pexels laptop"
      height="380"
      width="910"
    />

    <!-- genişlik baz alınarak çözünürlük bozulmadan img -->
    <h3>laptop image of pexel site</h3>
    <img src="images/pexel-laptop.jpeg" alt="pexels laptop" width="910" />

    <!-- 
        yada fotoğrafın üzerinde dışarıdan düzenleme yapılarak istenilen özelliklere getirilmesi sağlanabilir. 
    -->
  </body>
</html>
```

> ## 5-externalLinks(dışLink 'a' )

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>External Links(Dış Bağlantı)</title>
  </head>
  <body>

    <!--
        a tab tuşuna basarak link ekleme komutunu ekliyoruz
        href kısmına sitenin url kaynağını yazıyoruz.
        target="_blank" komutu yan sekmede açmamıza yarıyor
    -->
    <a href="https://github.com/SelimSevgi" target="_blank"
      >visit to for my github page</a
    >

    <!--
      resime tıklayıncada linke yönlendirme yapabiliriz
      linkin içine img ekleyerek yapılabilir.
    -->
    <a href="https://github.com/SelimSevgi" target="_blank">
      <img src="/images/git.png" alt="">
    </a

    <!--
        br komutuyla paragraf başı yada boşluk bırakılabilir
    -->
    <br>

    <!--
        iç kısımda html dosyaları arasında gezinti yapılabilir
        a tab tuşuna basarak link ekleme komutunu ekliyoruz
        href kısmına kaynağın url kaynağını yazıyoruz.
        target="_blank" komutu yan sekmede açmamıza yarıyor
    -->
    <a href="/6-internalLinks(dahiliLİnk).html" target="_blank"
      >back to 6- Internal Links page</a
    >

  </body>
</html>
```

> ## 6-internalLinks(dahiliLİnk)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Internal Links (Dahili Link)</title>
  </head>
  <body>
    <!-- 
          en sonda a da tanımlanan etiketi id olarak tamamlarsak
          linke bastığımız zaman id olarak tanımlanan yere yönlendirmektedir.
        -->
    <h1 id="bas">Sayfanın ilk kısmı</h1>

    <!-- 
        iç kısımda html dosyaları arasında gezinti yapılabilir
        a tab tuşuna basarak link ekleme komutunu ekliyoruz
        href kısmına kaynağın url kaynağını yazıyoruz.
        target="_blank" komutu yan sekmede açmamıza yarıyor
    -->
    <a href="/5-externalLinks(dışLink 'a' ).html" target="_blank"
      >back to 5- External Links page</a
    >

    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptatum
      exercitationem assumenda harum inventore in veritatis necessitatibus
      molestiae cupiditate odio, maiores repellat quaerat, fuga dolorem dolore
      ipsam reprehenderit minima est sapiente.
    </p>
    <!-- 
        a tab tuşuna basarak link ekleme komutunu ekliyoruz
        href kısmına birşey yazmayınca sayfanın başına yönlendiriyor.
    -->
    <a href="">Sayfanın başına git</a>

    <br />

    <!-- 
        id oluşturarak da yapabiliriz. 
        a tab tuşuna basarak link ekleme komutunu ekliyoruz
        href kısmına #etiket yazılarak id olarak tanımladığımız yere yönlendiriyor.
    -->
    <a href="#bas">Sayfanın başına git1</a>
  </body>
</html>
```

> ## 7-forms-writtingElements(yazıŞekilleri)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sup ans Sub Elements</title>
  </head>
  <body>
    <!--
        sub komutu içinde yer alan metin aşağıda 
        sup komutu içinde yer alan metin yukarıda 
        gösterilir.
    -->
    <h1>
      I <sub>am </sub> Selim, Electric <sub>and</sub> Eletronic
      <sup>Engineer</sup>
    </h1>

    <!--
        strong komutu içinde yer alan metin vurgulu
        em komutu içinde yer alan metin italik
    -->
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempore nostrum
      quas, fugiat consequuntur quaerat totam error quae dignissimos aspernatur
      blanditiis rem tenetur eveniet <br />
      <strong
        >maxime inventore iusto numquam, dicta quo explicabo at?Repudiandae,
        dolorum cum! Nesciunt, nulla dignissimos? Optio eveniet iusto quas.
        Reiciendis aperiam, sunt error quaerat, excepturi fugiat labore, sint
        tempore quisquam veniam perspiciatis quia aliquam quos dolor eos
        quibusdam nulla</strong
      >
      <br />
      <em
        >et eaque consectetur odio corrupti provident. Officia voluptates velit
        blanditiis provident eos et magni assumenda possimus facilis eaque
        officiis delectus, neque ipsum, repellendus nobis incidunt reprehenderit
        animi atque nemo,</em
      >
      <br />
    </p>
    <!--
        Özel karakterler 
        arama yerine 
        google special character in html yazarak istediğimiz karakteri bulabiliriz.
        &copy ->  ©
    -->
    <h2>TSE &copy</h2>
  </body>
</html>
```

> ## 8-list(listeler 'l')

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>List</title>
  </head>
  <body>
    <!--
        ul sırasız listeler
        li komutunu kullanarak liste oluşturuyoruz
    -->
    <ul>
      <li>selim</li>
      <li>sevgi</li>

      <!--
          listeler halinde sayfalar arasında geçiş yapabiliriz.
      -->
      <li>
        <a href="7-forms-writtingElements(yazıŞekilleri).html" target="_blank"
          >back to forms-writtingElements(yazıŞekilleri) page
        </a>
      </li>
    </ul>

    <!--
        ol sıralı liste
    -->
    <ol>
      <li>elektrik</li>
      <li>ve</li>
      <li>elektronik</li>
      <li>mühendisi</li>
    </ol>

    <!--
        iç içe listeler
        ul sırasız liste ve ol sıralı liste birlikte kullanımı
        3 tane liste oluşturmak istiyorsak (li*3) kısayolunu kullanabiliriz
    -->
    <h3>Dersler</h3>
    <ul>
      <li>Matematik</li>
      <ol>
        <li>Sayı ve kesir</li>
        <li>Yüzde</li>
        <li>Kar-Zarar</li>
      </ol>
      <li>Türkçe</li>
      <ol>
        <li>Cümlenin Öğeleri</li>
        <li>Paragraf</li>
      </ol>
      <li>Coğrafya</li>
      <ol>
        <li>Türkiyenin Yer Şekilleri</li>
      </ol>
    </ul>
  </body>
</html>
```

> ## 9-tableElement

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Table</title>
  </head>
  <body>
    <!--
        table tab tuşuna basarak tablo oluştuyoruz
        tr komutunu kullarak "row" satır halinde ekleme yapılıyor
        alt satıra geçmek için yine tr komutunu kullanıyoruz
        th başlık kalın olarak yazıyor
        td normal olarak yazıyor
      -->
    <table>
      <tr>
        <th>Hasta</th>
        <th>1</th>
        <th>2</th>
        <th>3</th>
      </tr>
      <tr>
        <th>Adı</th>
        <td>Emil</td>
        <td>Tobias</td>
        <td>Linus</td>
      </tr>
      <tr>
        <th>Yaşı</th>
        <td>16</td>
        <td>14</td>
        <td>10</td>
      </tr>
    </table>
  </body>
</html>
```

> ## 10-formsInput-submitElements

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>form</title>
  </head>
  <body>
    <!-- 
        FORM;
            Metin alanları, onay kutuları, radyo düğmeleri, gönderme düğmeleri,:
            eleman gibi girdi elemanlarının farklı türleri için bir kapsar.
            name="" kısmı sadece urlde ne olduğu hakkında biz bilgi sağlar.
            id="" kısmı etiket vermemizi sağlar.
    -->
    <form action="" method="">
      <!-- 
          LABEL;
            <label id='name'></label>  input id name kısmına etiketi burada vurgulamak için kullanıyoruz.
            p de kullanabiliriz.
        -->
      <label for="name">First Name:</label>

      <!--  
          TEXT;   
            <input type="text" name="name" id="name"> 
            text tipinde veri alanı oluşturur.
        -->
      <input type="text" name="isim" id="name" />
      <br />

      <!--
          ŞİFRE;
            <input type="password" name="" id="" placeholder="password" />
            placeholder="Lütfen şifrenizi giriniz" ne yazılması hakkında fikir verir.
        -->
      <p>Password</p>
      <input
        type="password"
        name="şifre"
        id=""
        placeholder="Lütfen şifrenizi giriniz"
      />
      <br />

      <!--
          EMAİL;
            value="email@email"
            verilen değer aktif olarak sürekli kullanılacak.
      -->
      <input type="email" name="emailadresi" id="" value="email@email" />
      <p>AÇIKLAMA</p>

      <!--
          TEXTAREA;
            daha uzun açıklama satırı yapabileceğimiz bir alan oluşturuyor.
            cols="60" sütün uzunluğu
            rows="10" satır uzunluğu
      -->
      <textarea name="" id="" cols="60" rows="10"></textarea>
      <p>Favori yazılım diliniz hangisidir?</p>

      <!--
          RADİO;
            seçenek sunmamıza ve seçmemize yarıyor
            value="py" kişi tarafından seçilen radio butonun değerini ne olduğunu gösterir.
      -->
      <input type="radio" name="coding" id="" value="javascript" />JavaScript
      <input type="radio" name="coding" id="" value="java" />Java
      <input type="radio" name="coding" id="" value="py" />Python
      <br />
      <p>hangi yazılım dillerini seviyorsunuz?</p>

      <!--
          CHECKBOX;
            birden fazla seçenek seçmemize yarıyor
      -->
      <input
        type="checkbox"
        name="programming"
        id=""
        value="javascript"
      />JavaScript
      <input type="checkbox" name="programming" id="" value="java" />Java
      <input type="checkbox" name="programming" id="" value="py" />Python
      <p>hangi yazılım dillerini seviyorsunuz?</p>

      <!--
          SELECT-OPTİON;
            Açılır menü halinde seçim yapmamızı sağlar 
            Sadece tek bir seçeneği seçebiliyoruz.
      -->
      <select name="langues" id="">
        <option value="javascript">JavaScript</option>
        <option value="java">Java</option>
        <option value="py">Python</option>
      </select>
      <br />

      <!--
          BUTTON;
            <button type="submit"> komutu sunucuya yollanmasını sağlayan butondur.
            -(aynı şekilde)
            <input type="submit" value="Submit Please"> komutuyla button oluşturulabilir.
        -->
      <button type="submit">Submit</button>
      <input type="submit" value="Submit Please" />
    </form>
  </body>
</html>
```

> ## 11- headElement(basEleman)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!--
        Asıl site hakkındaki veriler ana öğenin içinde yer alacak 
        <title>
            Etiket belgenin başlığını tanımlar. Başlık salt metin olmalıdır ve tarayıcının başlık çubuğunda veya sayfa sekmesinde gösterilir.
        <title>
        style 
            bir öğeye renk, yazı tipi, boyut ve daha fazlası gibi stiller eklemek için kullanılır.
        <meta> 
            etiketler her zaman <head> öğesinin içine girer ve genellikle karakter kümesini, sayfa açıklamasını, anahtar sözcükleri, belgenin yazarını ve görünüm penceresi ayarlarını belirtmek için kullanılır.
            Meta veriler sayfada görüntülenmeyecek, ancak makineyle ayrıştırılabilir.
            Meta veriler, tarayıcılar (içeriğin nasıl görüntüleneceği veya sayfanın nasıl yeniden yükleneceği), arama motorları (anahtar kelimeler) ve diğer web hizmetleri tarafından kullanılır.
        <link>
            Dış stil sayfaları için bağlantıyı için kullanılır.
        <script>
            Etiket gömmek bir istemci tarafı komut dosyası (JavaScript) için kullanılır.        
        <base>
            Bir belgedeki tüm göreli URL'ler için temel URL ve / veya hedef belirler.        
    -->

    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>headElement(basEleman)</title>
  </head>
  <body></body>
</html>
```

> ## 12- cssTutorial(cssEğitimi)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS TUTORİAL</title>
    <!--
        aynı şekilde css kodlarını head kısmında style içine yazabiliriz
    -->
    <style>
      /*
            css kımını yorum yapmak için;
            sadece bu sayfanın değişmesine olanak sağlıyor diğer sayfalarda görünmüyor
            h1{...} içindeki kodlar bütün h1 lere etkide bulundu.
        */
      h1 {
        color: rgb(209, 138, 46);
        font-size: 3rem;
      }

      h2 {
        color: rgb(88, 73, 231);
        font-size: 0.5rem;
      }
    </style>
  </head>
  <body>
    <a href="./12- cssTutorial_about.html">12- cssTutorial_about page</a>
    <!--
        inline css - Satır içi css
        style="" içerine görünümle alakalı değişiklik yapılabilir.
            - renk : color: olive;
            - yazı boyutu : font-size: 3rem;

    -->
    <h3 style="color: olive;font-size: 3rem;">Hello world</h3>

    <h1>Hello people</h1>
    <h1>Hello people</h1>
    <h1>Hello people</h1>

    <h2>Are u there?</h2>
    <h2>Are u there?</h2>
    <h2>Are u there?</h2>
    <h2>Are u there?</h2>
    <h2>Are u there?</h2>
    <h2>Are u there?</h2>
    <h2>Are u there?</h2>
    <h2>Are u there?</h2>
  </body>
</html>
```

> ## 12- cssTutorial_about

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <!--
        12- cssTutorial(cssEğitimi) sayfasında yapılan style içindeki değişiklikler bu sayfada görülmedi.
        aynı düzenlemeleri görmek için harici bir css dosyasına ihtiyacımız olacak
    -->
    <a href="./12- cssTutorial(cssEğitimi).html"
      >12- cssTutorial(cssEğitimi) page</a
    >
    <h1>Hello Word</h1>
    <h1>Hello Word</h1>
    <h1>Hello Word</h1>
    <h1>Hello Word</h1>
    <h1>Hello Word</h1>

    <h2>Hey..</h2>
    <h2>Hey..</h2>
    <h2>Hey..</h2>
    <h2>Hey..</h2>
    <h2>Hey..</h2>
    <h2>Hey..</h2>
    <h2>Hey..</h2>
  </body>
</html>
```

> ## 13- externalCss(hariciCss)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>externalCss(hariciCss)</title>

    <!--
        css dosyası ekledik ve değişiklikleri görmek için 
        <link rel="stylesheet" href=""> css aktif kılıyoruz.
            href="" kısımına css dosya uzantısını yazıyoruz.
    -->
    <link rel="stylesheet" href="./css/13- externalCss(hariciCss).css" />

    <!--
        -------------------------------
        Power Struggle - Güç Mücadelesi
        css dosyasının içinde h1 rengi turuncu olmasına rağmen 
        head kısmına yazdığımız style içindeki kod aktif oldu.
    -->
    <style>
      h1 {
        color: aqua;
      }
    </style>
  </head>
  <body>
    <a href="./13- externalCss(hariciCss)_about.html"
      >13- externalCss(hariciCss)_about.html</a
    >

    <!--
        style içindeki renk turkuaz olmasına rağmen 
        h1 içine yazığımız style rengi daha baskın
    -->
    <h1 style="color: green;">Hello world</h1>
    <h1>Hello world</h1>
    <h1>Hello world</h1>

    <h2>Hello people</h2>
    <h2>Hello people</h2>
    <h2>Hello people</h2>
    <h2>Hello people</h2>
  </body>
</html>
```

> ## 13- externalCss(hariciCss)\_about

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>externalCss(hariciCss)_about</title>

    <!--
        bir css dosyası ile birden fazla html dosya stilinde değişiklik yapabiliriz.
    -->
    <link rel="stylesheet" href="./css/13- externalCss(hariciCss).css" />
  </head>
  <body>
    <a href="./13- externalCss(hariciCss).html"
      >13- externalCss(hariciCss).html page</a
    >
    <h1>Hello world</h1>
    <h1>Hello world</h1>

    <h2>Hello people</h2>
    <h2>Hello people</h2>
    <h2>Hello people</h2>
  </body>
</html>
```

> ## 13- externalCss(hariciCss) .css

```css
/*
    Burada yapılan css kod değişiklikleri aktif kılınan html dosyalarında görülür.
*/
h1 {
  color: orange;
  font-size: 4rem;
}

h2 {
  color: red;
}
```

> ## 14- elementSelectors(elamanSeciciler)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>elementSelectors(elamanSeciciler)</title>
    <link
      rel="stylesheet"
      href="./css/14- elementSelectors(elamanSeciciler).css"
    />
  </head>
  <body>
    <h1>Hello Word</h1>
    <h2>Hi People</h2>
    <p>
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Qui placeat
      quasi maiores id ad accusantium neque illo voluptate, quaerat odit
      doloremque hic officia doloribus exercitationem quo eligendi fuga facilis,
      veniam aliquid quisquam laboriosam laudantium quis ipsam accusamus? Quia
      accusamus vel eligendi assumenda quos? Ipsum earum laborum repellat
      inventore necessitatibus repellendus fugit, quasi nesciunt delectus
      molestiae incidunt? Dolor totam incidunt commodi deserunt molestiae atque,
      placeat possimus voluptatum saepe sunt ratione excepturi libero odit,
      quasi nesciunt. Dicta consequatur modi officiis explicabo accusantium,
      inventore doloribus. Magnam, veniam deleniti dicta obcaecati enim
      accusantium, illo eligendi facere molestiae architecto earum perferendis
      quaerat consequuntur, voluptas nobis vel? Ullam ipsa at similique ex
      tempora veritatis dolor aliquam molestias laborum enim eos assumenda
      libero expedita voluptates, voluptate animi! Incidunt, vel obcaecati
      quidem quam ullam laudantium, id neque dolores laborum voluptate aperiam!
      Quidem ipsam delectus eos est voluptatibus expedita natus aperiam ipsum
      sapiente iste perferendis, sed, doloremque, excepturi omnis? Consectetur,
      harum? In, assumenda ipsum exercitationem debitis voluptas quis sit
      voluptatem vero architecto fugiat. Nihil ipsam voluptates rerum veritatis
      ratione mollitia eveniet sapiente dolorem pariatur veniam? Sequi nihil
      odio magnam, ducimus itaque eos provident commodi placeat mollitia
      voluptatum impedit, fugiat harum maxime saepe debitis pariatur sunt nisi?
      Pariatur asperiores veritatis facilis deleniti cumque. Expedita neque
      libero facilis fugit vitae eligendi pariatur excepturi quis, impedit unde
      non quibusdam consectetur at tempora nulla mollitia delectus saepe aliquam
      natus ipsa dicta illo earum. Quae minus expedita fuga hic esse incidunt
      error, libero facere explicabo officiis facilis quod nemo harum alias?
      Consectetur ullam quos repudiandae ab expedita dolorem voluptates rem
      inventore magni exercitationem! Commodi ipsum voluptatum velit cum
      repudiandae vero, saepe vel nemo, voluptatem voluptatibus fugiat aliquid
      consequatur veniam? Deserunt temporibus suscipit consectetur obcaecati
      natus, numquam incidunt illum possimus ad eveniet nobis rem vero
      cupiditate veritatis facilis totam? Adipisci consequatur similique maxime
      omnis dicta, odio odit reprehenderit quod ex cupiditate natus molestias
      iste enim minus ad nihil voluptas rerum fugiat obcaecati repudiandae modi,
      tempore ab velit. Dicta impedit reprehenderit neque maxime ipsum,
      excepturi porro quidem minima eaque et necessitatibus. Tenetur sapiente
      illum eveniet molestiae eum unde ipsam cupiditate, sint quaerat libero
      velit! Accusantium et facere natus eum deleniti vel magni quos quisquam
      officiis harum quidem, magnam reprehenderit cum tempore, eos impedit modi
      dignissimos dolore, odio qui animi itaque amet obcaecati quam. Tenetur
      amet, accusamus dolores sapiente adipisci sunt officia iste voluptas in
      quos. Molestiae earum veniam optio obcaecati, omnis quo eaque ad nisi
      ratione beatae voluptatem similique hic quibusdam asperiores reiciendis
      voluptates nihil exercitationem odio dolores velit? Officia, quidem! Eius
      animi eum soluta maiores, expedita dignissimos quos id velit, nemo sit
      nihil suscipit molestiae dolor molestias ducimus numquam repudiandae
      laudantium maxime fugit facere quas vero assumenda. Vero quibusdam vel
      eaque eos nulla porro beatae quam quidem ipsum neque necessitatibus fuga a
      obcaecati illo quaerat, maxime repudiandae suscipit praesentium quis!
      Sapiente aperiam a, quia necessitatibus mollitia veniam minus vero non
      earum porro est, nihil laborum consequuntur possimus officiis saepe ex
      aspernatur architecto. Placeat, harum! Expedita ipsum soluta maxime quo
      eveniet distinctio repudiandae culpa possimus corporis?
    </p>
  </body>
</html>
```

> ## 14- elementSelectors(elamanSeciciler) .css

```css
/* 
    Element Selectors 
    tek tek eleman seçimini yapıyoruz h1 h2 h3 p.... gibi
*/
h1 {
  color: red;
}

h2 {
  color: green;
}
p {
  color: grey;
}
```

> ## 15- groupingSelectors(grupSecici)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>groupingSelectors(grupSecici)</title>
    <link rel="stylesheet" href="./css/15- groupingSelectors(grupSecici).css" />
  </head>
  <body>
    <h1>Hello Word</h1>
    <h2>Hi People</h2>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ex dolorum
      mollitia, incidunt quasi fuga laborum dicta temporibus placeat expedita
      rerum aperiam molestias natus at sed fugiat ducimus voluptas doloremque
      error assumenda tempore nam! Necessitatibus architecto aspernatur delectus
      voluptatum nulla tenetur veniam eveniet iusto et, consequatur autem, ipsum
      recusandae! Voluptates, quo quidem quos non architecto voluptate? Deserunt
      at enim perspiciatis repellat aut. Tempore fuga, consectetur eaque cum
      ipsa quidem impedit quis excepturi, repellat reiciendis recusandae odit
      tempora cupiditate ipsum possimus quam! Consequuntur, tempore qui numquam
      doloremque, ex eligendi veritatis vitae obcaecati nesciunt eveniet quidem
      incidunt beatae. Ipsam, repellat! Dolores, aspernatur nulla! Similique
      pariatur corrupti, amet in soluta tempore ullam accusantium aliquam
      tenetur vero illum nobis suscipit atque, cumque reiciendis minima? Et
      excepturi expedita necessitatibus nam laboriosam quod quae magnam ex
      officiis ut repudiandae eligendi quis a pariatur laudantium, doloremque,
      tenetur odit ipsam voluptatem architecto, dicta eos! Velit consequatur
      error quisquam eligendi alias facilis, laboriosam hic fugiat, quidem
      aliquid est qui enim adipisci provident cum dolores. Cum animi magnam
      voluptatibus. Officia fuga consequuntur ex. Voluptatibus, vel assumenda
      est maiores, fuga obcaecati explicabo ea autem quam id nulla architecto
      deserunt dolore? Nisi voluptatum aspernatur natus tenetur quod unde at
      impedit, tempore blanditiis fugit hic velit veritatis atque aperiam nemo
      ab placeat illum saepe incidunt consectetur harum in debitis
      necessitatibus. Impedit ut, hic adipisci, eaque saepe perspiciatis iste ea
      sequi repudiandae sit atque perferendis officia libero doloremque enim!
      Nemo tempora nesciunt, quaerat iusto recusandae commodi molestias
      voluptatum atque asperiores sequi delectus fugit veniam, animi rerum
      officia eaque quae est dicta sed laborum qui quidem consectetur, sunt
      deserunt! Enim eius voluptatem ducimus tempore, odit dolor debitis
      voluptates, deserunt soluta ullam impedit cumque. Animi quia cumque nobis
      possimus totam perferendis reprehenderit, maiores adipisci aspernatur.
      Doloribus nobis cupiditate voluptates aliquam. Itaque error cum fugiat
      molestiae ad minus. Minima minus pariatur blanditiis et, vitae
      reprehenderit at, illum mollitia numquam facilis possimus earum quis
      repudiandae beatae sit eum quod molestiae officiis doloribus? Tempore
      omnis nobis blanditiis possimus dicta, ipsa consequatur maiores quisquam
      explicabo eaque facere quis voluptatibus! Maxime odit quidem quos neque.
      Vel ad voluptas dolor sint porro beatae, error doloremque! Corrupti
      necessitatibus, accusamus quisquam maxime ducimus atque, autem voluptatum
      accusantium obcaecati quas quo voluptatem consequatur perspiciatis?
      Repellat neque voluptatem, molestiae quasi itaque at. Sequi laudantium,
      consectetur eum accusamus tempore itaque provident obcaecati rerum
      inventore esse quasi praesentium repudiandae? Eligendi temporibus dolorum
      fuga iusto nam qui eaque eos ducimus praesentium mollitia, illo excepturi
      odit molestias ab autem soluta voluptatibus delectus iste, ipsam optio
      fugit! Quas quis quos impedit quasi pariatur ullam quibusdam, et, natus at
      doloribus placeat! Deserunt, rerum! Nostrum a illum neque sed tempore
      accusamus eaque adipisci! Voluptas possimus illum aliquid maiores
      explicabo ex magni sequi voluptate perferendis dignissimos alias
      consectetur, similique iure, at quam nesciunt quae illo delectus esse
      dolorem dolores ducimus corrupti. Cupiditate, perspiciatis unde? Quaerat
      autem pariatur culpa voluptatem! Perspiciatis inventore sit, asperiores
      exercitationem totam at pariatur, beatae placeat repellat necessitatibus
      nemo reiciendis veritatis iusto nostrum quas accusantium hic natus dolorem
      odio, explicabo ex quia!
    </p>
  </body>
</html>
```

> ## 15- groupingSelectors(grupSecici) .css

```css
/*
    Vucut kısında bulunan yazı renklerini
*/
body {
  color: blue;
}

/*
    Grouping Selectors
    h1 ve h2 ikisini gruplandırdığımız için ikiside aynı renge sahip
*/
h1,
h2 {
  color: red;
}
```
