---
author: "وودی"
title: آموزش ساخت سایت با دامنه اختصاصی در گیت هاب
date: "2025-08-16"
tags: [سایت شخصی , آموزش ساخت سایت با گیت هاب, دامنه دات آی آر , دامنه .ir , ساخت سایت]
categories: [گیت هاب]
description: ساخت سایت مینیمال شخصی با دامنه اختصاصی در گیت هاب (بهمراه خرید دامنه از ایرنیک)
ShowToc: true
ShowBreadCrumbs: false
---

### مقدمه
تو این پست قراره صفر تا صد مراحل ساخت یه سایت رو با دامنه اختصاصی .ir بهتون بگم؛ این یه روش کاملا رایگانه فقط برای شخصی سازی و بالا آوردن روی دامنه اختصاصیتون لازمه یه نمه سر کیسه رو شل کنید.
اگه فعلا قصد دارید صرفا سایت رو بالا بیارید بعد دامنه بخرید براش، از اینجا بخونید.
### ثبت دامنه اختصاصی .ir
مرحله اول مربوط به خرید دامنه اختصاصی هستش چون پروسه ثبت و تنظیم DNS یکم زمانبره برای همین اول کار میگم که اگه قصد دارید رو دامنه خودتون بالا بیارید قبل هر چیزی دامنه رو بخرید که بعدا وقتتون تلف نشه!
نترسید هزینه خیلی زیادی نداره و برای دامنه ی یکساله فقط کافیه 40 ت هزینه کنید :)
پیشنهاد میکنم بخرید چون دامنه اصلی io که قراره روی اون سایتتون رو بسازید تو بعضی از نت ها بالا نمیاد و فیلتره.. پس بخرید !

