<template>
  <div class = "cust">
        <ul>
          <li>
            <label for="dop">**작성일자</label>
            <input type="text" id="dop" autofocus
            placeholder="몇월 몇일" required>{{ CustomerData[0].Create_date }}
          </li>
          <li>
            <label for="name">*고객명</label>
            <input type="text" id="name" autofocus
            placeholder="이름" required>
          </li>
          <li>
            <label for="resident">*실명번호</label>
            <input type="text" id="resident" autofocus
            placeholder="번호" required>
          </li>
          <li>
            <label for="email">*E-mail</label>
            <input type="text" id="email" autofocus
            placeholder="이메일을 입력하세요" required>
          </li>
          <li>
            <label for="number">전화번호</label>
            <input type="text" id="number" autofocus
            placeholder="연락처" required>
          </li>
          <li>
            <label for="phone">*핸드폰번호</label>
            <input type="text" id="phone" required>
          </li>
          <li>
            <label for="job">*직업</label>
            <input type="text" id="job" required> 
          </li>
          <li>
            <label for="address">주소</label>
            <textarea cols="20" rows="3"></textarea>
          </li>
          </ul>
        </div> 
</template>

<script>
export default {
    name : 'CustDetailVue',
    props : {
        CustomerData: Array,
    }
}
</script>

<style>

</style>
