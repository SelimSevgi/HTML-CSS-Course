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

> ## 16- idSelectors(kimlikSeciciler)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>idSelectors(kimlikSeciciler)</title>
    <link rel="stylesheet" href="./css/16- idSelectors(kimlikSeciciler).css" />
  </head>
  <body>
    <!--
          h1'deki id kısımla cssdeki aynı olmak zorunda eşleşmesi için
      -->
    <h1 id="Heading">Title heading</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur adipisci
      aliquam quam soluta, fuga voluptatem id numquam laborum magni ullam?
      Quisquam autem nihil reiciendis dolore quaerat aspernatur omnis, quia
      deleniti illum molestias nulla corporis ab mollitia eligendi veniam
      pariatur quae et ipsum. Voluptas in minus perferendis ipsum fuga illo at.
      Enim dolorem, veniam facere ipsam quasi deleniti quo, iure ipsum rem
      excepturi repellat dolorum. Quidem quibusdam eum vero possimus eius
      aliquid pariatur sint, cupiditate assumenda est harum explicabo nemo velit
      minus quae delectus voluptate doloribus non quam porro expedita accusamus
      suscipit! Veritatis veniam ipsum tempore qui perferendis perspiciatis
      dolor adipisci, natus commodi excepturi reiciendis, ex molestias illum
      sunt minima pariatur voluptatum dolorum rerum aut ad deserunt non. A totam
      minus ex non, quaerat alias, atque dolore, fugiat voluptatum expedita enim
      suscipit impedit. Reiciendis culpa ipsam maxime accusamus est laborum,
      distinctio excepturi ex libero temporibus placeat atque nisi? Voluptas,
      ipsam modi voluptatibus sit, eveniet magni rem facilis cupiditate illo vel
      quis repudiandae iusto? Natus obcaecati qui ratione non laborum id tempora
      omnis nemo, libero, sunt amet optio rerum accusantium officia eos ullam
      incidunt impedit dolorum modi voluptatum animi sapiente ipsum! Delectus
      iusto tenetur quas error? At doloremque ipsa sunt nisi vero?
    </p>
    <h1 id="subHeading">Footer Heading</h1>
  </body>
</html>
```

> ## 16- idSelectors(kimlikSeciciler) .css

```css
/*
    ID
    İlk başta tanımlanın h1'e verilen id'i burada şekillendiriyoruz.
*/
#Heading {
  color: green;
  /* 
        background: arka plan rengi
    */
  background: black;
}
/*
    Verilen id isimleri eşsiz olmalıdır.
*/
#subHeading {
  color: red;
  background: blue;
}
```

> ## 17- classSelector(sınıfSeciciler)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>classSelector(sınıfSeciciler)</title>
    <link rel="stylesheet" href="./css/17- classSelector(sınıfSeciciler).css" />
  </head>
  <body>
    <!--
          classlar >'den önce kullanılmalıdır.
          class="yeş kharf" yeş ve kharf iki adet sınıf bulunmaktadır. 
      -->
    <h3 id="baslık" class="yeş kharf">Yeşil</h3>
    <h3 class="kırm">Kırmızı</h3>
    <h3 class="yeş">Yeşil</h3>
    <h3 class="kırm kharf">Kırmızı</h3>
    <h3 class="yeş">Yeşil</h3>
    <h3 class="kırm">Kırmızı</h3>
  </body>
</html>
```

> ## 17- classSelector(sınıfSeciciler) .css

```css
/*
    CLASS SELECTOR SINIF SECICI
    html de belirlenen sınıflar css de .(class_name) şekilde yazılmalıır.
*/
.yeş {
  color: green;
}
.kırm {
  color: red;
  background-color: blue;
}

/*
    font-size: yazı boyutu
*/
#baslık {
  font-size: 50px;
}

.kharf {
  /*
    
*/
  text-transform: lowercase;
}
```

> ## 18- div-spanElements

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>div-spanElements</title>
    <link rel="stylesheet" href="./css/18- div-spanElements.css" />
  </head>
  <body>
    <!--
        span - div bloklara ayırıyor.
        div parçalara ayırıyor.
    -->
    <div class="kırmızı">
      <h3>heading number one</h3>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi nihil
        commodi nobis reiciendis doloremque dignissimos quos recusandae qui odit
        animi.
      </p>
    </div>

    <div class="yesil">
      <h3>heading number two</h3>
      <!--
        spanda metin aynı kalıyor herhangi bir değişiklik yok
        div metodunda alt satıra bir blok şeklinde görülüyor
      -->
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div class="kırmızı">büyük harf</div> Eligendi nihil commodi nobis reiciendis
        doloremque dignissimos quos recusandae <span>büyük harf</span> qui odit
        animi.
      </p>
    </div>
  </body>
</html>
```

> ## 18- div-spanElements .css

```css
.kırmızı {
  color: red;
  background: grey;
}

.yesil {
  color: green;
}

span {
  text-transform: uppercase;
}
```

> ## 19- cssInheritance(Miras)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>cssInheritance(Miras)</title>
    <link rel="stylesheet" href="./css/19- cssInheritance(Miras).css" />
  </head>
  <body>
    <div>
      <h2>i'm heading</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem
        placeat ea nesciunt iusto cum tempore, possimus libero nobis
        consequuntur praesentium!
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem
        placeat ea nesciunt iusto cum tempore, possimus libero nobis
        consequuntur praesentium!
      </p>
    </div>
  </body>
</html>
```

> ## 19- cssInheritance(Miras) .css

```css
/*
    INHERİTANCE
*/

/*
    sırasıyla devralma listesi -> body - div - h2 genelden özele doğru
*/

/*
    font-family: yazı tipini değiştirir.
    line-height: satır yüksekliği
*/

body {
  font-family: monospace;
  line-height: 1.5em;
  color: red;
}

/*
    burada body taradından miras bırakılan div ektin olacaktır.
*/
div {
  border: 3px solid black;
  color: blue;
}

h2 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 3em;
  color: green;
}
```

> ## 20- specificity-universalSelector(ozgulluk-evrenselSeciciler)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>specificity-universalSelector(ozgulluk-evrenselSeciciler)</title>
    <link
      rel="stylesheet"
      href="./css/20- specificity-universalSelector(ozgulluk-evrenselSeciciler).css"
    />
  </head>
  <body>
    <div>
      <h2>başlık</h2>
      <p class="renk">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum nobis
        numquam, obcaecati vel officiis voluptatibus dicta laudantium illum in
        quisquam.
      </p>
      <p class="renk">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eveniet
        expedita aliquam sapiente corporis ea animi quisquam dicta vero nesciunt
        molestias eligendi nostrum quae voluptatibus debitis odit, explicabo ex
        in. Voluptatibus.
      </p>
    </div>
  </body>
</html>
```

> ## 20- specificity-universalSelector(ozgulluk-evrenselSeciciler) .css

```css
/*
    her zaman son yazılan kod geçerli olacaktır.
*/
p {
  color: blue;
}

/* .... */

/* buradaki kod aktif olacaktır. */
p {
  color: red;
}

/* 
    sınıf ve sınıfsız durumlarda ise sınıf verdiğimiz durum aktif olacaktır.
*/
p {
  color: brown;
}
/* buradaki kod aktif olacaktır. */
.renk {
  color: coral;
}
```

> ## 21- color-backgroundcolorProperties

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>color-backgroundcolorProperties</title>
    <link
      rel="stylesheet"
      href="./css/21- color-backgroundcolorProperties.css"
    />
  </head>
  <body>
    <h3 id="first">i'm heading number one</h3>
    <h3 id="second">i'm heading number two</h3>
    <h3 id="third">i'm heading number three</h3>
    <h3 id="four">i'm heading number four</h3>
  </body>
</html>
```

> ## 21- color-backgroundcolorProperties .css

