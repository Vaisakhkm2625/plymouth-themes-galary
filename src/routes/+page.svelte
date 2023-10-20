<script>
	let images = [
		// part 1
		{
			name: 'Abstract Rings',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/1.gif'
		},
		{
			name: 'Abstract Rings Alt',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/2.gif'
		},
		{
			name: 'Alienware',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/3.gif'
		},
		{
			name: 'Angular',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/4.gif'
		},
		{
			name: 'Angular Alt',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/5.gif'
		},
		{
			name: 'Black HUD',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/6.gif'
		},
		{
			name: 'Blockchain',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/7.gif'
		},
		{
			name: 'Circle',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/8.gif'
		},
		{
			name: 'Circle Alt',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/9.gif'
		},
		{
			name: 'Circle Flow',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/10.gif'
		},
		{
			name: 'Circle HUD',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/11.gif'
		},
		{
			name: 'Circuit',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/12.gif'
		},
		{
			name: 'Colorful',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/13.gif'
		},
		{
			name: 'Colorful Loop',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/14.gif'
		},
		{
			name: 'Colorful Sliced',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/15.gif'
		},
		{
			name: 'Connect',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/16.gif'
		},
		{
			name: 'Cross HUD',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/17.gif'
		},
		{
			name: 'Cubes',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/18.gif'
		},
		{
			name: 'Cuts',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/19.gif'
		},
		{
			name: 'Cuts Alt',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/20.gif'
		},

		// part 2

		{
			name: 'Cyanide',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/21.gif'
		},
		{
			name: 'Cybernetic',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/22.gif'
		},
		{
			name: 'Dark Planet',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/23.gif'
		},
		{
			name: 'Darth Vader',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/24.gif'
		},
		{
			name: 'Deus Ex',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/25.gif'
		},
		{
			name: 'DNA',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/26.gif'
		},
		{
			name: 'Double',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/27.gif'
		},
		{
			name: 'Dragon',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/28.gif'
		},
		{
			name: 'Flame',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/29.gif'
		},
		{
			name: 'Glitch',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/30.gif'
		},
		{
			name: 'Glow',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/31.gif'
		},
		{
			name: 'Green Blocks',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/32.gif'
		},
		{
			name: 'Green Loader',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/33.gif'
		},
		{
			name: 'Hexagon',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/34.gif'
		},
		{
			name: 'Hexagon 2',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/35.gif'
		},
		{
			name: 'Hexagon Alt',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/36.gif'
		},
		{
			name: 'Hexagon Dots',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/37.gif'
		},
		{
			name: 'Hexagon Dots Alt',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/38.gif'
		},
		{
			name: 'Hexagon HUD',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/39.gif'
		},
		{
			name: 'Hexagon RED',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/40.gif'
		},

		// part 3

		{
			name: 'Hexa Retro',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/41.gif'
		},
		{
			name: 'Hud',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/42.gif'
		},
		{
			name: 'Hud 2',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/43.gif'
		},
		{
			name: 'Hud 3',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/44.gif'
		},
		{
			name: 'Hud Space',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/45.gif'
		},
		{
			name: 'IBM',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/46.gif'
		},
		{
			name: 'Infinite Seal',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/47.gif'
		},
		{
			name: 'Ironman',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/48.gif'
		},
		{
			name: 'Liquid',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/49.gif'
		},
		{
			name: 'Loader',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/50.gif'
		},
		{
			name: 'Loader 2',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/51.gif'
		},
		{
			name: 'Loader Alt',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/52.gif'
		},
		{
			name: 'Lone',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/53.gif'
		},
		{
			name: 'Metal Ball',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/54.gif'
		},
		{
			name: 'Motion',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/55.gif'
		},
		{
			name: 'Optimus',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/56.gif'
		},
		{
			name: 'Owl',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/57.gif'
		},
		{
			name: 'Pie',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/58.gif'
		},
		{
			name: 'Pixels',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/59.gif'
		},
		{
			name: 'Polaroid',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/60.gif'
		},

		//part 4

		{
			name: 'Red Loader',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/61.gif'
		},
		{
			name: 'Rings',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/62.gif'
		},
		{
			name: 'Rings 2',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/63.gif'
		},
		{
			name: 'Rog',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/64.gif'
		},
		{
			name: 'Rog 2',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/65.gif'
		},
		{
			name: 'Seal',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/66.gif'
		},
		{
			name: 'Seal 2',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/67.gif'
		},
		{
			name: 'Seal 3',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/68.gif'
		},
		{
			name: 'Sliced',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/69.gif'
		},
		{
			name: 'Sphere',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/70.gif'
		},
		{
			name: 'Spin',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/71.gif'
		},
		{
			name: 'Spinner Alt',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/72.gif'
		},
		{
			name: 'Splash',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/73.gif'
		},
		{
			name: 'Square',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/74.gif'
		},
		{
			name: 'Square Hud',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/75.gif'
		},
		{
			name: 'Target',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/76.gif'
		},
		{
			name: 'Target 2',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/77.gif'
		},
		{
			name: 'Tech A',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/78.gif'
		},
		{
			name: 'Tech B',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/79.gif'
		},
		{
			name: 'Unrap',
			link: 'https://raw.githubusercontent.com/adi1090x/files/master/plymouth-themes/previews/80.gif'
		}
	];
</script>

<h2>
	A Preview for plymouth-themes from
	<a href="https://github.com/adi1090x/plymouth-themes"> adi1090x/plymouth-themes</a>
</h2>

adi1090x/plymouth-themes is a repo of increadible colloeciton of themes made by Aditya
Shakya(adi1090x, creator of arch craft)

<h4>click on each to view in fullscreen</h4>

{#each images as image}
	<div class="responsive">
		<div class="gallery">
			<a target="_blank" href="img_5terre.jpg">
				<img src={image.link} alt={image.name} width="600" height="400" />
			</a>
			<div class="desc">{image.name}</div>
		</div>
	</div>
{/each}

<div class="clearfix" />

<style>
	div.gallery {
		border: 1px solid #ccc;
	}

	div.gallery:hover {
		border: 1px solid #777;
	}

	div.gallery img {
		width: 100%;
		height: auto;
	}

	div.desc {
		padding: 15px;
		text-align: center;
	}

	* {
		box-sizing: border-box;
	}

	.responsive {
		padding: 0 6px;
		float: left;
		width: 24.99999%;
	}

	@media only screen and (max-width: 700px) {
		.responsive {
			width: 49.99999%;
			margin: 6px 0;
		}
	}

	@media only screen and (max-width: 500px) {
		.responsive {
			width: 100%;
		}
	}

	.clearfix:after {
		content: '';
		display: table;
		clear: both;
	}
</style>
