<template>
  <form>
    <label>Email:</label>
    <input type="email" required v-model="email" />
    <label>Password:</label>
    <input type="password" required v-model="password" />

    <label>Role</label>
    <select v-model="role">
      <option value="developer">Web Developer</option>
      <option value="designer">Web Designer</option>
    </select>

    <div class="terms">
      <input type="checkbox" required v-model="terms" />
      <label>Accept terms and conditions</label>
    </div>

    <!-- <div>
      <input type="checkbox" value="abdul" v-model="names" />
      <label>Abdul</label>
    </div>
    <div>
      <input type="checkbox" value="ayo" v-model="names" />
      <label>Ayo</label>
    </div>
    <div>
      <input type="checkbox" value="mary" v-model="names" />
      <label>Mary</label>
    </div> -->
  </form>

  <p>Email: {{ email }}</p>
  <p>Password: {{ password }}</p>
  <p>Role: {{ role }}</p>
  <p>Terms Accepted: {{ terms }}</p> 
  <p>Names: {{ names }}</p> 
</template>

<script>
export default {
  data() {
    return {
      email: 'abdul',
      password: '',
      role: 'designer',
      terms: false,
      names: []
    }
  }
}
</script>
