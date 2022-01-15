<script>
    import Header from '$lib/Header.svelte';
    import '../styles/styles.css'

    let services = [
        {
            name: 'Design',
            sourceImage: '/001.png'
        },
        {
            name: 'Development',
            sourceImage: '/002.png'
        },
        {
            name: 'SEO',
            sourceImage: '/003.png'
        },
        {
            name: 'Marketing',
            sourceImage: '/004.png'
        },
        {
            name: 'Mobile Tech',
            sourceImage: '/005.png'
        },
        {
            name: 'Error Fixing',
            sourceImage: '/006.png'
        }
    ]
</script>

<Header />

<section>
    <div class="title">
        <h1>Services that we can help you with</h1>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Alias quis eos, earum doloribus mollitia similique iure eveniet quisquam ratione nemo, dignissimos quasi numquam corporis obcaecati adipisci minima enim quia. Provident, enim accusantium labore harum blanditiis cupiditate quae culpa quo hic eveniet officia explicabo animi magnam quidem facere aliquid repudiandae? Qui!</p>
    </div>
    <div class="services">
        {#each services as service}
        <div class="service">
            <div class="icon">
                <img src={service.sourceImage} alt={service.name}>
            </div>
            <h2>{service.name}</h2>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maiores ab in qui consequatur neque, suscipit molestiae eos corrupti dolores, obcaecati repellat fugit dicta iste repudiandae doloremque asperiores? Eos, error voluptates!
        </div>
        {/each}
    </div>
</section>
