<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coffee.io</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.rtl.min.css" 
    integrity="sha384-gXt9imSW0VcJVHezoNQsP+TNrjYXoGcrqBZJpry9zJt8PCQjobwmhMGaDHTASo9N" crossorigin="anonymous">
    <script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.15.0/dist/cdn.min.js"></script>
    <link rel="stylesheet" href="../porject-bootstrap.1/stalys.css">
    
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css">
</head>
<body>
  
    <header x-data="{ navShow: false }" @scroll.window="navShow = window.scrollY > 100 ? true : false">
      <nav class=" a navbar navbar-expand-lg navbar-light fixed-top " :class="{'header-scrolled': navShow}">
<div class="container">
  <a class="navbar-brand" href="javascript:void(0)">Coffee.io</a>
  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="mynavbar">
    <ul class="navbar-nav me-auto">
      <li class="nav-item">
        <a class="nav-link" href="javascript:void(0)">صحفه اصلی</a>
      </li>
       <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">محصولات</a>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">ارتباط با ما</a></li>
          <li><a class="dropdown-item" href="#">خدمات</a></li>
          <li><a class="dropdown-item" href="#">محصولات</a></li>    </ul>
      <li class="nav-item">
        <a class="nav-link" href="javascript:void(0)">درباره ما </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="javascript:void(0)">تماس با ما</a>
      </li>
    </ul>
    
  </div>