```css
/* 
    COLOR PROPERTİES _ COLOR BACKGROUND-COLOR
    RGB (Red-Green-Blue) 0 - 255 arasında değerleri kapsar.
    RGBA RGB'de olduğu gibi renk kodları yazılır. en sonunda opaklık verilir.
    Colorname 140 adet renk kodlarını modern tarayıcılar destekler.  HEX kodunda renkleri verir
        Bej -> #F5F5DC
        HEX values #RRGGBB 0 - 15 arasında değer alır.
            1 2 3 4 6 7 8 9 A(10) B(11) C(12) D(13) E(14) F(15)
            1 2 3 4 5 6 7 8 9 10 11 12 13 14 15
            #FF0000 -> RED
            #00FF00 -> GREEN
    - https://coolors.co sitesinde projeniziçin güzel renkler seçmenizi sağlar.
*/
body {
  background: #f5f5dc;
}

#first {
  /* 
    kırmızı rgb de elde etmek için kırmızı bölümüne denk gelen kısma 
    255 diğer kısımlara 0 yazarak elde edebiliriz.
    */
  color: rgb(255, 0, 0);
  background-color: rgb(0, 0, 0);
}

/* background-color ve background arasında bir fark yok */
#second {
  color: coral;
  background: rgb(141, 1, 141);
}

/* 
    RGBA'da en sondakiyle opaklık ayarı yapabiliriz.
        opaklık 1 e yaklasınca rgb'deki gibi oluyor 0'a yaklasınca daha da saydam oluyor
*/
#third {
  color: darkseagreen;
  background: rgba(141, 1, 141, 0.2);
}

/* RGBA'daki opaklık değeri 0 olunca tamamen beyaz renk oluyor. */
#four {
  color: rgb(44, 94, 187);
  background: rgba(14, 155, 84, 0);
}
```

> ## 22- PixelsFontsizeWidthHeight(PikselYazıtipiBoyutuGenişlikYükseklik)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>
      PixelsFontsizeWidthHeight(PikselYazıtipiBoyutuGenişlikYükseklik)
    </title>
    <link
      rel="stylesheet"
      href="./css/22- PixelsFontsizeWidthHeight(PikselYazıtipiBoyutuGenişlikYükseklik).css"
    />
  </head>
  <body>
    <h1>units in the css</h1>
    <h2>PixelsFontsizeWidthHeight(PikselYazıtipiBoyutuGenişlikYükseklik)</h2>
    <!--
        iç içe 2 div oluşturduk. ilk oluşturduğumuz div içerideki bütün divleri .. kapsar.
    -->
    <div class="outer">
      <div class="inner"></div>
    </div>

    <div>
      <h3 class="relative">relative</h3>
    </div>
    <div>
      <h3 class="absolute">absolute</h3>
    </div>

    <div class="r-div">
      <h3 class="rela">relative</h3>
    </div>
    <div class="a-div">
      <h3 class="abso">absolute</h3>
    </div>
  </body>
</html>
```

> ## 22- PixelsFontsizeWidthHeight(PikselYazıtipiBoyutuGenişlikYükseklik) .css

```css
/*
    Piksel -> ekrandaki bir noktayı temsil eder. 
        pikseller ekrandaki (genişlik ve yükseklikten etkilenmez.)
        Mutlak değer alır ve orada kalır.
        width -> genişlik
        height -> yükseklik
*/
h1 {
  font-size: 80px;
  width: 200px;
  height: 300px;
  background: violet;
}

/*
    Percent Values - Relative -> yüzde değerleri göreceli
        yüzdelik ifadeler ana ekrana göre ayarlanıyor. Değişiklik gösterebilir.
        50% yüzdelik kısım olduğu için yarısını kırmızı gösteriyor
        .outer kısmındaki genişlik ve yükseklik otomatikmen inner kısmınıda değiştiriyor.
*/
.outer {
  width: 500px;
  height: 500px;
  background: blue;
}
.inner {
  width: 50%;
  height: 50%;
  background: red;
}

/*
    Relative - Absolute -> Göreceli - Mutlak
        em - GÖRECELİK ebeveyne bağlıdır
        1em -> 16px varsayılan tarayıcı stili
        1em -> temel değer
        Tarayıcıdaki font size ayarı değiştiğinde relative bağlı font size ayarında değişecektir.
*/
div {
  font-size: 10px;
}

/* div'deki font-size ayarı em değerinin değişmesinede neden olur. */
.relative {
  font-size: 2em;
}
.absolute {
  font-size: 32px;
}

/*
    rem -> GÖRECELİK köke bağlıdır
    1rem -> 16px varsayılan tarayıcı stili
    rem'de değişiklik yapmak için en başta bulunan köke gidilmelidir. HTML'e
*/

/* 
    html'e bağlı olarak değişiklik gösteriyor. Aynı zamanda
    Tarayıcıdaki font size ayarı değiştiğinde relative bağlı font size ayarında değişecektir.
*/
html {
  font-size: 32px;
}

/* istediğimiz kadar divdeki font-size ayarıyla oynasakta rem de değişiklik olmadı */
.r-div,
.a-div {
  font-size: 80px;
}
.rela {
  font-size: 2rem;
}
.abso {
  font-size: 32px;
}
```

> ## 23- vh-vwValues

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>vh-vwValues</title>
    <link rel="stylesheet" href="./css/23- vh-vwValues.css" />
  </head>
  <body>
    <div class="header"></div>
    <div class="banner"></div>
  </body>
</html>
```

> ## 23- vh-vwValues .css

```css
/*
    vh -> yükseklik - ekran yüzdesi - ekran değişimine bağlı olarak oranı anlık anlık olarak değişir 
    vw -> genişlik - ekran yüzdesi 
    küçük - büyük ekrana (istediğimiz boyuttaki ekrana) bağlı olarak anlık olarak değişimi gösterilir.
*/
/* 
    margin -> kenardaki boşlukları 0'lıyoruz. 
    padding -> içerideki boşluklarla alakalı
    box-sizing: border-box -> genişlik ve yüksekliğe dolgu ve kenarlık eklenir
*/

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.banner {
  width: 50vw;
  height: 50vh;
  background: red;
}
.header {
  width: 100vw;
  height: 100vh;
  background: blue;
}
```

> ## 24- calcFunction(matematikselFonks)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>calcFunction</title>
    <link rel="stylesheet" href="./css/24- calcFunction.css" />
  </head>
  <body>
    <!--
        Gezinme çubuğu
    -->
    <div class="navbar">This is navbar</div>

    <!--    
        Afiş
    -->
    <div class="banner"></div>
  </body>
</html>
```

> ## 24- calcFunction(matematikselFonks) .css

```css
/*
Calc()
Perform math operations - Matematiksel işlemler yap (+ - * /)
Mix and match values - Değerleri karıştır ve eşleştir.
*/

/* Varsayılan stili sıfırlıyoruz. */
* {
  margin: 0;
}
.navbar {
  /* arkaplan rengi */
  background: blue;
  /* yükseklik */
  height: 100px;
  /* yazı rengi */
  color: white;
  /* html deki varsayılan ayara göre yazı boyutu belirleniyor */
  font-size: 3rem;
}
.banner {
  background: red;
  /* 
        Matematiksel işlemleri yapmak için calc()'ı kullanıyoruz.
        banner'de 100px ve ekranı yüzde yüz görmek için ; 
        100vh'dan 100px'i çıkarıyoruz.
        işlemleri yaparken aralarında boşluk bırakılmalıdr.
    */
  min-height: calc(100vh - 100px);
}
```

> ## 25- font-stackGenericFonts(yazı_tipi_yığını-genel_yazı_tipleri)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>font-stackGenericFonts(yazı_tipi_yığını-genel_yazı_tipleri)</title>
    <link
      rel="stylesheet"
      href="./css/25- font-stackGenericFonts(yazı_tipi_yığını-genel_yazı_tipleri).css"
    />
    <!--
        Google Fonts
    -->
    <!--
            <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Damion&family=Roboto:ital,wght@0,400;1,700&display=swap"
      rel="stylesheet"
    />
    -->
  </head>
  <body>
    <h1 class="main">Hey dude i'm main heading</h1>
    <p class="one">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quia aliquid
      incidunt mollitia quae distinctio, repellendus tempora deleniti asperiores
      rerum omnis ipsum placeat alias
    </p>
    <h1 class="subheading">Subheading</h1>
    <p class="two">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cumque quis odio
      tempore exercitationem quae debitis error voluptatum perferendis nemo.
      Reiciendis quod omnis hic laborum culpa?
    </p>
  </body>
</html>
```

> ## 25- font-stackGenericFonts(yazı_tipi_yığını-genel_yazı_tipleri) .css

