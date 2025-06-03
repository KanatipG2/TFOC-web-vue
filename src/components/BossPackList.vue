<script setup>
import { ref } from 'vue';

const bossPacks = ref([
  {
    title: 'Boss Pack #1',
    lastUpdate: '03/06/2568', 
    bosses: [
      { name: 'Prayut Chan-o-cha', link: './bosses/prayut.html' },
      { name: 'TAE EXZENFIRE', link: './bosses/taeexzenfire.html' },
      'Absolutely Contrasting Characteristics Annoying Pyro Cat',
      'Aya Shameimaru',
      'Baron Medi-Mage',
      'Beta Tester Party Medic: The Last Stand of Terminus',
      'Chin Chin',
      'Commander Private',
      'Conclusion of Havoc',
      'Corrupted War Machine',
      'Cross Soldier',
      'Cyber Ninja Scout',
      'Enterprise & True Administrator [DUO]',
      'Enterprise',
      'Faith',
      'GZcross Sniper',
      'Horseless Headless Horsemann Jr.',
      'MLG Sniper',
      'Magic Bullet',
      'Malper',
      'Not Kenzo',
      'PPKUEYZA',
      'Phaethon',
      'Popuko & Pipimi [DUO]',
      'pu_shitcake',
      'Ruspy',
      'Ryu Yamato',
      'SCP-MTF',
      'Saxton Hale',
      'Sir. Wellington',
      'Sligaper',
      'Sun9z',
      'System Dominator, Brandted',
      'The Funeral of the Dead Butterflies',
      'True Administrator',
      'Xeacring',
      'Xyro',
      'Zanki',
      'Zerstorer'
    ]
  },
  {
    title: 'Boss Pack #2',
    bosses: [
      { name: 'Prayut Chan-o-cha', link: './bosses/prayut.html' },
      { name: 'TAE EXZENFIRE', link: './bosses/taeexzenfire.html' },
      'Agent Pink',
      'Bamboo-Hatted Kim',
      'Bonk Boy',
      'Cirno',
      'Commando Scout',
      'Demonic Wizard Liafail & Demonic Wizard Luard [DUO]',
      'Demonic Wizard Liafail',
      'Demonic Wizard Luard',
      'Devil Knight Scout',
      'Easter Bunny',
      'Female Sniper',
      'Future Breaker Machine',
      'GT Stream',
      'Gearmaster, Calces',
      'Ghostface',
      'Haunted Astolfo Bean Plushie',
      'Hidden',
      'Infamous Superunit \'Ares\'',
      'Insane 24kHax',
      'Javelin',
      'Kirby',
      'MLG Demoman',
      'Monoculus',
      'Ninja Spy',
      'Ninjineer',
      'Nister',
      'P.Y.R.O',
      'Pedobear',
      'Sagiri Izumi',
      'Saryx',
      'SnowFake',
      'Spyper',
      'THE CLOWNRIDER',
      'Terror of the Swamp',
      'The Night Wanderer',
      'The True Time Ruler',
      'UltraShino\'s Duck',
      'Zansetsu'
    ]
  },
  {
    title: 'Boss Pack #3',
    bosses: [
      { name: 'Prayut Chan-o-cha', link: './bosses/prayut.html' },
      { name: 'TAE EXZENFIRE', link: './bosses/taeexzenfire.html' },
      'Abygale, The Phantom Blade',
      'Akashi',
      'Akatsuki',
      'Alpha Unit Nighteye',
      'Biker Scout [DUO] & Biker Soldier [DUO]',
      'Christian Brutal Sniper',
      'Commando Direc',
      'Dark Plague Scout',
      'Deadeye 0',
      'Deadeye Qorr',
      'Heavy Sauce',
      'Holiday Poomy',
      'Hotline Sniper',
      'Jesus',
      'Koishi Komeiji & Satori Komeiji [DUO]',
      'Koishi Komeiji',
      'Lunatic Overrule Destroyer',
      'MLG Pyro',
      'MaKa Shark',
      'Magineertic',
      'MrTheBank',
      'Nightmare Medic',
      'Not True Administrator',
      'Nuclear Scout',
      'Redblade',
      'Roland',
      'Satori Komeiji',
      'Shin',
      'Shitcake-Bot 9000',
      'Sinyle',
      'The Blightcaller',
      'The Hellraiser',
      'The Mesmerist',
      'The Pequod Capatain Ahab, First Mate Starbuck, Harpooner Queequeg [TRIO]',
      'Theo'
    ]
  },
  {
    title: 'Boss Pack #4',
    bosses: [
      { name: 'Prayut Chan-o-cha', link: './bosses/prayut.html' },
      { name: 'TAE EXZENFIRE', link: './bosses/taeexzenfire.html' },
      'AE86',
      'Abuser',
      'Andoain, the \'Martyr\'',
      'Art of Darkness',
      'B4R0N M.E.D.I-BOT',
      'Bonk Boy',
      'Dementia',
      'Demo Samedi',
      'Fujiwara no Mokou',
      'GZcross Dimensions Breaker',
      'Gabriel',
      'Hametsu',
      'HeatCliff',
      'Kaizo',
      'Loftus',
      'MLG Soldier',
      'MaKaValz',
      'Machine Devastate',
      'Ninja Cross',
      'NinjaSlayer',
      'Outlaw Sniper & Outlaw Spy [DUO]',
      'Outlaw Sniper',
      'Outlaw Spy',
      'Pattun Chuen',
      'Rhine, Berthod, Rezner, Noarh [SQUAD]',
      'Scout Rider: The Yuusha Hiku',
      'Seeman & Seeldier [DUO]',
      'Shimakaze',
      'Shiranui',
      'Soldine',
      'Terror of the Swamp',
      'The Amalgamation',
      'The Gambler',
      'The Mysterious Scout',
      'The Roadside Ravager',
      'Ultimate LnwTrue',
      'Vagineer'
    ]
  },
  {
    title: 'Boss Pack #5',
    bosses: [
      { name: 'Prayut Chan-o-cha', link: './bosses/prayut.html' },
      { name: 'TAE EXZENFIRE', link: './bosses/taeexzenfire.html' },
      'Adolf Hitler',
      'Candy Man',
      'Commander Heavy',
      'Count Heavnich',
      'Cuddly Heavy',
      'Deadshot Sniper',
      'False Administrator',
      'Flandre Scarlet',
      'Florentino',
      'Foxy the Pirate',
      'GentleSpy',
      'Hentai Woody',
      'High Leader Soldier',
      'Light Wizard Metatron',
      'Megumin',
      'Necrozma',
      'Nightmare Medic',
      'No Random Crits V3: Intergalactic Terror',
      'Nue Houjuu',
      'Old Nick',
      'Piss Cakehole',
      'Pyrokinesis Camael',
      'Remilia Scarlet & Flandre Scarlet [DUO]',
      'Remilia Scarlet',
      'Rudol Von Stroheim',
      'Sans N°363',
      'Scout Rider: The Yuusha Hiku',
      'Shadow Thief & Count Heavnich [DUO]',
      'Shadow Thief',
      'Sir. Wellington',
      'SomeCleanTrash',
      'Suika Ibuki',
      'Team Service Announcement Medic',
      'The Mimicer',
      'The Wight',
      'Theo',
      'Weebshit Scout V3 : The Maou of Chuunibyou',
      'ZelanTheBetrayer'
    ]
  },
  {
    title: 'Boss Pack #6',
    bosses: [
      { name: 'Prayut Chan-o-cha', link: './bosses/prayut.html' },
      { name: 'TAE EXZENFIRE', link: './bosses/taeexzenfire.html' },
      'Beep Man',
      'Chief Maid of The Manor, Astral',
      'Daft Punk Gold [DUO]',
      'Daft Punk Silver [DUO]',
      'Demopan',
      'Detective Behind Chinatown',
      'Ghost Buster & Slimer',
      'Gordon Freeman',
      'GrandDark',
      'Loftus',
      'MA1NC0NN Mk.1',
      'Mafioso',
      'Nightmare Sniper',
      'Nocturne',
      'Ricardo Milos',
      'Ryuk',
      'SammyClassicSonicFan',
      'Sans',
      'Shilu',
      'Steve',
      'Stripper Soldier',
      'Super Pro Demoman',
      'Swag Spy',
      'Syn Luke',
      'The Last Wizard of Century & Detective Behind Chinatown [DUO]',
      'The Last Wizard of Century',
      'The Rocket',
      'True Server Ruler',
      'Veloce Bandito',
      'Virusdoctor',
      'Wankers',
      'Zetiwelg'
    ]
  },
  {
    title: 'Boss Pack #7',
    bosses: [
      { name: 'Prayut Chan-o-cha', link: './bosses/prayut.html' },
      { name: 'TAE EXZENFIRE', link: './bosses/taeexzenfire.html' },
    ]
  }
]);

