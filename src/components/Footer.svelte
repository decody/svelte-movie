<footer>
    <address>
        <a href="https://github.com/decody/svelte-movie">Github repo.</a>
    </address>
    <div>
        <a href="http://decody.github.io">
            &copy;{new Date().getFullYear()} Decody.
        </a>
    </div>
</footer>

<style lang="scss">
    footer {
        padding: 70px;
        text-align: center;
        address {
            display: block;
        }
        a {
            color: $color--white-10;
            text-decoration: none;
            &:hover {
                color: $color--white-50;
            }
        }
    }
</style>