```css
/*
    Google Fonts
    https://fonts.google.com sitesi üzerinden istediğimiz yazı stilinin html link'ini ve css kodunu alabilir.
    Roboto ve Damion yazı stili için aldık.
*/

/* 
    Yazı tipleri seçip import kısmına gelerek kullanmak istediğimiz yazı tipini import edebiliriz. 
    Html'de kullandığımız link'e gerek kalmıyor
    */

@import url("https://fonts.googleapis.com/css2?family=Damion&family=Roboto:ital,wght@0,400;1,700&display=swap");

body {
  font-family: "Roboto", sans-serif;
}

.main {
  font-family: "Damion", cursive;
  text-align: right; /* metni hizalamak -> sağ */
}
.one {
  font-weight: 500; /* yazı kalınlığı */
  font-style: italic; /* metin stili italik-kalın-normal vs. */
  text-indent: 150px; /* paragraf başlığı girintisi */
  text-align: left;
}
.two {
  font-weight: bolder;
  text-align: center;
}
```

> ## 26- textProperties(metinOzellikleri)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>textProperties(metinOzellikleri)</title>
    <link
      rel="stylesheet"
      href="./css/26- textProperties(metinOzellikleri).css"
    />
  </head>
  <body>
    <a href="">GOOGLE</a>
    <h1>hey i'm the main heading</h1>
    <p class="one">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa, eum ullam?
      Fugiat unde consequuntur nam fugit error odit sint molestiae blanditiis
      dolorum, sed praesentium a. Suscipit saepe excepturi, eligendi tempora,
      explicabo asperiores temporibus pariatur, quasi dolor neque qui quibusdam.
      Aspernatur illum architecto adipisci labore. Et laudantium inventore
      soluta alias itaque.
    </p>
    <p class="two">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa, eum ullam?
      Fugiat unde consequuntur nam fugit error odit sint molestiae blanditiis
      dolorum, sed praesentium a. Suscipit saepe excepturi, eligendi tempora,
      explicabo asperiores temporibus pariatur, quasi dolor neque qui quibusdam.
      Aspernatur illum architecto adipisci labore. Et laudantium inventore
      soluta alias itaque.
    </p>
    <p class="three">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa, eum ullam?
      Fugiat unde consequuntur nam fugit error odit sint molestiae blanditiis
      dolorum, sed praesentium a. Suscipit saepe excepturi, eligendi tempora,
      explicabo asperiores temporibus pariatur, quasi dolor neque qui quibusdam.
      Aspernatur illum architecto adipisci labore. Et laudantium inventore
      soluta alias itaque.
    </p>
  </body>
</html>
```

> ## 26- textProperties(metinOzellikleri) .css

```css
/*
    text-transform -> text dönüşümü
        uppercase -> her harf büyük
        capitalize -> her kelime büyük harfle başlar
        lowercase -> her harf küçük
*/
h1 {
  text-transform: lowercase; /*text dönüşümü */
}
/*
    text-decoration -> metin dekorasyonu
        none -> bir şey yok (sade hal)
        line-through -> üstü çizgili
        overline -> üstü çizgili
        underline -> altı çizgili
*/
a {
  font-size: 40px; /* yazı boyutu */
  text-decoration: none; /* metin dekorasyonu */
}
.one {
  line-height: 2.5em; /* her satır arasındaki boşluklar. */
  text-decoration: line-through;
}
.two {
  letter-spacing: 5px; /* harfler arasındaki boşluk */
  text-decoration: overline;
  line-height: 2rem;
}
.three {
  word-spacing: 20px; /* kelimeler arasındaki boşluk */
  text-decoration: underline;
}
```

> ## 27- boxModel(kutuModel)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>boxModel(kutuModel)</title>
    <link rel="stylesheet" href="./css/27- boxModel(kutuModel).css" />
  </head>
  <body>
    <h1>Hello ı would like to learn about css box model!</h1>
    <p class="pbox">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Inventore velit
      veritatis quidem, atque quisquam tenetur optio quos at placeat quasi.
    </p>
    <p class="pbox1">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Inventore velit
      veritatis quidem, atque quisquam tenetur optio quos at placeat quasi.
    </p>
    <p class="pbox2">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Inventore velit
      veritatis quidem, atque quisquam tenetur optio quos at placeat quasi.
    </p>
    <p class="pbox3">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Inventore velit
      veritatis quidem, atque quisquam tenetur optio quos at placeat quasi.
    </p>
    <p class="pbox4">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Inventore velit
      veritatis quidem, atque quisquam tenetur optio quos at placeat quasi.
    </p>
    <p class="pbox5">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Inventore velit
      veritatis quidem, atque quisquam tenetur optio quos at placeat quasi.
    </p>
  </body>
</html>
```

> ## 27- boxModel(kutuModel) .css

```css
/* 
    CSS BOX MODEL
        padding -> dolgu (iç)
        margin -> kenar boşluğu (dış)   =****= "-" negatif değer alırsa tam tersi kenar boşluğu sağlanır. =****=
            X: ? -> her taraftan aynı oranda
            X-top: ? -> üst
            X-bottom: ? -> alt
            X-left: ? -> sol
            X-right: ? -> sağ
            X: ?1 ?2 -> ?1(üst-alt) ?2(sağ-sol)
            X: ?1 ?2 ?3 ?4 -> ?1(üst) ?2(sağ) ?3(alt) ?4(sol)
        border -> sınır çizgisi
            border-color -> sınır çizgi rengi
            border-width -> sınır çizgi kalınlığı
            border-style -> sınır çizgi stili
            border: ?1 ?2 ?3 -> tek satırda ?1(piksel) ?2 çizgi stili ?3 çizgi rengi
            border-bottom-style -> alt sınır çizgi stili (üst sağ sol aynı şekilde) 
                Sınır çizgi stilleri;
                solid -> kutu halinde (düz çizgi)
                dashed -> kesikli çizgi
                dotted -> nokta nokta
            border-radius -> yarıçap - sınır çizgisine ovallik veriyoruz (en fazla 50px verebiliriz.)


*/

h1 {
  background: red;
  /* ------- padding ------- */
  padding-top: 30px; /* yukarıdan dolgu boşluk verir. */
  padding-bottom: 30px; /* aşağıdan dolgu boşluk verir. */
  padding-left: 10px; /*soldan dolgu boşluk verir. */
  padding-right: 70px; /*sağdan dolgu boşluk verir */
  /* ------- margin ------- */
  margin-right: 20px; /* sağdan kenar boşluğu */
  margin-bottom: 50px; /* alt kenar boşluğu */
  margin-top: 40px; /* üst kenar boşluğu */
  margin-left: 30px; /* sol kenar boşluğu */
  /* ------- border ------- */
  border-style: solid; /* sınır çizgileri */
  border-width: 10px; /* sınır çizgilerin kalınlığı */
  border-color: blueviolet; /* sınır çizgilerin rengi */
}
.pbox {
  background: violet;
  /* ------- padding ------- */
  padding: 50px; /* sağ sol yukarı ve aşağıdan dolgu boşluk verir. */
  /* ------- margin ------- */
  margin: 10px; /* bütün kenar boşluklarını aynı oranda ektiler */
  /* ------- border ------- */
  border: 15px solid chocolate; /*tek bir satırda sınır çizgilerini belirttik. */
}

/* 
    pbox1 ile pbox2 box kutularının kenar boşluğu alnıp ikisi bir görünmesi için;
        pbox1'in alt kenar boşluğu - pbox2'in üst kenar boşluğu sıfırlanmalıdır 
*/
.pbox1 {
  background: turquoise;
  /* ------- padding ------- */
  padding: 30px 60px; /* sağ ve soldan 60px yukarıdan ve aşağıdan 30px dolgu boşluğu*/
  /* ------- margin ------- */
  margin-bottom: 0px;
  /* ------- border ------- */
  border-bottom-style: dashed; /* alt sınır çizgi stili  dashed -> kesikli çizgi dotted -> nokta nokta */
  border-width: 5px; /* alt sınır çizgi kalınlığı */
  border-color: darkgoldenrod; /* alt sınır çizgi rengi */
}
.pbox2 {
  background: skyblue;
  /* ------- padding ------- */
  padding: 20px 70px 40px 50px; /* 20px -> üst; 70px -> sağ; 40px -> aşağı;  50px -> sol  dolgu boşluğu*/
  /* ------- margin ------- */
  margin-top: 0px;
}

.pbox3 {
  background: slategrey;
  /* ------- margin ------- */
  margin: 30px 60px; /* yukarı ve aşağıdan 30px - alt ve üstten 60 px kenar boşluğu */
  /* ------- border ------- */
  border: 5px solid orangered; /* tek satırda sınır çizgisi */
  border-radius: 15px; /* sınır çizgisine ovallik veriyoruz */
}
.pbox4 {
  background: rgb(215, 233, 149);
  /* ------- margin ------- */
  margin: 20px 60px 40px 30px; /* 20px -> üst  60px -> sağ 40px -> alt 30px ->sol kenar boşluğu*/
  /* ------- border ------- */
  border: 5px solid gold; /* tek satırda sınır çizgisi */
  border-radius: 50px; /* sınır çizgisine ovallik veriyoruz */
}
.pbox5 {
  background: rosybrown;
  border: 12px solid blue;
  border-radius: 15px;
  margin-top: -60px; /* negatif yönde kenar boşluğu */
}
```

