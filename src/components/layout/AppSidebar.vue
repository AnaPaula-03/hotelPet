<script setup>

import { RouterLink } from 'vue-router';

</script>

<template>

    <nav >
        <div class="flex-nav-pills gap-1">

            <RouterLink to="/pets">

                <i class="cloud-showers"></i>

                Novo pet 
            </RouterLink>

        </div>
    </nav>

</template>