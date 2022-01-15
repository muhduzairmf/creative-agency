<script>
    import '../styles/styles.css'

    let toggle = 'toggle';
    let navigation = 'navigation'

    const toggleMenu = () => {
        if (toggle === 'toggle' && navigation === 'navigation') {
            toggle = 'toggle active';
            navigation = 'navigation active'
        } else {
            toggle = 'toggle';
            navigation = 'navigation';
        }
    }
</script>

<svelte:head>
    <title>Creative Agency</title>
</svelte:head>

<header>
    <div class="logo">Creative Agency</div>
    <div class="{toggle}" on:click="{toggleMenu}"></div>
    <div class="{navigation}">
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/services">Services</a></li>
            <li><a href="/work">Work</a></li>
            <li><a href="/contact">Contact</a></li>
        </ul>
        <div class="social-bar">
            <ul>
                <li><a href="https://facebook.com" target="_blank">
                    <img src="/facebook.png"  alt="Facebook">
                </a></li>
                <li><a href="https://twitter.com">
                <img src="/twitter.png" alt="Twitter"></a></li>
                <li><a href="https://instagram.com">
                <img src="/instagram.png" alt="Instagram"></a></li>
            </ul>
            <a href="mailto:you@email.com" class="email-icon">
                <img src="/email.png" alt="Email">
            </a>
        </div>
    </div>
</header>
