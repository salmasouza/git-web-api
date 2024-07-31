<template>
    <header>
        <nav>
            <router-link to="/" class="logo">
                <img src="@/assets/logo.jpg" alt="Deep Space Store">
            </router-link>
            <router-link class="btn" to="/login">Vender / Login</router-link>
        </nav>
    </header>

</template>

<script>

export default{
    name: "TheHeader"
};

</script>

<style scoped>
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 15px 20px;
  box-shadow: 0 2px 4px rgba(30, 60, 90, 0.1);
}

.brand {
  padding: 10px 0;
}

.brand img {
  width: 90px;
}

.logo {
    padding: 10px 0;

}

.logo img {
    width: 250px;
}
</style>