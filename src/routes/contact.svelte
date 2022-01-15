<script>
    import Header from '$lib/Header.svelte';
    import '../styles/styles.css'
</script>

<Header />

<section>
    <div class="title">
        <h1>Contact Us</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam facere deserunt accusamus tempore minima perferendis. Delectus officia necessitatibus officiis cum expedita reprehenderit eveniet, excepturi laudantium cumque quia explicabo et, nemo ratione maxime, enim autem animi?</p>
    </div>
    <div class="contact">
        <div class="contact-form">
            <form>
                <div class="row">
                    <div class="input50">
                        <input type="text" placeholder="First Name">
                    </div>
                    <div class="input50">
                        <input type="text" placeholder="Last Name">
                    </div>
                </div>
                <div class="row">
                    <div class="input50">
                        <input type="text" placeholder="Email">
                    </div>
                    <div class="input50">
                        <input type="text" placeholder="Subject">
                    </div>
                </div>
                <div class="row">
                    <div class="input100">
                        <textarea placeholder="Message"></textarea>
                    </div>
                </div>
                <div class="row">
                    <div class="input100">
                        <input type="submit" value="Send">
                    </div>
                </div>
            </form>
        </div>
        <div class="contact-info">
            <div class="info-box">
                <img src="/address.png" class="contact-icon" alt="Contact">
                <div class="details">
                    <h4>Address</h4>
                    <p>123, Nice Premiere Street, Huddlesburgh City</p>
                </div>
            </div>
            <div class="info-box">
                <img src="/email.png" class="contact-icon" alt="Contact">
                <div class="details">
                    <h4>Email</h4>
                    <a href="mailto:anyone@email.com">anyone@email.com</a>
                    <a href="mailto:anybody@email.com">anybody@email.com</a>
                </div>
            </div>
            <div class="info-box">
                <img src="/address.png" class="contact-icon" alt="Contact">
                <div class="details">
                    <h4>Call</h4>
                    <a href="tel:+1123450987">+11 2345 0987</a>
                    <a href="tel:+1178905432">+11 7890 5432</a>
                </div>
            </div>
        </div>
    </div>
</section>