</div>
</nav>

  </header>

    <!-- Intro -->
    <section class="Intro d-flex align-items-center text-center text-lg-start overflow-hidden">
        <div class="container">
          <div class="row align-items-center">
            <div class="col-lg-6">
             <h3   data-aos="fade-up" class="fw-bold text-dark mt-3">یک کافه دنج در اصل یک محیط فراموش نشدنی و جذاب است که در هر گوشه آن خاطراتی حک شده است</h3>
             <h5   data-aos="fade-up"    data-aos-delay="200" class="text-muted">اولین کافه در قرن ۱۵ میلادی در عربستان ساخته شد</h5>
        <button  data-aos="fade-up"    data-aos-delay="400"  class="btn btn-lg btn-dark mt-3
         hover">کافه دنج</button>
        
        
        
            </div>
            <div class="col-lg-6 mt-3 mt-lg-0" 
            data-aos="zoom-out"    data-aos-delay="200">
              <img class="img-fluid" src="../porject-bootstrap.1/coffe.jpg" alt="">
            </div>
          </div>
        </div>
        </section>


 <!-- About -->
 <section class=" overflow-hidden">
  <div class="container mt-5">
    <div class="row gy-5 gx-0 align-items-center">
      <div class="col-lg-6" data-aos="fade-up"   data-aos-delay="500">
       <div class="contant">
        <h3 class="fw-bold text-dark mt-3"> قهوه نوشیدنی‌ای پرطرفدار است که از دانه‌های برشته‌شده گیاهی با همین نام تهیه می‌شود این نوشیدنی حاوی کافئین 
          است که هوشیاری را افزایش می‌دهد. </h3>
         <p class="text-dark">مصرف متعادل مثلاً ۳ تا ۴ فنجان در روز مهم است و مصرف بیش از حد می‌تواند مضراتی داشته باشد </p>
    <button class="btn btn-dark
     hover">قهوه تلخ</button>
       </div>
      </div>
      <div class="col-lg-6"  data-aos="zoom-out"   data-aos-delay="500">
     
        <img class="img-fluid" src="../porject-bootstrap.1/bar-1.jpg" alt="">
      </div>
    </div>
  </div>
  </section>
  
  <!-- Values -->
  <section class="counts py-5  overflow-hidden">
           <div class="container">
            <div class="row mt-5"  data-aos="fade-up"   data-aos-delay="400">
              <div class="col-12 text-center">
                <h2 class="fw-bold text-dark" >معلومات برند های قهوه</h2>
                <p>10 برند معروف در جهان است در مورد 3 برند پایین اطلاعات میدهم</p>
              </div>
            </div>
            <div class="row g-3 mb-4">
                <div class="col-lg-4" data-aos="flip-right"  data-aos-delay="400">
                  <div class="card shadow h-100">
                    <img src="../porject-bootstrap.1/imgs.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title text-end">Starbucks</h5>
                      <p class="card-text">استارباکس شرکت کافی‌شاپ‌های زنجیره‌ای چندملیتی آمریکایی است که با در اختیار داشتن شبکه گسترده‌ای
                         .از ۲۸،۲۱۸ شعبه در کشورهای مختلف، بزرگ‌ترین کافی‌شاپ زنجیره‌ای در جهان محسوب می‌شود</p>
                      <a href="#" class="btn btn-dark fw-bold">اطلاعات بیشتر</a>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4" data-aos="flip-right"  data-aos-delay="500">
                  <div class="card shadow h-100">
                    <img src="../porject-bootstrap.1/bars.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title text-end">Jacobs</h5>
                      <p class="card-text">
                        برند جاکوبز یا جیکوبز یکی از معروف‌ترین و قدرتمند‌ترین کمپانی‌های قهوه در جهان است که قهوه، قهوه فوری و کپسول قهوه تولید می‌کند
                        نه‌تنها در آلمان و اروپا، بلکه در سراسر جهان، برای خود جایگاه معتبری دست و پا کند</p>
                      <a href="#" class="btn btn-dark fw-bold">اطلاعات بیشتر</a>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4" data-aos="flip-right"  data-aos-delay="600">
                  <div class="card shadow h-100">
                    <img src="../porject-bootstrap.1/him.png" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title text-end">Lavazza</h5>
                      <p class="card-text">اواتزا یکی از پرطرفدارترین برندهای قهوه است این برند ایتالیایی با قدمت 125 ساله خود و با بکار گیری از مرغوب ترین دانه‌های قهوه و دانه‌های این قهوه در حد متوسط رست شده و بنابراین خیلی ملایم یا خیلی سوخته و تلخ نیست
                      </p>
                      <a href="#" class="btn btn-dark fw-bold">اطلاعات بیشتر</a>
                    </div>
                  </div>
                </div>
            </div>
           </div>
  </section>


  <!-- Counts -->
  <section class="counts py-5  overflow-hidden">
  <div class="container">
    <div class="row gy-3">
      <div class="col-md-6 col-lg-3"  data-aos="fade-up"   data-aos-delay="400">
        <div class="d-flex shadow p-3
    align-items-center justify-content-center">
          <i class="bi bi-emoji-smile me-3 color"></i>
          <div>
            <span class="fs-3 fw-bold text-primary purecounter" 
                    data-purecounter-start="0"
        data-purecounter-end="7082">0</span>
            <p>رضایت مردم</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-3"  data-aos="fade-up"   data-aos-delay="400">
        <div class="d-flex shadow p-3
        align-items-center justify-content-center">
              <i class="bi bi-emoji-frown me-3 color-1"></i>
              <div>
                <span class="fs-3 fw-bold text-primary purecounter" 
                        data-purecounter-start="0"
        data-purecounter-end="125">0</span>
                <p>شکایت مردم</p>
              </div>
            </div>
      </div>
      <div class="col-md-6 col-lg-3"  data-aos="fade-up"   data-aos-delay="400">
        <div class="d-flex shadow p-3
        align-items-center justify-content-center">
              <i class="bi bi-headset  me-3 color-2"></i>
              <div>
                <span class="fs-3 fw-bold text-primary purecounter" 
                        data-purecounter-start="0"
        data-purecounter-end="2843">0</span>
                <p>تماس مردم</p>
              </div>
            </div>
      </div>
      <div class="col-md-6 col-lg-3"  data-aos="fade-up"   data-aos-delay="400">
        <div class="d-flex shadow p-3
        align-items-center justify-content-center">
        <i class="bi bi-envelope-paper-heart me-3 color-3"></i>
              <div>
                <span class="fs-3 fw-bold text-primary purecounter" 
                        data-purecounter-start="0"
        data-purecounter-end="739">0</span>
                <p>پشنهاد مردم</p>
              </div>
            </div>
      </div>
    </div>
  </div>
  </section>


  <!-- Features -->
  <section class="Features py-5  overflow-hidden">
    <div class="container">
      <div class="row"  data-aos="fade-up"   data-aos-delay="500">
        <h4 class="mb-4">یک کافه دنج در اصل یک محیط فراموش نشدنی و جذاب است که در هر گوشه آن خاطراتی حک شده است</h4>

      </div>
      <div class="row align-items-center mt-5">
        <div class="col-lg-4"  data-aos="zoom-out"   data-aos-delay="500">
          <img class="img-fluid" src="../porject-bootstrap.1/coffe (2).jpg" alt="">
        </div>
        <div class="col-lg-8 mt-5 gy-4"  data-aos="fade-up"   data-aos-delay="500">
          <div class="row">
            <div class="col-md-6">
              <div class="d-flex">
                <i class="bi bi-emoji-smile me-3 text-dark"></i>
                <div>
                  <h5>دربار کافه</h5>
                  <p class="text-muted">
                    کافی‌شاپ مکانی است که در درجه اول انواع نوشیدنی‌های مبتنی بر قهوه مانند اسپرسو، کاپوچینو و لاته را سرو می‌کند
                  </p>
                </div>
              </div>
            </div>

            <div class="col-md-6">
              <div class="d-flex">
                <i class="bi bi-clipboard2-heart me-3 text-dark"></i>
                <div>
                  <h5>انواع قهوه</h5>
                  <p class="text-muted">
                    اسپرسو/ کاپوچینو / لاته / ربوستا / موکا / قهوه ترک / قهوه فرانسه / کلد برو / عربیکا
                  </p>
                </div>
              </div>
            </div>



            <div class="col-md-6">
              <div class="d-flex">
                <i class="bi bi-cup-hot me-3 text-dark"></i>
                <div>
                  <h5> قهوه اسپرسو</h5>
                  <p class="text-muted">
                    نوشیدنی ای با طعم غنی و غلیظ، با کفی اسفنجی روی آن، که اکثراً به عنوان اسپرسو شناخته می شود که از دانه های قهوه استاندارد و تازه و با استفاده از فشار بالا و آب گرم تهیه می شود
                  </p>
                </div>
              </div>
            </div>
            
            <div class="col-md-6">
              <div class="d-flex">
                <i class="bi bi-cup-hot me-3 text-dark"></i>
                <div>
                  <h5>قهوه لاته</h5>
                  <p class="text-muted">
                    علاوه بر نام ذکر شده، لاته، نوشیدنی قهوه ای محبوبی است که از ترکیب اسپرسو و شیر گرم تهیه می شود این نوشیدنی به خاطر ترکیب دقیق اسپرسو و شیر، طعمی ملایم تر از اسپرسو خالص دارد و از لایه کرم بر روی قهوه لذت می برد
                  </p>
                </div>
              </div>
            </div>

            <div class="col-md-6">
              <div class="d-flex">
                <i class="bi bi-cup-hot me-3 text-dark"></i>
                <div>
                  <h5>قهوه ربوستا </h5>
                  <p class="text-muted">
                    قهوه ربوستا معمولاً دارای تندی و مزه ای ملایم و متعادل است که برخی افراد به دلیل طعمش مورد علاقه شان قرار می دهند این نوع قهوه به عنوان یک گزینه متوسط بین قهوه های قوی و قهوه های ملایم شناخته می شود
                  </p>
                </div>
              </div>
            </div>

            <div class="col-md-6">
              <div class="d-flex">
                <i class="bi bi-cup-hot me-3 text-dark"></i>
                <div>
                  <h5> قهوه عربیکا</h5>
                  <p class="text-muted">
                    در نقطه مقابل و به عنوان یکی از ترکیبات کلیدی و پایه، قهوه عربیکا از اصلی ترین انواع قهوه است که از دانه های گیاه قهوه عربیکا به دست می آید دانه های قهوه عربیکا اغلب در مناطق با ارتفاعات بالا و شرایط آب و هوایی خاصی کشت می شوند 
                  </p>
                </div>
              </div>
            </div>



          </div>
        </div>
      </div>
    </div>
  </section>



  <!-- services -->

  <section class="py-5  overflow-hidden">
    <div class="container">
      <div class="row"  data-aos="fade-up"   data-aos-delay="400">
