<script>
	import Project from '$lib/Project.svelte';
</script>

<div class="m-5 gap-5 md:gap-10 flex flex-col md:flex-row items-center md:items-start">
	<div class="flex flex-col items-center md:items-start gap-5 md:gap-3">
		<h2 class="m-3 md:m-0 text-2xl md:text-2xl font-bold">يزن حمزه</h2>

		<img width="512" height="683" class="w-64 md:w-52 font-bold" src="yzn-512-683.webp" alt="صورة ليزن" />

		<p class="text-lg">متخرج من الثانوي</p>
        <a href="https://github.com/yzn-h">
            <!-- width="98" height="96" -->
			<svg
                viewBox="0 0 98 96"
                width="40px"
                style=""
				class="fill-black dark:fill-white"
				xmlns="http://www.w3.org/2000/svg"
				><path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M48.854 0C21.839 0 0 22 0 49.217c0 21.756 13.993 40.172 33.405 46.69 2.427.49 3.316-1.059 3.316-2.362 0-1.141-.08-5.052-.08-9.127-13.59 2.934-16.42-5.867-16.42-5.867-2.184-5.704-5.42-7.17-5.42-7.17-4.448-3.015.324-3.015.324-3.015 4.934.326 7.523 5.052 7.523 5.052 4.367 7.496 11.404 5.378 14.235 4.074.404-3.178 1.699-5.378 3.074-6.6-10.839-1.141-22.243-5.378-22.243-24.283 0-5.378 1.94-9.778 5.014-13.2-.485-1.222-2.184-6.275.486-13.038 0 0 4.125-1.304 13.426 5.052a46.97 46.97 0 0 1 12.214-1.63c4.125 0 8.33.571 12.213 1.63 9.302-6.356 13.427-5.052 13.427-5.052 2.67 6.763.97 11.816.485 13.038 3.155 3.422 5.015 7.822 5.015 13.2 0 18.905-11.404 23.06-22.324 24.283 1.78 1.548 3.316 4.481 3.316 9.126 0 6.6-.08 11.897-.08 13.526 0 1.304.89 2.853 3.316 2.364 19.412-6.52 33.405-24.935 33.405-46.691C97.707 22 75.788 0 48.854 0z"
				/>
			</svg>
		</a>
	</div>
	<div class="flex flex-col items-center gap-5 md:gap-3 md:items-start">
		<div class="md:hidden border w-28 border-gray-500 dark:border-gray-300" />
		<h3 class="text-2xl font-bold">مشاريع</h3>
		<Project
		title="3D watch"
		description="اول مجسم ثلاثي اللابعاد اصممه استخدم threejs لاضافته للموقع"
		url="/3d_watch"
		img_url="3d_watch.webp"
	/>
		<Project
			title="Protect The Root"
			description="مشاركتي في مسابقة Global Game Jam 2023"
			url="https://gdyzn.itch.io/protect-the-root"
			img_url="protect-the-root.webp"
		/>
		<Project
			title="Traffic Brake"
			description="مشاركتي في مسابقة CpES GAME JAM 2 مع @Sopdevv"
			url="https://sopdev.itch.io/traffic-brake"
			img_url="traffic-brake.webp"
		/>
	</div>
</div>
