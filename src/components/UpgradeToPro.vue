<template>
  <VBtn
    color="error"
    class="product-upgrade-to-pro"
    href="https://facebook.com/Krilinz98w"
    target="_blank"
    rel="noopener noreferrer"
  >
    Hỏi chấm

    <VMenu
      open-on-hover
      activator="parent"
      offset="15"
      max-width="400px"
      :close-on-content-click="false"
      transition="slide-y-reverse-transition"
    >
      <VCard>
        <VImg src="https://facebook.com/Krilinz98w" />
        <VCardTitle>Đây là website của tao</VCardTitle>
        <VCardText>
          Phú xe ôm, 1 mình tao chấp hết
        </VCardText>
        <VCardText>Hãy gọi Phú là leesin vì Phú đéo thấy gì cả</VCardText>
        <VCardText>
          <VBtn
            class="me-4"
            href="https://facebook.com/Krilinz98w"
            target="_blank"
            rel="noopener noreferrer"
          >
            Hello mai phờ ren
          </VBtn>
          <VBtn
            variant="outlined"
            href="https://facebook.com/Krilinz98w"
            target="_blank"
            rel="noopener noreferrer"
          >
            Đi đến facebook của Phú nào
          </VBtn>
        </VCardText>
      </VCard>
    </VMenu>
  </VBtn>
</template>

<style lang="scss" scoped>
.product-upgrade-to-pro {
  position: fixed;

  // To keep upgrade to pro button on top of v-layout
  z-index: 999;
  inset-block-end: 5%;
  inset-inline-end: 79px;

  .v-application &.v-btn.v-btn--elevated {
    box-shadow: 0 1px 20px 1px rgb(var(--v-theme-error)) !important;

    &:hover {
      box-shadow: none !important;
    }
  }
}
</style>
