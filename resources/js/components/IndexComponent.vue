<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Disclaimer : {{ nama }}</div>

                    <div class="card-body">
                        {{ message }}
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            nama: 'Rikho Septian',
            message: 'Selamat anda sudah berhasil menjalankan laravel + vue.',
        };
    },
};
</script>