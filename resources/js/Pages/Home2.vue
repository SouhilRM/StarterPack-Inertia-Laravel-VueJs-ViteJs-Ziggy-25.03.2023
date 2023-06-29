<template>
    <div>
        <h1>
            HOME NUMBER 222
        </h1>
    </div>
    <div>
        <Link :href="route('route_1')">
            vers home 111
        </Link>
    </div>
</template>

<script setup>
    import { Link } from '@inertiajs/vue3'
</script>