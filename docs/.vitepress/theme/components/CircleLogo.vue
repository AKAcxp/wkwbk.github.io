<template>
  <div class="circle-logo-container">
    <img src="/logo.png" alt="Logo" class="circle-logo" />
  </div>
</template>

<style scoped>
.circle-logo-container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.circle-logo {
  width: 128px;
  height: 128px;
  border-radius: 50%;
  overflow: hidden;
  box-shadow: 0 3px 8px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  object-fit: cover;
}

.circle-logo:hover {
  transform: scale(1.05);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}
</style> 