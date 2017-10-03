---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: soren-astrup-jorgensen-325552.jpg
widget1:
  title: ""
  url: '/cewla/'
  text: 'مؤسسة قضايا المرأة المصرية هي مؤسسة أهلية أنشأت عام 1995 بهدف تقديم
الدعم والمساندة القانونية للمرأة المصرية، مرجعيته في ذلك الدستور
والقوانين المصرية والاتفاقيات الدولية. و تسعى المؤسسة أيضا ألي تزويد
المرأة بالمهارات والقدرات التي تمكنها من ممارسة حياتها والتغلب علي
مشكلاتها. وقد تم إشهار المؤسسة تحت رقم 1829 لسنة 2003 وفقا لقانون
الجمعيات الجديد رقم 84 لسنة 2002 تحت العنوان السابق ذكره.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="/images/start-video-Azza-Soliman.png" width="302" height="182" alt=""/></a>'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/aUtBxeajiXI" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
