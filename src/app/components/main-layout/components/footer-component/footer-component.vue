<template>
    <div id="footer">
        <div class="section">
            <div class="first-section-logos">
                <GirlsAndBannerLogoComponent />
            </div>
            <div class="first-section-links">
                <ul class="links-list">
                    <li>
                        <router-link to="/association">Association</router-link>
                    </li>
                    <li>
                        <router-link to="/contact">Contact</router-link>
                    </li>
                    <li>
                        <router-link to="/shows">Concerts</router-link>
                    </li>
                    <li>
                        <router-link to="/classes">Master class</router-link>
                    </li>
                </ul>
            </div>
        </div>
        <div class="section">
            <div class="footer-contact">
                <div class="footer-club-location">
                    <div class="pin-icon"></div>
                    <p>
                        Le Club <br>
                        23 rue Voltaire <br>
                        Fontainebleau <br>
                    </p>
                </div>
                <div class="footer-email-contact">
                    <div class="mail-icon"></div>
                    <a href="mailto:lestatiesjazzy@gmail.com" title="Envoyer un email à lestatiesjazzy@gmail.com">
                        lestatiesjazzy@gmail.com
                    </a>
                </div>
            </div>
        </div>
        <div class="section">
            <div class="footer-social-media">
                <div class="footer-instagram">
                    <img src="@/assets/social-media/instagram.png" alt="Logo Instagram">
                    <a 
                    href="https://www.instagram.com/lestatiesjazzy/?hl=fr"
                    target="_blank"
                    title="Redirection vers le compte instagram"
                    >
                        @lestatiesjazzy
                    </a>
                </div>
                <div class="footer-facebook">
                    <img src="@/assets/social-media/facebook.png" alt="Logo Facebook">
                    <a 
                    href="https://www.facebook.com/lestatiesjazzy"
                    target="_blank"
                    title="Redirection vers le compte instagram"
                    >
                        Les Taties Jazzy
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import GirlsAndBannerLogoComponent from '@/app/shared/components/girls-and-banner-logo-component/girls-and-banner-logo-component.vue'

    export default {
        name: 'FooterComponent',
        components: {
            GirlsAndBannerLogoComponent
        }
    }
</script>
<style lang="scss">
   @import "footer-component.scss";
</style>
