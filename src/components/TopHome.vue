<script>
export default {
  name: 'TopHome',
}
</script>

<template>
    <div id="TopHomeDiv">
        <div>
            <img src="./icons/Vue_logo.png"/>
        </div>
        <div>
            <h1>Welcome to Vue.js</h1>
        </div>
        <div>
            <p>Become a coding ninja with the fastest-<br>growing JavaScript framework</p>
        </div>
        <div>
            <button type="button" >Awesome!</button>
        </div>
    </div>
</template>

<style>
    
    #TopHomeDiv {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    h1 {
        font-family: Inter;
        font-size: 50px;
        font-weight: 800;
        line-height: 95px;
        letter-spacing: -0.02em;
        text-align: center;
    }

    p {
        font-family: Inter;
        font-size: 14px;
        font-weight: 800;
        line-height: 20px;
        letter-spacing: -0.02em;
        text-align: center;

        margin-bottom: 27px;
    }

    button {
        background: rgba(52, 73, 94, 1);
        width: 121px;
        height: 31px;

        font-family: Inter;
        font-size: 14px;
        font-weight: 800;
        line-height: 20px;
        letter-spacing: -0.02em;
        text-align: center;
        color: rgba(255, 255, 255, 1);

        border-radius: 13px;

        margin-bottom: 71px;
    }
</style>