> ## 28- outlineProperty(anahatOzelligi)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>outlineProperty(anahatOzelligi)</title>
    <link
      rel="stylesheet"
      href="./css/28- outlineProperty(anahatOzelligi).css"
    />
  </head>
  <body>
    <div class="buttons">
      <a href="#" id="one">no outline</a>
      <a href="#" id="two">outline</a>
    </div>
  </body>
</html>
```

> ## 28- outlineProperty(anahatOzelligi) .css

```css
.buttons {
  margin: 3rem; /*kenar uzunluğu dış*/
}
a {
  background: #689f3f; /* arkaplan rengi */
  text-decoration: none;
  padding: 1.2rem 1.5rem; /* dolgu iç kısım */
  color: #222;
  text-transform: uppercase; /* metin dönüşümü büyük harf */
  cursor: pointer; /* imleç */
  margin: 0 20px;
}
#one {
  border: 0.2rem solid #222; /* sınır çizgisi */
}
#two {
  /* outline öğeyi ön plana çıkarmak için kullanılıyor. sınırların dışında öğenin etrafına çizilen bir çizgidir. */
  outline-color: 0.2rem;
  outline-style: solid;
  outline-color: #222;
  outline: 0.2rem solid #222; /* outline tek satır halinde yazılışı */
  outline-offset: 10px; /* öğenin 10px (üst - alt - sağ - sol) aynı oranda dışarıda solid(kutunun) oluşturulması */
  outline-offset: -15px; /* içeride */
}
```

> ## 29- blockInline

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>blockInline</title>
    <link rel="stylesheet" href="./css/29- blockInline.css" />
  </head>
  <body>
    <!--
        blok elementler yeni satırda başlarlar. 
        çizgideki elementler aynı satırda devam ederler.
    -->
    <div class="block">i'm block element</div>
    <h1 class="block">i'm block element</h1>
    <p class="block">i'm block element</p>
    <span class="inline">i'm inline element</span>
    <a href="#" class="inline">i'm inline element</a>
    <img
      src="./Images/display1.jpg"
      alt="display-photo"
      width="50vw"
      class="inline"
    />
  </body>
</html>
```

> ## 29- blockInline .css

```css
/*
    Blok -> her zaman yeni bir satır başlatır ve tam genişlik alır.
    inline(çizgideki) -> yeni satıra başlamaz ve yalnızca çok fazla kül içeriği alanı kaplar.
*/

.block {
  background: violet;
  color: bisque;
  /* blok elementi inline element yapmak için; */
  display: inline;
}
.inline {
  background: tomato;
  color: darkred;
  /* inline elementi blok elementi yapmak için; */
  display: block;
}
```

> ## 30- horizontalCentering(yatayMerkezleme)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>horizontalCentering(yatayMerkezleme)</title>
    <link
      rel="stylesheet"
      href="./css/30- horizontalCentering(yatayMerkezleme).css"
    />
  </head>
  <body>
    <div class="block">i'm block element</div>
    <h1 class="block">i'm block element</h1>
    <p class="block">i'm block element</p>

    <div class="block1">i'm block element</div>
    <h1 class="block1">i'm block element</h1>
    <p class="block1">i'm block element</p>

    <span class="inline">i'm inline element</span>
    <a href="#" class="inline">i'm inline element</a>
    <img src="./Images/display1.jpg" alt="" class="inline" width="50" />
  </body>
</html>
```

> ## 30- horizontalCentering(yatayMerkezleme) .css

```css
/* Horizontal Centering -> Yatay Merkezleme */
* {
  text-align: center; /* merkeze alma */
}
.block {
  background: yellowgreen;
  color: black;
  /* bu durumda genişlik verildiği için merkeze margin ile alabiliriz.*/
  width: 150px;
  /* margin ile merkeze alma 1.yol */
  margin: 20px auto; /* üst ve alt -> 20px sağ ve sol -> otomatik */
}
.block1 {
  background: rgb(91, 50, 205);
  color: black;
  /* bu durumda genişlik verildiği için merkeze margin ile alabiliriz.*/
  width: 150px;
  /* margin ile merkeze alma 2.yol */
  margin-left: auto;
  margin-right: auto;
}
.inline {
  background: turquoise;
  color: darkgreen;
}
```

> ## 31- mobileNavbar(mobilGezinmeCubugu)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>mobileNavbar(mobilGezinmeCubugu)</title>
    <link
      rel="stylesheet"
      href="./css/31- mobileNavbar(mobilGezinmeCubugu).css"
    />
  </head>
  <body>
    <ul>
      <li><a href="#">home</a></li>
      <li><a href="#">about us</a></li>
      <li><a href="#">products</a></li>
      <li><a href="#">contact us</a></li>
    </ul>
  </body>
</html>
```

> ## 31- mobileNavbar(mobilGezinmeCubugu) .css

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
ul li {
  list-style-type: none; /* listenin başında imleçler - listelerin nasıl sıralanacağını gösterir.*/
}
ul li a {
  text-decoration: none; /* metin dekorasyonunu sıfırlıyor. - link oluduğu için altındaki çizgi siliniyor*/
  text-transform: capitalize; /* her kelime büyük harfle başladı. */
  letter-spacing: 2px; /* harfler arasında boşluk bıraktık. */
  background: #222;
  color: red;
  display: block;
  padding: 10px 10px;
  margin: 10px 0px;
}
```

> ## 32- boxSizing-borderBox(kutuBoyutlandırma-kenarlıkKutusu)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>boxSizing-borderBox(kutuBoyutlandırma-kenarlıkKutusu)</title>
    <link
      rel="stylesheet"
      href="./css/32- boxSizing-borderBox(kutuBoyutlandırma-kenarlıkKutusu).css"
    />
  </head>
  <body>
    <div class="box1"><h1>i'm with border-box</h1></div>
    <div class="box2"><h1>i'm normal</h1></div>
    <div class="box3"><h1>i'm without border-box</h1></div>
  </body>
</html>
```

> ## 32- boxSizing-borderBox(kutuBoyutlandırma-kenarlıkKutusu) .css

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box; /* kullanılan bütün kutuların aynı boyutta olmasını sağlar */
}
.box1,
.box2,
.box3 {
  width: 200px;
  height: 200px;
  color: white;
}
.box1 {
  background: red;
  padding: 20px;
}
.box2 {
  background: blue;
}
.box3 {
  background: green;
  padding: 20px;
}
```

> ## 33- opacityVisibility(opaklikGorunurluk)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>opacityVisibility(opaklikGorunurluk)</title>
    <link
      rel="stylesheet"
      href="./css/33- opacityVisibility(opaklikGorunurluk).css"
    />
  </head>
  <body>
    <div class="none">none</div>
    <div class="opacity-1">opacity-1</div>
    <div class="opacity-5">opacity-5</div>
    <div class="opacity-0">opacity-0</div>
    <div class="visibility">visibility</div>
  </body>
</html>
```

> ## 33- opacityVisibility(opaklikGorunurluk) .css

