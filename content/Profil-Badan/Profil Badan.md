---
author: TIM IT MSI
title: "Profil Badan"
date: 2024-08-01 05:22:45
---
<div style="display: flex; flex-wrap: wrap; gap: 30px; width: 100%; margin-top: 40px;">

  <div style="flex: 1 1 calc(33.333% - 20px); box-sizing: border-box; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;" class="border-customGreen bg-customGreen rounded-2xl dark:bg-gray-700 dark:text-white">
      <i class="fas fa-history text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif;" class="text-white">Profil</span>
    <button onclick="window.location.href='/master-profil-badan/profil-lembaga'" class="px-2.5 py-1.5 bg-transparent text-white border border-white rounded-xl text-base cursor-pointer transition-colors duration-300 hover:bg-white hover:text-customGreen dark:hover:text-gray-700">Lihat Detail <i class="fas fa-arrow-right ml-1.5"></i></button>
  </div>

  <div style="flex: 1 1 calc(33.333% - 20px); box-sizing: border-box; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;" class="border-customGreen bg-customGreen rounded-2xl dark:bg-gray-700 dark:text-white">
      <i class="fas fa-bullseye text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif;" class="text-white">Visi Misi</span>
    <button onclick="window.location.href='/master-profil-badan/visi-misi'" class="px-2.5 py-1.5 bg-transparent text-white border border-white rounded-xl text-base cursor-pointer transition-colors duration-300 hover:bg-white hover:text-customGreen dark:hover:text-gray-700">Lihat Detail <i class="fas fa-arrow-right ml-1.5"></i></button>
  </div>



<style>
@media (max-width: 1024px) { 
  div[style*="display: flex; flex-wrap: wrap;"] > div {
    flex: 1 1 100%; 
    margin-bottom: 20px;
    padding: 20px 0;
    text-align: center;
  }
}

@media (max-width: 768px) { 
  div[style*="display: flex; flex-wrap: wrap;"] {
    flex-direction: column; 
    align-items: center; 
  }

  div[style*="display: flex; flex-wrap: wrap;"] > div {
    flex: none; 
    width: calc(70% - 30px); 
    height: 150px; 
    max-width: calc(70% - 30px);
    margin-bottom: 20px;
    padding: 20px 0;
  }
}
</style>

</div>