<template>
  <div class="text-center">
    <h6 class="colr-dark-blue fw-bold text-uppercase" v-if="tagline_place == 'before'">
      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="42" height="21" viewBox="0 0 42 21">
        <image id="_6a46b3eea1b8b9bb4cab9a0c26dc2a74-graduation-cap-icon-graduation-icons_copy" data-name="6a46b3eea1b8b9bb4cab9a0c26dc2a74-graduation-cap-icon-graduation-icons copy" width="42" height="21" xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAACoAAAAVCAYAAAAw73wjAAACZElEQVRIic3WS4hPYRgG8N+McSfkHtGQiLAgt8ktl5FYYGNhRRZsbOxYSmyUjQ0WspWUSIxb7syCNJTLCiUxKA3DMPrqPXU6ze3/91fz1Nf5Tt95v+85z/u87zlVOw+1qQBmYA02YzLu4DJu4E0lDqgpM64vlqEeazG3sF6LbTF/iOu4inv4Vs6BpSg6ESuxDqswtozzvuAWrgX5Jz0N7E7RhZHSpNrSMogVMRwbYyS8Dnsk4jfxrqdER2JFTrXaCpDrClNj7EA77ofSDbiL1iw2pX41tobnpv1nYqWiKRQ/Ux2BAzCkl5H8jT5RuO01IXNDLO7GInwOH3WV+qbwVqrq5/gUcS2RxnTACIzDYtQhZW90J/ul+Afh1dt4hF/ZYtGjf3AOZ7EHC6LSN2AOLuJUVGtqM0PDLjNjjMfAUKMZL2Ocx/E4OPXZ9dG+kgcvRd9txI/OVCkSrYnDMjyMcTgKbRhm40D00Ald5a6AtiCURLiAYyXEqi7ct+YrrYC90U6S4ttLJClEWI6jeIWDpQZnSKnblzpBtIZnhWeXl0isO4wq5eG8ovvDP5NiXkRzhYl26seOkFf0RJg8tYSTJR6a/PcV32Oe9u2HQZVqe3miqdW8xYf4gSiiKnf/Alei0J7ifSjeWth7MMZEpubFF29FrLeXSzQpOSv6XxHJIlPwOIqqoxcpIlP5a7Sohuge83Ea08sluiSukyNlLYXndsXn7F/RGILURZZ6pGy+mOrj2j82yuNnhUhm+BO/ez1Of57oltx8TgVJVQQZ0VXxdplqm3ob0cyj6cdhJz7iSPio9wB/AYv8hOgwY7rZAAAAAElFTkSuQmCC"/>
      </svg>
      Student <span class="colr-blue">WordPress Theme</span>
    </h6>
    <h2 class="colr-dark-blue fw-bold text-uppercase">
      <slot name="heading" />
      <span class="colr-blue font-pristina text-lowercase fs-1"><slot name="styled" /></span>
    </h2>
    <h6 class="colr-dark-blue fw-bold text-uppercase" v-if="tagline_place == 'after'">
      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="42" height="21" viewBox="0 0 42 21">
        <image id="_6a46b3eea1b8b9bb4cab9a0c26dc2a74-graduation-cap-icon-graduation-icons_copy" data-name="6a46b3eea1b8b9bb4cab9a0c26dc2a74-graduation-cap-icon-graduation-icons copy" width="42" height="21" xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAACoAAAAVCAYAAAAw73wjAAACZElEQVRIic3WS4hPYRgG8N+McSfkHtGQiLAgt8ktl5FYYGNhRRZsbOxYSmyUjQ0WspWUSIxb7syCNJTLCiUxKA3DMPrqPXU6ze3/91fz1Nf5Tt95v+85z/u87zlVOw+1qQBmYA02YzLu4DJu4E0lDqgpM64vlqEeazG3sF6LbTF/iOu4inv4Vs6BpSg6ESuxDqswtozzvuAWrgX5Jz0N7E7RhZHSpNrSMogVMRwbYyS8Dnsk4jfxrqdER2JFTrXaCpDrClNj7EA77ofSDbiL1iw2pX41tobnpv1nYqWiKRQ/Ux2BAzCkl5H8jT5RuO01IXNDLO7GInwOH3WV+qbwVqrq5/gUcS2RxnTACIzDYtQhZW90J/ul+Afh1dt4hF/ZYtGjf3AOZ7EHC6LSN2AOLuJUVGtqM0PDLjNjjMfAUKMZL2Ocx/E4OPXZ9dG+kgcvRd9txI/OVCkSrYnDMjyMcTgKbRhm40D00Ald5a6AtiCURLiAYyXEqi7ct+YrrYC90U6S4ttLJClEWI6jeIWDpQZnSKnblzpBtIZnhWeXl0isO4wq5eG8ovvDP5NiXkRzhYl26seOkFf0RJg8tYSTJR6a/PcV32Oe9u2HQZVqe3miqdW8xYf4gSiiKnf/Alei0J7ifSjeWth7MMZEpubFF29FrLeXSzQpOSv6XxHJIlPwOIqqoxcpIlP5a7Sohuge83Ea08sluiSukyNlLYXndsXn7F/RGILURZZ6pGy+mOrj2j82yuNnhUhm+BO/ez1Of57oltx8TgVJVQQZ0VXxdplqm3ob0cyj6cdhJz7iSPio9wB/AYv8hOgwY7rZAAAAAElFTkSuQmCC"/>
      </svg>
      Student <span class="colr-blue">WordPress Theme</span>
    </h6>
    <p v-if="txt"><slot /></p>
  </div>
</template>

<script>
export default {
  name: 'section-heading',
  props: {
    tagline_place: {
      type: String,
      default: 'before'
    },
    txt: {
      type: Boolean,
      default: true
    }
  }
}
</script>

<style lang="scss" scoped>
h6 {
  font-size: 12px;
}
</style>