```css
div {
  background: blue;
  color: white;
  margin: 10px;
}
.none {
  display: none; /* ekranda gösterilmiyor - öğeden tamamen kurtulmak isteniyorsa */
}
.opacity-1 {
  opacity: 1; /* saydamlığı 1 tam olarak görünüyor. - görünümü sadece şeffaf oluyor. */
}
.opacity-5 {
  opacity: 0.5;
}
.opacity-0 {
  opacity: 0; /* saydamlığı sıfır olduğu için ekranda görünmüyor. */
}
.visibility {
  visibility: hidden; /* görünümü hidden olduğu için ekranda görünmüyor. */
}
```

> ## 34- backgroundImages(arkaplanGoruntusu)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>backgroundImages(arkaplanResimleri)</title>
    <link
      rel="stylesheet"
      href="./css/34- backgroundImages(arkaplanGoruntusu).css"
    />
  </head>
  <body>
    <div class="big-image">
      <h1>BIG IMAGE</h1>
    </div>
    <div class="small-image">
      <h1>SMALL IMAGE</h1>
    </div>
    <div class="folder-image">
      <h1>FOLDER IMAGE</h1>
    </div>
  </body>
</html>
```

> ## 34- backgroundImages(arkaplanGoruntusu) .css

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
div {
  min-height: 100vh;
  color: green;
  font-size: 60px;
  display: flex; /* kayan nokta veya konumlandırma kullanmadan esnek duyarlı düzen yapısı tasarlamayı kolaylaştırır. */
  justify-content: center; /* Ürün ana ekseni (yatay) kullanılabilir alanın tamamını kullanmadığınızda mülkiyet esnek kabın öğeleri hizalar. */
  align-items: center; /* Mülkiyet esnek kap içindeki öğeler için varsayılan hizalamasını belirtir. */
}
.big-image {
  background: url("/Course/Images/back-big.jpeg");
  background-repeat: round; /* arkaplan görüntüsü pikselde bozulmalar meydana gelmeyerek tekrarlanır. */
  background-size: cover; /* arkaplan görüntüsü bulunduğu alanı doldurur. pikselde bozulmalar meydana gelebilir. */
}
.small-image {
  border: 3px solid green;
  background: url("/Course/Images/back-small.jpeg");
  /* Arkaplan görüntüsünün tekrarlanma durumu */
  background-repeat: repeat; /* arkaplan görüntüsünü hem dikey hem yatay olarak tekrarlanır */
  background-repeat: repeat-x; /* arkaplan görüntüsünü yatay olarak tekrarlanır */
  background-repeat: repeat-y; /* arkaplan görüntüsünü dikey olarak tekrarlanır */
  background-repeat: space; /* arkaplan görüntüsünü görüntüler arasında boşluk olacak şekilde tekrarlanır */
  background-repeat: round; /* arkaplan görüntüsü boşluğu doldurmak görüntü tekrarlanır. orantısı bozulur. */
  background-repeat: no-repeat; /* arkaplan görüntüsünü tekrarlamaz. */
  /* Arkaplan görüntüsünün konumu */
  background-position: center; /* arkaplan görüntüsünü merkeze sabitler */
  background-position: bottom; /* arkaplan görüntüsünü sağ ve solda eşit olarak altta görünmesini sağlar */
  background-position: top; /* arkaplan görüntüsünü sağ ve solda eşit olarak üstte görünmesini sağlar */
  background-position: left; /* arkaplan görüntüsünü alt ve üstte eşit olarak solda görünmesini sağlar */
  background-position: right; /* arkaplan görüntüsünü alt ve üstte eşit olarak sağda görünmesini sağlar */
  background-position: 0 0; /* background-position: ?1 ?2 -> ?1(X-ekseni) ?2(Y-ekseni) */
  background-position: 20% 70%; /* background-position: 20% 70% -> 20%(X-ekseni) 70%(Y-ekseni) */
}
.folder-image {
  background: url("/Course/Images/back-folder.jpeg");
  background-size: contain; /* arkaplan görüntüsünün görünür olmasını sağlar görüntüyü tamamen boyutlandırır. */
  background-repeat: no-repeat;
}
```

> ## 35- backgroundAttachment(arkaplanEk)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>backgroundAttachment(arkaplanEk)</title>
    <link
      rel="stylesheet"
      href="./css/35- backgroundAttachment(arkaplanEk).css"
    />
  </head>
  <body>
    <div class="big-img">BİG İMG</div>
    <div class="folder-img">FOLDER İMG</div>
    <div class="big-img">BİG İMG</div>
  </body>
</html>
```

> ## 35- backgroundAttachment(arkaplanEk) .css

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
div {
  min-height: 100vh;
  color: rgb(255, 0, 0);
  font-size: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.big-img {
  background: url(/Course/Images/back-big.jpeg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed; /* Arka plan resminin sayfa geri kalanı ile kayar */
}
.folder-img {
  background: url(/Course/Images/back-folder.jpeg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed; /* Arka plan resminin sayfa geri kalanı ile kayar */
}
```

> ## 36- linearGradients

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>linearGradients</title>
    <link rel="stylesheet" href="./css/36- linearGradients.css" />
  </head>
  <body>
    <div class="one"></div>
    <div class="two"></div>
    <div class="three"></div>
    <div class="four"></div>
    <div class="five"></div>
    <div class="six"></div>
  </body>
</html>
```

> ## 36- linearGradients .css

```css
div {
  height: 150px;
  width: 150px;
  margin: 10px;
}
.one {
  background: linear-gradient(red, yellow); /* üstten altta */
}
.two {
  background: linear-gradient(
    to top,
    red,
    yellow,
    blue,
    green
  ); /* alttan üste */
}
.three {
  background: linear-gradient(
    315deg,
    red,
    yellow
  ); /* 315 dereceyle üstten aşağıya */
}
.four {
  background: linear-gradient(to top right, red, yellow); /* sağ alttan üstte */
}
.five {
  background: linear-gradient(
    rgba(0, 0, 0, 0.2),
    rgba(0, 0, 0, 0.8)
  ); /* aynı işlem rgba içinde yapılabilir. */
}
.six {
  background: linear-gradient(
    to left,
    rgba(0, 0, 0, 0.2),
    rgba(0, 0, 0, 0.8)
  ); /* sağdan sola */
}
```

> ## 37- backgroundImage-shortcutsCombined(arkaplanResmi-kısayollarıKombine)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>
      backgroundImage-shortcutsCombined(arkaplanResmi-kısayollarıKombine)
    </title>
    <link
      rel="stylesheet"
      href="./css/37- backgroundImage-shortcutsCombined(arkaplanResmi-kısayollarıKombine).css"
    />
  </head>
  <body>
    <div class="banner"><h1>Hello World</h1></div>
    <div class="header"><h1>Hello People</h1></div>
    <div class="colorzilla"></div>
  </body>
</html>
```

> ## 37- backgroundImage-shortcutsCombined(arkaplanResmi-kısayollarıKombine) .css

```css
/* 
    https://www.colorzilla.com/gradient-editor/ sitesinde gradient seçilebiliyor.
*/
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
div {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  font-size: 60px;
  color: orange;
}
.banner {
  background: url("/Course/Images/back-big.jpeg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
/* tek satır halinde yazılabiliyor. */
.header {
  background: linear-gradient(rgba(134, 103, 103, 0.5), rgba(0, 0, 0, 0.5)),
    url(/Course/Images/back-big.jpeg) center/cover no-repeat fixed;
}
.colorzilla {
  /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#2bef38+0,3a5eff+47,ff3a3a+100 */
  background: rgb(43, 239, 56); /* Old browsers */
  background: -moz-linear-gradient(
    -45deg,
    rgba(43, 239, 56, 1) 0%,
    rgba(58, 94, 255, 1) 47%,
    rgba(255, 58, 58, 1) 100%
  ); /* FF3.6-15 */
  background: -webkit-linear-gradient(
    -45deg,
    rgba(43, 239, 56, 1) 0%,
    rgba(58, 94, 255, 1) 47%,
    rgba(255, 58, 58, 1) 100%
  ); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(
    135deg,
    rgba(43, 239, 56, 1) 0%,
    rgba(58, 94, 255, 1) 47%,
    rgba(255, 58, 58, 1) 100%
  ); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#2bef38', endColorstr='#ff3a3a',GradientType=1 ); /* IE6-9 fallback on horizontal gradient */
}
```

