<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Teruntuk kamu :</div>

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
                message: 'Cuma Mau Bilang Sok Semangat🎉🎉🎉'
            };
        },
        props() {
            nama: string
            description: string
            stoc: number
        },
    };
</script>
