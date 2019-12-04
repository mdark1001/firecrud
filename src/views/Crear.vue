<template>
  <div class="about">
    <form action="">
      <label for="name">Nombre</label>
      <input name="name" v-model="contact.name" type="text" class="lui-input"/>

    </form>

  </div>
</template>
<script>
export default {
  name: 'crear_contacto',
  data: () => ({
    contact: {
      name: '',
      phone: '',
      email: ''
    }
  })
}
</script>
