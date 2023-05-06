<template>
    <nav class="navbar navbar-expand-lg bg-dark link">
        <div class="container-fluid">
            <a class="navbar-brand text-white logo-font" href="#">T-Shop</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active text-white" aria-current="page" href="#">All T-Shirts</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link text-white" href="#">About</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link text-white" href="#">Choose custom Print</a>
                    </li>
                </ul>
                <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Search an Item" aria-label="Search">
                    <button class="btn btn-outline-success text-white" type="submit">Login</button>
                </form>
            </div>
        </div>
    </nav>
</template>

<script>
    export default {
        name: 'NavBarComponent',
        data() {
            return {
                testVariable: 'Test'
            }
        }
    }

</script>

<style scoped>
    .logo-font {
        font-family: 'Cormorant', serif;
        font-style: italic;
        font-size: x-large;
    }
</style>