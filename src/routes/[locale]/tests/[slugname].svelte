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


</script>


<section>
    <h1>
        Buggy site
    </h1>
</section>

