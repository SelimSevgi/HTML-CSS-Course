>## 1-giriş-kütüphaneler
```html 
<!-- AÇIKLAMA SATIRI-->
<!-- 
    Kütüphane eklemek için;  
    Uzantılar - Live Server  
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
>## 2-headingElements(Başlık 'h1'-'h2'-'h3'-'h4'-'h5'-'h6')
```html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
>## 3-paragraph-br-Elements(Metin 'p'-'br')
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
      perspiciatis architecto corporis <br> neque quaerat placeat
      reprehenderit dolore consequuntur omnis excepturi? Odit vitae sint tempora
      quaerat maiores temporibus assumenda rem recusandae nobis deleniti
      nesciunt quod ipsam ipsum inventore hic pariatur suscipit adipisci rerum
      molestiae, corporis expedita error. Sunt dolorem debitis libero
      praesentium. <br> <br> <br> <br>
      Ducimus delectus saepe quam quos excepturi aperiam dicta
      voluptatum eius!
    </p>
  </body>
</html>
```
>## 4-images(Fotoğraf 'img')
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
    <h3>          laptop       image of pexel site</h3>
    <img src="images/pexel-laptop.jpeg" alt="pexels laptop"/>

    <!--
        Resim boyutunu bilmek için resme tıklayıp tam görüntü kısmında öğrenebiliriz.
        git resmin boyutu 910x380
        pexel-laptop resmini
        Resmin boyutunu ayarlamk için ise
        height="380" width="910" 
        bu şekilde görüntünün çözünürlüğünde sorun meydana gelebilir.
    -->
    <h3>laptop image of pexel site</h3>
    <img src="images/pexel-laptop.jpeg" alt="pexels laptop" height="380" width="910"/>

    <!-- genişlik baz alınarak çözünürlük bozulmadan img -->
    <h3>laptop image of pexel site</h3>
    <img src="images/pexel-laptop.jpeg" alt="pexels laptop" width="910"/>

    <!-- 
        yada fotoğrafın üzerinde dışarıdan düzenleme yapılarak istenilen özelliklere getirilmesi sağlanabilir. 
    -->
  
    </body>
</html>
```
>## 5-externalLinks(dışLink 'a' )
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
>## 6-internalLinks(dahiliLİnk)
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
    
    <br>

    <!-- 
        id oluşturarak da yapabiliriz. 
        a tab tuşuna basarak link ekleme komutunu ekliyoruz
        href kısmına #etiket yazılarak id olarak tanımladığımız yere yönlendiriyor.
    -->
    <a href="#bas">Sayfanın başına git1</a>
  </body>
</html>
```
>## 7-forms-writtingElements(yazıŞekilleri)
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