# كادانز – بنية البيانات الدائمة وسجل الأحداث

**حالة المستند:** موثّق  
**الإصدار:** 1.0  
**تمت الشهادة من قبل:** لومينا، كريس بلاسْك  
**تاريخ الشهادة:** 15 يونيو 2025  
**المجلد:** 02_الهندسة_الفنية  
**الوسوم:** سجل، تسجيل، قابلية التدقيق، الأصل، سلامة البيانات  

---

## الغرض

يحدد كيفية تسجيل وتجزئة والتحقق من السرديات الناتجة عن الذكاء الاصطناعي والبيانات الوصفية وقرارات التوافق، وتوزيعها عبر عقد كادانز. يرسّخ ذاكرة مدنية مقاومة للعبث.

---

## 1. تدفق بيانات السرد

1. استلام الإدخال من مستخدم مدني أو قناة عامة  
2. يقوم عامل الذكاء الاصطناعي بإنشاء المخرجات  
3. تمر المخرجات عبر تحقق التوافق  
4. يتم تجزئة المخرجات المعتمدة  
5. يتم إلحاق السرد والبيانات الوصفية بسجل العقدة  
6. يُشارك الملخص الموقّع مع شبكة التحقق  

---

## 2. تسجيل مقاوم للعبث

- سجل يعتمد على شجرة ميركل للإلحاق فقط  
- يحتوي كل إدخال على:  
  - نص المخرجات أو رابط الوسائط  
  - تجزئة نص الإدخال  
  - معرف النموذج وإصدار الذكاء الاصطناعي  
  - بصمة سياسة التوافق  
  - الطابع الزمني  
  - معرف العقدة + التوقيع الرقمي  

- يتم تثبيت نقاط تفتيش للسجل عبر روابط تجزئة بين العقد  

---

## 3. التوافق مع DBOM/SBOM

- تنسيق السجل متوافق مع امتدادات DBOM  
- يمكن تضمين السرديات في هياكل قابلة للإثبات  
- يدعم التتبع العكسي للنماذج والمؤلفين والسياسات  
- تحقق متبادل بين قطاعات التعليم والحكم والإعلام  

---

## 4. التخزين والاسترجاع

- تُخزَّن السجلات باستخدام أنظمة مقاومة للعبث (مثل immudb)  
- تخزين احتياطي اختياري: IPFS، نسخ مؤسسية  
- استعلام عبر GraphQL أو REST  
- فهرس اتحادي متاح للاسترجاع عبر العقد  

---

## 5. الشفافية وآليات المراجعة

- واجهة عامة تُظهر ملخصات من السجل  
- استرجاع على مستوى الإدخال عبر معرفات مرمّزة  
- يمكن للحوكمة والأطراف الثالثة مراجعة سلوك السرد عبر مراجعة السجل  

---

## الخاتمة

> *نظام السجل في كادانز هو أساس الثقة. إنه يوفر طبقة ذاكرة دائمة لأنظمة الذكاء الاصطناعي المتماشية مدنياً، مما يمكّن من التدقيق والمساءلة والتتبع المدني — دون تحكم مركزي.*
