---
permalink: /
title: "Description"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
header:
 image: /Header_picture.jpg
---

I'm Fabian Ballar Trigueros, a Ph.D. student in Markus Heyl’s group at the University of Augsburg. My research lies at the interface of quantum many-body physics, quantum information, and computational physics.

I am interested in understanding how complexity emerges in quantum systems, how it can be represented efficiently, and when it becomes a useful resource. Many quantum systems possess special structures that make them tractable: locality, symmetry, integrability, Gaussianity, stabilizer structure, or efficient variational descriptions. At the same time, the richness of quantum many-body physics often comes from the gradual breakdown, deformation, or controlled violation of these structures.

A central goal of my work is to understand this boundary. What makes a quantum state easy or hard to represent? Which resources are responsible for the transition from classically simulable dynamics to genuinely complex quantum behavior? How can ideas from quantum information help us characterize phases of matter, nonequilibrium dynamics, and the capabilities of quantum devices?

To address these questions, I use a combination of analytical and computational tools, including neural quantum states, tensor networks, Krylov methods, exact diagonalization, variational circuits, and concepts from quantum information theory. My work aims to connect concrete many-body models with broader organizing principles such as learnability, simulability, randomness, and quantum resources.

<br>

## Research Roadmap

My current research is organized around three broad themes:

### Ansatz Complexity and Learnability
Variational descriptions are among the most powerful tools for studying quantum many-body systems. Tensor networks, neural quantum states, and related ansätze allow us to compress quantum states into tractable representations. However, their success raises a fundamental question: what makes a quantum state easy or hard to learn?

In this direction, I am interested in the principles that determine the expressive power of variational ansätze. This includes the role of entanglement, correlations, symmetries, sign structures, and physically motivated inductive biases. More broadly, I aim to understand not only how to build better ansätze, but also what their successes and failures reveal about the structure of quantum matter.

### Quantum Resources and the Breakdown of Simulability
Many important classes of quantum systems are efficiently describable because they possess special algebraic or dynamical structure. Stabilizer states, Gaussian fermionic systems, and integrable models are examples where complexity is strongly constrained.

I am interested in what happens when these structures are perturbed or enriched. Resources such as magic, non-Gaussianity, and entanglement provide a language for understanding how quantum systems move beyond efficiently simulable regimes. This perspective connects questions of classical simulation, quantum advantage, and many-body complexity and offers a way to study how small ingredients can qualitatively change the behavior of quantum dynamics.

### Unitary Designs, Error-Resilience, and Quantum Information
Randomness is a powerful organizing principle in quantum many-body physics and quantum information. It appears in thermalization, scrambling, unitary designs, quantum error correction, and encoding-decoding protocols. At the same time, physically relevant dynamics are rarely fully random; they often interpolate between structured evolution and generic behavior.

In this direction, I study how randomness emerges dynamically, how structured circuits approach generic Haar-random-like behavior, and how these effects affect information storage, error resilience, and the generation of complex quantum states. More broadly, I am interested in using quantum information ideas to understand nonequilibrium dynamics and in using many-body physics to design new quantum information protocols.

<br>

## Contact

Email me at [First Name].[First Last Name]@uni-a.de

-__Para estudiantes de la UCR:__ Estoy disponible para asesorar proyectos en Laboratorio Avanzado II. Si está motivado e interesado en recibir orientación, no dude en enviarme un correo para discutir su proyecto.

<br>

Brought to you by physics:
====

A collection of pictures from cool places physics has taken me.

