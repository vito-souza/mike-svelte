<script lang="ts">
	import 'iconify-icon';
</script>

<header class="header">
	<div class="logo">
		<img src="https://static.nike.com.br/v11-9-0/images/brands/logo.svg" alt="Logo" />
	</div>
	<nav class="topics" aria-label="Menu principal">
		<ul>
			<li><a href="#home">Home</a></li>
			<li><a href="#collections">Coleções</a></li>
			<li><a href="#releases">Lançamentos</a></li>
			<li><a href="#brands">Marcas</a></li>
		</ul>
	</nav>
	<nav class="actions">
		<input type="text" placeholder="Pesquisar..." />
		<ul>
			<li>
				<button aria-label="Carrinho de compras">
					<iconify-icon
						icon="material-symbols-light:shopping-bag-outline-sharp"
						width="32"
						height="32"
					></iconify-icon>
				</button>
			</li>
			<li>
				<button aria-label="Favoritos">
					<iconify-icon icon="material-symbols-light:favorite-outline" width="32" height="32"
					></iconify-icon>
				</button>
			</li>
		</ul>
	</nav>
</header>

<style lang="scss">
	.header {
		display: flex;

		align-items: center;
		justify-content: space-between;

		padding: 2rem 10rem 1rem;
	}

	.topics,
	.actions,
	ul {
		display: flex;

		align-items: center;
		justify-content: center;

		list-style: none;
	}

	a {
		text-decoration: none;
		color: #333;

		padding: 1rem;

		border-bottom: 2px solid transparent;
		transition: border-color 0.3s ease;

		&:hover {
			border-bottom: 2px solid #333;
		}
	}

	button {
		background: none;
		border: none;

		cursor: pointer;

		padding: 0 1rem;
		transition: transform 0.3s ease;

		&:hover {
			transform: scale(1.1);
		}
	}

	input {
		border: 1px solid rgba(0, 0, 0, 0.1);
		border-radius: 1rem;

		padding: 0.5rem 1rem;

		transition: border-color 0.3s ease;

		&:hover {
			border: 1px solid rgba(0, 0, 0, 0.3);
		}
	}

	img {
		cursor: pointer;
	}
</style>
