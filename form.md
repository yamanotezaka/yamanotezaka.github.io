---
layout: default
---

## お問い合わせフォーム

以下の項目を入力して送信頂くと、山の手坂自治会へメールが送られます。

<form
  action="https://formspree.io/myrjenex"
  method="POST"
>
  <label class="cp_iptxt">
    <input type="text" name="name" placeholder="お名前：">
    <i class="fa fa-user fa-lg fa-fw" aria-hidden="true"></i>
  </label>
  <label class="cp_iptxt">
    <input type="text" name="_replyto" placeholder="Email：">
    <i class="fa fa-mail fa-lg fa-fw" aria-hidden="true"></i>
  </label>
  <label class="cp_txtarea">
    <span>内容：</span>
    <textarea name="message"></textarea>
  </label>

  <!-- your other form fields go here -->

  <div class="btn_wrap">
    <a href="/" class="cancel_btn">戻る</a>
    <button class="submit_btn btn" type="submit">送信</button>
  </div>
</form>
