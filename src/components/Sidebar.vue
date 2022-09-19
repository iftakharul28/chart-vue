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
      <div class="side-bar__logo-wrapper">
        <img class="side-bar__image" src="logo.png" alt="logo" />
        <img
          class="side-bar__image-text"
          src="logo-bottom.png"
          alt="logo-bottom"
        />
      </div>
      <div class="side-bar__item-wrapper side-bar__item-wrapper--active">
        <div class="side-bar__item-bg"></div>
        <div
          class="side-bar__item-icon-wrapper side-bar__item-icon-wrapper--active"
        >
          <DashBoardIcon class="side-bar__item-icon" />
        </div>
        <p class="side-bar__item-name side-bar__item-name--active">Dashboard</p>
      </div>
      <div class="side-bar__item-wrapper">
        <div class="side-bar__item-icon-wrapper">
          <CashIcon class="side-bar__item-icon side-bar__item-icon--yellow" />
        </div>
        <p class="side-bar__item-name">Investments</p>
      </div>
      <div class="side-bar__item-wrapper">
        <div class="side-bar__item-icon-wrapper">
          <InvestmentsIcon
            class="side-bar__item-icon side-bar__item-icon--green"
          />
        </div>
        <p class="side-bar__item-name">Real Estate</p>
      </div>
      <div class="side-bar__item-wrapper">
        <div class="side-bar__item-icon-wrapper">
          <HomeIcon class="side-bar__item-icon side-bar__item-icon--red" />
        </div>
        <p class="side-bar__item-name">Insurance</p>
      </div>
      <div class="side-bar__item-wrapper">
        <div class="side-bar__item-icon-wrapper">
          <UmbrellaIcon class="side-bar__item-icon side-bar__item-icon--blue" />
        </div>
        <p class="side-bar__item-name">Legal Planning</p>
      </div>
      <div class="side-bar__item-wrapper">
        <div class="side-bar__item-icon-wrapper">
          <JudgmentIcon
            class="side-bar__item-icon side-bar__item-icon--orange"
          />
        </div>
        <p class="side-bar__item-name">Tax Planning</p>
      </div>
      <div class="side-bar__item-wrapper">
        <div class="side-bar__item-icon-wrapper">
          <TaxIcon class="side-bar__item-icon side-bar__item-icon--purple" />
        </div>
        <p class="side-bar__item-name">Goals</p>
      </div>
      <div class="side-bar__item-wrapper">
        <div class="side-bar__item-icon-wrapper">
          <GoalIcon class="side-bar__item-icon side-bar__item-icon--earth" />
        </div>
        <p class="side-bar__item-name">Learn</p>
      </div>
    </div>
  </aside>
</template>
