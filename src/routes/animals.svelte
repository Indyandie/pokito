<script>
  console.log('hello world')
  const animals = [
    {name: "dog", emoji: "🐕🐶"},
    {name: "lion", emoji: "🦁"},
    {name: "monkey", emoji: "🐒🐵"},
    {name: "pig", emoji: "🐖🐷"},
    {name: "camel", emoji: "🐫"},
    {name: "cat", emoji: "🐈🐱"}
  ]
</script>

<main>
  <h1>Animals</h1>

  {#each animals as animal}
  <div class="animals">
    {animal.emoji}
    <div>{animal.name}</div>
  </div>
  {/each}
</main>

<style>
  .animals {
    font-size: 78px;
  }
</style>