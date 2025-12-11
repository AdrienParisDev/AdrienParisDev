<!--
## Bienvenue sur le profil Github de Adrien Pâris 👋

### Une petite présentation s'impose :) 

Ancien marketeux et commercial, aujoud'hui, je tente ma chance dans l'univers du dévellopement Wed 

### En recherche de stage pour Début 2026

### Compétences 

### 


**AdrienParisDev/AdrienParisDev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<main style="display: flex; flex-direction: column; align-items: center; text-align: center">
    <section id="header">
        <h1>Bienvenue sur le profil Github de Adrien Pâris 👋</h1>
    </section>
    <section id="intro">
        <h2>Une petite présentation s'impose :)</h2>
        <p>Ancien marketeux et commercial, aujoud'hui, je tente ma chance dans l'univers du dévellopement Web</p>
    </section>
    <section id="looking-for">
        <h2>En recherche d'un stage de 2 à 6 mois à partir de janvier 2026</h2>
    </section>
    <section id="skill">
        <h2>Compétences</h2>
        <div id="all-skills">
            <div class="skill-box">
                <h3>Langages & Frameworks</h3>
                <div>
                    <img src="icons8-brillant-48.png" alt="">
                    <img src="icons8-brillant-48.png" alt="">
                    <img src="icons8-brillant-48.png" alt="">
                </div>
            </div>
            <div class="skill-box">
                <h3>Bases de données & ORM</h3>
                <div>
                    <img src="icons8-brillant-48.png" alt="">
                    <img src="icons8-brillant-48.png" alt="">
                    <img src="icons8-brillant-48.png" alt="">
                </div>
            </div>
            <div class="skill-box">
                <h3>Outils & Méthodologies</h3>
                <div>
                    <img src="icons8-brillant-48.png" alt="">
                    <img src="icons8-brillant-48.png" alt="">
                    <img src="icons8-brillant-48.png" alt="">
                </div>
            </div>
        </div>
    </section>
    <section id="more-news">
        <h2>Pour plus d'informations ...</h2>
        <div id="all-news">
            <div>
                <h3>Mon Portofolio</h3>
                <img src="icons8-brillant-48.png" alt="">
                <a href="">Découvrir</a>
                <p>Découvrez mes projets, même ceux privés sur Github</p>
            </div>
            <div>
                <h3>Mon LinkedIn</h3>
                <img src="icons8-brillant-48.png" alt="">
                <a href="">Voir</a>
                <p>Un parcours atypique mais qui vous donnera matière a entamer la conversation</p>
            </div>
            <div>
                <h3>Mon CV</h3>
                <img src="icons8-brillant-48.png" alt="">
                <a href="">Voir</a>
                <p>Un CV rien de particulier à dire ...</p>
            </div>
        </div>
    </section>
    <p id="ref-icon8">* Les logos est images proviennent dus site <a href="" target="_blank">Icons8</a></p>
</main>
<style>
    main {
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        section {
            width: 100%;
            margin-bottom: 20px;
        }
        #header {
            background: rgba(198, 57, 240, 0.15);
            border-radius: 16px;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(7.8px);
            -webkit-backdrop-filter: blur(7.8px);
            border: 1px solid rgba(198, 57, 240, 0.28);
        }
        #intro {
            background: rgba(68, 26, 192, 0.15);
            border-radius: 16px;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(7.8px);
            -webkit-backdrop-filter: blur(7.8px);
            border: 1px solid rgba(68, 26, 192, 0.28);
        }
        #looking-for {
            background: rgba(68, 26, 192, 0.15);
            border-radius: 16px;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(7.8px);
            -webkit-backdrop-filter: blur(7.8px);
            border: 1px solid rgba(68, 26, 192, 0.28);
            animation: search_job infinite 3s ease-in-out;
            h2 {
                opacity: 1;
            }
        }
        #skill {
            background: rgba(68, 26, 192, 0.15);
            border-radius: 16px;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(7.8px);
            -webkit-backdrop-filter: blur(7.8px);
            border: 1px solid rgba(68, 26, 192, 0.28);
            #all-skills {
                display: grid;
                grid-template-columns: repeat(2, 1fr);
                grid-template-rows: repeat(2, 1fr);
                grid-column-gap: 0px;
                grid-row-gap: 0px;
                .skill-box:first-child {
                    grid-column: 1;
                    grid-row: 1;
                }   
                .skill-box:nth-child(2n) {
                    grid-column: 2;
                    grid-row: 1;
                }
                .skill-box:last-child {
                    grid-column: 2;
                    grid-row: 2;
                }
            }
        }
        #more-news {
            background: rgba(68, 26, 192, 0.15);
            border-radius: 16px;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(7.8px);
            -webkit-backdrop-filter: blur(7.8px);
            border: 1px solid rgba(68, 26, 192, 0.28);
            #all-news {
                display: flex;
            }
        }
    }
    #ref-icon8{
        text-align: right;
        align-self: flex-end;
        margin-right: 30px;
        color: rgb(146, 144, 144);
        font-style: italic;
    }
    @keyframes search_job {
        0% {
            opacity: 1;
        }
        50% {
            opacity: 0.4;
        }
        100% {
            opacity: 1;
        }
    }
</style>
