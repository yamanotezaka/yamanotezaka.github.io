---
layout: default
---

## お問い合わせフォーム

以下の項目を入力して送信頂くと、山の手坂自治会へメールが送られます。

<!-- class, action, methodを変更しないでください -->
<form class="formrun" action="https://form.run/api/v1/r/bitqzpp79otpe1at9sn7yx5h" method="post">
  <!-- ↓自由に要素を追加・編集することができます -->
    <label class="cp_iptxt">
    <input name="お名前" type="text" placeholder="お名前：">
    <i class="fa fa-user fa-lg fa-fw" aria-hidden="true"></i>
  </label>

  <label class="cp_iptxt">
    <input name="メールアドレス" type="text" placeholder="Email：" data-formrun-type="email" data-formrun-required>
    <i class="fa fa-mail fa-lg fa-fw" aria-hidden="true"></i>
  </label>

  <label class="cp_txtarea">
    <span>内容：</span>
    <textarea name="お問い合わせ" data-formrun-required></textarea>
  </label>

  <!-- ボット投稿をブロックするためのタグ -->
  <div class="_formrun_gotcha">
    <style media="screen">._formrun_gotcha {position:absolute!important;height:1px;width:1px;overflow:hidden;}</style>
    <label for="_formrun_gotcha">If you are a human, ignore this field</label>
    <input type="text" name="_formrun_gotcha" id="_formrun_gotcha" tabindex="-1">
  </div>

  <div class="errors">
    <div data-formrun-show-if-error="メールアドレス">メールアドレスを正しく入力してください</div>
    <div data-formrun-show-if-error="お問い合わせ">お問い合わせ入力してください</div>
  </div>

  <div class="btn_wrap">
    <a href="/" class="cancel_btn">戻る</a>
    <button type="submit" class="submit_btn btn" data-formrun-submitting-text="送信中...">送信</button>
  </div>
</form>