<h2 class="fw-bold">انواع طعم های قهوه</h2>
<p>قهوه یعنی نشاط زندگی</p>
      </div>

      <div class="row"  data-aos="fade-up"   data-aos-delay="400">
        <div class="col-md-6 col-lg-4 services-box">
          <div class="services-box-1 blue mt-4">
            <i class="bi bi-cup-hot-fill me-3 icon"></i>
            <h3 class="fw-bold">قهوه تلخ</h3>
            <p>
              قهوه تلخ نوشیدنی بدون شکر است که فواید زیادی برای سلامتی دارد
              مصرف قهوه تلخ فواید زیادی دارد اما مصرف بی‌رویه آن می‌تواند باعث اختلالات خواب شود
            </p>
            <a href="#" class="a-1 mt-4">
              <span class=" read-more">
                مشاهد بیشتر
              </span>
              <i class="bi bi-arrow-left read-more">

              </i>
            </a>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 services-boxs">
          <div class="services-box-2 orang mt-4">
            <i class="bi bi-cup-hot-fill me-3 icon-1"></i>
            <h3 class="fw-bold">قهوه ساده</h3>
            <p>
              نوشیدنی دم‌کردنی که از دانه‌های قهوه بو داده (رُست شده) تهیه می‌شود
              دو گونه اصلی قهوه، عربیکا و روبوستا هستند که هر کدام طعم و ویژگی‌های متفاوتی دارند. 
            </p>
            <a href="#" class="a-2 mt-4">
              <span class=" read-more-1">
                مشاهد بیشتر
              </span>
              <i class="bi bi-arrow-left read-more-1">

              </i>
            </a>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 services-boxsz">
          <div class="services-box-3 pink mt-4">
            <i class="bi bi-cup-hot-fill me-3 icon-2"></i>
            <h3 class="fw-bold">قهوه شیرین</h3>
            <p>
              قهوه شیرین به دو دسته اصلی تقسیم می‌شود: قهوه‌هایی که به طور طبیعی طعم شیرین دارند و قهوه‌هایی که با افزودنی‌ها شیرین شده‌اند
            </p>
            <a href="#" class="a-3 mt-4">
              <span class=" read-more-2">
                مشاهد بیشتر
              </span>
              <i class="bi bi-arrow-left read-more-2">

              </i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

