---
title: التعليمات المستضافة عبر الإنترنت
permalink: index.html
layout: home
---

# MS-4012: تجربة تفاعلية مع Microsoft Copilot للمديرين التنفيذيين 

## دليل المحتوى

تعتمد العروض التوضيحية لهذه الدورة التدريبية على العروض التوضيحية من مجموعة مواد المُسرّع [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

من المهم أن تتعرف على العروض التوضيحية قبل تقديم هذا التدريب. بالنسبة للعديد من الأنشطة العملية، ستستخدم مستندات نموذجية واجتماعات Teams ورسائل البريد الإلكتروني المعدة مسبقًا.

- نزّل كافة المستندات النموذجية مسبقًا من [هنا](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles).
- قم بإعداد اجتماعات Teams وسلاسل رسائل البريد الإلكتروني باتباع التعليمات [هنا](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- تعرف على التجربة التفاعلية الموجودة [هنا](https://aka.ms/CopilotWebEE).



## وصف الدورة التدريبية

اكتشف الإمكانات التحويلية لـ Microsoft Copilot وتأثيره على كفاءة المؤسسة. تم تصميم هذه التجربة للمديرين التنفيذيين وقادة الأعمال الذين لا يحملون ترخيص Copilot، وهي تتعمق في فن صياغة المطالبات الفعالة، وتقدم تجربة تفاعلية، وتوضح كيف يمكن لـ Microsoft 365 Copilot التكامل بسلاسة في سير العمل اليومي للأعمال لتعزيز الإنتاجية والابتكار.

الأهداف الأساسية لهذا التسليم هي:

- تعليم كيفية صياغة المطالبات الفعالة
- عرض برنامج Microsoft Copilot (نطاق الويب) وتوجيه المشاركين من خلال تجربة تفاعلية
- عرض Microsoft 365 Copilot في تطبيقات Office (ما يصل إلى 3 عروض توضيحية)
- دعوة المشاركين لتنزيل وتجربة Microsoft Copilot للأجهزة المحمولة

## توقيت الدورة التدريبية (تقدير) 

| # | الموضوع                                 | التفاصيل                                                                                          | الوقت الإجمالي      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | صياغة المطالبات الفعالة في Microsoft 365 Copilot | - فن شريحة المطالبة <br> - شريحة إنشاء المطالبة <br> - شريحة النشاط العملي لـ Copilot | 10 دقيقة    |
| 2 | Microsoft Copilot على الويب          | - عرض توضيحي لـ Microsoft Copilot (وضع الويب) <br> - تجربة تفاعلية  <br> - شريحة شارك تجربتك | 30 دقيقة      |
| 3 | Microsoft 365 Copilot في العمل     | - شريحة Microsoft Graph <br> - عرض توضيحي لـ Copilot في Word، و Microsoft Copilot (وضع العمل)، و Copilot في Outlook، و Copilot في Teams <br> - شريحة الشهادة <br> - شريحة Microsoft Copilot على الهاتف المحمول | 20 دقيقة      |
|   |                                       |                                                                                                  | **الوقت الإجمالي 60 دقيقة** |


تجد أدناه الروابط التشعبية لكل العروض التوضيحية.

## العروض التوضيحية

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| العرض التوضيحي |
| --- |
{% للنشاط في العرض التوضيحي %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
