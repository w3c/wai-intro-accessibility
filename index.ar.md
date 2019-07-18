---
# Translation instructions are after the "#" character in this first section. (They are comments that do not show up in the web page.)
title:  مقدمة لولوجية الويب  # Do not translate "title:". Do translate the text after "title:".
lang: ar   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-07-16   # Put the date of this translation 2019-07-16 (with month in the middle)
translators: #Add one -name: line for every translator
- name: "نجيب التونسي"
# contributors: #Add one -name: line for every contributor
# - name: "Contributor Name Here"
permalink: /fundamentals/accessibility-intro/ar   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/ar
ref: /fundamentals/accessibility-intro/   # Do not change this
layout: default
github:
  repository: w3c/wai-intro-accessibility
  branch: gh-pages
  path: index.ar.md   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". Do not change these dates.
  <p><strong>تاريخ:</strong>تحديث 5 يونيو 2019.  أول نشر في فبراير 2005.</p>
  <p><strong>النشر:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>تم التطوير من قبل مجموعة عمل التعليم والتوعية(<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>
# Read Translations Notes at https://github.com/w3c/wai-intro-accessibility/blob/gh-pages/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="ملخص" class="full" %}
{:/}

عندما يتم تصميم مواقع الويب وأدوات الويب وترميزها بشكل صحيح، يمكن للأشخاص ذوي الإعاقة استخدامها. ومع ذلك، يتم حاليا تطوير العديد من المواقع والأدوات مع حواجز الولوج يجعلها صعبة أو مستحيلة الاستخدام على بعض الأشخاص. 
 
إن ولوجية الويب  تفيد الأفراد والشركات والمجتمع. معايير الويب الدولية تحدد ما هو مطلوب للولوجية.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="محتويات الصفحة" class="full" %}
{:/}

<ul>
<li><a href="#context">سياق الولوجية</a></li>
<li><a href="#what">ما هي ولوجية الويب</a></li>
<li><a href="#important">الولوجية مهمة للأفراد والشركات والمجتمع</a></li>
<li><a href="#making">جعل الويب ولوجي</a></li>
<li><a href="#evaluate">تقييم الولوجية</a></li>
<li><a href="#examples">أمثلة</a></li>
<li><a href="#more-info">للمزيد من المعلومات</a></li>
</ul>

<span class="box-h box-h-simple box-h-full">الموارد ذات الصلة</span><br>
{% include video-link.html title="مقدمة فيديو إلى ولوجية الويب ومعايير W3C (4 دقائق)" href="https://www.w3.org/WAI/videos/standards-and-benefits.html" src="/content-images/wai-intro-accessibility/video-still-accessibility-intro-16-9.jpg" %}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## سياق الولوجية {#context}

<blockquote class="pull">
  <p>قوة الويب في عموميته.<br />
     ولوج الجميع بغض النظر عن الإعاقة يعد جانبًا أساسيًا.</p>
  <footer><cite>تيم بيرنرز لي، مدير W3C ومخترع شبكة الويب العالمية</cite></footer>
</blockquote>

تم تصميم الويب أساسَا للعمل مع جميع الأشخاص، بغض النظر عن أجهزتهم أو برامجهم أو لغتهم أو موقعهم أو قدرتهم. عندما يحقق الويب هذا الهدف  يكون في متناول أشخاص لديهم مجال  متنوع في السمع والحركة والبصر والقدرة المعرفية.

وبالتالي،  تأثير الإعاقة تغير بشكل جذري على الويب لأن الويب يزيل الحواجز التي تعترض التواصل والتفاعل التي يواجهها كثير من الأشخاص في العالم المادي. وهكذا، عندما تكون مواقع الويب والتطبيقات والتقنيات والأدوات سيئة التصميم، فيمكنها إنشاء حواجز تقصي المستخدمين من استخدام الويب.

**تعد الولوجية ضرورية للمطورين والمؤسسات الذين يرغبون في إنشاء مواقع ويب وأدوات ويب عالية الجودة بدون إقصاء المستخدمين من  منتجاتهم وخدماتهم.**

## ما هي ولوجية الويب {#what}

الولوجية تعني أنه تم تصميم وتطوير مواقع الويب والأدوات والتقنيات بحيث يمكن للأشخاص ذوي الإعاقة استخدامها. وبشكل معين يمكن للأشخاص:

