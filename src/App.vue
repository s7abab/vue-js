<!-- 1 -->
<!-- conditional rendering -->

<!-- <template>
  <h1>Header</h1>
  <h1 v-if="num===0" >Number = {{ num }}</h1>
  <h1 v-else >Number = -1</h1>
</template>


<script>
export default {
  name: 'App',
  data() {
    return {
      num:0
    }
  }
}
</script>


<style>
.italic {
  font-style: italic;
  color: blueviolet;
}
</style> -->


<!-- 2 -->
<!-- rendering list -->

<!-- <template>
  <h1>This is array of objects</h1>
  <div v-for="person in people" :key="person.name">
    <div>{{ person.name }} | {{ person.age }}</div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      people: [{ name: 'John', age: 30 }, { name: 'Mary', age: 29 }, { name: 'Superman', age: 120 }]
    }
  }
}
</script>

<style>

</style> -->

<!-- 3 -->
<!-- methods -->

<!-- <template>
  <h1>{{ add()}}</h1>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {

    }
  },
  methods:{
    add(){
      return 5+5
    }
  }
}
</script> -->

<!-- 4  -->
<!-- event handling -->
<!-- <template>
  <h1>Counter</h1>
  <h1>{{ count }}</h1>
  <div class="flex_container">
    <button v-on:click="increment()">+</button>
    <button v-on:click="decrement()">-</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    increment() {
      this.count++;
    },
    decrement() {
      this.count--
    }
  }
}
</script>

<style>
.flex_container {
  display: flex;
  gap: 10px;
  background-color: blue;
}
</style> -->