<!-- Pricing -->
<section class="py-5 Pricing  overflow-hidden">
  <div class="container">
    <div class="row mb-4"  data-aos="fade-up"   data-aos-delay="400">
<h2 class="fw-bold">   معلومات در مورد کافه های قدیمی و مشور </h2>
<p>قهوه خانه / کافه</p>
    </div>

    <div class="row text-center gy-3">
      <div class="col-md-6 col-lg-3 h-100"  data-aos="flip-right"  data-aos-delay="300">
        <div class="card shadow">
          <div class="card-body">
<h4 class="fw-bold text-primary">  کافه فلوریان  </h4>
<div>250 <sup>دالر</sup>/در ماه</div>
<img class="img-fluid p-4" src="../porject-bootstrap.1/کافه فلوریان.png" alt="">
<ul class="list-unstyled">
  <li class="my-2"> ونیز، ایتالیا - ۱۷۲۰</li>
  <li class="my-2">  کافه‌ای تاریخی که در میدان سن  مارکو قرار دارد</li>
  <li  class="my-2">کافه قدیمی با محیط ارام</li>
  <li class="text-decoration-line-through text-muted my-2">کافه‌ مدرن</li>
  <li class="text-decoration-line-through text-muted">کافه جدید</li>
</ul>

<button class="btn btn-outline-dark mt-4">مشاهد بیشتر</button>
          </div>
        </div>
      </div>

      <div class="col-md-6 col-lg-3 h-100"  data-aos="flip-right"   data-aos-delay="400">
        <div class="card shadow">
          <div class="card-body">
