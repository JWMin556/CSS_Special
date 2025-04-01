<template>
  <main class="component-grid">
    <section class="component-card">
      <h2>버튼</h2>
      <BaseButton class="btn-primary">primary</BaseButton>
      <BaseButton class="btn-outline">outline</BaseButton>
      <!-- <BaseButton variant="outline">outline</BaseButton> -->
      <!-- <BaseButton :variant="outline">outline</BaseButton> -->
      <!-- :variant="outline"은 outline을 변수나 계산된 값으로 해석하려고 하기 때문에 제대로 동작하지 않습니다. -->
      <!-- variant="outline"은 "outline"이라는 문자열로 전달되므로 예상한 대로 동작합니다. -->
      <BaseButton class="btn-pill">pill</BaseButton>
    </section>

    <section class="component-card">
      <h2>알림창</h2>
      <BaseAlert variant="success">Success</BaseAlert>
      <BaseAlert variant="warning">경고</BaseAlert>
      <BaseAlert variant="error">에러</BaseAlert>
    </section>

    <section class="component-card">
      <h2>뱃지</h2>
      <BaseBadge variant="success">Sucess</BaseBadge>
      <BaseBadge variant="number">3</BaseBadge>
    </section>
  </main>
</template>

<script setup>
import BaseButton from './UI/BaseButton.vue'
import BaseAlert from './UI/BaseAlert.vue'
import BaseBadge from './UI/BaseBadge.vue'
</script>
