<script>
	import { gsap } from 'gsap';
	let logo;

	import { onMount } from 'svelte';

	onMount(() => {
		gsap.to('.logo', {
			xPercent: +50,
			duration: 3,
			ease: "elastic.out(1,0.3)",
			y: 50
		});
	});
</script>

<section class="intro">
	<header>
		<div class="logo">
			<strong>Sharia</strong>
			<img src="/logo-s-11.svg" alt="Logo" />
			<strong>Design</strong>
		</div>
		<div class="header-ctas">
			<a href="https://kurs.sharia.design/me" target="_blank" class="btn-header-cta">
				<span
					><svg
						xmlns="http://www.w3.org/2000/svg"
						width="13"
						height="15"
						fill="none"
						viewBox="0 0 13 15"
					>
						<path
							fill="#565D6C"
							d="M6.5 7.25A3.49 3.49 0 0 1 3 3.75C3 1.836 4.559.25 6.5.25c1.914 0 3.5 1.586 3.5 3.5 0 1.941-1.586 3.5-3.5 3.5ZM5.242 8.563H7.73a4.89 4.89 0 0 1 4.895 4.894c0 .438-.383.793-.82.793H1.168a.794.794 0 0 1-.793-.793c0-2.707 2.16-4.895 4.867-4.895Z"
						/>
					</svg>
				</span>
				<strong>ჩემი ანგარიში</strong>
				<span
					><svg
						xmlns="http://www.w3.org/2000/svg"
						width="14"
						height="13"
						fill="none"
						viewBox="0 0 14 13"
					>
						<path
							fill="#565D6C"
							d="M9.625 1.875A.864.864 0 0 1 8.75 1c0-.465.383-.875.875-.875h1.75A2.626 2.626 0 0 1 14 2.75v7a2.626 2.626 0 0 1-2.625 2.625h-1.75a.864.864 0 0 1-.875-.875c0-.465.383-.875.875-.875h1.75a.881.881 0 0 0 .875-.875v-7a.9.9 0 0 0-.875-.875h-1.75Zm-.219 4.867L5.47 10.461a.671.671 0 0 1-.711.11c-.246-.083-.383-.329-.383-.602V8h-3.5A.864.864 0 0 1 0 7.125v-1.75C0 4.91.383 4.5.875 4.5h3.5V2.531c0-.246.137-.492.383-.601.246-.082.52-.055.71.136l3.938 3.72a.67.67 0 0 1 .219.464.685.685 0 0 1-.219.492Z"
						/>
					</svg>
				</span>
			</a>
			<button class="btn-header-cta">
				<strong>ჩანიშნე ზარი</strong>
				<span>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						width="17"
						height="18"
						fill="none"
						viewBox="0 0 17 18"
					>
						<path
							fill="#2F333A"
							d="M6.875 2.25c.438.25.625.844.438 1.313l-.875 2.312c-.188.438-.594.719-1.032.656l-1.312-.125a8.28 8.28 0 0 0 0 5.219l1.312-.125c.438-.063.844.219 1.032.656l.875 2.281c.187.5 0 1.094-.438 1.344l-1.75 1.094c-.375.25-.875.156-1.188-.188C0 12.47 0 5.563 3.938 1.313 4.25 1 4.75.906 5.125 1.157l1.75 1.094Zm6.844-.188C15.719 3.72 17 6.22 17 9a9.02 9.02 0 0 1-3.281 6.969.754.754 0 0 1-1.063-.125c-.25-.313-.219-.781.094-1.031A7.467 7.467 0 0 0 15.5 9a7.451 7.451 0 0 0-2.75-5.781c-.313-.25-.344-.719-.094-1.063a.78.78 0 0 1 1.063-.094Zm-2.031 2.25C13.094 5.407 14 7.095 14 9a5.937 5.937 0 0 1-2.313 4.719.715.715 0 0 1-1.03-.125.715.715 0 0 1 .124-1.031C11.812 11.719 12.5 10.437 12.5 9c0-1.406-.688-2.688-1.719-3.531a.715.715 0 0 1-.125-1.032c.25-.343.719-.406 1.031-.125Zm-2.032 2.22A2.942 2.942 0 0 1 11 9a2.956 2.956 0 0 1-1.344 2.5.717.717 0 0 1-1.031-.188c-.25-.343-.156-.812.188-1.062C9.219 10 9.5 9.531 9.5 9c0-.5-.281-.969-.688-1.219-.343-.25-.437-.718-.187-1.062a.717.717 0 0 1 1.031-.188Z"
						/>
					</svg>
				</span>
			</button>
		</div>
	</header>

	<div class="intro-content">
		<div class="intro-text">
			<div class="headlines">
				<h1>ისწავლე საიტების შექმნა <br /> მარტივად</h1>
				<h2>
					დიზაინის შექმნიდან დაწყებული, დეველოპმენტი და პროდაქშენი.
					<br />
					All In One/ “ყოვლისმომცველი” კურსით!
				</h2>
			</div>

			<div class="intro-ctas">
				<button>
					<strong>აირჩიე კურსი</strong>
					<span>⬇️</span>
				</button>
				<button>
					<strong>ნახე რას ისწავლი</strong>
					<span>📑</span>
				</button>
			</div>

			<ul class="bullets">
				<li>დიზაინი</li>
				<li>კოდი</li>
				<li>უახლესი ტქნოლოგიები</li>
				<li>ბონუს ვიდეო გაკვეთილები</li>
			</ul>
		</div>

		<div class="intro-video">[video]</div>
	</div>

	<!-- Blurs -->
	<div class="blur blur-green"></div>
	<div class="blur blur-red"></div>
	<div class="blur blur-hue"></div>
	<!-- Blurs -->
