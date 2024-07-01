# Servo-motor
<div dir="rtl">
## خوارزمية تشغيل محركات من نوع سيرفو موتر لتشكيل حركة مشي الروبوت
1- ندرس حركة الروبوت وهي عادة ما تكون خطوات محددة وتتكرر بشكل مستمر، نقسم الحركة الى خطوات يتم تنفيذها بالتبادل بين القدمين على سبيل المثال في القدم اليمنى يتحرك المفصل العلوي ثم مفصل الركبة ثم القدم. <br>
<br>
2- كل قدم تمثلها 3 من السيرفوهات، نقوم بتحديد الزوايا المناسبة لكل سيرفو لكل خطوة.<br>
<br>
3- توصيل القطع الالكترونية (محركات السيرفو) <br>
- منفذ Signal في أحد منافذ digital. 
- منفذ VCC مصدر طاقة خارجي <br>
- منفذ Gnd مشترك مع ارضي مصدر الطاقة الخارجي و الاردوينو<br>
<br>
4- كتابة الكود:   <br>
- تحميل برنامج الاردوينو   <br>
- كتابة الكود بدايةً باستدعاء المكتبة و تعريف المحركات و منافذ توصيلها، ثم كتابة كود الحركة بالزوابا المناسبة، بما أن حركة القدمين هي خطوات متكررة يمكن كتابة دوال لتنفيذ حركة القدم بشكل مستمر و تعمل بأمر واحد.<br>
<br>
5- الاختبار و التجريب: يتم اختبار حركة الروبوت بشكل فعلي و تعديل الزوايا حسب الحاجة والتأكد من أن الاكواد تنتج الحركة المرغوبة بشكل صحيح قبل استخدامها بشكل نهائي.<br>
</div>

