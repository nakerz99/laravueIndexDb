<template>
    <div class="content">
        <div class="container">
            <div class="flex flex-wrap -mx-3">
                <div class="w-full md:w-3/3 px-3">
                    <div class="page-card">
                        <CRUD />
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import CRUD from '../Components/CRUD';

    export default {
        components: { CRUD },
    }
</script>
