# شروع تسک بنتوک


## ساخت المان‌های کاستوم 

در پوشه components/UI دو فایل برای ساخت button کاستوم و المان‌های فرم کاستوم ایجاد شده است که هر کدام ازین المان‌ها میتوانند در کامپوننت‌های دلخواه تعریف شده واستفاده شوند.


### در button ایجاد شده مقادیر steps برای مراحل پروژه تعریف شده است که در صورت استفاده از آن مراحل پروژه به کاربر نمایش داده میشود.  

### ساخت hook با نام useInput برای استفاده از inputها تعریف شده است که با استفاده از آن میتوان value المان input استفاده شده را برای موارد 1.گرفتن مقدار، 2. بررسی validation المان، 3.بررسی خطاهای ایجاد شده با استفاده از تعریف یک function برای بررسی value المان، 4. تعریف onChange event المان، 5.تعریف onBlur event المان و 6.ریست کردن مقدار المان

## ساخت صفحه login و استفاده از المان‌های کاستوم ساخته شده
در این صفحه با استفاده از المان‌ها مقادیر را دریافت کرده و پس از تکمیل تمام inputها و ارسال آنها کاربر میتواند به صفحه داشبورد وارد شود.

## استفاده از redux/toolkit به عنوان state management
در این بخش با استفاده از stateها و actionهای ایجاد شده برای فرستادن اطلاعات و وارد شدن به داشبورد از صفحه login و ست کردن token و همچنین گرفتن اطلاعات و logout کردن در صفحه داشبورد استفاده شده است. 
