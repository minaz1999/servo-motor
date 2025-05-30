عنوان: 
کنترل سروو موتور با استفاده از آردوینو
هدف آزمایش:
هدف اصلی این آزمایش، درک نحوه عملکرد سروو موتور و کنترل موقعیت زاویه‌ای آن با استفاده از برد آردوینو و برنامه‌نویسی مناسب است.
تئوری آزمایش:
•	برد آردوینو UNO: یک میکروکنترلر است که می‌تواند سیگنال‌های کنترلی مورد نیاز برای سروو موتور را تولید کند. آردوینو با استفاده از کتابخانه Servo.h، فرآیند تولید سیگنال PWM برای سرووها را بسیار ساده می‌کند.
•	سروو موتور (Servo Motor): سروو موتور یک موتور الکتریکی کوچک با قابلیت کنترل دقیق موقعیت زاویه‌ای است. برخلاف موتورهای DC معمولی که به صورت پیوسته می‌چرخند، سروو موتورها قادرند در یک محدوده زاویه‌ای خاص (معمولاً 0 تا 180 درجه) به یک موقعیت دقیق منتقل شده و در همان موقعیت ثابت بمانند. کنترل سروو موتور معمولاً از طریق سیگنال PWM (Pulse Width Modulation) انجام می‌شود؛ عرض پالس سیگنال ورودی، زاویه سروو را تعیین می‌کند.
•	پین‌های دیجیتال: پین‌های دیجیتال آردوینو می‌توانند برای ارسال سیگنال PWM به سروو موتور استفاده شوند.


شرح مدار و قطعات مورد استفاده:
•	برد آردوینو UNO
•	1عدد سروو موتور
•	سیم‌های مخابراتی
•	برد بورد

روش انجام آزمایش:

روش انجام آزمایش:
1.	اتصالات سخت افزاری: 
2.	سیم مشکی سروو موتور (GND): به پین GND (زمین) آردوینو وصل می‌شود.
3.	سیم زرد سروو موتور (VCC): به پین 5V (تغذیه 5 ولت) آردوینو وصل می‌شود.
4.	سیم نارنجی سروو موتور (Signal): به یکی از پین‌های دیجیتال PWM دار که ما به پین 9 آردوینو وصل کردیم.

نتیجه گیری:
در این آزمایش، هدف، درک و کنترل سروو موتور با استفاده از برد آردوینو بود. نتایج به دست آمده نشان می‌دهد که:
•	اتصال سروو موتور به آردوینو طبق شماتیک، با موفقیت انجام شد و سروو از طریق پین دیجیتال 9 تغذیه سیگنال گرفت.
•	کدهای نوشته شده با استفاده از کتابخانه Servo.h  به درستی عمل کردند و سروو موتور را به زوایای مشخص (0، 45، 90، 135، 180 درجه) حرکت دادند.
•	تاخیرهای (delay) تعریف شده در کد، امکان مشاهده حرکت سروو در هر زاویه را فراهم آوردند.
•	این آزمایش به وضوح نشان داد که می‌توان با استفاده از آردوینو و سروو موتور، سیستم‌های کنترل موقعیت دقیق را پیاده‌سازی کرد که کاربردهای فراوانی در رباتیک، اتوماسیون و سایر پروژه‌های الکترونیکی دارند.


![servo motor](https://github.com/user-attachments/assets/a284815c-1a21-493b-8aeb-f07ca54f3558)
[servo motor.pdf](https://github.com/user-attachments/files/20469718/servo.motor.pdf)
[servo motor.docx](https://github.com/user-attachments/files/20469717/servo.motor.docx)
![photo18778646818](https://github.com/user-attachments/assets/d6df9f75-0642-41ff-9bc5-d002192f4161)
![photo18778646137](https://github.com/user-attachments/assets/c4cd704b-806a-4bf7-9be7-da6759877188)


https://github.com/user-attachments/assets/ea2d580a-0b3f-44f2-8825-9a66a2a94ab7

