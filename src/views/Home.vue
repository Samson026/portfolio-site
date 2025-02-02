<template>
    <div id="home">
        <div id="header">
            <nav class="navbar">
                <ul>
                    <li>This</li>
                    <li>is</li>
                    <li>test</li>
                </ul>
            </nav>
        </div>
        <h1>Hi this is Sam</h1>
    </div>
    
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>

#home {
    background-color: #333;
    width: 100vw;   
    height: 100vh;
}

.navbar {
  background-color: white;
  padding: 10px;
}

.navbar ul {
  list-style: none;
  display: flex;
  gap: 15px;
  padding: 0;
  margin: 0;
  width: 100vw;
}

.navbar ul li {
  display: inline;
  color: white;
  opacity: 1;
}

.navbar ul li a {
  color: white;
  text-decoration: none;
}

.navbar ul li a:hover {
  text-decoration: underline;
}
</style>