<script>
    import media from '../medias/BW-SSaver.mp4'
</script>

<video autoplay muted loop id="backgroundScreensaver">
    <source src={media} type="video/mp4" />
</video>

<style>
    #backgroundScreensaver {
        position: fixed;
        right: 0;
        bottom: 0;
        min-width: 100%;
        min-height: 100%;
        z-index: 0;
        object-fit: cover;
        border: none;
    }
</style>