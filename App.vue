





















<!-- <template>
  <div class="card container" :style="{ backgroundColor: selectedColor }">
    <img :src="imageUrl" :style="{ filter: `hue-rotate(${hueRotate}deg)` }" />
    <div class="color-picker">
      <!-- label1 -->
      <label for="color1">
        <input
          type="radio"
          name="color"
          id="color1"
          value="#ff0000"
          @change="selectColor" />
        <span class="color-swatch" style="background-color: #ff0000"></span>
      </label>

      <label for="color2">
        <input
          type="radio"
          name="color"
          id="color2"
          value="green"
          @change="selectColor" />
        <span class="color-swatch" style="background-color: green"></span>
      </label>
      <label for="color3">
        <input
          type="radio"
          name="color"
          id="color3"
          value="#0000ff"
          @change="selectColor" />
        <span class="color-swatch" style="background-color: #0000ff"></span>
      </label>
    </div>
    <div class="counter">
      <button @click="decrement">-</button>
      <span>{{ count }}</span>
      <button @click="increment">+</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  data() {
    return {
      count: 0,
      selectedColor: "#fff",
      imageUrl: "https://placekitten.com/300/200",
      hueRotate: 0,
    };
  },
  methods: {
    increment() {
      this.count++;
    },
    decrement() {
      if (this.count > 0) {
        this.count--;
      }
    },
    selectColor(event) {
      this.selectedColor = event.target.value;
      this.hueRotate = Math.floor(Math.random() * 360);
    },
  },
};
</script>

<style scoped>
.card {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 300px;
  height: 400px;
  padding: 20px;
  box-shadow: 10px 0px 10px 0px rgba(12, 0, 10, 0.2);
  border: solid #333;
  border-radius: 10px;
  margin-top: 50px;
}

.card img {
  width: 200px;
  height: 200px;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 20px;
}

.color-picker {
  display: flex;
  justify-content: center;
  margin-bottom: 20px;
}

.color-swatch {
  display: inline-block;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  margin-right: 10px;
  cursor: pointer;
}

.counter {
  display: flex;
  align-items: center;
}

.counter button {
  font-size: 24px;
  font-weight: bold;
  border: none;
  background-color: #fff;
  color: #333;
  width: 30px;
  height: 30px;
  margin: 10px;
}
</style> -->
