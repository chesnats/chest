<template>
    <div class="loading-overlay">
        <img src="@/assets/99d1ec8b1fce6845f422f3796b002688.gif" alt="Loading..." class="loading-image" />
    </div>
  </template>
  
  <script>
  export default {
    name: 'BaseLoading'
  }
  </script>
  
  <style scoped>
.loading-overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.8);
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 9999;
}
  
.loading-image {
  width: 500px; 
  height: 500px;
  border-radius: 50%;
}
  </style>
  