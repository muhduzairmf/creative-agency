<script>
    import Header from '$lib/Header.svelte';
    import '../styles/styles.css'

    let portfolios = [
        1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16
    ]
</script>

<Header />

<section>
    <div class="title">
        <h1>Some of our finest work</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero suscipit eius harum odio, praesentium consectetur, sed laudantium nostrum accusantium voluptatibus veritatis velit quasi blanditiis sapiente veniam et! Deserunt laudantium, nulla voluptatibus amet tempore, tenetur aliquam officiis itaque cum debitis veniam.</p>
    </div>
    <div class="portfolio">
        {#each portfolios as portfolio}
        <div class="item">
            <img src="/portfolio-item{portfolio}.jpg" alt="Portfolio Item 1">
            <div class="action">
                <!-- svelte-ignore a11y-invalid-attribute -->
                <a href="#">Launch</a>
            </div>
        </div>
        {/each}
    </div>
</section>
