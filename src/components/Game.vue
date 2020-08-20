<template>
  <div>
    <p>
      HP Player{{ randomNo(1,7) }}
      {{player[randomNo(1,7)-1].name }}
    </p>
    +รูป
    <hr />
    name = {{ aPlayer.name }}
    hp={{ aPlayer.hp }}
    
  </div>
</template>