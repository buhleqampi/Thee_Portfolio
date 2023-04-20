<template>
<div>
            <nav class="navbar navbar-expand-lg bg-light sticky">
                <div class="container-fluid">
                    <div class="logo">
                        <img src="https://i.postimg.cc/mZcKDrbT/Screenshot-2023-03-10-135359.png"/>
                    </div>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <router-link to="/"><i class="fa-solid fa-house"></i>Home</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/about"><i class="fa-solid fa-circle-info"></i>About</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/products"><i class="fa-sharp fa-solid fa-books"></i>Products</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/admin"><i class="fa-solid fa-user-plus"></i>Admin</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/signIn"><i class="fa-solid fa-right-to-bracket"></i>Sign In</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/signUp"><i class="fa-solid fa-user-plus"></i>Sign Up</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/contact"><i class="fa-solid fa-phone"></i>Contact Us</router-link>
                    </li>
                    <li class="nav-item" id="icon">
                        <router-link to="/cart"><i class="fa-solid fa-cart-shopping"></i></router-link> 
                    </li>
                    <li class="nav-item" id="icon">
                        <router-link to="/product"><i class="fa-solid fa-book"></i></router-link> 
                    </li>
                    <li class="nav-item" id="icon">
                        <router-link to="/profile"><i class="fa-solid fa-user"></i> </router-link> 
                    </li>
                    </ul>
                </div>
                </div>
            </nav>
        </div>
</template>
<script>
export default {
    name: "NavbarComp"
}

</script>