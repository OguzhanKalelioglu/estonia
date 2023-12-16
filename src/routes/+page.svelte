<svelte:head>
	<title>Home</title>
	<meta name="description" content="Estonya Startup Topluluğu" />
</svelte:head>

<section>
	<div class="container is-max-desktop">
		<div class="notification is-primary">
		  
			<section class="hero is-primary">
				<div class="hero-body">
				  <p class="title">
					Estonya Startup Vize Topluluğu
				  </p>
				  <p class="subtitle">
					Bu topluluk Estonya'da startup kurmak isteyenlerden oluşan bir topluluktur. Amacı fikir alışverişi yaparak ve yeni bilgiler öğrenerek, fayda sağlamaktır.
				  </p>
				</div>
				</section>


		</div>

		<section>
			<figure class="image is-960x580">
			  <!-- svelte-ignore a11y-missing-attribute -->
			  <img src="/estonia.jpg">
			</figure>
		  </section>

		  <div class="container nelerYapabiliriz">
			<div class="notification">
				<h1 class="title">Neler Yapabiliriz?</h1>
				<ul>
					<li><h2 class="subtitle">Deneyimleri Paylaşma</h2></li>
					<li><h2 class="subtitle">E-Residency Süreçlerinde Destek Olma</h2></li>
					<li><h2 class="subtitle">Girişimciliğe Adım Atma</h2></li>
					<li><h2 class="subtitle">Yazılım Fikirleri Oluşturma</h2></li>
					<li><h2 class="subtitle">Yetkinlikleri Keşfetme</h2></li>
				</ul>
			</div>
		  </div>


		  <div class="container telegram">
			<div class="notification">
				<h1 class="title">Telegram Grubuna Katıl</h1>
				<p><a href="https://t.me/+NQeJLJb-1b45ODg8">
					https://t.me/+NQeJLJb-1b45ODg8
				   </p>
				   <div class="Img">
					  <!-- svelte-ignore a11y-missing-attribute -->
					  <img class="center" src="/telegram.jpeg">
				   </div>
			</div>
		  </div>
	  </div>
</section>


<style>
.nelerYapabiliriz .notification{
	margin-top: 1em;
	background-color: #0072CE;
	color: #fff;
}
.nelerYapabiliriz ul li{
	display: flex;
	justify-content: center;
	padding: 1em;
}
.telegram {
	margin-top: 1em;
	background-color: lightgrey;
}

.center {
  display: block;
  margin-top: 1em;
  margin-left: auto;
  margin-right: auto;
  width: 30%;
}

p {
	display: flex;
	justify-content: center;
}
</style>