<h4 class="fw-bold text-primary">کافه لو پروکوپ</h4>
<div>400  <sup>دالر</sup>/در ماه</div>
<img class="img-fluid p-4 h-75" src="../porject-bootstrap.1/کافه پروکوب.png" alt="">
<ul class="list-unstyled">
  <li class="my-2">پاریس، فرانسه - ۱۶۸۶</li>
  <li class="my-2"> یکی از قدیمی‌ترین کافه‌های جهان </li>
  <li class="my-2">  میزبان بسیاری از چهره‌های سرشناس تاریخی بوده است.</li>
  <li class="text-decoration-line-through text-muted my-2">کافه‌ مدرن</li>
  <li class="text-decoration-line-through text-muted">کافه جدید</li>
</ul>

<button class="btn  btn-outline-dark mt-4">مشاهد بیشتر</button>
          </div>
        </div>
      </div>


      <div class="col-md-6 col-lg-3 h-100"  data-aos="flip-right"  data-aos-delay="500">
        <div class="card shadow">
          <div class="card-body">
<h4 class="fw-bold text-primary">کافه گرکو   </h4>
<div>300  <sup>دالر</sup>/در ماه</div>
<img class="img-fluid p-4" src="../porject-bootstrap.1/کافه گرکو.png" alt="">
<ul class="list-unstyled">
  <li class="my-2">  در سال ۱۷۶۰ در خیابان کوندوتی شماره ۸۶ در رم افتتاح شد</li>
  <li class="my-2">از قدیمی‌ترین کافه‌های رم است</li>
  <li class="my-2">پاتوق هنرمندان و نویسندگان بوده است</li>
  <li class="text-decoration-line-through text-muted my-2">نواع طعم های</li>
  <li class="text-decoration-line-through text-muted">نواع طعم های</li>
</ul>

<button class="btn btn-outline-dark mt-4">مشاهد بیشتر</button>
          </div>
        </div>
      </div>


      <div class="col-md-6 col-lg-3 h-100" data-aos="flip-right"   data-aos-delay="600">
        <div class="card shadow">
          <div class="card-body">
<h4 class="fw-bold text-primary">کافه سنترال </h4>
<div>740 <sup>دالر</sup>/در ماه</div>
<img class="img-fluid p-4" src="../porject-bootstrap.1/کافه سنترل.png" alt="">
<ul class="list-unstyled">
  <li class="my-2">کافه در سال ۱۸۶۰ افتتاح شد</li>
  <li class="my-2"> در اواخر قرن نوزدهم به یکی از نقاط کلیدی ملاقات‌های طبقه روشنفکر وین تبدیل شد</li>
  <li class="my-2"> کافه در پایان جنگ جهانی دوم تعطیل شد</li>
  <li class="text-decoration-line-through text-muted my-2">نواع طعم های</li>
  <li class="text-decoration-line-through text-muted">نواع طعم های</li>
</ul>

<button class="btn btn-outline-dark mt-4">مشاهد بیشتر</button>
          </div>
        </div>
      </div>
    </div>
  </div>

 
        </section>


        <!-- Contact -->
        <section class="py-5 Contact  overflow-hidden">
          <div class="container">
            <div class="row mb-4 text-center"   data-aos="fade-up"   data-aos-delay="400">
        <h2 class="fw-bold">ارتباط با ما</h2>
       
            </div>
        
            
          <div class="row gy-1"   data-aos="fade-up"   data-aos-delay="400">
