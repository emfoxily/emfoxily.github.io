<template>
    <nav>
        <ul>

            <li>
                About
            </li>

            <li>
                Portfolio
            </li>

            <li>
                <img src="../assets/logo.png" />
            </li>

            <li>
                Socials
            </li>

            <li>
                Contact
            </li>
        </ul>
    </nav>
</template>

<script>
    export default {
        name: 'NavBar'
    }
</script>

<style scoped>

    nav {
        margin: 1em 0 0;
        background-color: rgb(252, 252, 252);
        /* width: 100vw; */
        padding: .5em 0;
        margin-bottom: 1em;
        border-radius: .65em;
        font-family: 'Open Sans', sans-serif;
        font-size: .7em;
        font-weight: 600;
        text-transform: uppercase;
        color: rgb(182, 182, 182);
    }

    nav ul {
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-around;
        /* width: 75vw; */
        padding: 0;
    }

    nav li {
        display: flex;
        flex: 1;
        justify-content: center;
        align-items: center;
        list-style: none;
    }

    nav li img {
        width: 3vw;
    }

</style>