> ## 38- floatPosition(resmin-yuzmeOzelligi)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>floatPosition(resmin-yuzmeOzelligi)</title>
    <link
      rel="stylesheet"
      href="./css/38- floatPosition(resmin-yuzmeOzelligi).css"
    />
  </head>
  <body>
    <div class="bar">
      <img src="./Images/back-small.jpeg" class="one" alt="nice view" />
      <img src="./Images/back-small.jpeg" class="two" alt="nice view" />
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quos,
        quibusdam impedit nisi tempore eaque porro unde excepturi praesentium
        saepe soluta, ratione facilis aspernatur, obcaecati quidem commodi ipsa
        dolore nemo? Consequatur repellat sequi iure earum iste qui accusantium,
        eligendi harum minima! Voluptate repellat maiores consectetur ipsum quos
        eius officia nulla? Fugiat.
      </p>
    </div>
  </body>
</html>
```

> ## 38- floatPosition(resmin-yuzmeOzelligi) .css

```css
.bar {
  border: 5px solid red;
  padding: 10px;
}

.one {
  float: left;
  height: 250px;
}
.two {
  float: right;
}
p {
  clear: right;
}
```

> ## 39- float-propertyColumn-Layout(yüzmeSutun)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>float-propertyColumn-Layout(yüzmeSutun)</title>
    <link
      rel="stylesheet"
      href="./css/39- float-propertyColumn-Layout(yüzmeSutun).css"
    />
  </head>
  <body>
    <div class="one">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim, nam!
    </div>
    <div class="two">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim, nam!
    </div>
    <div class="three">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim, nam!
    </div>
    <div class="three">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim, nam!
    </div>
    <h1>Hello World</h1>
  </body>
</html>
```

> ## 39- float-propertyColumn-Layout(yüzmeSutun) .css

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
div {
  float: left;
  height: 200px;
  width: 33.33%;
}
.one {
  background: rebeccapurple;
}
.two {
  background: rgb(51, 153, 102);
}
.three {
  background: red;
}
h1 {
  clear: both;
}
```

> ## 40- positionStatic(durgunKonum)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>positionStatic(durgunKonum)</title>
    <link rel="stylesheet" href="./css/40- positionStatic(durgunKonum).css" />
  </head>
  <body>
    <div>
      <p class="one">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis porro
        repellat debitis tempore officiis animi quo illum. Minima quos
        voluptatem ipsa incidunt quas at doloremque, ad culpa quam recusandae.
        Eveniet, illum aperiam odit molestias minus alias consequuntur.
        Accusantium, quam sequi.
      </p>
      <p class="two">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis porro
        repellat debitis tempore officiis animi quo illum. Minima quos
        voluptatem ipsa incidunt quas at doloremque, ad culpa quam recusandae.
        Eveniet, illum aperiam odit molestias minus alias consequuntur.
        Accusantium, quam sequi.<span class="special">Hey i'm absolute</span>
      </p>
    </div>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam deserunt
      velit dolorem perspiciatis vero rerum autem ea, temporibus placeat
      voluptate ullam omnis reprehenderit eos vitae pariatur nobis ipsum?
      Explicabo deleniti atque incidunt iusto repellendus! Soluta cumque, vero
      cum aspernatur a quasi obcaecati repellendus, voluptas, commodi assumenda
      odio molestias? Sequi culpa eius ab, reiciendis optio excepturi. Id,
      repellendus voluptatem corporis consectetur consequatur, dolores odit
      iusto nam ipsam quasi, fugit quis ratione modi sapiente ipsum nisi aliquam
      illum praesentium vitae? Sint necessitatibus deserunt voluptatibus
      asperiores reprehenderit dolor obcaecati, nobis quasi ex blanditiis,
      architecto tempora! Deserunt perspiciatis a libero, rerum neque harum
      ducimus esse aliquid aspernatur! Dolore id voluptatem illum quas veniam
      hic exercitationem error, dolor ipsum eum animi quos suscipit, magni ut
      corporis nam rem! Ipsa, dolorem numquam dicta officia sint quae,
      architecto tempore explicabo quibusdam nihil, fugit aliquid accusamus sed
      ex neque. Est, dicta iure. Eaque, laudantium nobis itaque tempora, aperiam
      ex nesciunt tempore quis minus facere enim, modi explicabo! Natus sunt
      voluptatem impedit temporibus quis libero repellat repudiandae rerum? Modi
      nesciunt quo, debitis molestiae, animi error aperiam quisquam odio
      recusandae placeat necessitatibus rerum adipisci aliquid porro cupiditate.
      Consequatur ipsam iste optio eius cupiditate exercitationem cum, vitae
      ratione at nemo. Tempora, pariatur nam ipsa qui nihil dolore enim
      dignissimos deleniti eum fugit necessitatibus saepe repellat, nobis quis!
      Deserunt ducimus laborum aliquid natus harum asperiores nam repellendus
      officiis hic assumenda? Architecto corrupti nesciunt accusantium
      perferendis eligendi. Velit id quis, tempora nesciunt explicabo blanditiis
      placeat molestiae earum debitis repudiandae corporis excepturi, mollitia
      cum doloremque laborum temporibus, eligendi expedita hic deleniti fuga.
      Totam sint quas nobis sed dolorem vel possimus quia ipsa consequatur culpa
      porro officiis sapiente, blanditiis natus molestiae, amet minima provident
      odit similique ipsum inventore neque? Nihil, maiores facere. Incidunt,
      animi non! Magnam, odio dolore. Voluptates autem error quidem eos eaque
      aliquam expedita earum nam facilis ducimus accusantium quo, perspiciatis
      quasi voluptatum minus ea repudiandae in atque hic repellat quia maiores
      assumenda et? Veniam dicta dolorem molestias beatae praesentium aut
      maxime, est, vitae quidem, error totam. Voluptatibus placeat dolorem natus
      animi impedit, laudantium tenetur, nobis consequuntur delectus tempore
      consectetur quidem ipsam voluptatem quas nulla dolore reprehenderit fugiat
      repellat error a qui! Nesciunt quae saepe voluptas fuga quod laborum
      delectus itaque quam dolorum rerum atque autem vitae accusantium hic cum
      temporibus mollitia voluptate, sunt laudantium non similique in animi
      ullam. Ea quisquam deserunt fugiat reprehenderit ullam praesentium
      veritatis dolores consequuntur culpa, ipsam totam nisi laborum ipsum
      libero tempore quam maxime officia rem sit non, accusamus facere commodi
      est eveniet! Delectus reprehenderit quidem perferendis beatae provident,
      neque praesentium, quod fugiat odio quam amet eligendi inventore quia
      numquam cupiditate modi placeat quibusdam at reiciendis quo hic. Nulla
      veniam nemo voluptatum natus aspernatur enim dolorem, molestiae doloremque
      deleniti voluptates quia unde dolorum similique, dignissimos iste neque
      suscipit rem vel recusandae optio. Quaerat voluptatibus laudantium ab non
      nam placeat, cum, fugit iusto praesentium, corporis dignissimos accusamus
      alias ut id dolorem. Aliquid, facilis et. Sequi fuga quas ducimus, error
      officia nisi eveniet labore! Recusandae dolores qui odio saepe!
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum,
      recusandae delectus. Iure facere adipisci molestiae eius recusandae
      deleniti nostrum, magnam illo vel porro minus omnis dolorem est error
      delectus cum aut? Consectetur accusantium explicabo veritatis asperiores
      repellat voluptatibus cupiditate in! Obcaecati est, quos hic quam earum
      illum, reprehenderit veritatis eaque optio voluptatem asperiores eos
      consectetur? Nulla quod itaque nesciunt sit sunt ducimus. Qui impedit,
      dolorem voluptatem quo perspiciatis excepturi placeat quod enim autem,
      iste tempora atque repellendus deserunt hic quae expedita quisquam? Culpa
      ad nulla eveniet cupiditate? Quaerat dolorem ipsum assumenda ad sed,
      laboriosam facilis, excepturi veniam minima expedita quos aliquam natus
      mollitia? Fugit, modi quam beatae, assumenda esse molestias tenetur,
      provident eos pariatur ipsam nostrum officiis tempore voluptatibus. A quae
      molestias veritatis cumque numquam nostrum recusandae unde doloremque
      architecto quos aliquam tempora dicta accusantium, vitae, maiores autem
      debitis omnis. Dignissimos consequuntur soluta magni iusto numquam, ullam
      voluptatibus aliquid velit nihil debitis voluptate? Iure iste aperiam
      porro nisi, voluptates quasi praesentium aliquid aspernatur temporibus hic
      nulla nam laboriosam, possimus doloribus quisquam nesciunt in esse eveniet
      quaerat suscipit tempora earum accusantium vitae. Quia ex eius beatae unde
      totam magnam provident, fugit nobis, velit facere vitae officia ipsa vero
      doloribus, mollitia saepe? Et corporis distinctio sit ipsum eum
      dignissimos porro ex, iusto placeat est consectetur! Asperiores iure at
      reprehenderit voluptatem, pariatur eveniet eum numquam, earum quos aliquam
      magni ad. Nihil, omnis rerum dolor blanditiis incidunt quis necessitatibus
      ducimus? Ea facere necessitatibus quae aliquid veniam, mollitia voluptates
      omnis, dolorum reiciendis sit incidunt. Tempore, tempora. Maxime, numquam.
      Necessitatibus perferendis veniam quis numquam distinctio modi aut sit
      expedita! Animi tempore dolore sapiente rerum quas a. Sequi mollitia
      aspernatur fugiat? Asperiores repellat fuga eius unde consequuntur
      corporis soluta nesciunt sequi consequatur molestiae non voluptatibus
      repellendus delectus labore quia suscipit et voluptates, ea ipsa odio,
      explicabo animi illo optio? Odit ullam necessitatibus aliquam deserunt
      voluptate dolore corporis sequi, tempora in eum inventore perferendis
      quidem asperiores atque molestias sapiente, aut unde aperiam omnis nulla,
      autem amet. Ratione tempore asperiores quo, quibusdam possimus accusantium
      corrupti maiores architecto in facilis debitis eligendi? Ducimus repellat
      ab tempora totam accusamus, consequatur quas eius, perspiciatis dicta
      dolore aliquam iste voluptatibus dolor autem quod? Exercitationem
      consectetur laboriosam, illum laborum quod facilis praesentium ab saepe
      nostrum aperiam cupiditate sed adipisci doloribus tempora assumenda
      nesciunt perspiciatis, itaque velit! Cum asperiores perspiciatis soluta
      vero quis dolorem ex quas nostrum sint? Commodi dolore placeat, at sint
      temporibus sapiente adipisci expedita fugit, magnam ipsum provident. Earum
      officiis molestias asperiores. Quisquam ipsa, praesentium non optio
      blanditiis asperiores inventore laborum distinctio architecto, nulla
      similique quos quam dolores cum aspernatur corporis. Aut minima quae nihil
      sint sapiente quod, magnam beatae. Inventore nemo perspiciatis quisquam
      placeat ut animi rerum recusandae alias, accusamus odit incidunt numquam
      ea veniam, accusantium debitis explicabo. Id alias facilis magni quaerat
      sint temporibus dolorum illo accusantium voluptate reiciendis eos eveniet,
      error ullam delectus nobis rerum laudantium? Velit totam voluptatem ipsa
      suscipit culpa cum qui, debitis labore tenetur vero dolore at impedit
      numquam fuga. Culpa laudantium soluta earum. Veniam, quidem?
    </p>
    <button>Nav Button</button>
  </body>
</html>
```