<div class="col-lg-6">
  <div class="row">
    <div class="col-md-6 mt-1">
      <div class="info-box">
        <i class="bi bi-geo-alt"></i>
        <h5>ادرس</h5>
        <p>هرات افغانستان<br>کابل افغانستان </p>
      </div>
    </div>
    
    <div class="col-md-6 mt-1">
      <div class="info-box">
        <i class="bi bi-telephone"></i>
        <h5>شماره تماس</h5>
        <p class="cellphone"> +93 790 965 164 <br> +93 794 314 340 </p>
      </div>
    </div>
    
          </div>

          <div class="row my-4">
            <div class="col-md-6 mt-1">
              <div class="info-box">
                <i class="bi bi-clock"></i>
                <h5>پشنبانی</h5>
                <p> 8:00pm - 4:00pm <br>شنبه - چهارشنبه </p>
              </div>
            </div>
            
            <div class="col-md-6 mt-1">
              <div class="info-box">
                <i class="bi bi-envelope"></i>
                <h5>ایمیل</h5>
                <p class="cellphone"> info@example.com <br> container@example.com</p>
              </div>
            </div>
            
                  </div>

                </div>

        <div class="col-md-6"   data-aos="fade-up"   data-aos-delay="400">
          <form action="#" class="Contact-form">
            <div class="row gy-3">
        <div class="col-md-6">
                      <label for="" class="form-label">نام</label>
                      <input type="text" class="form-control">
        </div>

        <div class="col-md-6">
                      <label for="" class="form-label">ایمیل</label>
                      <input type="email" class="form-control">
        </div>

        <div class="col-md-12">
                      <label for="" class="form-label">موضوع</label>
                      <input type="text" class="form-control">
        </div>


            <div class="col-md-12">
                      <label for="" class="form-label">موضوع پیام</label>
                     <textarea name="text" class="form-control" cols="30" rows="3"></textarea>
            </div>

            <div class="col-md-12 text-center">
              <button class="btn btn-dark">ارسال پیام</button>
            </div>
           </div>
          </form>
        </div>
      </div>
        </section>


        <!-- footer -->
        <footer class="footer">
          <div class="container">
            <div class="row gy-4"   data-aos="fade-up"   data-aos-delay="400">
              <div class="col-lg-5">
                <h3 class="fw-bold">Coffee.io</h3>
                <p>من عاشق قهوه هستم گاهی اوقات شب‌ها با فکر فنجانی که صبح می‌خواهم بنوشم هیجان‌زده می‌شوم قهوه دلیلی برای بیدار شدن‌است</p>
                <div class="social-link">
                  <a class="mx-2" href=""><i class="bi bi-twitter"></i></a>
                  <a class="mx-2" href=""><i class="bi bi-facebook"></i></a>
                  <a class="mx-2" href=""><i class="bi bi-instagram"></i></a>
                  <a class="mx-2" href=""><i class="bi bi-linkedin"></i></a>
                </div>
              </div>



              <div class="col-lg-2 offset-lg-1 col-6">
                <h5>لینک ها</h5>
                <hr>
                <ul class="list-unstyled footer-link">
                  <li><a href=""><i class="bi bi-chevron-left"></i>صحفه اصلی</a></li>
                  <li><a href=""><i class="bi bi-chevron-left"></i> محصولات</a></li>
                  <li><a href=""><i class="bi bi-chevron-left"></i> خدمات</a></li>
                  <li><a href=""><i class="bi bi-chevron-left"></i> دربار ما</a></li>
                  <li><a href=""><i class="bi bi-chevron-left"></i> تماس با ما</a></li>
                </ul>
              </div>


              
              <div class="col-lg-2 col-6">
                <h5>خدمات</h5>
                <hr>
                <ul class="list-unstyled footer-link">
                  <li><a href=""><i class="bi bi-chevron-left"></i> خدمات محدود</a></li>
                  <li><a href=""><i class="bi bi-chevron-left"></i>خدمات عالی</a></li>
                  <li><a href=""><i class="bi bi-chevron-left"></i> معلومات دهی</a></li>
                  <li><a href=""><i class="bi bi-chevron-left"></i>مشاوره</a></li>
                </ul>
              </div>



              
              <div class="col-lg-2 col-6">
                <h5>ارتباط با ما</h5>
                <hr>
                <ul class="list-unstyled footer-link">
                  <li><a href=""><i class="bi bi-chevron-left"></i>تماس با ما</a></li>
                  <li><a href=""><i class="bi bi-chevron-left"></i> دربار ما</a></li>

                </ul>
              </div>
            </div>
          </div>


          <div class="container-fluid text-center py-3"  style="background-color: #f6f6f6;"   data-aos="fade-up"   data-aos-delay="400">
            <h5 class="fw-bold">Coffee.io</h5>
            <p>با نوشیدن قهوه از زندگی لذت</p>
          </div>
        </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" 
    integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@srexi/purecounterjs/dist/purecounter_vanilla.js"></script>
    <script>
        new PureCounter();
    </script>

<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
</script>

</body>
</html>