-   إدراك الويب وفهمه والتصفح والتفاعل معه
-   المساهمة في الويب

تشمل الولوجية جميع الإعاقات التي تؤثر على الولوج إلى الويب بما في ذلك:

-   السمع
-   قدرة المعرفة
-   الأعصاب
-   القدرة البدنية
-   الخطاب
-   البصر

ولوجية الويب تفيد أيضًا الأشخاص من غير ذوي الإعاقة، على سبيل المثال:

-   أشخاص يستخدمون الهواتف المحمولة والساعات الذكية وأجهزة التلفزيون الذكية والأجهزة الأخرى ذات الشاشات الصغيرة وطرق الإدخال المختلفة إلخ.
-   كبار السن مع قدراتهم المتغيرة بسبب الشيخوخة
-   أشخاص يعانون من "إعاقات مؤقتة" مثل كسر في الذراع أو نظارات مفقودة 
-   أشخاص يعانون من "قيود ظرفية" كما هو الحال في ضوء الشمس الساطع أو في بيئة حيث لا يمكن الاستماع إلى الصوت
-   أشخاص  يستخدمون اتصال بإنترنت بطيئ أو لديهم نطاق ترددي محدود أو مكلِّف


للحصول على فيديو مدته 7 دقائق مع أمثلة عن مدى أهمية الولوجية للأشخاص ذوي الإعاقة وفوائدها للجميع في ظروف متنوعة، أنظر:<br>
{% include video-link.html title="فيديو أفاق ولوجيات الويب (يوتوب)" href="https://www.youtube.com/watch?v=3f31oufqFSM" src="/content-images/wai-intro-accessibility/video-still-accessibility-perspectives-16-9.jpg" %}

{::nomarkdown}
{% include box.html type="start" h="3" title="مزيد من المعلومات حول ما هي الولوجية " class="simple aside" %}
{:/}

