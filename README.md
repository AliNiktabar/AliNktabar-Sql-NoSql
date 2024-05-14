<H2>تحقیق های درس آزمایشگاه پایگاه داده 2</H2>
<H4 dir="rtl"><b>علی نیک تبار - کد دانشجویی :02221033705016</b></H4>
<hr>

 <b>موضوع : Sql-NoSql - تحقیق شماره 1</b>
 <br>
 <br>
دیتابیس NoSql (Not Only Sql) یک نوع دیتابیس است که در آن از مدل داده ای غیر رابطه ای استفاده می شود در حالی که در Sql  که وابسته به روابط و جداول می باشد.
در دیتابیس NoSql داده ها به جای اینکه در جداول ذخیره شوند در سند ها ذخیره می شوند و می توان داده های ساختار دهی نشده مثل تصویر و ویدئو را در آن ذخیره کرد
کلمه Sql مخفف Structured Query Language (زبان ساختار یافته کوئری) است. بنابراین به خودی خود پایگاه داده نیست بلکه زبانی برای تعامل با پایگاه های داده Sql است.  Sql به شما اجازه دستیابی و کنترل داده‌ها را می‌دهد و می‌تواند درخواست های پیوسته یک پایگاه داده را اجرا کند. 

مقیاس پذیری در دیتابیس sql  به صورت عمودی است و این به این معناست که برای افزایش مقیاس بر روی سرور می توانیم مقدار Ram یا Cpu و همچنین ssd را افزایش بدیم .
در NoSql  مقیاس پذیری به صورت افقی می باشد و برای افزایش مقیاس پذیری باید سرور های بیشتری را به دیتابیس NoSql خود اضافه کنید.

دیتابیس NoSql به دلیل مقیاس پذیری بالا و در دسترس بودن به طور گسترده در برنامه های وب و دیتای حجیم استفاده می شود. همچنین بسیاری از داده های تحلیلی را می توان در NoSql ذخیره و برای تجزیه و پیش بینی استفاده کرد. نمونه ای بسیاری از این داده ها را می توانید در سایت های مختلف مثل اینستاگرام، فیسبوک و توییتر مشاهده کرد.

در دیتابیس ها مبحثی به نام اسکیما وجود دارد که به نحوه سازماندهی داده ها اشاره دارد. دیتابیس Sql از اسکیما table-based استفاده می کند در حالی که در دیتابیس NoSql اسکیمای استانداردی وجود ندارد.

<hr>
 <div dir="rtl"><b>موضوع : تفاوت Oracle,MySql,SqlServer - تحقیق شماره 2</b></div>
 <br>
 
در رده بندی دیتابیس های موجود در سایت db.engines.com دیتابیس oracle در رده اول و mysql و sql server در رده های دوم و سوم قرار دارند. دیتابیس oracle جزو محبوب ترین دیتابیس ها در دنیا که برای سازماندهی سیستم های بزرگ به کار می رود مثالی که خودم هم مشاهده کردم در لیگ برتر انگلیس که آمار بازی و بازیکنان رو در پخش زنده با استفاده از مدل های ماشین لرنینگ به نمایش گذاشته می شود تا به طرفداران درک عمیق تری از آمار موجود در بازی ارائه بدهد . همچنین از دیگر مزایای این دیتابیس سیستم رمز دهی قدرتمند که باعث بالارفتن امینت آن می شود. از معایب oracle میتونیم به سختی در نصب و کار کردن با اون اشاره کنیم در حالی که sql server مثل بقیه محصولات مایکروسافت کاربرپسند تر هست و راحت تر میتونیم با اون کار کنیم.

از نظر قیمت oracle از sql server به صرفه تر است و sql server دارای قیمت بالایی است در حالی که mysql که رقیب دیگر این دو شرکت هست دیتابیس خودش رو به صورت رایگان در اختیار کاربران قرار می دهد. oracle و mysql با زبان C و ++C نوشته شده و sql server تنها با زبان ++C نوشته شده اند . oracle و mysql از زبان های برنامه نویسی متعددی پشتیبانی می کنند اما sql server از زبان های کمی پشتیبانی می کند.

از mysql در سیستم هایی با حجم متوسط استفاده می شود اما از sql server برای پروژه های کوچک استفاده می شود . قابلیت های مدیریتی موجود در oracle از mysql و sql server بسیار بیشتر است.
<hr>
 <div dir="rtl"><b>موضوع : LogStash-DataWarehouse-Cash-Server - تحقیق شماره 3</b></div>
 <br>