> ## 40- positionStatic(durgunKonum) .css

```css
button {
  background: red;
  font-size: 40px;
  color: white;
  position: fixed; /* ekranda sürekli aktif olacak */
  top: 0;
  right: 0;
}
div {
  border: 3px solid red;
  background: yellow;
  margin-top: 40px;
  position: static;
}
.one {
  background: rgb(140, 140, 202);
  text-align: left;
  position: relative; /*  konumlandırma */
  top: 40px;
  left: 20rem;
}
.two {
  background: green;
  position: relative;
}
.special {
  background: red;
  font-size: 20px;
  /* two sınıfını mutlak yaptığımız zaman */
  /* special two sınıfının olduğu için  o sınıfın içinde içinde göreceli olarak konumlandırılacak. */
  position: absolute; /* göreceli konumlandırma */
  top: 50%;
  right: 50%;
}
```

> ## 41- mediaQuries(telefonGorunumu)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>mediaQuries(telefonGorunumu)</title>
    <link rel="stylesheet" href="./css/41- mediaQuries(telefonGorunumu).css" />
  </head>
  <body>
    <div class="banner">
      <h1>hello world i'm learning css</h1>
    </div>
  </body>
</html>
```

> ## 41- mediaQuries(telefonGorunumu) .css

```css
/* 
Media Queries --- Medya Sorguları
Responsive Desing --- Duyarlı Tasarım
Style Elements on Different Screen Sizes --- Farklı Ekran Boyutlarında Stil Öğeleri
min-width: -> Starting from --- 'den başlayarak
max-width: -> up to --- kadar
Mobile First --- önce mobil
*/
body {
  background: yellow;
}
h1 {
  background: blue;
  color: white;
  text-align: center;
  text-decoration: underline;
  text-transform: capitalize;
}
@media screen and (max-width: 500px) /* min 576 ve altındaki genişlikler için uygundur --- max width verildiğinde 800 px de max olduğunda 500px lik görünmeyecek */ {
  body {
    background: red;
  }
  .banner {
    background: yellow;
  }
  h1 {
    color: black;
    font-size: 60px;
  }
}
@media screen and (min-width: 800px) /* min 800px ve altındaki genişlikler için uygundur --- max verildiği zaman 500 px görülmeyecek*/ {
  body {
    background: rgb(10, 5, 255);
  }
  .banner {
    background: rgb(9, 255, 0);
  }
  h1 {
    color: black;
    font-size: 60px;
  }
}
```

> ## 42- Z-Index(zİndeksi)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Z-Index(zİndeksi)</title>
    <link rel="stylesheet" href="./css/42- Z-Index(zİndeksi).css" />
  </head>
  <body>
    <div class="banner">
      <img src="./Images/back-small.jpeg" alt="" class="one" />
      <img src="./Images/back-big.jpeg" alt="" class="two" />
      <img src="./Images/back-folder.jpeg" alt="" class="three" />
    </div>
  </body>
</html>
```

> ## 43- before-after_pseudoElements(once-sonra_sozdeOgeler)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>before-after_pseudoElements(once-sonra_sozdeOgeler)</title>
    <link
      rel="stylesheet"
      href="./css/43- before-after_pseudoElements(once-sonra_sozdeOgeler).css"
    />
  </head>
  <body>
    <p>before and after pseudo elements</p>
    <div>
      <img src="./Images/back-big.jpeg" alt="" />
    </div>
  </body>
</html>
```

> ## 43- before-after_pseudoElements(once-sonra_sozdeOgeler) .css

```css
/*
    Pseudo elements ::before ::after CONTENT not element (::before ve ::after içerik öğe değil)
    content:'' --- required (içerik --- gerekli)
    img --- does't work (img'da çalışmıyor
*/
p::before {
  content: "before "; /* html'de yazdığımız paragrafın başına "yazmış olduğumuz" kısım görünüyor. */
  font-size: 2rem;
  display: block;
  background-color: black;
  font-weight: bold;
  color: red;
}
p::after {
  content: ""; /* bir şey eklemek istediğimiz zaman content: komutunu kullanıyoruz. */
  display: block;
  width: 50px;
  height: 50px;
  background: green;
}
div {
  width: 60vw;
  margin: 100px auto;
  /* border: 2px solid rebeccapurple; */
  position: relative;
}
img {
  width: 100%; /* yüzde işareti verdiğimiz zaman resmimiz div e duyarlı hale geliyor */

  display: block; /* resmin altında boşluk meydana geliyor Sıfırlamak için */
}
/* görüldüğü gibi img içerisine ::before komutunu yerleştiremedik. */
img::before {
  content: "img before ";
}
/* div'in içerisinde img oluğu için div'e direk ::before veya ::after komutunu eklebiliriz. */
div::before {
  content: "";
  border: 2px solid grey;
  width: 100%;
  height: 100%;
  position: absolute;
  box-sizing: border-box;
  top: -40px;
  left: -40px;
  z-index: -2;
  transition: all 0.5s linear; /* geçiş efekti sağlar */
}
div::after {
  content: "";
  background: grey;
  width: 100%;
  height: 100%;
  position: absolute;
  box-sizing: border-box;
  top: -20px;
  left: -20px;
  z-index: -1;
  transition: all 0.5s linear;
}
div:hover::before, /* hover komutu fare öğenin üzerine glediğinde seçmek için kullanılır */
div:hover::after {
  top: 0;
  left: 0;
}
```

> ## 44- basicSelectors(temelSeciciler)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>basicSelectors(temelSeciciler)</title>
    <link
      rel="stylesheet"
      href="./css/44- basicSelectors(temelSeciciler).css"
    />
  </head>
  <body>
    <h1 id="heading">i'm id heading</h1>
    <h1 class="heading">i'm class heading</h1>
    <p>hello world</p>
  </body>
</html>
```

