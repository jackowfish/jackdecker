<script>
	import 'bulma/css/bulma.css'
	import '@fortawesome/fontawesome-free/css/all.css'
	import Button from 'svelma/src/components/Button.svelte'
	  
	let name = 'world';
</script>

<svelte:head>
	
	<!-- The core Firebase JS SDK is always required and must be listed first -->
	<script src="/__/firebase/8.1.1/firebase-app.js"></script>

	<!-- TODO: Add SDKs for Firebase products that you want to use
		https://firebase.google.com/docs/web/setup#available-libraries -->
	<script src="/__/firebase/8.1.1/firebase-analytics.js"></script>

	<!-- Initialize Firebase -->
	<script src="/__/firebase/init.js"></script>
</svelte:head>

<h1>Hello {name}!</h1>