</section>

<style>
	.intro {
		padding: 22px 4vw;
		background-color: #ebe4d7;
		background-size: 22px 22px;
		position: relative;
		max-width: 100vw;
		min-height: 80vh;
		overflow: hidden;
	}
	header {
		display: flex;
		align-items: center;
		justify-content: space-between;
	}
	.header-ctas {
		display: flex;
		gap: 2rem;
	}
	.btn-header-cta {
		font-size: 1.5rem;
		padding: 1rem 2rem;
	}
	a.btn-header-cta {
		display: flex;
		align-items: center;
		gap: 1rem;
		color: black;
	}
	.logo {
		display: flex;
		align-items: center;
		justify-content: space-between;
		gap: 11px;
	}
	.intro-content {
		margin-top: 69px;
		display: flex;
		justify-content: space-between;
		gap: 5vw;
	}
	h1 {
		font-size: 5rem;
		font-family: 'GA Dzen';
	}
	h2 {
		font-size: 2rem;
		font-family: 'Contractica Regular';
	}

	/* =============== blurs ============== */
	.blur {
		z-index: 1;
		pointer-events: none;
		user-select: none;
	}
	.blur-green {
		position: absolute;
		width: 1600px;
		height: 1600px;
		border-radius: 1610px;
		background: rgba(36, 240, 0, 0.11);
		animation: move 11s 2s alternate infinite;
		filter: blur(222px);
	}
	.blur-red {
		top: -11%;
		left: -50%;
		position: absolute;
		width: 1600px;
		height: 1600px;
		border-radius: 1610px;
		animation: move 4s alternate infinite;
		background: rgba(237, 0, 0, 0.11);
		filter: blur(222px);
	}
	.blur-hue {
		top: 22vh;
		left: 0%;
		position: absolute;
		width: 1600px;
		height: 1600px;
		border-radius: 1474px;
		background: rgba(0, 88, 240, 0.11);
		animation: move 3s alternate infinite;
		filter: blur(111px);
	}
	@keyframes move {
		0% {
			filter: blur(221px);
			transform: translate3d(10px, -200px, 0);
		}
		100% {
			filter: blur(111px);
			transform: translate3d(550px, 200px, 0);
		}
	}
	/* =============== blurs ============== */
</style>
