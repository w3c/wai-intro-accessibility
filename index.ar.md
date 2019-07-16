---
# Translation instructions are after the "#" character in this first section. (They are comments that do not show up in the web page.)
title:  مقدمة لولوجية الويب  # Do not translate "title:". Do translate the text after "title:".
lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-06-05   # Put the date of this translation 2019-07-16 (with month in the middle)
# translators: #Add one -name: line for every translator
# - name: "نجيب التونسي"
# contributors: #Add one -name: line for every contributor
# - name: "Contributor Name Here"
permalink: /fundamentals/accessibility-intro/   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/ar
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

عندما يتم تصميم مواقع الويب وأدوات الويب وترميزها بشكل صحيح ، يمكن للأشخاص ذوي الإعاقة استخدامها. ومع ذلك ، يتم حاليا تطوير العديد من المواقع والأدوات مع حواجز الولوج يجعلها صعبة أو مستحيلة الاستخدام على بعض الأشخاص. 
 
إن ولوجية الويب  تفيد الأفراد والشركات والمجتمع. معايير الويب الدولية تحدد ما هو مطلوب للولوجية

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
{% include video-link.html title="مقدمة فيديو إلى ولوجية الويب ومعايير W3C <em>(4 دقائق)</em>" href="https://www.w3.org/WAI/videos/standards-and-benefits.html" src="/content-images/wai-intro-accessibility/video-still-accessibility-intro-16-9.jpg" %}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## سياق الولوجية {#context}



وبالتالي،  تأثير الإعاقة تغير بشكل جذري على الويب لأن الويب يزيل الحواجز التي تعترض التواصل والتفاعل التي يواجهها كثير من الأشخاص في العالم المادي. وهكذا، عندما تكون مواقع الويب والتطبيقات والتقنيات والأدوات سيئة التصميم، فيمكنها إنشاء حواجز تمنع المستخدمين من استخدام الويب.

وبالتالي،  تأثير الإعاقة تغير بشكل جذري على الويب لأن الويب يزيل الحواجز التي تعترض التواصل والتفاعل التي يواجهها كثير من الأشخاص في العالم المادي. وهكذا، عندما تكون مواقع الويب والتطبيقات والتقنيات والأدوات سيئة التصميم، فيمكنها إنشاء حواجز تقصي المستخدمين من استخدام الويب.

**تعد الولوجية ضرورية للمطورين والمؤسسات الذين يرغبون في إنشاء مواقع ويب وأدوات ويب عالية الجودة، بدون إقصاء المستخدمين من  منتجاتهم وخدماتهم.**

## ما هي ولوجية الويب {#what}

الولوجية تعني أنه تم تصميم وتطوير مواقع الويب والأدوات والتقنيات بحيث يمكن للأشخاص ذوي الإعاقة استخدامها. بشكل معين، يمكن للأشخاص:

-   إدراك الويب وفهمه والتصفح والتفاعل معه
-   المساهمة في الويب

تشمل الولوجية جميع الإعاقات التي تؤثر على الولوج إلى الويب، بما في ذلك:

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
-   أشخاص  يستخدمون اتصال بإنترنت بطيئ أو لديهم نطاق ترددي محدود أو مكلف


للحصول على فيديو مدته 7 دقائق مع أمثلة عن مدى أهمية الولوجية للأشخاص ذوي الإعاقة وفوائدها للجميع في ظروف متنوعة، أنظر:<br>
{% include video-link.html title="فيديو أفاق ولوجيات الويب (يوتوب)</em>" href="https://www.youtube.com/watch?v=3f31oufqFSM" src="/content-images/wai-intro-accessibility/video-still-accessibility-perspectives-16-9.jpg" %}

{::nomarkdown}
{% include box.html type="start" h="3" title="مزيد من المعلومات حول ما هي الولوجية " class="simple aside" %}
{:/}

