<template>
    <div class="flex justify-center items-center my-auto main bg-cream">
        <div class="relative mt-20 mb-20 bg-white rounded-xl flex card" style="width: 500px; height: 384px;">
            <div class="">
                <img src="./..\assets\images\image-product-desktop.jpg" class="w-60 h-96 rounded-l-xl image" alt="">
            </div>
            <div class="ml-5 mr-4 mt-8 text-left flex flex-col w-52 content">
                <h6 class="font-Montserrat text-xs font-medium leading-4 tracking-widest text-dark-grayish-blue" style="letter-spacing: 5px;">PERFUME</h6>
                <h2 class="mt-3 font-Fraunces font-bold text-3xl leading-8 text-very-dark-blue name">Gabrielle Essence Eau De
                    Parfum</h2>
                <p class="mt-3 text-sm font-Montserrat font-medium text-dark-grayish-blue para">A floral, solar and voluptuous
                    interpretation composed by Olivier Polge,
                    Perfumer-Creator for the House of CHANEL.</p>
                <div class="mt-3 flex justify-evenly items-center">
                    <h2 class="font-Fraunces font-bold text-2xl text-dark-cyan">$149.99</h2>
                    <h5 class="font-Montserrat font-medium text-sm line-through text-dark-grayish-blue">$169.99</h5>
                </div>
                <button class="flex justify-center gap-2 mt-3 text-black border py-2 px-6 rounded-lg text-sm font-Montserrat font-bold bg-dark-cyan text-white hover:bg-deep-aquamarine button">
                    <img src="./..\assets\images\icon-cart.svg" alt="">
                    Add to Cart
                </button>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* Mobile */
@media only screen and (max-width: 480px) {
    .main{
        background-color: white;
        margin-top: 20px;
        margin-bottom: 20px;
    }
    .card {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin-left: 50px;
        margin-top: 100px;
        width: 300px;
        height: 611px;
    }
    .image {
        width: 400px;
        height: 300px;
        border-radius: 15px 15px 0 0;
    }
    .content {
        margin-top: 20px;
        width: 400px;
        margin-left: 50px;
    }
    .name{
        width: 300px;
    }
    .para {
        width: 350px;
    }
    .button{
        margin-right: 20px;
    }
}
</style>