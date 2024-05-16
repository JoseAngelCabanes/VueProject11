<template>
<section>
  <h2>My friends</h2>
  <ul>
    <friend-contact></friend-contact>
    <friend-contact></friend-contact>
  </ul>
</section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        {
          id: "manuel",
          name: "Manuel Lorenz",
          phone: "0123 45678 91",
          email: "manue@localhost.com",
        },
        {
          id: "julie",
          name: "Julie Jones",
          phone: "0987 65432 10",
          email: "julie@localhost.com",
        },
      ],
    };
  },
};
</script>

<style>

* {
  box-sizing: border-box;
}

html {
  font-family: 'Jost', sans-serif;
}

body {
  margin: 0;
}

header {
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
  margin: 3rem auto;
  border-radius: 10px;
  padding: 1rem;
  background-color: #58004d;
  color: white;
  text-align: center;
  width: 90%;
  max-width: 40rem;
}

#app ul {
  margin: 0;
  padding: 0;
  list-style: none;
}
</style>