<div class="top">
	<div class="name">
		<h2>M-user Signup</h2>
		<div class="outer">
			<input class="inner" type="text" placeholder="Username">
			<input class="inner" type="text" placeholder="Full Name">
			<input class="inner" type="password" placeholder="Password">
			<input class="inner" type="password" placeholder="Comfirm Password">
			<button class="log" type="button">Signup</button>
			<p class="sign">Already have an account? <a href="#signup">Login</a></p>
			<!--login settings-->
		</div>
	</div>
</div>
<style>
  :global(body) {
    background-color: #faaca8;
    background-image: linear-gradient(90deg, #faaca8 0%, #ddd6f3 100%);
  }
  .top {
    background: rgba(255, 255, 255, 0.15);
    box-shadow: 0 8px 32px 0 #1f26875e;
    backdrop-filter: blur(3px);
    -webkit-backdrop-filter: blur(3px);
    border-radius: 10px;
    border: 1px solid #ffffff2e;
    width: 350px;
    height: 500px;
    padding: 20px;
    position: absolute;
    top: 50%;
    left: 50%;
    text-align: center;
    transform: translate(-50%, -50%);
  }
  .sign {
    text-decoration: none;
    font-weight: bold;
    cursor: default;
    transform: translate(-00%, 400%);
  }
  .sign a {
    text-decoration: none;
    color: rgb(253, 0, 156);
  }
  .outer {
    display: grid;
    place-items: center;
    height: 30vh;
  }
  .name {
    cursor: default;
  }
  .inner {
    color: rgb(255, 0, 140);
    width: 80%;
    position: relative;
    left: 50%;
    top: 15%;
    transform: translate(-60%, 20%);
    border-radius: 20px;
    margin-top: 20px;
    padding: 10px;
    outline: none;
    background: rgba(255, 255, 255, 0.15);
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
    backdrop-filter: blur(3px);
    -webkit-backdrop-filter: blur(3px);
    border-radius: 10px;
    border: 1px solid rgba(255, 255, 255, 0.18);
  }
  .log {
    color: black;
    width: 50%;
    position: relative;
    left: 50%;
    top: 56%;
    transform: translate(-100%, 30%);
    border-radius: 20px;
    margin-top: 20px;
    padding: 10px;
    background: rgba(255, 255, 255, 0.15);
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
    backdrop-filter: blur(100px);
    -webkit-backdrop-filter: blur(200px);
    border-radius: 10px;
    border: 1px solid rgba(255, 255, 255, 0.18);
    cursor: pointer;
  }
  h2 {
    font-size: 35px;
    font-family: josefin sans;
  }
</style>
