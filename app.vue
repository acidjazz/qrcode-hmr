<template>
  <div>
    <span> this is a test </span>
    <client>
      <qrcode
        :width="600"
        :height="600"
        value="https://www.google.com"
      />
    </client>
  </div>
</template>
