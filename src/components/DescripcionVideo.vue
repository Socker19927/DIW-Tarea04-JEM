<template>
<div id="desvid">
    <div id="descripcion">
        <section id="producto-descripcion">
            <h1>Incluido en la compra de este producto</h1>
            <ul>
                <li>World of Warcraft: Shadowlands.</li>
                <li>Wandering Ancient Mount.</li>
                <li>Shadowlands-Level Character Boost. </li>
                <li>Vestments of the Eternal Traveler transmog set quest.  </li>
                <li>Wraithchill cosmetic weapon effect.  </li>
                <li>Eternal Traveler's Hearthstone.  </li>
                <li>30 days of game time.  </li>
                <li>Anima Wyrmling pet.  </li>
                <li>Ensorcelled Everwyrm flying mount.  </li>
            </ul>
        <h2>Requisitos minimos</h2>
            <p> OS	Windows Mac Minimum Requirements Operating System Windows® 7 64-b</p>
            <p>CPU	Intel® Core™ i5-760 or AMD FX™-8100 or better</p>
            <p>RAM	4 GB RAM (8GB for Intel HD Graph</p>
            <p>GPU	NVIDIA® GeForce® GTX 560 2GB or AMD™ Radeon™ HD 7850 2GB or Intel® HD Graphics 530 (45W TDP)</p>
            <p>HDD	100GB</p>
        <h2>Requisitos recomendados</h2>
            <p>OS	Windows® 10 64-bit</p>
            <p>CPU	Intel® Core™ i7-4770 or AMD FX™-8310 or better</p>
            <p>RAM	8 GB</p>
            <p>GPU	NVIDIA® GeForce® GTX 960 4GB or AMD™ Radeon™ R9 280 or better</p>
            <p>HDD	100GB</p>
    
        </section>
    </div>
    <div id="video">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/pU0uaUkYus8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style>
#producto-descripcion {
    margin:1rem;
    text-align: justify;
}
#producto-descripcion h1 h2{
    align-content: center;
    align-items: center;
    justify-content: center;
}
#desvid{
    display: flex;
    flex-direction: row;
}
#descripcion{
    display: flex;
    flex-grow: 1;
    margin-left: 10%;
}
#video{
    margin-right: 10%;
    margin-bottom: 5%;
}
p{
    text-align: justify;
}
</style>