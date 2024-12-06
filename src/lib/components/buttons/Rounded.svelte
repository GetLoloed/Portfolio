<script lang="ts">
	export let href: string;
	export let text: string;
</script>

<a {href}>{text}</a>

<style lang="scss">
	a {
		display: flex;
		width: 237px;
		padding: 19px 0px;
		justify-content: center;
		align-items: center;
		text-align: center;
		border-radius: var(--RADIUS-RAD---60, 60px);
		border: 1px solid var(--COULEURS-BLANC, #f5f5f5);
	}
</style>
