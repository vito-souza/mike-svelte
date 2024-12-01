<script lang="ts">
	import 'iconify-icon';
</script>

<footer>
	<div class="footer">
		<ul>
			<li><a href="#stores">Encontre uma Loja Mike</a></li>
			<li><a href="#news">Cadastre-se para receber novidades</a></li>
			<li><a href="#gift-card">Cartão Presente</a></li>
			<li><a href="#site-map">Mapa do Site</a></li>
			<li><a href="#mike-journal">Mike Journal</a></li>
			<li><a href="#corinthians">Corinthians</a></li>
			<li><a href="#black-friday">Black Friday</a></li>
		</ul>
		<ul>
			<span>Ajuda</span>
			<li><a href="#general-questions">Dúvidas Gerais</a></li>
			<li><a href="#size-guide">Encontre seu Tamanho</a></li>
			<li><a href="#deliveries">Entregas</a></li>
			<li><a href="#orders">Pedidos</a></li>
			<li><a href="#returns">Devoluções</a></li>
			<li><a href="#payments">Pagamentos</a></li>
			<li><a href="#products">Produtos</a></li>
			<li><a href="#corporate">Corporativo</a></li>
			<li><a href="#contact">Fale Conosco</a></li>
		</ul>
		<ul>
			<span>Sobre a Mike</span>
			<li><a href="#purpose">Propósito</a></li>
			<li><a href="#sustainability">Sustentabilidade</a></li>
			<li><a href="#about-mike-inc">Sobre a Mike, Inc.</a></li>
			<li><a href="#about-sbf-group">Sobre o Grupo SBF</a></li>
		</ul>
		<div>
			<span>Redes sociais</span>
			<div class="social-media-links">
				<button aria-label="Facebook"
					><iconify-icon icon="fa6-brands:facebook" width="2em" height="2em"></iconify-icon></button
				>
				<button aria-label="Instagram"
					><iconify-icon icon="fa6-brands:instagram" width="1.75em" height="2em"
					></iconify-icon></button
				>
				<button aria-label="Youtube"
					><iconify-icon icon="fa6-brands:youtube" width="2.25em" height="2em"
					></iconify-icon></button
				>
			</div>
		</div>
	</div>
	<div class="info">
		<div>
			<a href="#brasil">Brasil</a>
			<a href="#privacy-policy">Política de Privacidade</a>
			<a href="#cookies-policy">Política de Cookies</a>
			<a href="#use-terms">Termos de Uso</a>
		</div>
		<span>© 2024 Mike. Todos os direitos reservados.</span>
	</div>
</footer>

<style lang="scss">
	.footer,
	.info {
		display: flex;

		align-items: flex-start;
		justify-content: space-between;

		padding-bottom: 2rem;
		margin: 2rem 10rem 0;
	}

	.info div a {
		margin-left: 1rem;
	}

	.footer {
		border-bottom: 1px solid rgba(0, 0, 0, 0.3);
	}

	ul {
		list-style: none;

		margin: 0;
		padding: 0;
	}

	li {
		margin-top: 0.5rem;
	}

	a {
		text-decoration: none;
		color: #333;

		transition: color 0.3s ease;

		&:hover {
			color: #000;
		}
	}

	.social-media-links {
		display: flex;

		gap: 1rem;
		margin-top: 1rem;
	}

	button {
		background: none;
		border: none;

		cursor: pointer;

		transition: transform 0.3s ease;

		&:hover {
			transform: scale(1.1);
		}
	}
</style>