ابزار "LogStash" یک ابزار متن باز و سمت سرور می باشد که میتواند داده ها را از منبع دریافت کرده آن ها را ذخیره کند Logstash از بسیاری از قالب ها، برنامه ها و سرور ها پشتیبانی می کند. این ابزار ابتدا داده هارا فیلتر کرده و سپس برای تحلیل و بررسی آن ها را با یک ساختار جدید به یک داده تجاری تبدیل می کند. این ابزار متعللق به Elasticsearch است اما خروجی آن به Elasticsearch محدود نیست بلکه دارای خروجی های مختلفی است و این امکان را برای کاربر فراهم میکند تا داده ها را در ابزار های مختلفی تجزیه و تحلیل کند.

از معایب کار با Logstash پیچیدگی در کار با آن و داشتن دانش فنی در زمنه های Ruby و Elasticsearch می باشد از مزایای Logstash هم می توان به قابلیت جمع آوری داده از منابغ مختلف مثل فایل ها، پایگاه های داده، برنامه و خدمات وب و همچنین قابلیت مقیاس پذیری که میتواند به صورت افقی مقیاس بندی شود که برای داده های بزرگ قابل استفاده است اشاره کرد.
................................................................................................................................................................................................................................................................................................

انبار داده یا "Data Warehouse" یک بانک اطلاعاتی گسترده است که به وسیله آن مدیران به تمامی داده ها و اطلاعات سازمان برای تهیه گزارش و انجام تحلیل و بررسی دسترسی دارند و کمک زیادی به مدیر سازمان می کند. از انبار داده در صنایع مختلفی مانند: بانکداری، بازاریابی و فروش، صنعت سلامت، خدمات فناوری اطلاعات، خدمات مالی، صنعت خرده فروشی و انبار داری استفاده می شود.

از مزایای انبار داده می توان به کاهش هزینه ها اشاره کرد که باعث می شود هزینه تحلیل داده ها کاهش پیدا کند و به شرکت ها این امکان را می دهد تا بهینه تر با منابع خود رفتار کنند. از دیگر مزایای انبار داده کاهش خطا و اشتباه می باشد که با دسترسی به داده های دقیق و گزارش گیری از آن، احتمال خطا و اشتباه کاهش پیدا می کند و به شرکت ها کمک می کند تا تصمیمات بهتر و موثر تری داشته باشند. بسیاری پایگاه داده یا Database را با انبار داده اشتباه می گیرند درحالی که تفاوت هایی بین این دو وجود دارد. انبار داده به صورت متمرکز برای جمع آوری و ذخیره سازی و تحلیل داده های سازمانی به کار می رود اما پایگاه داده برای مدیریت داده در برنامه های کاربردی به کار گرفته می شود.
................................................................................................................................................................................................................................................................................................
کش سرور "Cash Server" یک سرویس شبکه یا سرویس در سرور که صفحه های وب و محتوای اینترنت را در خود ذخیره می کند و هدف این کار این است که در مراجعات بعدی درخواست کاربر بر اساس اطلاعات ذخیره شده و در حافظه پنهان یا همان Cash خوانده شود و این کار باعث افزایش سرعت بارگذاری صفحات وب و همچنین صرفه جویی در مصرف پهنای باند می شود. این سرور همچنین تضمین می کند که کاربران می توانند در حالت آفلاین به محتوای وب مثل فایل های رسانه های دسترسی داشته باشند.

کش سرور در پایگاه داده یک عامل تاثیرگذار است و کاربرد دارد. استفاده از Cash Server باعث می شود که سرعت دستیابی به اطلاعات در پایگاه داده خیلی بیشتر از قبل باشد و این امکان را برای کاربر فراهم می کند که با کاهش تاخیردر بازیابی داده ها در هنگام استفاده از پایگاه داده توان عملیاتی را افزایش دهد و این امر باعث بهبود عملکرد برنامه ها می شود. کاربر می تواند کش پایگاه داده را در هر نوع پایگاه داده ای از جمله Nosql و پایگاه داده های رابطه ای استفاده کند.

<hr>
 <div dir="rtl"><b>موضوع : DatabaseSecurity-BigData - تحقیق شماره 4</b></div>
 <br>