> ## 44- basicSelectors(temelSeciciler)) .css

```css
/* Basic Selector (Temel Seçiciler) */
/* Descendant and Child Combinators (Torun ve Çocuk Birleştirici) */
* {
  color: red;
}
#heading {
  font-size: 40px;
  text-transform: uppercase; /* Tüm harfler büyük */
  color: blue;
}
.heading {
  font-size: 20px;
  text-transform: capitalize; /* baş harfi büyük */
  color: green;
}
p {
  letter-spacing: 20px;
}
```

> ## 45- descendant_childSelectors(soydan-gelen_cocukSeçiciler)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>descendant_childSelectors(soydan-gelen_cocukSeçiciler)</title>
    <link
      rel="stylesheet"
      href="./css/45- descendant_childSelectors(soydan-gelen_cocukSeçiciler).css"
    />
  </head>
  <body>
    <div class="header">
      <h1>i'm child and descendant</h1>
    </div>
    <div class="header">
      <ul>
        <li>
          <h1>i'm descendant</h1>
        </li>
      </ul>
    </div>
  </body>
</html>
```

> ## 45- descendant_childSelectors(soydan-gelen_cocukSeçiciler) .css

```css
/* Descendant and Child Combinators (Torun ve Çocuk Birleştirici) */

div h1 {
  color: red;
}
/* ilk yazdığımız div'in içerisindeki birinci başlığın rengi değişti */
div > h1 {
  color: blue;
}
/* clasın içinde olduğu için daha özel oluyor. her iki başlık rengi değişiyor. */
.header h1 {
  color: green;
}
/* birleştirici olayından dolayı div'deki olayın aynısı burada da geçerli oluyor. */
.header > h1 {
  color: purple;
}
```

> ## 46- firstLine-firstLetter(ilkSatır-ilkHarf)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>firstLine-firstLetter(ilkSatır-ilkHarf)</title>
    <link
      rel="stylesheet"
      href="./css/46- firstLine-firstLetter(ilkSatır-ilkHarf).css"
    />
  </head>
  <body>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam ex
      atque nesciunt quidem deleniti quisquam mollitia non nihil eum molestias
      ad dolorum, possimus earum quibusdam nulla ipsum pariatur rem eaque.
    </p>
  </body>
</html>
```

> ## 46- firstLine-firstLetter(ilkSatır-ilkHarf) .css

```css
/* ::first-line ::first-letter (ilk Satır  ilk Harf) */
/* İlk satır */
p::first-line {
  font-weight: bold;
}
/* İlk harf */
p::first-letter {
  font-size: 3rem;
}
```

> ## 47- hoverPseudo_classSelector(fareyle-uzerineGelme_sınıfSecici)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>hoverPseudo_classSelector(fareyle-uzerineGelme_sınıfSecici)</title>
    <link
      rel="stylesheet"
      href="./css/47- hoverPseudo_classSelector(fareyle-uzerineGelme_sınıfSecici).css"
    />
  </head>
  <body>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Qui porro
      molestiae numquam error vero nemo maxime at, facere praesentium dicta
      nostrum tempore consectetur rerum labore soluta veniam non ducimus
      architecto neque? Nisi cupiditate dolorem alias velit facere. Tempora
      harum, quod iure distinctio cumque maxime, cum eveniet, repellat ut
      officiis doloribus!
    </p>
    <div class="header">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus harum
      nam unde asperiores pariatur ex corrupti! Vero aperiam nihil laudantium
      sit, esse debitis repudiandae modi quis! Consectetur eum pariatur
      laudantium!
    </div>
    <a href="#">This is a link</a>
  </body>
</html>
```

> ## 47- hoverPseudo_classSelector(fareyle-uzerineGelme_sınıfSecici) .css

```css
/* :hover (üzerine gelmek) */

/* fareyle üzerine gelindiğinde yazı rengi kırmızı oluyor */
p:hover {
  color: red;
}
/* fareyle üzerine gelindiğinde arkaplan rengi mavi ve yazı rengi beyaz oluyor */
.header:hover {
  background: blue;
  color: white;
}
a:hover {
  text-decoration: none; /* fareyle üzerine geldiğinde linkin alt çizgisi görünmüyor */
}
```

> ## 48- linkPseudo_classSelectors(sozdeBaglanti_sinifSecici)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>linkPseudo_classSelectors(sozdeBaglanti_sinifSecici)</title>
    <link
      rel="stylesheet"
      href="./css/48- linkPseudo_classSelectors(sozdeBaglanti_sinifSecici).css"
    />
  </head>
  <body>
    <a href="https://www.google.com" target="_blank">General link</a>
    <a href="#">Visited link</a>
    <a href="https://www.google.com" target="_blank">Hover link</a>
    <a href="https://www.google.com" target="_blank">Active link</a>
  </body>
</html>

```

> ## 48- linkPseudo_classSelectors(sozdeBaglanti_sinifSecici) .css

```css
/* :link :visited :hover :active */

a:link{
    color: aqua;
}
/* fareyle üzerine tıklandığı zaman rengi değişiyor */
a:visited{
    color: red;
}
/* üzerine fare ile gelindiğinde */
a:hover{
    color: blue;
}
/* fareyle linkin üzerine tıklandığı zaman boyunca */
a:active{
    color: green;
}
```

> ## 49- rootPseudo_classSelectors(sozdeKok_sinifSecici)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>rootPseudo_classSelectors(sozdeKok_sinifSecici)</title>
    <link
      rel="stylesheet"
      href="./css/49- rootPseudo_classSelectors(sozdeKok_sinifSecici).css"
    />
  </head>
  <body>
    <h1>i'm heading</h1>
    <p class="absolute">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos eveniet iste
      culpa inventore, necessitatibus eligendi voluptate asperiores nulla
      temporibus deleniti quaerat! Inventore fugit expedita ipsam quam fuga odio
      tenetur nostrum!
    </p>
        <p class="responsive">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos eveniet iste
      culpa inventore, necessitatibus eligendi voluptate asperiores nulla
      temporibus deleniti quaerat! Inventore fugit expedita ipsam quam fuga odio
      tenetur nostrum!
    </p>
  </body>
</html>
```

> ## 49- rootPseudo_classSelectors(sozdeKok_sinifSecici) .css

```css
/* 
    :root root element od the document(belgenin kök öğesi)
    html element(html öğesi)
    general styles(genel stiller)
    css variables(css değişkenleri)
*/
:root{
    background: red;
    /* 
        tarayıcıdaki ayarlarına gerek kalmadan yazı boyutunu değiştirmek için 
        rem'e bağlı olan yazı yotuları aynı oranda değiştiğini görebiliyoruz.
    */
    font-size: 150%;
}
/* 1rem = 16px */
/* tarayıcı ayarlarında yazı boyutu değiştiği zaman rem ile yazı boyutları değişmektedir. */ 
h1{
    font-size: 3rem;
}
.absolute{
    font-size: 24px;
}
.responsive{
    font-size: 1.5rem;
}
```
> ## 50- 

```html

```

> ## 50-  .css

```css

```
> ## 50- 

```html

```

> ## 50-  .css

```css

```

> ## 50- 

```html

```

> ## 50-  .css

```css

```

> ## 50- 

```html

```

> ## 50-  .css

```css

```

> ## 50- 

```html

```

> ## 50-  .css

```css

```

> ## 50- 

```html

```

> ## 50-  .css

```css

```

> ## 50- 

```html

```

> ## 50-  .css

```css

```

> ## 50- 

```html

```

> ## 50-  .css

```css

```