-   إذا كنت ترغب في معرفة المزيد عن تأثير الإعاقات المختلفة على استخدام الويب  وقراءة سيناريوهات الأشخاص ذوي الإعاقة الذين يستخدمون الويب، راجع  [[كيف يستخدم الأشخاص ذوو الإعاقة الويب]](/people-use-web/).
-  إذا كنت ترغب في الحصول على المزيد من الأمثلة عن المزايا للآخرين، مع روابط إلى WCAG التي تدعم الأمثلة، راجع [[تجارب الويب المشتركة: الحواجز العامة  لمستخدمي الأجهزة المحمولة والأشخاص ذوي الإعاقة]](/standards-guidelines/shared-experiences/)  والأرشيف [ولوجية الويب تفيد الأشخاص ذوي الإعاقات وبدونها](https://www.w3.org/WAI/business-case/archive/soc#groups).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Accessibility is Important for Individuals, Businesses, Society {#important}

The Web is an increasingly important resource in many aspects of life: education, employment, government, commerce, health care, recreation, and more. It is essential that the Web be accessible in order to provide equal access and equal opportunity to people with diverse abilities. Access to information and communications technologies, including the Web, is defined as a basic human right in the United Nations Convention on the Rights of Persons with Disabilities (UN [CRPD](https://www.un.org/development/desa/disabilities/convention-on-the-rights-of-persons-with-disabilities.html)).

The Web offers the possibility of unprecedented access to information and interaction for many people with disabilities. That is, the accessibility barriers to print, audio, and visual media can be much more easily overcome through web technologies.

Accessibility supports social inclusion for people with disabilities as well as others, such as:

-   older people
-   people in rural areas
-   people in developing countries

**There is also a strong business case for accessibility.** As shown in the previous section, accessible design improves overall user experience and satisfaction, especially in a variety of situations, across different devices, and for older users. Accessibility can enhance your brand, drive innovation, and extend your market reach.

Web accessibility is **required by law** in many situations.

{::nomarkdown}
{% include box.html type="start" h="3" title="More Info on Accessibility is Important" class="simple aside" %}
{:/}

-   General information on business benefits is in [[The Business Case for Digital Accessibility]](/business-case/).
-   Guidance on figuring out legal requirements is in the archived [Legal and Policy Factors](https://www.w3.org/WAI/business-case/archive/pol).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Making the Web Accessible {#making}

Web accessibility depends on several components working together, including web technologies, web browsers and other \"user agents\", authoring tools, and websites.

The W3C Web Accessibility Initiative ([WAI](/get-involved/)) develops technical specifications, guidelines, techniques, and supporting resources that describe accessibility solutions. These are considered international standards for web accessibility; for example, <abbr title="Web Content Accessibility Guidelines (WCAG)">WCAG</abbr> 2.0 is also an <abbr title="International Organization for Standardization">ISO</abbr> standard: ISO/<abbr title="International Electrotechnical Commission">IEC</abbr> 40500.

{::nomarkdown}
{% include box.html type="start" h="3" title="More Info on Making the Web Accessible" class="simple aside" %}
{:/}

-   More about these aspects of accessibility working together is in [[Essential Components of Web Accessibility]](/fundamentals/components/).
-   Web Content Accessibility Guidelines (WCAG), Authoring Tool Accessibility Guidelines (ATAG), ARIA for Accessible Rich Internet Applications, and other important resources are introduced in [[W3C Accessibility Standards Overview]](/standards-guidelines/).
-   To learn more about how W3C WAI develops material through multi-stakeholder, international participation and how you can contribute, see [[About WAI]](/about/) and [[Participating in WAI]](/get-involved/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Making Your Website Accessible {#website}

Many aspects of accessibility are fairly easy to understand and implement. Some accessibility solutions are more complex and take more knowledge to implement.

It is most efficient and effective to incorporate accessibility from the very beginning of projects, so you don't need go back and to re-do work.

{::nomarkdown}
{% include box.html type="start" h="3" title="More Info on Making Your Website Accessible" class="simple aside" %}
{:/}

-   For an introduction to accessibility requirements and international standards, see [[Accessibility Principles]](/fundamentals/accessibility-principles/).
-   To understand some common accessibility barriers from the perspective of testing, see [[Easy Checks - A First Review]](/test-evaluate/preliminary/).
-   For some basic considerations on designing, writing, and developing for accessibility, see [[Tips for Getting Started]](/tips/).
-   When you're ready to know more about developing and designing, you'll probably use resources such as:
    -   [How to Meet WCAG (Quick Reference)](http://www.w3.org/WAI/WCAG21/quickref/)
    -   [Web Accessibility Tutorials](https://www.w3.org/WAI/tutorials/)
-   For project management and organizational considerations, see [[Planning and Managing Web Accessibility]](/planning-and-managing/).<br>
    If you need to make quick fixes now, see [[Approaches for Interim Repairs]](/planning/interim-repairs/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}
	
## Evaluating Accessibility {#evaluate}

When developing or redesigning a website, evaluate accessibility early and throughout the development process to identify accessibility problems early, when it is easier to address them. Simple steps, such as changing settings in a browser, can help you evaluate some aspects of accessibility. Comprehensive evaluation to determine if a website meets all accessibility guidelines takes more effort.

There are evaluation tools that help with evaluation. However, no tool alone can determine if a site meets accessibility guidelines. Knowledgeable human evaluation is required to determine if a site is accessible.


{::nomarkdown}
{% include box.html type="start" h="3" title="More Info on Evaluating Accessibility" class="simple aside" %}
{:/}

-   Resources to help with accessibility evaluation are described in [[Evaluating Websites for Accessibility]](/test-evaluate/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% include excol.html type="start" id="examples" %}

## Examples

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
