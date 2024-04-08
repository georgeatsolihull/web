<script lang="ts">
    import '../app.scss';
</script>

<div class="gweb-banner"/>

<main class="gweb-container">
    <slot />
</main>

<footer class="gweb-footer footer-sticky">
    <div class="content footer-text has-text-centered">
        <div class="gweb-text-layout">
            <p style="font-size: 15px;"><b>© George Hotten 2024</b></p>
            <p style="font-size: 15px;" class="gweb-link-white">
                <a href="https://github.com/georgeatsolihull/web" target="_blank" rel="noopener">source</a> &middot;
                <a href="https://ghott.me" target="_blank" rel="noopener">personal site</a> &middot;
                <a href="https://github.com/georgeatsolihull/" target="_blank" rel="noopener">github</a>
            </p>
        </div>
        <div class="footer-colours">
            <div class="footer-colour" id="aston"></div>
            <div class="footer-colour" id="solihull"></div>
            <div class="footer-colour" id="george"></div>
            <div class="footer-colour" id="hotten"></div>
        </div>
    </div>
</footer>
