<template>
    <div>
        <h1>
            HOME NUMBER 111
        </h1>
    </div>
    <div>
        <Link :href="route('route_2')">
            vers home 222
        </Link>
    </div>
</template>

<script setup>
    import { Link } from '@inertiajs/vue3'
</script>