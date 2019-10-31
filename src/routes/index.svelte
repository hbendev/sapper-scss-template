<style type="text/scss">
  @import "../styles/colors";

  .box {
    height: 400px;
    width: 80%;
    margin: 0 auto;
  }

  .grey {
    background: grey;

    h2.red {
      color: $primary-color;
    }
  }
</style>

<svelte:head>
	<title>Sapper scss template</title>
</svelte:head>

<h1>Great success!</h1>

<div class="grey box">
  <h2 class="red">red</h2>
</div>

<div class="global-rule">
  <h3>small</h3>
</div>

<p><strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong></p>
