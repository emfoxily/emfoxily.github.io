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
                logo
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
        background-color: rgb(252, 252, 252);
        width: 100vw;
        padding: 1em 0;
        margin-bottom: 1em;
    }

    nav ul {
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-around;
        width: 75vw;
    }

    nav li {
        display: flex;
        flex: 1;
        justify-content: center;
        align-items: center;
        list-style: none;
    }

</style>