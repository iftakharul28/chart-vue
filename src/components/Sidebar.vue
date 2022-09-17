<script setup>
import DashBoardIcon from "./icons/DashBoardIcon.vue";
import CashIcon from "./icons/CashIcon.vue";
import InvestmentsIcon from "./icons/InvestmentsIcon.vue";
import HomeIcon from "./icons/HomeIcon.vue";
import UmbrellaIcon from "./icons/UmbrellaIcon.vue";
import JudgmentIcon from "./icons/JudgmentIcon.vue";
import TaxIcon from "./icons/TaxIcon.vue";
import GoalIcon from "./icons/GoalIcon.vue";
</script>
<template>
  <aside class="side-bar">
    <div class="side-bar__wrapper">
      <div class="side-bar__item-wrapper">
        <DashBoardIcon />
      </div>
      <div class="side-bar__item-wrapper">
        <CashIcon />
      </div>
      <div class="side-bar__item-wrapper">
        <InvestmentsIcon />
      </div>
      <div class="side-bar__item-wrapper">
        <HomeIcon />
      </div>
      <div class="side-bar__item-wrapper">
        <UmbrellaIcon />
      </div>
      <div class="side-bar__item-wrapper">
        <JudgmentIcon />
      </div>
      <div class="side-bar__item-wrapper">
        <TaxIcon />
      </div>
      <div class="side-bar__item-wrapper">
        <GoalIcon />
      </div>
    </div>
  </aside>
</template>
