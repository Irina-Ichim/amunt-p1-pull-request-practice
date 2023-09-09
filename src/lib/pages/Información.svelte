<script>
    import img from "../../assets/pastores-aleman (1).png"
    import img1 from "../../assets/cachorros.jpg"
    import img2 from "../../assets/alergiasmascotas.jpg"
</script>

<main>
    <div class="card">
        <img src={img} alt="">
        <h2>Qué cambia la ley de bienestar animal para los que tienen mascotas:<br> cursos para todos los dueños de perros y esterilización de gatos</h2>
        <p>El artículo 30 de la ley recoge que “las personas que opten a ser titulares de perros deberán acreditar la realización de un curso de formación para la tenencia de perros con una validez indefinida.</p>
    </div>

    <div class="card">
        <img src={img1} alt="">
        <h2>Cuidados básicos para los animales de compañía (perros y gatos)</h2>
        <p>La tenencia de un animal de compañía en nuestro hogar implica una serie de responsabilidades relativas a su cuidado y atención que debemos conocer. A continuación se detallan una serie de recomendaciones relativas a estos aspectos.</p>
    </div>

    <div class="card">
        <img src={img2} alt="">
        <h2>LA ALERGIA A LAS MASCOTAS Y A OTROS ANIMALES</h2>
        <p>La alergia a los animales se produce por el contacto o la inhalación de pequeñas partículas de la caspa o de la orina que contienen los alérgenos responsables de causar los síntomas de rinoconjuntivitis, asma, urticaria de contacto e, incluso, de anafilaxia.</p>
    </div>
</main>

<style>
    main {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        background-color: #f9f9f9;
        padding: 20px;
    }

    .card {
        background-color: #fff;
        border-radius: 5px;
        box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        margin-bottom: 20px;
        padding: 20px;
        text-align: center;
    }

    img {
        max-width: 100%;
        max-height: 200px;
        margin-bottom: 10px;
    }

    h2 {
        font-size: 1.5rem;
        color: #333;
        margin-top: 10px;
    }

    p {
        font-size: 1rem;
        line-height: 1.4;
        color: #666;
    }
</style>

