<script>
  let imageUrl = "https://picsum.photos/200"
  let caption = "random picture"
  let linkUrl = "chrome://newtab/"
</script>

<figure>
  <a href={linkUrl}>
    <img src={imageUrl} alt="Example" />
  </a>
  <figcaption>{caption}</figcaption>
</figure>

<style>
  figure {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: auto;
    margin-bottom: auto;
    padding: 1.5rem;
    width: fit-content;
    border-radius: 10px;
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
    color: black;
    backdrop-filter: blur(4px);
    background-image: url(https://www.okinawastory.jp/files/contents/000/000/525/block_r6F9G9DA_0f868d7c443929613c70c94bb9f239b14a14046d-w1500.jpg);
    background-color: rgba(255, 255, 255, 0.5);
    background-blend-mode: lighten;
  }
</style>
