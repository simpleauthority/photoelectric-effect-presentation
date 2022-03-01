<template>
    <section>
        <section data-auto-animate>
            <h3 data-id="title">How can Planck's<br />constant be<br />derived using it?</h3>
            <div data-id="animatable">
                <p class="pt-20">First, we need to talk about <strong>stopping voltage</strong> <small>(or <strong>stopping <em>potential</em></strong>)</small></p>
            </div>
        </section>
        <section data-auto-animate>
            <h4 data-id="title">How can Planck's constant<br />be derived using it?</h4>
            <div data-id="animatable">
                <div class="flex justify-center items-center">
                    <img src="@/images/stopping-potential-meme.png" alt="Stopping potential meme" />
                </div>
            </div>
        </section>
        <section data-auto-animate>
            <h4 data-id="title">How can Planck's constant<br />be derived using it?</h4>
            <div data-id="animatable">
                <p><strong>stopping voltage: </strong> every material has its own <em>work function</em>, which indicates the work is required to cause emission of electrons when light hits it</p>
                <p>If the frequency of light contacting a material cannot produce enough work to overcome the work function, no current will be generated via the photoelectric effect.</p>
            </div>
        </section>
        <section data-auto-animate>
            <h4 data-id="title">How can Planck's constant<br />be derived using it?</h4>
            <div data-id="animatable">
                \[V_{stopping} = \frac{hf}{e} - \phi_{work}\]
            </div>
        </section>
        <section data-auto-animate>
            <h4 data-id="title">How can Planck's constant<br />be derived using it?</h4>
            <div data-id="animatable">
                \[h = \frac{e(V_{stopping} + \phi_{work})}{f}\]
            </div>
        </section>
        <section>
            <h4>Finding Planck's constant:</h4>
            <p>My experiment to derive Planck's constant was as follows:</p>
            <ol>
                <li>Shine light of known wavelengths onto a phototube to cause a current</li>
                <li>Adjust voltage applied to the phototube until the light no longer causes a current</li>
                <li>Use that <strong>stopping voltage</strong> to determine the work function of the material</li>
                <li>Use these two values to find an experimental value for Planck's constant</li>
            </ol>
        </section>
    </section>
</template>

<style scoped>
img {
    height: 500px;
}
</style>