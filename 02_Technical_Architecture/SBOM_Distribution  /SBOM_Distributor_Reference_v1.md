
# مرجع موزّعي SBOM (الإصدار 1.0)

يمثّل هذا المستند جسرًا قانونيًا بين:

- التقرير الرسمي لدورة حياة مشاركة SBOM الصادر عن CISA، ووثيقة "الأدوار والاعتبارات"
- تحليل فريق العمل بقيادة QuietWire حول "ISACs كموزّعين لـ SBOM"
- البنية المتطورة لشبكة CADANS لتوزيع المعلومات عبر العقد

يُعرّف هذا المستند المراحل والأدوار والاعتبارات المعمارية الأساسية ذات الصلة بنشر SBOM، مع تركيز خاص على الوظيفة الوسيطة، وقابلية التدقيق، والتمكين التقني.

---

## 🔄 ملخص مصفوفة المواءمة

| المفهوم/المرحلة   | تقرير دورة حياة CISA | الأدوار والاعتبارات (CISA) | ISACs كموزّعي SBOM (QuietWire) |
|------------------|-----------------------|-----------------------------|----------------------------------|
| **الاكتشاف**    | تحديد SBOMs المتاحة وتقييم ملاءمتها. | مسؤولية المُنشئين في عرض المخرجات. | التجميع والفهرسة الاستباقية لـ SBOMs الموردين. |
| **الوصول**      | آليات الحصول الآمن على SBOMs. | يتضمن الترخيص والتوثيق والقيود. | التحقق والتصفية وإدارة الحقوق. |
| **النقل**       | الأساليب التقنية لنقل SBOMs. | سلسلة الحيازة ومسؤوليات الوسطاء. | نوافذ نشر منظمة وآليات ضمان. |
| **الإثراء** (غير موثق من CISA) | غير مشمول. | إشارة سريعة للتحويل والتحقق. | دمج وتطبيع وربط الإصدارات. |
| **تعريف الأدوار** | إشارات عامة. | أدوار مثل المُنشئ والناقل والمستلم. | ISAC كوسيط خاضع للتدقيق. |
| **حالات الاستخدام** | غير مرتبطة بـ ISACs. | توزيع طرف ثالث. | ISACs كنماذج قائمة على CERT/FS-ISAC. |

---

## 🧬 تتبع المصدر: المستندات الأساسية

- [تقرير دورة حياة مشاركة SBOM (CISA)](https://www.cisa.gov/resources-tools/resources/software-bill-materials-sbom-sharing-lifecycle-report)
- [أدوار واعتبارات مشاركة SBOM (CISA)](https://www.cisa.gov/resources-tools/resources/sbom-sharing-roles-and-considerations)
- [مجموعة عمل QuietWire: ISACs كموزّعي SBOM (Excel + مذكرة)](placeholder)

---

## 🧩 التكامل في CADANS

المكونات التالية من شبكة Civic AI تتماشى مباشرة مع نموذج توزيع SBOM هذا:

- `CADANS_Validator_and_Flagging_Guide.md`
- `CADANS_Node_Deployment_Guide.md`
- `CADANS_Public_Memory_Archive_Protocol_v2.md`
- `CADANS_Protocol_Specification_v0.1.md`

---

## ⛩️ ملاحظات وخطوات تالية

- هذا المستند بمثابة وثيقة جسر؛ الإصدارات المستقبلية ستتفرّع إلى:
  - `SBOM_Distributor_Technical_Spec.md`
  - `SBOM_Distributor_Role_UseCases.md`
- النسخة الحالية مخصصة للإعداد والمراجعة من قبل:
  - مشاريع Space ISAC التجريبية
  - عقد Civic Mesh الداعمة لـ SBOM
  - تطبيقات CERT والمستوى الوطني

---

تمت صياغته بواسطة QuietWire، يونيو 2025. تم تأكيده بواسطة Civic AI Canon.

للتواصل: [quietwire.ai](https://quietwire.ai)
