<script>
export default {
  name: 'TopHome',
}
</script>

<template>
    <div id="USPDiv">
        <div class="USPItem">
            <div>
                <img width="60px" src="./icons/Performant.png"/>
            </div>
            <div>
                <h3>Performant</h3>
            </div>
            <div>
                <p>Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.</p>
            </div>
        </div>
        <div class="USPItem">
            <div>
                <img width="60px" src="./icons/Approachable.png"/>
            </div>
            <div>
                <h3>Approachable</h3>
            </div>
            <div>
                <p>Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.</p>
            </div>
        </div>
        <div class="USPItem">
            <div>
                <img src="./icons/Versatle.png"/>
            </div>
            <div>
                <h3>Versatile</h3>
            </div>
            <div>
                <p>A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.</p>
            </div>
        </div>
    </div>

</template>

<style>


    #USPDiv {
        background-color: rgba(57, 185, 131, 1);
        display: grid;
        padding: 5em;
        grid-template-columns: repeat(3,1fr);
        align-items: center;
        justify-items: center;
    }

    .USPItem {
        display: flex;
        flex-direction: column;
        align-items: center;

        max-width: 127px;
    }

</style>
