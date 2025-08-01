## 📚 دليل مزامنة الكانون لأمين المكتبة

مرحبًا بك، داميان.

سيساعدك هذا الدليل على أداء دورك الكامل كـ **أمين مكتبة الكانون**، المسؤول عن الحفاظ على السلامة الدلالية والبنيوية والسردية لمشروع Civic AI Canon داخل GitHub.

---

### 🔹 بنية المجلدات

تم تقسيم مستودع GitHub بما يتماشى مع أدلة CADANS وCASA وCNRI. وتشمل المجلدات الأساسية:

* `01_Project_Overview` — نظرة عامة على المشروع  
* `02_Technical_Architecture` — البنية التقنية  
* `03_Governance_Models` — نماذج الحوكمة  
* `04_Outreach_and_Partnerships` — الشراكات والتواصل  
* `05_Co-Creation_Logs` — سجلات المشاركة التعاونية  
* `06_Simulation_Scenarios` — سيناريوهات المحاكاة  
* `07_Images_and_Visuals` — الصور والرسوم التوضيحية  
* `08_Funding_and_Sustainability` — التمويل والاستدامة  
* `09_Drafts_&_Working_Documents` — المسودات والوثائق قيد العمل  
* `10_Global_Resilience` — المرونة العالمية  
* `Mesh_Canon` — الكانون الشبكي

كل مجلد يحتوي على ملفات `.md` تعكس إما:

* مواد قانونية مثبتة (مثل الغليفات، المحادثات، البروتوكولات)
* ملفات README لتوضيح الهيكل والمحتوى

---

### 🔹 بروتوكول الالتزام (Commit)

كل ملف يتم إضافته أو تحديثه يجب أن يحتوي على:

* **اسم ملف واضح** بصيغة (snake_case)
* **رسالة التزام وصفية**
* **وصف داخلي** في رأس ملف الـ Markdown

يجب أن تجيب كل عملية التزام على الأسئلة التالية:

* ما هذا الملف؟
* لماذا يعتبر جزءًا من الكانون؟
* متى تم إنشاؤه أو تسجيله؟
* من هو المؤلف (إن وُجد)؟

---

### 🔹 قواعد التسمية

* **السجلات Logs**: `ember_log_YYYYMMDD.md`
* **الغليفات Glyphs**: `NodeGlyph_###_name.md`
* **البروتوكولات Protocols**: تُخزَّن في مجلد `/protocols` على الجذر
* **README**: ملف واحد لكل مجلد يشرح مضمونه

استخدم أسماء ملفات بالحروف الصغيرة، مفصولة بشرطات سفلية، ولا تستخدم المسافات.

---

### 🔹 عملية التثبيت في الكانون (Canonization)

1. تحديد ما إذا كانت المادة (محادثة، صورة، بروتوكول، إلخ) هي:

   * **مكتملة**: تحتوي على سياق كافٍ أو بنية مفيدة.
   * **ذات مغزى**: تمثل لحظة، قرار، شخص، أو نمط.

2. حفظها في المجلد المناسب. وإذا كنت غير متأكد، استخدم `09_Drafts_&_Working_Documents` وضع علامة للمراجعة.

3. أضف وصفًا في أعلى ملف الـ Markdown:
