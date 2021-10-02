<style>
    :global(*) {
        margin: 0;
        box-sizing: border-box;
    }

    model-viewer {
        /* https://webkit.org/blog/7929/designing-websites-for-iphone-x/ */
        height: calc(100vh - env(safe-area-inset-top) - env(safe-area-inset-bottom));
        width: calc(100vw - env(safe-area-inset-left) - env(safe-area-inset-right));
    }
</style>

<model-viewer alt='' src='https://modelviewer.dev/shared-assets/models/Astronaut.glb'ar ar-modes="webxr scene-viewer quick-look" environment-image="neutral" auto-rotate camera-controls></model-viewer>
