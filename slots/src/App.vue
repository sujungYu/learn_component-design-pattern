<template>
  <div>
    <ul>
      <item>
        아이템 1
      </item>
      <item>
        아이템 2 <button>CLick me</button>
      </item>
      <item>
        아이템 3
      </item>
      <img src="./assets/endgame.png" alt="어벤져스 엔드게임" width="20px" height="20px">
      <item style="color: blue; font-size: 20px">
        아이템 4
      </item>
      <item>아이템 5</item>
    </ul>
  </div>
</template>

<script>
import Item from './Item.vue';

export default {
  components: {
    Item,
  },
}
</script>