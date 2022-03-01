<template>
    <section>
        <section data-auto-animate>
            <h3 data-id="title">How can Planck's constant<br />be derived using it?</h3>
            <div data-id="animatable">
                <p class="pt-20">First, we need to talk about <strong>stopping voltage</strong></p>
                <p><small>(also called <strong>stopping <em>potential</em></strong>)</small></p>
            </div>
        </section>
        <section data-auto-animate>
            <h3 data-id="title">How can Planck's constant<br />be derived using it?</h3>
            <div data-id="animatable">
                <div class="flex justify-center items-center">
                    <img src="@/images/stopping-potential-meme.png" alt="Stopping potential meme" />
                </div>
            </div>
        </section>
        <section data-auto-animate>
            <h4 data-id="title">How can Planck's constant<br />be derived using it?</h4>
            <div data-id="animatable">
                <div class="mt-20" />
                <p>Every material has a <em>work function</em> indicating the work required to cause emission of electrons upon contact with light</p>
                <div class="mt-20" />
                <p>The work function, represented by $\phi$ and having units in $eV$, is found in determing the kinetic energy of emitted electrons:</p>
                \[E_e = hf - \phi\]
            </div>
        </section>
        <section data-auto-animate>
            <h4 data-id="title">How can Planck's constant<br />be derived using it?</h4>
            <div data-id="animatable">
                \[E_e = hf - \phi\]
                <p>If we divide each component by the elementary charge, $e$, we find:</p>
                \[V_{stopping} = \frac{hf}{e} - \phi_{work}\]
                <p><strong>Note: </strong>This looks like a linear equation, $y = mx + b$...</p>
            </div>
        </section>
        <section data-auto-animate>
            <h4 data-id="title">How can Planck's constant<br />be derived using it?</h4>
            <div data-id="animatable">
                \[V_{stopping} = \frac{hf}{e} - \phi_{work}\]
                <p>If we find a few stopping voltages and graph them, our slope will be $\frac{h}{e}$ and our y-intercept will be $\phi_{work}$!</p>
            </div>
        </section>
        <section>
            <h4>Finding Planck's constant:</h4>
            <p>Knowing this, my experiment consisted of the following data-gathering steps:</p>
            <ol>
                <li>Shine light of known wavelengths onto a phototube to cause a current</li>
                <li>Adjust voltage applied to the phototube until the light no longer causes a current</li>
                <li>Record this stopping voltage and the frequency of light in use on a graph</li>
            </ol>
        </section>
        <section data-auto-animate>
            <h4>Findings:</h4>
            <table class="table-auto">
                <thead>
                    <tr>
                        <th>$\lambda$ (nm)</th>
                        <th>$f$ (THz)</th>
                        <th>$V_s$ (V)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>365</td>
                        <td>822</td>
                        <td>1.91</td>
                    </tr>
                    <tr>
                        <td>436</td>
                        <td>688</td>
                        <td>1.33</td>
                    </tr>
                    <tr>
                        <td>546</td>
                        <td>549</td>
                        <td>0.73</td>
                    </tr>
                    <tr>
                        <td>577</td>
                        <td>520</td>
                        <td>0.62</td>
                    </tr>
                </tbody>
            </table>
        </section>
        <section data-auto-animate>
            <h4>Findings:</h4>
            <div class="flex justify-center items-center">
                <img class="fullimg" src="@/images/vs-f-chart.png" alt="Stopping voltage vs frequency chart" />
            </div>
        </section>
        <section data-auto-animate>
            <h4>Findings: </h4>
            <p>Theoretical: $V_s = \frac{h}{e}f - \phi_{work}$</p>
            <p>Experimental: $V_s = 0.0043f - 1.6136$</p>
            <p>This tells us $\phi_{work} = 1.6136$! The coefficient of the frequency, $f$, is $\frac{h}{e}$.</p>
            <p>We can replace 0.0043 with $\frac{h}{e}$, because we want to find $h$.</p>
        </section>
        <section data-auto-animate>
            <h4>Determining Planck's constant:</h4>
            <p>To find Planck's constant, we can simply plug values<br />into the following equation:</p>
            <p>$V_s = \frac{h}{e}f - 1.6136$</p>
            <p>We can rearrange this to solve for $h$:</p>
            <p>$h = \frac{e(V_s + 1.6136)}{f}$</p>
            <p>We know the values of $e$, $V_s$, and $f$. We can find $h$!</p>
        </section>
        <section data-auto-animate>
            <p>We will plug each $V_s$ and $f$ into $\frac{e(V_s + 1.6316)}{f}$<br />to find <strong>Planck's constant</strong> $h$:</p>
            <table class="table-auto">
                <thead>
                    <tr>
                        <th>$\lambda$ (nm)</th>
                        <th>$f$ (THz)</th>
                        <th>$V_s$ (V)</th>
                        <th>$h_{exp}$ (J$\cdot$s)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>365</td>
                        <td>822</td>
                        <td>1.91</td>
                        <td>$6.94\text{x}10^{-34}$</td>
                    </tr>
                    <tr>
                        <td>436</td>
                        <td>688</td>
                        <td>1.33</td>
                        <td>$6.92\text{x}10^{-34}$</td>
                    </tr>
                    <tr>
                        <td>546</td>
                        <td>549</td>
                        <td>0.73</td>
                        <td>$6.91\text{x}10^{-34}$</td>
                    </tr>
                    <tr>
                        <td>577</td>
                        <td>520</td>
                        <td>0.62</td>
                        <td>$6.95\text{x}10^{-34}$</td>
                    </tr>
                </tbody>
            </table>
        </section>
        <section>
            <h4>Analysis of Results:</h4>
            <p>We know the accepted value of $h$ is $h = 6.626\text{x}10^{-34}$.</p>
            <p>I was fairly close, within 5% every time:</p>
            <table class="table-auto">
                <thead>
                    <tr>
                        <th>$h_{theo}$ (J$\cdot$s)</th>
                        <th>$h_{exp}$ (J$\cdot$s)</th>
                        <th>% Difference</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>$6.626\text{x}10^{-34}$</td>
                        <td>$6.94\text{x}10^{-34}$</td>
                        <td>-4.52</td>
                    </tr>
                    <tr>
                        <td>$6.626\text{x}10^{-34}$</td>
                        <td>$6.92\text{x}10^{-34}$</td>
                        <td>-4.44</td>
                    </tr>
                    <tr>
                        <td>$6.626\text{x}10^{-34}$</td>
                        <td>$6.91\text{x}10^{-34}$</td>
                        <td>-4.29</td>
                    </tr>
                    <tr>
                        <td>$6.626\text{x}10^{-34}$</td>
                        <td>$6.95\text{x}10^{-34}$</td>
                        <td>-4.89</td>
                    </tr>
                </tbody>
            </table>
        </section>
        <section>
            <h4>Sources of Error:</h4>
            <ul>
                <li class="fragment"><strong>Rounding! </strong>Using terahertz for the light frequency discarded many significant figures &ndash; the net result is reduction in accuracy of the experimental Planck constant.</li>
                <li class="fragment"><strong>Data collection inconsistencies.</strong> The precise electrical equipment had to be constantly zero-checked while working. It is possible this was not always done in the best way, losing accuracy.</li>
                <li class="fragment"><strong>Data recording inconsistencies.</strong> Viewing the data collected by the equipment over the internet was difficult at best, and there is a good chance some numbers were not recorded correctly.</li>
            </ul>
        </section>
    </section>
</template>

<style scoped>
img {
    height: 500px;
}

img.fullimg {
    height: auto;
}
</style>