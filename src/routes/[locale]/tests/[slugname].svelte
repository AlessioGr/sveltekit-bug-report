<script context="module" lang="ts">
    export const prerender = true;


    export async function load({  params , url, fetch }) {

        const locale = params.locale;
        const slug = params.slugname;
        console.log("Slug: " + slug);
        console.log("URL: ");
        console.log(url);
        return { props: { } };
    }
</script>

<script lang="ts">
    import { goto } from "$app/navigation"


    //console.log(tests);

</script>


<section>
    <h1>
        Buggy site
    </h1>
</section>

