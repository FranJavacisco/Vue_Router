<template>
    <div class="px-4 py-5 my-5 text-center">
        <h1 class="display-5 fw-bold text-body-emphasis">Contacto</h1>
        <div class="col-lg-6 mx-auto">
            <form>
                <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
                </div>
                <div class="mb-3">
                    <label for="exampleInputPassword1" class="form-label">Password</label>
                    <input type="password" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="mb-3 form-check">
                    <input type="checkbox" class="form-check-input" id="exampleCheck1">
                    <label class="form-check-label" for="exampleCheck1">Check me out</label>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
        </div>
    </div>

    <div class="text-center mb-3">
        <!-- <button class="btn btn-outline-success fs-1" @click="volverInicio">Volver al Inicio</button> -->
        <router-link 
            class="btn btn-outline-success fs-1"
            to="/"
        >Volver al home</router-link>
    </div>
</template>

<script>


export default {
    // methods: {
    //     volverInicio() {
    //         return this.$router.push('/')
    //     }
    // }
}
</script>