const currentYear = new Date().getFullYear() + 543; // Convert current year to Buddhist calendar year 
const lastUpdateDate = '03/06/' + currentYear;
</script>

<template>
  <div id="content">
    <div class="pageitem">
      <h2>Welcome to our Freak Fortress 2</h2>
      <p class="sub">ようこそ、私たちのFreak Fortress 2へ</p>
      <p>Tap on the boss's name to see their information if it glows purple.</p>
      <blockquote>Raynovo — 12/4/2568 12:35<br>
        ปกตถ้ามีคนเติมมึงแก้ยังไง<br>
        เข้าไปแก้ใน db?<br>
        ethelred — 12/4/2568 12:36<br>
        โอนเครดิตตัวเองให้คนที่มาเติม<br>
        Raynovo — 12/4/2568 12:37<br>
        ไอสัส 555</blockquote>
      <p>Current SECRET boss: ***, ***, ***</p>
    </div>

    <div class="pageitem">
      <h2>All Boss Packs List</h2>
      <p class="sub">Last Update: {{ lastUpdateDate }}</p>

      <div v-for="(pack, index) in bossPacks" :key="index" class="two-col-cell">
        <h3>{{ pack.title }}</h3>
        <ul>
          <li v-for="(boss, bossIndex) in pack.bosses" :key="bossIndex">
            <a v-if="typeof boss === 'object' && boss.link" :href="boss.link">{{ boss.name }}</a>
            <template v-else>{{ boss }}</template>
          </li>
        </ul>
      </div>
      <div class="clear"></div> </div>
    </div>
</template>

<style scoped>
/* Ensure the clear div works */
.clear {
  clear: both;
}

/* Add some margin to the bottom of the main content div to avoid overlap with footer */
#content {
    padding-bottom: 20px; /* Adjust as needed */
}

/* The .pageitem blockquote width needs to be adjusted based on the new layout */
blockquote {
  width: 90%; /* Adjust width for better fit within the pageitem */
}
</style>