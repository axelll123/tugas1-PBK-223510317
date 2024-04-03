<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>
    Saat ini, saya tengah menempuh pendidikan sebagai mahasiswa di Universitas Islam Riau, yang berlokasi di Jalan Kaharuddin Nst, Pekanbaru. Sedang berada di semester 4, saya mengambil jurusan Teknik Informatika di institusi tersebut.
    Saya Berasal dari Kota Pekanbaru, Riau tepatnya berada di perumahan damai langgeng blok 1-1 no 16. Saya berusia 20 tahun dan memiliki golongan darah B
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    Sekarang, saya sedang menempuh pendidikan tinggi di salah satu perguruan tinggi swasta di Riau, yakni
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
    .
    Sebelumnya, saya bersekolah di Sekolah Menengah Atas
    <a href="https://sman12pkuofficial.sch.id/" target="_blank" rel="noopener">SMA Negeri 12 Pekanbaru</a>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi saya</template>
    <ul>
      <li>Dance</li>
      <li>Bernyanyi</li>
      <li>Menonton</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Pengalaman</template>
    Pengalaman adalah guru terbaik dalam kehidupan. Setiap detiknya mengajarkan kita pelajaran berharga. Jangan pernah sia-siakan kesempatan untuk belajar dan tumbuh dari setiap pengalaman yang kita alami.<ul>
      <li>Kejuaraan DBL</li>
      <li>Menghadiri Seminar Web Developer</li>
      <li>Menjadi Kontributor Proyek Open Source</li>
      <li>Magang</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
untuk menghubungi saya kalian dapat mengontak di bawah ini
   sosmed Instagram :<a href="https://www.instagram.com/rethacindy/" target="_blank">rethacindy </a
    ><br />
    Email : rethacindyaulia@gmail.com<br />
    No HP : +6289616137511
  </WelcomeItem>
</template>