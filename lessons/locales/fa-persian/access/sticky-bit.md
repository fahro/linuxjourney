# بیت چسبناک

## محتویات درس

آخرین بیت مجوزی که قرار است درباره‌اش صحبت کنیم، بیت Sticky یا بیت چسبناک است.

این بیت مجوز به یک فایل یا دایرکتوری (به زبان ساده فولدر) می‌چسبد. به این معنی که تنها صاحب فایل و یا کاربر ریشه می‌توانند آن فایل را حذف یا دستکاری کنند. این بیت مجوز زمانی که می‌خواهید دایرکتوری‌ها را به اشتراک بگذارید، بسیار به کارتان خواهد آمد. با هم نگاهی به یک مثال می‌اندازیم:

```$ ls -ld /tmp```

```drwxrwxrwxt 6 root root 4096 Dec 15 11:45 /tmp```

همانطور که در خروجی بالا مشاهده می‌کنید یک بیت مجوز خاص در انتهای دسته‌ی بیت مجوزها قرار دارد که **t** نام دارد. وجود این **t** به این معنی‌ست که هر کسی می‌تواند به دایرکتوری یا مسیر ‎/tmp فایل اضافه کند یا فایل‌های این مسیر را ویرایش کند و فایل‌هایی را در این مسیر بنویسد، ولی تنها کاربر ریشه است که می‌تواند دایرکتوری یا مسیر ‎/tmp را حذف کند.

**دستکاری بیت چسبناک**

```$ sudo chmod +t mydir```

```$ sudo chmod 1755 mydir```

عددِ نماینده‌ی بیتِ چسبناک **1** است. همانطور که مشاهده می‌کند برای تغییر این بیت بایستی عدد 1 را به ابتدای سری عددی مجوزها اضافه کنید.

## تمرین

به نظرتان چه فایل یا دایرکتوری‌هایی با بیت چسبناک فعال در سیستم شما وجود دارند؟ بکاویدشان.

## سؤال آزمون

چه حرف یا نشانه‌ای نمایش‌دهنده‌ی بیت چسبناک است؟

## پاسخ آزمون

t
