<script lang="ts">
	export let title: string;
	export let description: string;
	export let url: string;
	export let img_url: string;
</script>

<a target="_blank" class="text-right flex gap-3" href={url}>
	<img class="w-44 aspect-video" src={img_url} alt={title} />
	<div class="max-w-[300px] md:max-w-md">
		<h4 class="font-bold">{title}</h4>
		<p>{description}</p>
	</div>
</a>
