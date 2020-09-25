<template>
    <footer>
        <div class="footer">
            <div class="container">
                <hr>
                <div class="flex flex-wrap mt-8">
                    <div class="w-full md:w-1/2">
                        <p class="copy">&copy;   {{ date }}</p>
                    </div>
                    <div class="w-full md:w-1/2">
                        <p>Made by @SMT DEV</p>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        computed: {
            date() {
                return new Date().getFullYear();
            }
        }
    }
</script>
