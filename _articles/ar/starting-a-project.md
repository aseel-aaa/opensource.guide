---
lang: ar
title: البدء بمشروع مفتوح المصدر
description: تعلّم المزيد عن عالم المصادر المفتوحة واستعد لإطلاق مشروعك الخاص.
class: beginners
order: 2
image: /assets/images/cards/beginner.png
related:
  - finding
  - building
---

<div dir="rtl" markdown="1">

## "ماذا" و"لماذا" المصادر المفتوحة

إذًا، أنت تفكر في البدء بالمصادر المفتوحة؟ تهانينا! العالم يقدّر مساهمتك. دعنا نتحدث عن ماهية المصادر المفتوحة ولماذا يفعل الناس ذلك.

### ماذا يعني "المصدر المفتوح"؟

عندما يكون المشروع مفتوح المصدر، فهذا يعني **أن أي شخص حر في استخدام مشروعك ودراسته وتعديله وتوزيعه لأي غرض.** يتم فرض هذه الأذونات من خلال [ترخيص مفتوح المصدر](https://opensource.org/licenses).

المصدر المفتوح قوي لأنه يخفض حواجز التبني والتعاون، مما يسمح للناس بنشر المشاريع وتحسينها بسرعة. كما أنه يمنح المستخدمين إمكانية التحكم في حوسبتهم الخاصة، مقارنةً بالمصادر المغلقة. على سبيل المثال، الشركة التي تستخدم برامج مفتوحة المصدر لديها خيار توظيف شخص ما لإجراء تحسينات مخصصة على البرنامج، بدلاً من الاعتماد حصريًا على قرارات منتج بائع <span dir='ltr' markdown="1">vendor</span> المصادر المغلقة.

_البرمجيات الحرة_ <span dir='ltr' markdown="1">Free software</span> تشير إلى نفس مجموعة المشاريع كـ _المصدر المفتوح_. أحيانًا سترى أيضًا [هذه المصطلحات](https://en.wikipedia.org/wiki/Free_and_open-source_software) مدمجة كـ "البرمجيات الحرة والمفتوحة المصدر" <span dir='ltr' markdown="1">(FOSS)</span> أو "البرمجيات الحرة والحُرّة والمفتوحة المصدر" <span dir='ltr' markdown="1">(FLOSS)</span>. _الحر_ <span dir='ltr' markdown="1">Free</span> و _الحُرّ_ <span dir='ltr' markdown="1">libre</span> يشيران إلى الحرية، [وليس السعر](#does-open-source-mean-free-of-charge).

### لماذا يفتح الناس مصدر أعمالهم؟

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/kentcdodds?s=180" class="pquote-avatar" alt="avatar">
  واحدة من أكثر التجارب المجزية التي أحصل عليها من استخدام والتعاون في المصادر المفتوحة تأتي من العلاقات التي أبنيها مع مطورين آخرين يواجهون العديد من نفس المشاكل التي أواجهها.
  <p markdown="1" class="pquote-credit">
— @kentcdodds, ["كيف كان الدخول إلى المصادر المفتوحة رائعًا بالنسبة لي"](https://kentcdodds.com/blog/how-getting-into-open-source-has-been-awesome-for-me)
  </p>
</aside>

[هناك العديد من الأسباب](https://ben.balter.com/2015/11/23/why-open-source/) التي قد تجعل شخصًا أو منظمة يرغب في فتح مصدر مشروع. بعض الأمثلة تشمل:

* **التعاون:** يمكن لمشاريع المصادر المفتوحة قبول التغييرات من أي شخص في العالم. [<span dir='ltr' markdown="1">Exercism</span>](https://github.com/exercism/)، على سبيل المثال، هي منصة تمارين برمجية تضم أكثر من 350 مساهمًا.

* **التبني والاقتباس:** يمكن لأي شخص استخدام مشاريع المصادر المفتوحة لأي غرض تقريبًا. يمكن للناس حتى استخدامها لبناء أشياء أخرى. [<span dir='ltr' markdown="1">WordPress</span>](https://github.com/WordPress)، على سبيل المثال، بدأ كـ <span dir='ltr' markdown="1">fork</span> لمشروع موجود يسمى [<span dir='ltr' markdown="1">b2</span>](https://github.com/WordPress/book/blob/HEAD/Content/Part%201/2-b2-cafelog.md).

* **الشفافية:** يمكن لأي شخص فحص مشروع مفتوح المصدر بحثًا عن أخطاء أو تناقضات. الشفافية مهمة للحكومات مثل [بلغاريا](https://medium.com/@bozhobg/bulgaria-got-a-law-requiring-open-source-98bf626cf70a) أو [الولايات المتحدة](https://www.cio.gov/2016/08/11/peoples-code.html)، والصناعات المنظمة مثل البنوك أو الرعاية الصحية، وبرامج الأمان مثل [<span dir='ltr' markdown="1">Let's Encrypt</span>](https://github.com/letsencrypt).

المصادر المفتوحة ليست للبرمجيات فقط. يمكنك فتح مصدر كل شيء من مجموعات البيانات إلى الكتب. راجع [<span dir='ltr' markdown="1">GitHub Explore</span>](https://github.com/explore) للأفكار حول ما يمكنك فتح مصدره.

### هل المصدر المفتوح يعني "مجاني"؟

أحد أكبر عوامل الجذب للمصادر المفتوحة هو أنها لا تكلف مالاً. ومع ذلك، فإن "المجانية" هي مجرد نتيجة ثانوية للقيمة الإجمالية للمصادر المفتوحة.

نظرًا لأن [ترخيص المصدر المفتوح يتطلب](https://opensource.org/definition-annotated/) أن يتمكن أي شخص من استخدام مشروعك وتعديله ومشاركته لأي غرض تقريبًا، فإن المشاريع نفسها تميل إلى أن تكون مجانية. إذا كان المشروع يكلف مالاً لاستخدامه، يمكن لأي شخص قانونيًا عمل نسخة واستخدام النسخة المجانية بدلاً من ذلك.

ونتيجة لذلك، فإن معظم مشاريع المصادر المفتوحة مجانية، لكن "المجانية" ليست جزءًا من تعريف المصدر المفتوح. هناك طرق لفرض رسوم على مشاريع المصادر المفتوحة بشكل غير مباشر من خلال الترخيص المزدوج <span dir='ltr' markdown="1">dual licensing</span> أو الميزات المحدودة <span dir='ltr' markdown="1">limited features</span>، مع الالتزام بالتعريف الرسمي للمصادر المفتوحة.

## هل يجب أن أطلق مشروعي المفتوح المصدر الخاص؟

الإجابة القصيرة هي نعم، لأنه بغض النظر عن النتيجة، فإن إطلاق مشروعك الخاص هو طريقة رائعة لتعلم كيفية عمل المصادر المفتوحة.

إذا لم تفتح مصدر مشروع من قبل، فقد تكون متوترًا بشأن ما سيقوله الناس، أو ما إذا كان أي شخص سيلاحظ على الإطلاق. إذا كان هذا يبدو مثلك، فأنت لست وحدك!

عمل المصادر المفتوحة يشبه أي نشاط إبداعي آخر، سواء كان الكتابة أو الرسم. قد يبدو من المخيف مشاركة عملك مع العالم، لكن الطريقة الوحيدة لتحسين مهاراتك هي الممارسة - حتى لو لم يكن لديك جمهور.

إذا لم تكن مقتنعًا بعد، خذ لحظة للتفكير في ما قد تكون أهدافك.

### تحديد أهدافك

يمكن أن تساعدك الأهداف في معرفة ما يجب العمل عليه، وما يجب قول "لا" له، وأين تحتاج إلى مساعدة من الآخرين. ابدأ بسؤال نفسك، _لماذا أفتح مصدر هذا المشروع؟_

لا توجد إجابة صحيحة واحدة على هذا السؤال. قد يكون لديك أهداف متعددة لمشروع واحد، أو مشاريع مختلفة بأهداف مختلفة.

إذا كان هدفك الوحيد هو إظهار عملك، فقد لا تريد حتى مساهمات، بل وحتى تقول ذلك في ملف <span dir='ltr' markdown="1">README</span> الخاص بك. من ناحية أخرى، إذا كنت تريد مساهمين، فستستثمر الوقت في توثيق واضح وجعل الوافدين الجدد يشعرون بالترحيب.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/mavris?s=180" class="pquote-avatar" alt="avatar">
  في مرحلة ما أنشأت <span dir='ltr' markdown="1">UIAlertView</span> مخصصًا كنت أستخدمه... وقررت جعله مفتوح المصدر. لذلك قمت بتعديله ليكون أكثر ديناميكية ورفعته إلى <span dir='ltr' markdown="1">GitHub</span>. كتبت أيضًا توثيقي الأول لأشرح للمطورين الآخرين كيفية استخدامه في مشاريعهم. من المحتمل أن لا أحد استخدمه لأنه كان مشروعًا بسيطًا لكنني كنت أشعر بالرضا عن مساهمتي.
  <p markdown="1" class="pquote-credit">
— @mavris, ["مطورو البرمجيات ذاتيو التعلم: لماذا المصادر المفتوحة مهمة لنا"](https://medium.com/rocknnull/self-taught-software-engineers-why-open-source-is-important-to-us-fe2a3473a576)
  </p>
</aside>

مع نمو مشروعك، قد يحتاج مجتمعك إلى أكثر من مجرد كود منك. الرد على <span dir='ltr' markdown="1">issues</span>، ومراجعة الكود، والترويج لمشروعك كلها مهام مهمة في مشروع مفتوح المصدر.

بينما تعتمد كمية الوقت الذي تقضيه في المهام غير البرمجية على حجم مشروعك ونطاقه، يجب أن تكون مستعدًا كمسؤول للتعامل معها بنفسك أو العثور على شخص لمساعدتك.

**إذا كنت جزءًا من شركة تفتح مصدر مشروع،** تأكد من أن مشروعك لديه الموارد الداخلية التي يحتاجها للازدهار. ستحتاج إلى تحديد من المسؤول عن صيانة المشروع بعد الإطلاق، وكيف ستشارك هذه المهام مع مجتمعك.

إذا كنت بحاجة إلى ميزانية مخصصة أو موظفين للترويج والعمليات وصيانة المشروع، ابدأ تلك المحادثات مبكرًا.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/captainsafia?s=180" class="pquote-avatar" alt="avatar">
  عندما تبدأ في فتح مصدر المشروع، من المهم التأكد من أن عمليات إدارتك تأخذ في الاعتبار المساهمات والقدرات للمجتمع المحيط بمشروعك. لا تخف من إشراك المساهمين غير الموظفين في نشاطك التجاري في الجوانب الرئيسية للمشروع - خاصة إذا كانوا مساهمين متكررين.
  <p markdown="1" class="pquote-credit">
— @captainsafia, ["إذن تريد فتح مصدر مشروع، صحيح؟"](https://dev.to/captainsafia/so-you-wanna-open-source-a-project-eh-5779)
  </p>
</aside>

### المساهمة في مشاريع أخرى

إذا كان هدفك هو تعلم كيفية التعاون مع الآخرين أو فهم كيفية عمل المصادر المفتوحة، ففكر في المساهمة في مشروع موجود. ابدأ بمشروع تستخدمه وتحبه بالفعل. يمكن أن تكون المساهمة في مشروع بسيطة مثل إصلاح الأخطاء الإملائية أو تحديث التوثيق.

إذا لم تكن متأكدًا من كيفية البدء كمساهم، تحقق من [دليل كيفية المساهمة في المصادر المفتوحة](../how-to-contribute/).

## إطلاق مشروعك المفتوح المصدر الخاص

لا يوجد وقت مثالي لفتح مصدر عملك. يمكنك فتح مصدر فكرة، أو عمل قيد التقدم، أو بعد سنوات من كونه مصدرًا مغلقًا.

بشكل عام، يجب عليك فتح مصدر مشروعك عندما تشعر بالراحة في أن يشاهد الآخرون عملك ويقدمون ملاحظات عليه.

بغض النظر عن المرحلة التي تقرر فيها فتح مصدر مشروعك، يجب أن يتضمن كل مشروع التوثيق التالي:

* [ترخيص المصدر المفتوح](https://help.github.com/articles/open-source-licensing/#where-does-the-license-live-on-my-repository)
* [<span dir='ltr' markdown="1">README</span>](https://help.github.com/articles/create-a-repo/#commit-your-first-change)
* [إرشادات المساهمة](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
* [قواعد السلوك](../code-of-conduct/)

كمسؤول، ستساعدك هذه المكونات في توصيل التوقعات، وإدارة المساهمات، وحماية الحقوق القانونية للجميع (بما في ذلك حقوقك). تزيد بشكل كبير من فرص حصولك على تجربة إيجابية.

إذا كان مشروعك على <span dir='ltr' markdown="1">GitHub</span>، فإن وضع هذه الملفات في دليلك الجذري بأسماء الملفات الموصى بها سيساعد <span dir='ltr' markdown="1">GitHub</span> على التعرف عليها وإظهارها تلقائيًا لقرائك.

### اختيار ترخيص

يضمن ترخيص المصدر المفتوح أن يتمكن الآخرون من استخدام مشروعك ونسخه وتعديله والمساهمة فيه دون عواقب. كما يحميك من المواقف القانونية اللزجة. **يجب عليك تضمين ترخيص عند إطلاق مشروع مفتوح المصدر.**

العمل القانوني ليس ممتعًا. الخبر السار هو أنه يمكنك نسخ ولصق ترخيص موجود في مستودعك. سيستغرق الأمر دقيقة واحدة فقط لحماية عملك الشاق.

[<span dir='ltr' markdown="1">MIT</span>](https://choosealicense.com/licenses/mit/)، [<span dir='ltr' markdown="1">Apache 2.0</span>](https://choosealicense.com/licenses/apache-2.0/)، و[<span dir='ltr' markdown="1">GPLv3</span>](https://choosealicense.com/licenses/gpl-3.0/) هي تراخيص المصادر المفتوحة الأكثر شعبية، لكن [هناك خيارات أخرى](https://choosealicense.com) للاختيار من بينها.

عند إنشاء مشروع جديد على <span dir='ltr' markdown="1">GitHub</span>، يتم منحك خيار تحديد ترخيص. سيجعل تضمين ترخيص مفتوح المصدر مشروعك على <span dir='ltr' markdown="1">GitHub</span> مفتوح المصدر.

![اختر ترخيصًا](/assets/images/starting-a-project/repository-license-picker.png)

إذا كانت لديك أسئلة أو مخاوف أخرى حول الجوانب القانونية لإدارة مشروع مفتوح المصدر، [فنحن نغطيك](../legal/).

### كتابة ملف <span dir='ltr' markdown="1">README</span>

تفعل ملفات <span dir='ltr' markdown="1">README</span> أكثر من مجرد شرح كيفية استخدام مشروعك. كما أنها تشرح لماذا مشروعك مهم، وماذا يمكن لمستخدميك فعله به.

في <span dir='ltr' markdown="1">README</span> الخاص بك، حاول الإجابة على الأسئلة التالية:

* ماذا يفعل هذا المشروع؟
* لماذا هذا المشروع مفيد؟
* كيف أبدأ؟
* أين يمكنني الحصول على مزيد من المساعدة، إذا كنت بحاجة إليها؟

يمكنك استخدام <span dir='ltr' markdown="1">README</span> الخاص بك للإجابة على أسئلة أخرى، مثل كيفية التعامل مع المساهمات، وما هي أهداف المشروع، ومعلومات حول التراخيص والإسناد. إذا كنت لا تريد قبول المساهمات، أو أن مشروعك ليس جاهزًا بعد للإنتاج، اكتب هذه المعلومات.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/tracymakes?s=180" class="pquote-avatar" alt="avatar">
  توثيق أفضل يعني المزيد من المستخدمين، وطلبات دعم أقل، والمزيد من المساهمين. (...) تذكر أن قراءك ليسوا أنت. هناك أشخاص قد يأتون إلى مشروع لديهم تجارب مختلفة تمامًا.
  <p markdown="1" class="pquote-credit">
— @tracymakes, ["الكتابة بحيث تُقرأ كلماتك (فيديو)"](https://www.youtube.com/watch?v=8LiV759Bje0&list=PLmV2D6sIiX3U03qc-FPXgLFGFkccCEtfv&index=10)
  </p>
</aside>

في بعض الأحيان، يتجنب الناس كتابة <span dir='ltr' markdown="1">README</span> لأنهم يشعرون أن المشروع غير مكتمل، أو أنهم لا يريدون مساهمات. هذه كلها أسباب وجيهة جدًا لكتابة واحد.

للمزيد من الإلهام، جرب استخدام دليل <span dir='ltr' markdown="1">@dguo</span> ["اصنع <span dir='ltr' markdown="1">README</span>"](https://www.makeareadme.com/) أو قالب <span dir='ltr' markdown="1">@PurpleBooth</span> [لملف <span dir='ltr' markdown="1">README</span>](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) لكتابة <span dir='ltr' markdown="1">README</span> كامل.

عند تضمين ملف <span dir='ltr' markdown="1">README</span> في الدليل الجذري، سيعرضه <span dir='ltr' markdown="1">GitHub</span> تلقائيًا على الصفحة الرئيسية للمستودع.

### كتابة إرشادات المساهمة الخاصة بك

يخبر ملف <span dir='ltr' markdown="1">CONTRIBUTING</span> جمهورك بكيفية المشاركة في مشروعك. على سبيل المثال، قد تتضمن معلومات حول:

* كيفية تقديم تقرير عن خطأ (حاول استخدام [قوالب <span dir='ltr' markdown="1">issue</span> و<span dir='ltr' markdown="1">pull request</span>](https://github.com/blog/2111-issue-and-pull-request-templates))
* كيفية اقتراح ميزة جديدة
* كيفية إعداد بيئتك وتشغيل الاختبارات

بالإضافة إلى التفاصيل التقنية، يُعد ملف <span dir='ltr' markdown="1">CONTRIBUTING</span> فرصة لتوصيل توقعاتك للمساهمات، مثل:

* أنواع المساهمات التي تبحث عنها
* خارطة طريقك أو رؤيتك للمشروع
* كيف يجب (أو لا يجب) على المساهمين التواصل معك

استخدام نبرة دافئة وودية وتقديم اقتراحات محددة للمساهمات (مثل كتابة التوثيق، أو إنشاء موقع ويب) يمكن أن يقطع شوطًا طويلاً في جعل الوافدين الجدد يشعرون بالترحيب والحماس للمشاركة.

على سبيل المثال، يبدأ [<span dir='ltr' markdown="1">Active Admin</span>](https://github.com/activeadmin/activeadmin/) [دليل المساهمة الخاص به](https://github.com/activeadmin/activeadmin/blob/HEAD/CONTRIBUTING.md) بـ:

> أولاً، شكرًا لك على التفكير في المساهمة في <span dir='ltr' markdown="1">Active Admin</span>. إنه أشخاص مثلك الذين يجعلون <span dir='ltr' markdown="1">Active Admin</span> أداة رائعة.

في المراحل الأولى من مشروعك، يمكن أن يكون ملف <span dir='ltr' markdown="1">CONTRIBUTING</span> بسيطًا. يجب عليك دائمًا شرح كيفية الإبلاغ عن الأخطاء أو تقديم <span dir='ltr' markdown="1">issues</span>، وأي متطلبات تقنية (مثل الاختبارات) لتقديم مساهمة.

مع مرور الوقت، قد تضيف أسئلة أخرى يتم طرحها بشكل متكرر إلى ملف <span dir='ltr' markdown="1">CONTRIBUTING</span> الخاص بك. كتابة هذه المعلومات يعني أن عددًا أقل من الناس سيسألك نفس الأسئلة مرارًا وتكرارًا.

للمزيد من المساعدة في كتابة ملف <span dir='ltr' markdown="1">CONTRIBUTING</span> الخاص بك، راجع قالب دليل المساهمة لـ <span dir='ltr' markdown="1">@nayafia</span> [<span dir='ltr' markdown="1">contributing guide template</span>](https://github.com/nayafia/contributing-template/blob/HEAD/CONTRIBUTING-template.md) أو ["كيفية بناء <span dir='ltr' markdown="1">CONTRIBUTING.md</span>"](https://mozillascience.github.io/working-open-workshop/contributing/) لـ <span dir='ltr' markdown="1">@mozilla</span>.

اربط ملف <span dir='ltr' markdown="1">CONTRIBUTING</span> الخاص بك من <span dir='ltr' markdown="1">README</span>، حتى يراه المزيد من الناس. إذا [وضعت ملف <span dir='ltr' markdown="1">CONTRIBUTING</span> في مستودع مشروعك](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)، فسيربط <span dir='ltr' markdown="1">GitHub</span> تلقائيًا إلى ملفك عندما ينشئ مساهم <span dir='ltr' markdown="1">issue</span> أو يفتح <span dir='ltr' markdown="1">pull request</span>.

![إرشادات المساهمة](/assets/images/starting-a-project/Contributing-guidelines.jpg)

### إنشاء قواعد السلوك

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/mlynch?s=180" class="pquote-avatar" alt="avatar">
  لقد مررنا جميعًا بتجارب واجهنا فيها ما كان على الأرجح سوء معاملة إما كمسؤول يحاول شرح لماذا يجب أن يكون شيء ما بطريقة معينة، أو كمستخدم... يطرح سؤالاً بسيطًا. (...) قواعد السلوك تصبح وثيقة يسهل الرجوع إليها وربطها والتي تشير إلى أن فريقك يأخذ الخطاب البناء على محمل الجد.
  <p markdown="1" class="pquote-credit">
— @mlynch, ["جعل المصادر المفتوحة مكانًا أكثر سعادة"](https://medium.com/ionic-and-the-mobile-web/making-open-source-a-happier-place-3b90d254f5f)
  </p>
</aside>

أخيرًا، تساعد قواعد السلوك في وضع قواعد أساسية للسلوك لمشاركي مشروعك. هذا ذو قيمة خاصة إذا كنت تطلق مشروع مفتوح المصدر لمجتمع أو شركة. تمكّنك قواعد السلوك من تسهيل سلوك المجتمع الصحي والبنّاء، مما سيقلل من توترك كمسؤول.

لمزيد من المعلومات، راجع [دليل قواعد السلوك](../code-of-conduct/).

بالإضافة إلى توصيل _كيف_ تتوقع من المشاركين أن يتصرفوا، تميل قواعد السلوك أيضًا إلى وصف من تنطبق عليه هذه التوقعات، ومتى تنطبق، وماذا تفعل إذا حدث انتهاك.

مثل تراخيص المصادر المفتوحة، هناك أيضًا معايير ناشئة لقواعد السلوك، لذلك لا داعي لكتابة قواعدك الخاصة. [<span dir='ltr' markdown="1">Contributor Covenant</span>](https://contributor-covenant.org/) هي قواعد سلوك جاهزة للاستخدام يستخدمها [أكثر من 40,000 مشروع مفتوح المصدر](https://www.contributor-covenant.org/adopters)، بما في ذلك <span dir='ltr' markdown="1">Kubernetes</span> و<span dir='ltr' markdown="1">Rails</span> و<span dir='ltr' markdown="1">Swift</span>. بغض النظر عن النص الذي تستخدمه، يجب أن تكون مستعدًا لفرض قواعد السلوك الخاصة بك عند الضرورة.

الصق النص مباشرة في ملف <span dir='ltr' markdown="1">CODE_OF_CONDUCT</span> في مستودعك. احتفظ بالملف في الدليل الجذري لمشروعك حتى يسهل العثور عليه، واربطه من <span dir='ltr' markdown="1">README</span> الخاص بك.

## تسمية مشروعك ووضع علامة تجارية عليه

العلامة التجارية هي أكثر من مجرد شعار لامع أو اسم مشروع جذاب. إنها تتعلق بكيفية حديثك عن مشروعك، ومن تصل إليه برسالتك.

### اختيار الاسم الصحيح

اختر اسمًا يسهل تذكره، ومن الناحية المثالية، يعطي فكرة عما يفعله المشروع. على سبيل المثال:

* [<span dir='ltr' markdown="1">Sentry</span>](https://github.com/getsentry/sentry) يراقب التطبيقات للإبلاغ عن الأعطال
* [<span dir='ltr' markdown="1">Thin</span>](https://github.com/macournoyer/thin) هو خادم ويب <span dir='ltr' markdown="1">Ruby</span> سريع وبسيط

إذا كنت تبني على مشروع موجود، فإن استخدام اسمهم كبادئة يمكن أن يساعد في توضيح ما يفعله مشروعك (على سبيل المثال، [<span dir='ltr' markdown="1">node-fetch</span>](https://github.com/bitinn/node-fetch) يجلب <span dir='ltr' markdown="1">`window.fetch`</span> إلى <span dir='ltr' markdown="1">Node.js</span>).

ضع الوضوح قبل كل شيء. التورية ممتعة، لكن تذكر أن بعض النكات قد لا تُترجم إلى ثقافات أخرى أو أشخاص ذوي تجارب مختلفة عنك. قد يكون بعض مستخدميك المحتملين موظفين في الشركة: لا تريد أن تجعلهم غير مرتاحين عندما يضطرون إلى شرح مشروعك في العمل!

### تجنب تعارضات الأسماء

[تحقق من مشاريع المصادر المفتوحة ذات الأسماء المشابهة](https://namechecker.vercel.app/)، خاصة إذا كنت تشارك نفس اللغة أو النظام البيئي. إذا كان اسمك يتداخل مع مشروع شائع موجود، فقد تربك جمهورك.

إذا كنت تريد موقع ويب، أو مقبض <span dir='ltr' markdown="1">Twitter</span>، أو خصائص أخرى لتمثيل مشروعك، فتأكد من أنه يمكنك الحصول على الأسماء التي تريدها. من الناحية المثالية، [احجز هذه الأسماء الآن](https://instantdomainsearch.com/) لراحة البال، حتى لو لم تكن تنوي استخدامها بعد.

تأكد من أن اسم مشروعك لا ينتهك أي علامات تجارية. قد تطلب منك شركة ما إزالة مشروعك لاحقًا، أو حتى اتخاذ إجراء قانوني ضدك. الأمر لا يستحق المخاطرة.

يمكنك التحقق من [قاعدة بيانات العلامات التجارية العالمية لـ <span dir='ltr' markdown="1">WIPO</span>](http://www.wipo.int/branddb/en/) لتعارضات العلامات التجارية. إذا كنت في شركة، فهذا أحد الأشياء التي يمكن لـ [فريقك القانوني مساعدتك فيها](../legal/).

أخيرًا، قم بإجراء بحث سريع على <span dir='ltr' markdown="1">Google</span> عن اسم مشروعك. هل سيتمكن الناس من العثور على مشروعك بسهولة؟ هل يظهر شيء آخر في نتائج البحث لا تريد منهم رؤيته?

### كيفية كتابتك (وكتابة الكود) تؤثر على علامتك التجارية أيضًا!

طوال حياة مشروعك، ستقوم بالكثير من الكتابة: ملفات <span dir='ltr' markdown="1">README</span>، والبرامج التعليمية، ووثائق المجتمع، والرد على <span dir='ltr' markdown="1">issues</span>، وربما حتى النشرات الإخبارية وقوائم البريد.

سواء كانت وثائق رسمية أو بريدًا إلكترونيًا عاديًا، فإن أسلوب كتابتك هو جزء من علامة مشروعك التجارية. ضع في اعتبارك كيف قد تبدو لجمهورك وما إذا كانت هذه هي النبرة التي ترغب في نقلها.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/janl?s=180" class="pquote-avatar" alt="avatar">
  حاولت أن أشارك في كل موضوع في القائمة البريدية، وأظهر سلوكًا نموذجيًا، وأكون لطيفًا مع الناس، وأخذ مشاكلهم على محمل الجد وأحاول أن أكون مفيدًا بشكل عام. بعد فترة، التزم الناس ليس فقط لطرح الأسئلة، ولكن للمساعدة في الإجابة أيضًا، وكانت سعادتي كاملة، فقد قلدوا أسلوبي.
  <p markdown="1" class="pquote-credit">
— @janl على [<span dir='ltr' markdown="1">CouchDB</span>](https://github.com/apache/couchdb), ["المصادر المفتوحة المستدامة"](https://web.archive.org/web/20200723213552/https://writing.jan.io/2015/11/20/sustainable-open-source.html)
  </p>
</aside>

استخدام لغة دافئة وشاملة (مثل "هم"، حتى عند الإشارة إلى شخص واحد) يمكن أن يقطع شوطًا طويلاً في جعل مشروعك يبدو ترحيبيًا للمساهمين الجدد. التزم باللغة البسيطة، حيث قد لا يكون العديد من قرائك متحدثين أصليين للغة الإنجليزية.

بالإضافة إلى كيفية كتابة الكلمات، قد يصبح أسلوب البرمجة الخاص بك أيضًا جزءًا من علامة مشروعك التجارية. [<span dir='ltr' markdown="1">Angular</span>](https://angular.io/guide/styleguide) و[<span dir='ltr' markdown="1">jQuery</span>](https://contribute.jquery.org/style-guide/js/) مثالان من المشاريع ذات أساليب البرمجة والإرشادات الصارمة.

ليس من الضروري كتابة دليل أسلوب لمشروعك عندما تبدأ للتو، وقد تجد أنك تستمتع بدمج أساليب برمجة مختلفة في مشروعك على أي حال. لكن يجب أن تتوقع كيف يمكن لأسلوب كتابتك وبرمجتك أن يجذب أو يثني أنواعًا مختلفة من الناس. المراحل الأولى من مشروعك هي فرصتك لتحديد السابقة التي ترغب في رؤيتها.

## قائمة التحقق قبل الإطلاق

هل أنت مستعد لفتح مصدر مشروعك؟ إليك قائمة تحقق للمساعدة. ضع علامة على جميع المربعات؟ أنت مستعد للانطلاق! [انقر على "نشر"](https://help.github.com/articles/making-a-private-repository-public/) وربت على ظهرك.

**<span dir='ltr' markdown="1">Documentation</span> (التوثيق)**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox1" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox1" class="overflow-hidden d-block text-normal">
    يحتوي المشروع على ملف <span dir='ltr' markdown="1">LICENSE</span> مع ترخيص مفتوح المصدر
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox2" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox2" class="overflow-hidden d-block text-normal">
    يحتوي المشروع على توثيق أساسي (<span dir='ltr' markdown="1">README, CONTRIBUTING, CODE_OF_CONDUCT</span>)
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox3" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox3" class="overflow-hidden d-block text-normal">
    الاسم سهل التذكر، يعطي فكرة عما يفعله المشروع، ولا يتعارض مع مشروع موجود أو ينتهك العلامات التجارية
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox4" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox4" class="overflow-hidden d-block text-normal">
    قائمة <span dir='ltr' markdown="1">issues</span> محدثة، مع <span dir='ltr' markdown="1">issues</span> منظمة ومصنفة بوضوح
  </label>
</div>

**<span dir='ltr' markdown="1">Code</span> (الكود)**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox5" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox5" class="overflow-hidden d-block text-normal">
    يستخدم المشروع اتفاقيات كود متسقة وأسماء واضحة للدوال/الأساليب/المتغيرات
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox6" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox6" class="overflow-hidden d-block text-normal">
    الكود مُعلّق بوضوح، يوثق النوايا والحالات الحدية
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox7" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox7" class="overflow-hidden d-block text-normal">
    لا توجد مواد حساسة في سجل المراجعات أو <span dir='ltr' markdown="1">issues</span> أو <span dir='ltr' markdown="1">pull requests</span> (على سبيل المثال، كلمات المرور أو معلومات أخرى غير عامة)
  </label>
</div>

**<span dir='ltr' markdown="1">People</span> (الأشخاص)**

إذا كنت فردًا:

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox8" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox8" class="overflow-hidden d-block text-normal">
  لقد تحدثت إلى القسم القانوني و/أو تفهم الملكية الفكرية وسياسات المصادر المفتوحة لشركتك (إذا كنت موظفًا في مكان ما)
  </label>
</div>

إذا كنت شركة أو منظمة:

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox9" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox9" class="overflow-hidden d-block text-normal">
    لقد تحدثت إلى قسمك القانوني
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox10" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox10" class="overflow-hidden d-block text-normal">
    لديك خطة تسويقية للإعلان والترويج للمشروع
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox11" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox11" class="overflow-hidden d-block text-normal">
    هناك شخص ملتزم بإدارة تفاعلات المجتمع (الرد على <span dir='ltr' markdown="1">issues</span>، مراجعة ودمج <span dir='ltr' markdown="1">pull requests</span>)
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox12" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox12" class="overflow-hidden d-block text-normal">
    لدى شخصين على الأقل صلاحيات إدارية للمشروع
  </label>
</div>

## لقد فعلتها!

تهانينا على فتح مصدر مشروعك الأول. بغض النظر عن النتيجة، فإن العمل بشكل علني هو هدية للمجتمع. مع كل <span dir='ltr' markdown="1">commit</span> وتعليق و<span dir='ltr' markdown="1">pull request</span>، أنت تخلق فرصًا لنفسك وللآخرين للتعلم والنمو.

</div>
