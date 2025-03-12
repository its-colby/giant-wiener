<script lang="ts">
    // You can adjust the image path to your actual image location
    const imagePath = "/zach-huang.HEIC";
</script>

<main>
    <img src={imagePath} alt="Centered responsive image" />
</main>

<style>
    :global(body) {
        margin: 0;
        background-color: black;
    }

    main {
        width: 100%;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: black;
    }

    img {
        max-width: 100%;
        max-height: 100vh;
        object-fit: contain;
    }
</style>