<script>
  const socials = [
    {name: "Instagram", url: "https://www.instagram.com/", classIcon: "fab fa-instagram"},
    {name: "Github", url: "https://github.com/devcleverton", classIcon: "fab fa-github"},
    {name: "Telegram", url: "https://t.me/E", classIcon: "fab fa-telegram"},
  ]
</script>

<div id="social">
  {#each socials as social}
    <a href="{social.url}" target="_blank">
      <i class="{social.classIcon}"></i>
    </a>
  {/each}
</div>

<style>
  #social {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 50px;
    width: 210px;
    background: rgba(55, 62, 97, 0.5);
    border-radius: 50px;
    transform: translateY(-50%);
    -webkit-box-shadow: 4px 4px 18px -5px #2D3769;
    -moz-box-shadow: 4px 4px 18px -5px #2D3769;
    box-shadow: 4px 4px 18px -5px #2D3769;
  }

  #social a {
    background: #eee;
    border-radius: 50%;
    width: 40px;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-decoration: none;
    transition:.3s;
  }

  #social a:hover{
    transform: translateY(-5px);
  }

  #social i {
    color: rgb(32, 32, 78);
    cursor:pointer;
  }
</style>