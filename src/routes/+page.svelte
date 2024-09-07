<script>
	import SupabaseComponent from './supabase.svelte'; // Asegúrate de importar correctamente el componente
	// Recibir la data que viene de `load` en `+page.server.js`
	export let data;
</script>

<h3>Paises en Supabase DB</h3>
<SupabaseComponent {data} />
