<script>

</script>

<section id="About" class="flex flex-col justify-center py-4 pl-4 pr-6">
    <div class="section-header flex flex-row items-center py-4">
        <h2 class="font-roboto font-extrabold text-3xl">Who Am I</h2>
    </div>
    <div class="article-container flex flex-col md:flex-row justify-center items-center">
        <article class="text-left text-lg">
            <p class="font-roboto mb-3">
                Hi! I'm Jeremias Bulanadi, although most people call me Jay.
                I've been playing with computers since 2002. I took up coding as a
                hobby ; And then soon thereafter, a possible career.
            </p>
            <p class="font-roboto mb-3">
                I've also taken an inspiration for arts and design eversince
                I was exposed to video games and animated shows. Now anytime
                I make anything, I've always had the urge to flair things up.
            </p> 
            <p class="font-roboto">
                My recent escapades involved the use and learning of:
            </p>
            <ul class="font-readex text-xs mt-6 ml-5">
                <li>
                    Typescript
                </li>
                <li>
                    MySQL
                </li>
                <li>
                    Node.js
                </li>
                <li>
                    Svelte
                </li>
                <li>
                    Vue.js
                </li>
                <li>
                    React
                </li>
                <li>
                    Golang
                </li>
                <li>
                    C#
                </li>
                <li>
                    Java
                </li>
            </ul>
        </article>
        <div class="image-container flex justify-center items-center m-9 right-5 sm:right-0 sm:pr-0 text-white font-lato font-bold">
            <div class="image-holder flex justify-center items-center">
                <img src="./jaydb.png" alt="Jeremias Bulanadi" class="transition">
            </div>
        </div>
    </div>
</section>

<style>
    section {
        padding-top: 15vw;
        margin-bottom: 15vw;
    }
    p {
        max-width: 500px;
        margin-right: 10px;
    }

    ul {
        line-height: 1.75rem;

        columns: 3;
        -webkit-columns: 3;
        -moz-columns: 3;
    }

    .article-container {
        margin: 1rem 0;
    }
    .section-header {
        width: 100%;
    }

    .section-header > h2 {
        min-width: 5em;
    }

    .section-header::after{
        content: "";
        margin: 0 auto;
        width: 75%;
        height: 1px;
        background-color: #D1D5DB;
    }
    .image-holder {
        width: 100%;
        height: 100%;
        border-radius: 1.5%;
    }

    .image-holder > img {
        filter: grayscale(1) brightness(1.25);
        border-radius: 1.5%;
    }

    .image-holder > img:hover {
        filter: none;
        transform: translateY(-10px);
    }

   .image-container {
        position: relative;
        z-index: 0;

        min-width: 250px;
        min-height: 250px;

        border-radius: 1.5%;

        width: 250px;
        height: 250px;
   }

   .image-container::after {
        content: "";
        display: block;
        z-index: -1;
        position: absolute;
        top: 15px;
        left: 15px;
        border: 2px solid #9CA3AF;
        border-radius: 1.5%;
        width: 100%;
        height: 100%;
   }
</style>