امنیت در پایگاه داده: امنیت در پایگاه داده شامل حفاظت از داده ها در برابر دسترسی غیرمجاز، افشاگری، تخریب، تغییر و استفاده نامشروع می باشد. یکی از تهدیدات موجود در پایگاه داده تهدیدات داخلی می باشد . به عنوان مثال فردی در داخل خود سازمان یک خطر امنیتی ایجاد کند یا یک فرد بی دقت که باانجام کاری سهل انگارانه پایگاه داده را در وضعیت خطر قرار می دهد یا یک فرد خارجی که در سازمان حضور ندارد و از طریق روش های مختلفی مانند مهندسی اجتماعی به اطلاعات پایگاه داده دست پیدا می کند. خطای انسانی دیگر تهدید امنیتی پایگاه داده است که در آن با انتخاب گذرواژه های ضعیف، به اشتراک گذاشتن رمز عبور با دیگران، حذف یا خراب شدن تصادفی داده ها باعث به خطر افتادن امنیت پایگاه داده می شود. برای پیشگیری از این خطاها توصیه می شود که از گذرواژه قوی استفاده کرده و از در اختیار گذاشتن اطلاعات پایگاه داده با افراد خارج از سازمان خودداری کنیم.

از دیگر تهدیدات پایگاه داده می توان به حملات Dos و DDos اشاره کرد که در آن فرد با استفاده از تعداد زیادی درخواست جعلی پایگاه داده را تحت تاثیر قرار می دهد در نتیجه سرور نمی تواند درخواست های واقعی کاربران را انجام دهد و اغلب از کار می افتد یا ناپایدار می شود.

روش های مختلفی برای محافظت از پایگاه داده وجود دارد به عنوان مثال رمزنگاری که در آن داده ها کدگذاری می شود و این کدگذاری به گونه ای انجام می شود که تنها کاربران مجاز بتوانند داده ها را بخوانند. از دیگر روش ها برای حفظ امنیت پایگاه داده، کنترل دسترسی می باشد که در آن دسترسی به پایگاه داده تا سطح لازم برای هر شخص در نظر گرفته می شود. مدیریت هویت روش دیگر حفظ امنیت است که به این معناست که کاربر چه کسی و مجاز به انجام چه کاری است .

................................................................................................................................................................................................................................................................................................

مدیریت داده های بزرگ : داده های بزرگ یا کلان داده، داده هایی هستند که دارای اندازه و پیچیدگی بسیار زیاد بوده و به طور معمول فراتر از حدی هستند که بتوانیم آن ها را در ابزار های سنتی ذخیره و مدیریت کنیم. این داده ها با گذشت زمان به سرعت در حال رشد هستند.

سه ویزگی مهم در کلان داده که این داده ها را با دیگر داده ها متمایز می کند شامل :

حجم داده (Volume): مجموعه داده ها در کلان داده بسیار بزرگتر از این است که بتوان آن را با یک لپ تاپ پردازش کرد. نمونه ای از مجموعه داده ای با حجم بالا، تمامی تراکنش های بانکی در یک روز است .

سرعت داده (Velocity): داده ها با چنان سرعت تولید می شوند که نیاز به تکنیک های پردازش مجزا دارند.

تنوع داده (Variety): داده های بزرگ از منابع متنوعی به دست می آید و به طور کلی یکی از سه نوه ساختار یافته، نیمه ساختار یافته و بدون ساختار یافته می باشد.

از فریمورک های موجود برای ذخیره و پردازش داده های بزرگ در اندازه های مختلف از گیگابایت تا پتابایت می توان به Haddop اشاره کرد. Spark دیگر تکنولوژی موجود برای داده های بزرگ که یک موتور سریع و عمومی برای پردازش در مقیاس بزرگ است . راز سریع بودن این تکنولوژی این است که روی Ram اجرا می شود و این باعث می شود پردازش بسیار سریع تر از درایور های دیسک باشد.Sql برای اطمینان از اعتبار داده ها استفاده می شود اما NoSql زمانی استفاده می شود که سرعت دسترسی به داده های بزرگ مهم تر باشد به این دلیل که مقیاس پذیری در آن به گونه ای طراحی شده که با افزودن گره های بیشتر یا گسترش زیر ساخت، به راحتی به صورت افقی/عمودی مقیاس پذیر باشند. ابزار های متعددی برای تحلیل داده های بزرگ در دسترس هستند به عنوان مثال آپاچی ماهوت (Apache Mahout) که برای حل چالش های کلان داده ایجاد شده است و این فریمورک قصد فراهم کردن روش های یادگیری ماشین مقیاس پذیر و تجاری برای نرم افزار های تحلیل داده هوشمند و با مقیاس بزرگ را دارد. از جمله شرکت هایی که از الگوریتم های مقیاس پذیر یادگیری ماشین استفاده می کنند می توان به گوگل، آمازون و فیسبوک اشاره کرد.
<hr>

