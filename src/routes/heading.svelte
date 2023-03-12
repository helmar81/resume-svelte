<script lang="ts">
	import { enhance } from '$app/forms'
	import { getUser } from '@lucia-auth/sveltekit/client'
	import { AppBar, LightSwitch } from '@skeletonlabs/skeleton'

	const user = getUser()
</script>

<!-- svelte-ignore a11y-missing-content -->
<AppBar>
	<svelte:fragment slot="lead">
		<a href="/"></a>
	

		<LightSwitch />
	</svelte:fragment>
</AppBar>
