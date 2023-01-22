<template>
  <div class="detail">
    
    <div class="img-container">
    </div>
    
    <img src="https://i.ibb.co/51LLKTK/kaiju-no-8.jpg" alt="kaiju-no-8" border="0" class="poster"/>

    <div class="desc-container">

        <h1 class="manga-header">Kaiju No-8</h1>

        <div class="manga-tag">
            <span>Shouene</span>
            <span>Action</span>
            <span>Sci-Fi</span>
        </div>

        <div class="other-detail">
            <p class="manga-author">
                Author - <span class="special-text">Naoya Matsumoto</span>
            </p>

            <p class="manga-type">
                Type - <span class="special-text">Ongoing</span>
            </p>

            <p class="manga-chp">
                Chapters - <span class="special-text">77</span>
            </p>
        </div>

        <p class="desc-text">
when they were children, childhood friends Kafka Hibino and Mina Ashiro both vowed to become members of the Defense Force. Mina has become famous as commander of the Defense Force's Third Unit, but Kafka has failed...
        </p>
    </div>


  </div>
</template>

<script>
export default {

}
</script>

<style>

    .detail{
        width: 100%;
    }

    .img-container{
        width: 100%;
        height: 500px;
        background-image: url("@/assets/kaiju_no-8.jpg");
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        filter: blur(8px);

        position: relative;

        overflow: hidden;
    }

    .poster{
        width: 300px;
        height: 450px;
        border: 20px solid #fff;
        border-radius: 10px;

        margin: 0;
        padding: 0;
       
        z-index: 2;

        transform: rotate(10deg);

        position: absolute;
        top: 50px;
        right: 100px;
    }

    .desc-container{
        width: 400px;
        text-align: left;

        background: rgba(255, 255, 255, 0.2);
        border-radius: 16px;
        box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
        backdrop-filter: blur(5px);
        -webkit-backdrop-filter: blur(5px);
        border: 1px solid rgba(255, 255, 255, 0.3);

        color: #000;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-weight: 600;

        position: absolute;
        top: 15%;
        left: 100px;

        padding: 10px;
        margin: 10px;
    }

    .manga-header{
        font-size: 45px;
        color: #000;
    }

    .manga-tag span{
        margin: 3px;
        padding: 5px;
        background: #000;
        color: #fff;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        font-weight: 900;
        border-radius: 10px;
    }

    .other-detail > p{
        margin-left: 8px;
    }

    .special-text{
        color: #fff;
        font-weight: 600;
    }

</style>