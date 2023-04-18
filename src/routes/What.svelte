<script>
    import Button from "$lib/button.svelte";

</script>
<div class="container grid">
    <div class="what">
        <h3>What We Do</h3>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. A deserunt neque tempore recusandae animi soluta quasi? Asperiores rem dolore eaque vel, porro, soluta unde debitis aliquam laboriosam. Repellat explicabo, maiores!
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Omnis optio neque consectetur consequatur magni in nisi, natus beatae quidem quam odit commodi ducimus totam eum, alias, adipisci nesciunt voluptate. Voluptatum.
        </p>
        <Button class="secondary" id="a-button" size="medium">Call to Action >></Button>
    </div>
    <div class="contact">
        <h3>Contact Us</h3>
        <p>Smart Dev Solution Co.,Ltd.</p>
        <p>261/25 Moo 4, Rangsit, Thanyaburi,</p>
        <p>Pathumtani, Thailand, 12110</p>
        <p>P: (+662) 026-3723</p>
        <p>E: <a href="mailto:rachaphol.p@smartdevsolution.com">rachaphol.p@smartdevsolution.com</a> </p>
    </div>
</div>

<style>
    .grid{
        display: grid;
        grid-template-columns: repeat(12, 1fr);
        gap: 2em;
    }
    .what{
        grid-column: span 8;
    }
    .contact{
        grid-column: span 4;
    }
    h3{
        padding-bottom: 0.5em;
        margin-bottom: 0.5em;
        font-size: 2em;
        font-weight: 500;
        border-bottom: 1px solid #ddd;
    }
    a{
        text-decoration: none;
        color: var(--primary-color);
    }
    a:hover{
        text-decoration: underline;
    }
</style>