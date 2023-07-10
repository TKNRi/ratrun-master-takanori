<template>
  <div class="container">
    <div class="content">
      <h1>新規会員登録</h1>
      <div class="form-group">
        <label class="form-text" for="name">メールアドレス</label>
        <input
          type="text"
          class="form-control"
          placeholder="○○○○○○○○@gmail.com"
        />
      </div>
      <div class="form-group">
        <label class="form-text">パスワード</label>
        <input type="text" class="form-control" placeholder="ABCDEFG" />
      </div>
      <div class="registar-button">
        <button class="registar-btn">同意して新規登録する（無料）</button>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

<style lang="scss">
.container {
  max-width: 800px;
  margin: 0 auto;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}
.content {
  background-color: #fff;
  padding: 20px;
}
.form-text {
  display: block;
  margin-top: 8px;
}
.form-control {
  margin: 12px 0;
}
.registar-button {
  text-align: center;
}
.registar-btn {
  color: #fff;
  background-color: pink;
  border: none;
  border-radius: 3px;
  padding: 10px 30px;
  cursor: pointer;
}
</style>