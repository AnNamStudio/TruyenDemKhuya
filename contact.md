---
layout: default
title: Contact Long Haul
---

<div id="contact">
  <h1 class="pageTitle">Liên hệ</h1>
  <div class="contactContent">
    <p class="intro" style="text-align: justify;">Chúng tôi mong muốn được lắng nghe những ý kiến đóng góp của bạn, hoặc nếu bạn có bất kỳ câu hỏi nào, vui lòng điền theo mẫu. Chúng tôi sẽ liên lạc với bạn ngay khi có thể!</p>
  </div>
  <form action="http://formspree.io/{{site.email}}" method="POST">
    <label for="name">Họ tên</label>
    <input type="text" id="name" name="dem-name" class="full-width"><br>
    <label for="email">Email</label>
    <input type="email" id="email" name="dem-email" class="full-width"><br>
    <label for="message">Nội dung</label>
    <textarea name="dem-message" id="message" cols="30" rows="10" class="full-width"></textarea><br>
    <input type="submit" value="Gửi" class="button">
  </form>
</div>