-   إذا كنت ترغب في معرفة المزيد عن تأثير الإعاقات المختلفة على استخدام الويب  وقراءة سيناريوهات الأشخاص ذوي الإعاقة الذين يستخدمون الويب، راجع  [[كيف يستخدم الأشخاص ذوو الإعاقة الويب]](/people-use-web/).
-  إذا كنت ترغب في الحصول على المزيد من الأمثلة عن المزايا للآخرين، مع روابط إلى WCAG (إرشادات الولوج إلى محتويات الويب) التي تدعم الأمثلة، راجع [[تجارب الويب المشتركة: الحواجز العامة  لمستخدمي الأجهزة المحمولة والأشخاص ذوي الإعاقة]](/standards-guidelines/shared-experiences/)  والأرشيف [ولوجية الويب تفيد الأشخاص ذوي الإعاقات وبدونها](https://www.w3.org/WAI/business-case/archive/soc#groups).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

##  الولوجية مهمة للأفراد والشركات والمجتمع {#important}

يعد الويب مورداً متزايد الأهمية في العديد من جوانب الحياة: التعليم والتوظيف والإدارة والتجارة والرعاية الصحية والترفيه وأكثر من ذلك. من الضروري أن يكون الويب متاحًا لتوفير تكافؤ الولوج وتكافؤ الفرص للأشخاص ذوي القدرات المتنوعة. يُعرّف الولوج إلى تكنولوجيات المعلومات والاتصالات، بما في ذلك الويب، بأنه حق أساسي من حقوق الإنسان في اتفاقية الأمم المتحدة لحقوق الأشخاص ذوي الإعاقة (UN CRPD).

يوفر الويب إمكانية  غير مسبوقة للولوج إلى المعلومات والتفاعل للعديد من الأشخاص ذوي الإعاقة. بمعنى أنه بواسطة تقنيات الويب يمكن التغلب بسهولة أكبر على حواجز الولوج إلى الوسائط المطبوعة والصوتية والمرئية.

الولوجة تدعم الإدماج الاجتماعي للأشخاص ذوي الإعاقة وغيرهم مثل:

-   العجزة
-   الناس في المناطق القروية
-   الناس في البلدان النامية

**هناك أيضا تحليل تجاري قوي للولوجية.**  كما هو موضح في الفقرة السابقة، يعمل التصميم الولوجي على تحسين تجربة المستخدمين  بشكل عام ورضاهم، لا سيما في ظروف متنوعة عبر أجهزة مختلفة وكذلك للمستخدمين الأقدم. يمكن للولوجية أن تعمل على تعزيز شعارك التجاري وتحفيز الابتكار وتوسيع السوق.

ولوجية الويب **مطلوبة بموجب القانون** في العديد من الحالات.

{::nomarkdown}
{% include box.html type="start" h="3" title="مزيد من المعلومات حول أهمية الولوجية" class="simple aside" %}
{:/}

-   معلومات عامة عن المزايا في الأعمال في [[التحليل التجاري للولوجية الرقمية]](/business-case/).
-   إرشادات لمعرفة المتطلبات القانونية في [العوامل القانونية والسياسة](https://www.w3.org/WAI/business-case/archive/pol) المؤرشفة.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## جعل الويب ولوجي {#making}

تعتمد ولوجية الويب على العديد من المكونات التي تعمل معًا، بما في ذلك تقنيات الويب ومتصفحات الويب و \"وكلاء المستخدم\"  وأدوات التأليف ومواقع الويب.

تقوم مبادرة ولوجية الويب (WAI)  لدى W3C بتطوير المواصفات التقنية والإرشادات والتقنيات والموارد الداعمة التي تصف حلول الولوجية. وتعتبر هذه معايير دولية للولوجية الويب؛ على سبيل المثال، <abbr title="إرشادات الولوج إلى محتويات الويب (WCAG)">WCAG</abbr> 2.0 هي أيضًا معيار <abbr title="منظمة المعايير الدولية">ISO</abbr>:‏ ISO / <abbr title="اللجنة الكهرتقنية الدولية">IEC</abbr> 40500.

{::nomarkdown}
{% include box.html type="start" h="3" title="مزيد من المعلومات عن جعل الويب ولوجي" class="simple aside" %}
{:/}

-   لمعرفة المزيد عن جوانب  ولوجية الويب هذه، راجع [[المكونات الأساسية لولوجية الويب]](/fundamentals/components/).
-  يتم تقديم إرشادات إمكانية الولوج إلى محتوى الويب (WCAG)  وإرشادات الولوج إلى أدوات التأليف (ATAG)  و ARIA لتطبيقات الويب الغنية القابلة للولوج ، وغيرها من الموارد المهمة في [[نظرة عامة على معايير الولوجية  عند W3C]](/standards-guidelines/).
-   لمعرفة المزيد حول كيفية قيام W3C WAI بتطوير المواد من خلال المشاركة الدولية متعددة الأذطراف وكيف يمكنك المساهمة، راجع  [[حول W3C WAI](/about/) و [[والمشاركة في WAI]](/get-involved/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### جعل موقعك ولوجي {#website}

العديد من جوانب الولوجية سهلة الفهم والتنفيذ. بعض حلول الولوجية أكثر تعقيدًا وتتطلب المزيد من المعرفة لتنفيذها.

يعد دمج الولوجية مبكرًا في  المشاريع أكثر فعالية. لذلك ليس عليك العودة والقيام بالعمل مرة أخرى.

{::nomarkdown}
{% include box.html type="start" h="3" title="لمعرفة المزيد عن جعل موقعك ولوجي" class="simple aside" %}
{:/}

-   للحصول على مقدمة لمتطلبات الولوجية والمعايير الدولية، راجع [[مبادئ الولوجية]](/fundamentals/accessibility-principles/).
-    لفهم بعض تحديات الولوجية الشائعة بمنظور الاختبار، راجع  [[الاختبارات البسيطة: نظرة أولى على ولوجية الويب]](/test-evaluate/preliminary/).
-   للإطلاع على بعض الاعتبارات الأساسية المتعلقة بالتصميم والكتابة والتطوير لأجل الولوجية، انظر [[ تلميحات للبدء]](/tips/).
-  عندما تكون مستعدًا لمعرفة المزيد عن التطوير والتصميم، فربما تستخدم موارد مثل:
    -   [كيفية التوافق مع WCAG (مرجع سريع)](http://www.w3.org/WAI/WCAG21/quickref/)
    -   [البرامج التعليمية في ولوجية الويب](https://www.w3.org/WAI/tutorials/)
-   للحصول على الاعتبارات  التنظيمية وإدارة المشاريع، راجع  [[تخطيط ولوجية الويب وإدارتها]](/planning-and-managing/).<br>
    إذا كنت بحاجة إلى إجراء إصلاحات سريعة الآن، فراجع  [[طرق الإصلاحات المؤقتة]](/planning/interim-repairs/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}
	
## تقييم الولوجية {#evaluate}

عند تطوير موقع ويب أو إعادة تصميمه، قم بتقييم الولوجية مبكراً وأثناء عملية التطوير لتحديد مشكلات الولوجية مبكرًا ، عندما يكون من السهل معالجتها. الخطوات البسيطة مثل تغيير الإعدادات في المستعرض يمكن أن تساعدك على تقييم بعض الجوانب. التقييم الشامل لتحديد ما إذا كان موقع الويب يستوفي جميع إرشادات الولوجية يتطلب مزيدًا من الجهد.

هناك أدوات التقييم التي تساعد في التقييم. ومع ذلك لا يمكن لأي أداة بمفردها تحديد ما إذا كان الموقع متوافقًا مع إرشادات الولوجية. يلزم إجراء تقييم إنساني جيد الاطلاع لتحديد ما إذا كان الموقع ولوجي أم لا.


{::nomarkdown}
{% include box.html type="start" h="3" title="مزيد من المعلومات عن تقييم الولوجية" class="simple aside" %}
{:/}

-    يتم وصف الموارد للمساعدة في تقييم الولوجية في [[نظرة عامة على تقييم ولوجية الويب]](/test-evaluate/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% include excol.html type="start" id="أمثلة" %}

## أمثلة

{% include excol.html type="middle" %}

### Alternative Text for Images

![image of logo; HTML markup img alt='Web Accessibility Initiative logo'](https://www.w3.org/WAI/intro/alt-logo.png){:.right}

Images should include *[equivalent alternative text](http://www.w3.org/TR/UNDERSTANDING-WCAG20/text-equiv.html)* (alt text) in the markup/code.

If alt text isn't provided for images, the image information is inaccessible, for example, to people who cannot see and use a screen reader that reads aloud the information on a page, including the alt text for the visual image.

When equivalent alt text is provided, the information is available to people who are blind, as well as to people who turn off images (for example, in areas with expensive or low bandwidth). It's also available to technologies that cannot see images, such as search engines.

### Keyboard Input

![mouse crossed out](https://www.w3.org/WAI/intro/no-mouse.png){:.left width="67" height="45"}

Some people cannot use a mouse, including many older users with limited fine motor control. An accessible website does not rely on the mouse; it makes [all functionality available from a keyboard](http://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation.html). Then people with disabilities can use [assistive technologies](/planning/involving-users/#at) that mimic the keyboard, such as speech input.

### Transcripts for Audio

[![example transcript](https://www.w3.org/WAI/intro/transcript.png){:.right width="251" height="254"}](http://www.w3.org/WAI/highlights/200606wcag2interview.html)

Just as images aren't available to people who can't see, audio files aren't available to people who can't hear. Providing a text transcript makes the audio information accessible to people who are deaf or hard of hearing, as well as to search engines and other technologies that can't hear.

It's easy and relatively inexpensive for websites to provide transcripts. There are also [transcription services](http://www.uiaccess.com/transcripts/transcript_services.html) that create text transcripts in HTML format.

{::nomarkdown}
{% include box.html type="start" h="3" title="More Examples" class="simple aside" %}
{:/} 

-   [[Tips for Getting Started]](/tips/)
-   [[Easy Checks - A First Review]](/test-evaluate/preliminary/)
-   {% include video-link.html class="small inline" title="Web Accessibility Perspectives &mdash; videos and descriptions" href="/perspective-videos/" src="/content-images/wai-intro-accessibility/video-still-accessibility-perspectives-16-9.jpg" %}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% include excol.html type="end" %}

## For More Information {#more-info}

W3C WAI provides a wide range of resources on different aspects of web accessibility [standards](/standards-guidelines/), [education](https://www.w3.org/WAI/train), [testing/evaluation](/test-evaluate/), [project management, and policy](https://www.w3.org/WAI/managing). We encourage you to explore this website, or look through the [WAI Resources](http://www.w3.org/WAI/Resources/) list.