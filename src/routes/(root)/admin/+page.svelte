<script lang="ts">
	import SignInButton from 'clerk-sveltekit/client/SignInButton.svelte';
	import SignOutButton from 'clerk-sveltekit/client/SignOutButton.svelte';
	import UserButton from 'clerk-sveltekit/client/UserButton.svelte';
	import UserProfile from 'clerk-sveltekit/client/UserProfile.svelte';
</script>

<UserButton afterSignOutUrl="/" />
