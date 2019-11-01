<template>
  <a-layout-header
    class="header"
    :style="{
      backgroundColor: '#fff',
      borderBottom: '1px solid rgb(232, 232, 232)'
    }"
  >
    <div>
      <span class="float-l">
        <a-icon
          type="code"
          theme="filled"
          :style="{ fontSize: '1.5rem', color: '#ec79d8' }"
        />
        <span :style="{ marginLeft: '0.6rem', fontSize: '1.5rem' }"
          >n2ptune</span
        >
      </span>
      <span class="float-r">
        <a-button-group>
          <a-button
            type="default"
            icon="bars"
            size="large"
            shape="circle"
            :style="{ border: 'none' }"
          ></a-button>
        </a-button-group>
      </span>
    </div>
  </a-layout-header>
</template>

<style scoped></style>