<!-- Add the gallery below -->
<div class="gallery">
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/PI.JPG" alt="Im1">
        <div class="caption">A sunny winter day at Perimeter. (2023) </div>
    </div>
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/DPGTalk.JPG" alt="Im2">
        <div class="caption">Giving a talk at TU Berlin. (2024) </div>
    </div>
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/dpg.JPG" alt="Im3">
        <div class="caption"> With some of my colleagues during the DPG meeting in Berlin. (2024)</div>
    </div>
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/Krntk.JPG" alt="Im4">
        <div class="caption"> Honnavar, Karnataka, India  (2023)</div>
    </div>
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/Trento.JPG" alt="Im5">
        <div class="caption">Conference on neural quantum states. Trento, Italy (2023) </div>
    </div>
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/ECT.JPG" alt="Im6">
        <div class="caption">The view at ECT*, Trento. (2023) </div>
    </div>
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/IISCBeng.JPG" alt="Im7">
        <div class="caption">Indian Institute of Science, Bengaluru. (2023) </div>
    </div>
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/ICTP.JPG" alt="Im8">
        <div class="caption">The outdoor blackboards at ICTP, Trieste. (2024) </div>
    </div>
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/SAIFR.JPG" alt="Im9">
        <div class="caption">ICTP-SAIFR, Sao Paulo, Brazil. (2019) </div>
    </div>
    <div class="gallery-item">
        <img src="{{ site.baseurl }}/images/SAIFR2.JPG" alt="Im10">
        <div class="caption">Journeys into theoretical physics, Sao Paulo. (2019) </div>
    </div>
</div>


<style>
    .gallery {
        display: grid;
        grid-template-columns: repeat(2, 1fr); /* Set the grid to be 2 columns wide */
        grid-auto-rows: minmax(100px, auto); /* Flexible row heights */
        gap: 15px;
        align-items: start; /* Align items to the start of the grid cell */
        padding: 20px;
    }
    .gallery-item {
        position: relative;
        display: block; /* Ensure items are block to fill cells */
    }
    .gallery-item img {
        width: 100%;
        height: auto;
        display: block;
    }
    .caption {
        position: absolute;
        bottom: 0;
        left: 0;
        width: 100%;
        background: rgba(0, 0, 0, 0.5);
        color: #fff;
        text-align: center;
        padding: 10px 0;
        font-size: 16px;
        display: none; /* Initially hide the caption */
    }
    .gallery-item:hover .caption {
        display: block; /* Display the caption on hover */
    }

    /* Media query for smaller screens */
    @media (max-width: 600px) {
        .gallery {
            grid-template-columns: 1fr; /* Change to 1 column for smaller screens */
        }
    }
</style>

<br>

Land Acknowledgment
====
On this personal website, I acknowledge that I was raised on the ancestral lands of the Huetar people in what is now known as the Central Valley of Costa Rica. These lands were not ceded but stolen through colonization and violent displacement.

As a Costa Rican with roots deeply intertwined in this complex history, I recognize that my presence on these lands is a direct result of centuries of colonization, displacement, and cultural assimilation.

Learning about the pain in our roots is not just an academic exercise; it is a moral imperative. It challenges us to question the narratives we've inherited and to recognize the ongoing impacts of historical injustices. By investigating these histories, we begin to understand the complex fabric of identities that make up our nation and the responsibilities we carry as inheritors of this legacy. We are not passive inheritors, but active agents of change, bound by a sacred duty to reclaim our histories, heal our communities, and liberate our lands for all who have been silenced, marginalized, and dispossessed.

I honor the resilience and ongoing presence of the Huetar people, as well as other indigenous groups of Costa Rica - including the Chorotega, Bribri, Cabécar, Maleku, Guaymí, and Boruca. Their cultures, languages, and traditions continue to enrich Costa Rica despite centuries of oppression.

As academics, we must carry a profound responsibility to challenge and dismantle colonial narratives wherever we go. The academic world has long been complicit in perpetuating colonial mindsets and marginalizing indigenous knowledge systems. It is our duty to actively confront these biases within our institutions, research methodologies, and teaching practices.

The Costa Rican government's approach to indigenous rights has been woefully inadequate, marked by empty promises and systemic neglect. The 1977 Indigenous Law, touted as progressive, has proven to be little more than a paper tiger. Decades later, indigenous territories remain under siege, with illegal occupations rampant and unpunished. The government's failure to fully implement this law exposes a lack of political will to address historical injustices. Indigenous communities continue to be marginalized, their lands exploited, and their cultural practices eroded. The state's policies have perpetuated a cycle of poverty and discrimination, while paying lip service to indigenous rights. Costa Rica's international image as an environmental and human rights leader stands in stark contrast to the reality faced by its indigenous peoples. Meaningful reform is long overdue. The government must be held accountable for its failures and take immediate, concrete steps to restore indigenous lands, guarantee true autonomy, and dismantle the systemic barriers that have kept indigenous communities disenfranchised for generations.