### مراحل ثبت دامنه از طریق [nic.ir](https://www.nic.ir/)
برای ثبت دامنه تو سایت [ایرنیک](https://www.nic.ir/) اول باید توی سایت ثبت نام کنید، مراحل ثبت نام سخت و عجیب غریبی نداره با ایمیل و مشخصاتتون توی سایت ثبت نام کنید؛ بعد از اون اقدام به ثبت دامنه کنید.
بعد از ثبت نام از منوی بالا روی `دامنه ها` و بعد گزینه `ثبت دامنه` رو انتخاب کنید.


https://i.postimg.cc/25t5DTGD/02.png
https://i.postimg.cc/pLGWfkgF/03.png
https://i.postimg.cc/MTRz8wX7/04.png
https://i.postimg.cc/5tXxnLVk/05.png

بعد از اون باید دامنه ای که میخواید رو انتخاب کنید. 
مثل انتخاب آیدی میمونه و فقط باید یه آیدی رو بزنید که قبلا تکرار نشده باشه!
بعد انتخاب دامنه اگه زد قابل ثبت یا همچین چیزی بزنید روی ادامه و برید پرداخت کنید؛ البته قبلش تیک همه گزینه های موجود رو روی `خودم` بزنید.

حالا باید منتظر شید وضعیتش به حالت `ثبت شده` تغییر پیدا کنه تا بتونید DNS تنظیم کنید.
> چند ساعتی طول میکشه

این مرحله رو میتونید بعد از ساخت ریپو هم ادامه بدید تا وقتی که وضعیت به حالت `ثبت شده` تغییر پیدا کنه..

https://i.postimg.cc/MHmxvY7X/06.png

### تنظیم DNS
برای تغییر DNS و تنظیم ریکورد علاوه بر سایت ایرنیک شما به سایت دیگه ای هم نیاز دارید؛ با استفاده از سایت [cloudflare](https://www.cloudflare.com/) میتونید رکورد های گیت هاب رو روی دامنه اتون ست کنید.
با استفاده از اکانت گوگلتون توی سایت ثبت نام کنید.

https://i.postimg.cc/8CKMFqdf/Screenshot-2025-08-18-183029.png


و دامنه اتون رو وارد کنید. 
> دامنه رو دستی بنویسید کپی پیست نکنید.
> 
https://i.postimg.cc/xdB978jj/09.png
https://i.postimg.cc/J0V4ynSY/10.png
https://i.postimg.cc/sf7gkYZk/11.png

پلن رایگان رو انتخاب کنید (همینو لازم داریم و کارمون راه میفته)
حالا لازمه name server های دامنه امون رو از طریق سایت [ایرنیک](https://www.nic.ir/) ست کنیم تا بتونیم با استفاده از cloudflare رکورد های گیت هاب رو تنظیم کنیم که برای اینکار لازمه که دامنه اتون وضعیتش تغییر کرده باشه تا بتونید نیم سرور هاشو تغییر بدید

بعد از اینکه وضعیت به `ثبت شد` تغییر کرد، روی دامنه اتون کلیک کنید و با انتخاب گزینه `ویرایش ردیف عای کارگزاری نام و ومیزبانی دامنه`  وارد صفحه تنظیمات DNS بشید.

https://i.postimg.cc/MHmxvY7X/06.png
https://i.postimg.cc/15S3s8Gf/07.png

فقط کافیه این بخش هارو که تو تصویر پر کردم با این نیم سرور ها تغییر بدید و  پایین حتما قبل از اعمال، سوال امنیتی رو جواب بدید؛ حالا برید تو سایت [cloudflare](https://www.cloudflare.com/en-gb/) و روی `check nameserver now` رو بزنید.
> این مرحله حداقل نیم ساعت / یه ربع وقت میبره..

`alice.ns.cloudflare.com`  
`bob.ns.cloudflare.com`

https://i.postimg.cc/MpKZfgrw/08.png

بعد از اینکه ایمیل تغییر dns رو دریافت کردید دوباره وارد سایت [cloudflare](https://www.cloudflare.com/en-gb/) بشید و صفحه رو رفرش کنید، باید یه باکس سبز رنگی ببینید که نوشته `Active`، این یعنی نیم سرور ها درست تنظیم شدند و الان میتونید رکورد هارو تنظیم کنید.

https://i.postimg.cc/xTPTC95g/12.png

روی لینک DNS Records که آبی نوشته شده بزنید و وارد صفحه اضافه کردن رکورد ها بشید و طبق این تنظیماتی که نوشتم رکورد هارو اضافه کنید.

https://i.postimg.cc/JnBz4JYB/13.png
https://i.postimg.cc/WzGp0VvN/14.png

باید چهار تا رکورد `A` تنظیم کنید با این Ip هایی که مینویسم؛ بخش `Name` همشون رو `@` وارد کنید.
`185.199.108.153`
`185.199.109.153`
`185.199.110.153`
`185.199.111.153`
و یک رکورد `CNAME`  با این تنظیمات که `Name` رو `www` و ip رو `username.github.io` قرار بدید.
یوزرنیم رو باید آیدی اکانت گیت هابتون قرار بدید.
در آخر باید رکورد هایی که تنظیم کردید به این شکل باشه:

https://i.postimg.cc/3JD543d4/Screenshot-2025-08-18-203738.png

### ساخت ریپازیتوری در [گیت هاب](https://github.com/)
بزارید اینطوری بگم که ریپو یک ظرفیه که قراره محتویات اصلیه سایتتون رو توش قرار بدید؛ برای اینکه ریپو بسازید اول با اکانت گوگلتون توی سایت [گیت هاب](https://github.com/) ثبت نام کنید و بعد توی پروفایلتون یه بخشی هست بنام `Repositories` وارد اون بخش بشید و روی `new` بزنید تا به صفحه ساخت ریپو جدید برید.
> حتما تیک `README` رو فعال کنید.

https://i.postimg.cc/g2QKwPLJ/15.jpg
https://i.postimg.cc/yYfjHRV0/Screenshot-20250812-190237.png

### وصل کردن دامنه اختصاصی به ریپو (اگه دامنه خریدید)
بعد از اینکه تمام مراحل تنظیم DNS رو انجام دادید، وارد ریپوتون بشید و روی سه نقطه بزنید و وارد تنظیمات بشید؛
برید به بخش `Pages`

https://i.postimg.cc/k5SvKhWy/16.png
https://i.postimg.cc/Y9wf3f3B/17.png

> تو این بخش `Branch` رو روی `main` و `/ root` قرار بدید.
> و دامنه رو دستی بنویسید توی کادر مشخص شده و بعد از اینکه `DNS` تایید شد تیک `HTTPS` رو هم حتما فعال کنید.

https://i.postimg.cc/rmCGY0n0/Screenshot-20250812-190311.png

### ساخت فایل های مورد نیاز سایت
من قراره کد های مورد نیاز سایت شخصی خودم رو براتون بزارم چون یه صفحه ساده و مینیمال هستش و چیزیه که فکر کنم در وهله اول نیازتون رو برطرف کنه.. حالا بعدا میتونید محتواشو کلا حذف و تغییرش بدید فعلا میخوام طریقه ساخت و جایگذاری محتوای سایت خودم رو بهتون آموزش بدم.
برای ساخت سایت من سه تا فایل لازمه بسازید.
`index.html`
`style.css`
`script.js`

فایل index
```
<!DOCTYPE html>
<!-- credit by woodywork.ir -->
<html lang="en">
 <head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Detail for your web (name / description for preview / img for preview)  -->
  <!--
          این بخش پیش نمایش لینک شما مثلا در تلگرام هست میتونید عکس / عنوان / توضیحات دلخواهتون رو بنویسید.
         -->
  <meta property="og:title" content="woody work !" />
  <meta property="og:image" content="https://biaupload.com/do.php?imgf=org-c310a777b03b1.jpg" />
  <meta property="og:description" content="all about me in this web.." />

  <!-- Icon for your web -->
  <!--
          اینجا میتونید آیکون توی مروگر سایتتون رو تغییر بدید
         -->
  <link href="https://uploadkon.ir/uploads/be3712_25ico-2.png" rel="shortcut icon" />

  <!-- Web Name -->
  <title>woody work</title>

  <!-- Style Link -->
  <link rel="stylesheet" href="style.css" />

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Pixelify+Sans&display=swap" rel="stylesheet" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet" />
 </head>
 <body>
  <div class="window">
   <!-- Menu | Page Links -->
   <!--
          میتونی هر چند تا بخش مخفی که خواستید بسازید و اینجا توی بخش منو با لینک #id به اون بخش دسترسی پیدا کنی.
          -->
   <p class="menu"><a href="#">home</a> ✦ <a href="#my-link">links</a> ✦ <a href="#my-detail">about</a> ✦ <a href="/">misc.</a></p>
   <!-- Header | Profile , Say What U Want! -->
   <img src="https://biaupload.com/do.php?imgf=org-c310a777b03b1.jpg" style="width: 266px;" />
   <p style="padding: 0px 18px;">
    I want to be worshipped. Not just loved... I want someone to look at me and say, 'Without you, my life is incomplete.
    <br />
    <span class="highlight">— 염미정</span>
   </p>
   <!-- Hide Section | Links (You Can Change ID & Content) -->
   <!--
            آیدی هر بخش رو میتونید برحسب نیازتون تغییر بدید ولی یادتون باشه توی بخش منو که لینک بخش رو باید بنویسید همین آیدی که برای بخش مخفی مورد نظرتون در نظر گرفتید رو بنویسید.
             -->
   <div class="section" id="my-link" style="display: none;">
    <div class="empty"></div>
    <p class="links">
     <strong>My Links :</strong><br />
     <div class="other-link-box">
      <a href="https://balteredit.ir/" class="other-link"><img src="/file-directory/link/balter edit web.png" /></a>
      <a href="https://ko-fi.com/woodywork" class="other-link"><img src="/file-directory/link/support.png" /></a>
      <a href="https://woodywork.ir/tools/vazir-style" class="other-link"><img src="/file-directory/link/text style online tools.png" /></a>
      <a href="https://github.com/iweiu1005/woodywork" class="other-link"><img src="/file-directory/link/source code.png" /></a>
      <a href="https://www.aparat.com/balteredit" class="other-link"><img src="/file-directory/link/aparat.png" /></a>
      <a href="https://de.pinterest.com/editbalter/" class="other-link"><img src="/file-directory/link/deviantart.png" /></a>
      <a href="https://youtube.com/@sevdafjsh" class="other-link"><img src="/file-directory/link/youtube sketch.png" /></a>
      <a href="https://youtube.com/@editbalter" class="other-link"><img src="/file-directory/link/youtube phone tutorial.png" /></a>
      <a href="https://youtube.com/@balteredit" class="other-link"><img src="/file-directory/link/youtube pc tutorial.png" /></a>
      <a href="https://youtube.com/@wxfjsh" class="other-link"><img src="/file-directory/link/youtube edit.png" /></a>
      <a href="https://de.pinterest.com/editbalter/" class="other-link"><img src="/file-directory/link/pinterest 2.png" /></a>
      <a href="https://de.pinterest.com/sevdafjsh/" class="other-link"><img src="/file-directory/link/pinterest 1.png" /></a>
      <a href="https://t.me/balteredit" class="other-link"><img src="/file-directory/link/telegram tutorial.png" /></a>
      <a href="https://t.me/wxfjsh" class="other-link"><img src="/file-directory/link/telegram misc.png" /></a>
      <a href="https://woodypurple.blog.ir/" class="other-link"><img src="/file-directory/link/bayan web.png" /></a>
     </div>
    </p>
   </div>

   <!-- Hide Section | Links (You Can Change ID & Content) -->
   <!--
            آیدی هر بخش رو میتونید برحسب نیازتون تغییر بدید ولی یادتون باشه توی بخش منو که لینک بخش رو باید بنویسید همین آیدی که برای بخش مخفی مورد نظرتون در نظر گرفتید رو بنویسید.
             -->
   <div class="section" id="my-detail" style="display: none;">
    <div class="empty"></div>
    <p class="details">
     <strong>About me :</strong><br />
     call me woody !<br />
     <span class="highlight">She/Her</span>
     <br />
     mbti / zodiac: INFP ✿ Libra <br />
     bd: sep 2000 <br />
     country: iran <br />
     lan: turk / persian (en not good -_-) <br />
     Graphic design, Motion Flyer, FanArt.. <br />
     Figma, Ph, Ae, Csp 𐙚ᅠ
    </p>
   </div>
  </div>
  <div class="credit"><span>powerd by</span><a href="https://woodywork.ir/" target="_blank">woody</a>&<a href="https://chatgpt.com/" target="_blank">gpt</a>&<a href="https://www.deepseek.com/" target="_blank">deepseek</a></div>
  <script src="section-change.js"></script>
 </body>
</html>
```

```
body {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 95vh;
  
  /* ارتفاع کامل صفحه */
  font-family: "Noto Sans", sans-serif;
  font-size: 20px;
  margin: 0;
  background-color: #fff;
  background-size: cover;
  background-repeat: no-repeat;
  padding: 0;
  color: #333;
  line-height: 1.6;
  flex-direction: column;
  overflow: hidden;
}
p {
  text-align: justify;
  padding: 0px 18px;
  font-size: 9px;
  text-align: justify;
  width: 88%;
}
a {
  color: #ff5f56;
  text-decoration: none;
  padding: 0px 5px 0px 5px;
}
a:hover {
  background-color: #ffe9e9;
}
::selection {
  background-color: #ffe9e9;
  color: #ff5f56;
}
.window {
  display: flex;
  position: relative;
  flex-direction: column;
  align-items: center;
  max-width: 600px;
  width: 300px;
  background: white;
  padding: 5px 0px 5px 0px;
}
.other-link-box {
  display: flex;
  flex-wrap: wrap;
  gap: 2px;
  padding: 0px 15px;
}
a.other-link {
  display: contents;
} 
.other-link a:hover {
  background: none;
}
.other-link img {
  height: 25px;
}
.menu {
  text-align: right;
}
.empty {
  height: 15px;
  background-color: #1d1210;
  width: 90%;
}
.section {
  display: none;
  flex-direction: column;
  align-items: center;
}
.flex-column-center {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.main {
  flex-grow: 1;
  display: flex;
  flex-direction: column;
  gap: 5px;
  width: 220px;
  padding: 15px 10px;
}
.highlight {
  background: #f9f5c0;
}
.credit {
  color: #dadada;
  font-size: 9px;
  position: absolute;
  bottom: 5px;
  width: 100%;
  text-align: center;
}
.credit a {
  color: #ababab;
}
.credit a:hover {
  background-color: white;
  text-decoration: underline;
}

/* ————— RESPONSIVE ————— */
@media (max-width: 768px) {
  body {
    padding: 20px;
  }
  p {
    font-size: 8px;
  }
  .window {
    margin: 0 auto;
  }

  .window-body {
    gap: 15px;
  }
}
@media (max-width: 480px) {
  body {
    padding: 10px;
  } 
  
}
```

```
function showSectionFromHash() {
    const hash = location.hash;
    const sections = document.querySelectorAll(".section");
    sections.forEach(section => {
      section.style.display = "none";
      section.classList.remove("flex-column-center");
    });
    if (hash) {
      const activeSection = document.querySelector(hash);
      if (activeSection) {
        activeSection.style.display = "flex";
        activeSection.classList.add("flex-column-center");
      }
    }
  }
  showSectionFromHash();
  window.addEventListener("hashchange", showSectionFromHash);
```

