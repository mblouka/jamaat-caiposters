<script>
  import Footer from "../../components/Footer.svelte";
  import Icon from "@iconify/svelte";
</script>

<main>
  <section>
    <h1>L'islam</h1>

    <div class="row">
      <div
        style="flex: 1 1 0; text-align: justify; display: flex; flex-direction: column; gap: 1rem;"
      >
        <div>
          <b>Islam</b>, le nom qu'Allah a donné à cette religion (Coran 5:4),
          est un mot arabe qui signifie l'obéissance et la paix. <i>islam</i>
          est pris de la racine Salema, qui veux dire <b>paix</b>,
          <b>pûreté</b>, <b>soumission</b> et <b>obéissance</b>.
          <b
            >L'islam est donc le chemin de ceux qui sont obéissants à Dieu et
            qui établissent la paix envers ses créatures.</b
          > Les adhérents de l'islam s'appellent les musulmans.
        </div>
        <div>
          L'islam n'est pas une nouvelle religion. Il est la continuation du
          même message qu'Allah a révélé à d'autres prophètes avant Mohammed
          (que la paix soit sur lui). Allah dit dans le Saint Coran:
          <blockquote class="verset">
            Nous croyons en Allah et en ce qui nous a été révélé, et en ce lui
            qui a été révélé à Abraham, à Ismaël, à Isaac, à Jacob et aux
            tribus, et en ce qui a été donné à Moïse, à Jésus et aux autres
            Prophètes. Nous ne faisons aucune distinction entre eux, et c'est à
            Lui que nous nous sousmettons.
            <div class="author">Le Coran 3:85</div>
          </blockquote>
        </div>
        <div style="text-align: left">
          L'islam croit que l'homme est né pur et non dans le péché. Nous sommes
          responsables de nos actions, et nous ne pouvons nous sauver par
          l'expiation d'un tiers. Il faut choisir entre le bien et le mal, et
          œuvrer pour notre salut à travers la foi, la prière et la charité. La
          piété ne signifie pas abandonner les joies licites pour mener une vie
          d'ascète ou de moine. Nous devons plutôt mener une vie active saine et
          utile au cours de laquelle la bonté, l'honnêteté, l'humilité, la
          compassion, la patience et la propreté jouent un rôle important.
        </div>
      </div>
      <div id="piliers" style="flex: 1 1 0">
        <h2>Les cinq piliers d'islam</h2>
        <ul>
          <li>
            <b>La chahada <Icon icon="game-icons:chat-bubble" /></b>
            <div>
              La chahada (la profession de la foi) signifie affirmer que l'on
              croit qu'il n'y a pas d'autre Dieu qu'Allah et que Muhammad est
              son messager.
            </div>
          </li>
          <li>
            <b>La Salat <Icon icon="game-icons:prayer" /></b>
            <div>
              Les cinq prières quotidiennes obligatoires, autrement dit la Salat
              en arabe, est incombée au musulman après sa déclaration de foi.
            </div>
          </li>
          <li>
            <b>La Zakat <Icon icon="mdi:donation" /></b>
            <div>
              La Zakat est une aumône qui est prélevée sur le capital d'un
              musulman afin de subvenir aux besoins des indigents.
            </div>
          </li>
          <li>
            <b>Le jeûne <Icon icon="mdi:food-variant-off" /></b>
            <div>
              Le Ramadan est un mois du calendrier islamique. Au cours de ce
              mois, il incombe à tout musulman, ayant atteint l'âge de la
              maturité, de s'abstenir de tout aliment, liquide ou autre de
              l'aube jusqu'au coucher du soleil.
            </div>
          </li>
          <li>
            <b>Le Hajj <Icon icon="fa6-solid:kaaba" /></b>
            <div>
              Il incombe à tout musulman ayant les moyens d'accomplir au moins
              une fois dans sa vie la pèlerinage à la Mecque, à condition que le
              voyage vers le lieu saint soit sécuritaire.
            </div>
          </li>
        </ul>
      </div>
    </div>
  </section>

  <Footer />
</main>

<style>
  main {
    color: white;
    position: relative;
    padding-left: 3rem;
    padding-right: 3rem;
    padding-top: 1.5rem;
    box-sizing: border-box;
    height: 100%;

    background-color: #052e16;
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='77' height='107' viewBox='0 0 77 107'%3E%3Cg fill-rule='evenodd'%3E%3Cg id='stamp-collection' fill='%2314532d' fill-opacity='0.4'%3E%3Cpath d='M46 101a5 5 0 0 1 5 5h5a5 5 0 0 1 10 0h5a5 5 0 0 1 5-5v-5a5 5 0 0 1 0-10v-5a5 5 0 0 1 0-10v-5a5 5 0 0 1 0-10v-5a5 5 0 0 1 0-10v-5a5 5 0 0 1 0-10v-5a5 5 0 0 1 0-10V6a5 5 0 0 1-5-5h-5a5 5 0 0 1-10 0h-5a5 5 0 0 1-10 0h-5a5 5 0 0 1-10 0h-5a5 5 0 0 1-10 0H6a5 5 0 0 1-5 5v5a5 5 0 0 1 0 10v5a5 5 0 0 1 0 10v5a5 5 0 0 1 0 10v5a5 5 0 0 1 0 10v5a5 5 0 0 1 0 10v5a5 5 0 0 1 0 10v5a5 5 0 0 1 5 5h5a5 5 0 0 1 10 0h5a5 5 0 0 1 10 0h5a5 5 0 0 1 5-5zm15-2a7 7 0 0 0-6.71 5h-1.58a7 7 0 0 0-13.42 0h-1.58a7 7 0 0 0-13.42 0h-1.58a7 7 0 0 0-13.42 0H7.71A7.01 7.01 0 0 0 3 99.29v-1.58a7 7 0 0 0 0-13.42v-1.58a7 7 0 0 0 0-13.42v-1.58a7 7 0 0 0 0-13.42v-1.58a7 7 0 0 0 0-13.42v-1.58a7 7 0 0 0 0-13.42v-1.58A7 7 0 0 0 3 9.29V7.71A7.02 7.02 0 0 0 7.71 3h1.58a7 7 0 0 0 13.42 0h1.58a7 7 0 0 0 13.42 0h1.58a7 7 0 0 0 13.42 0h1.58a7 7 0 0 0 13.42 0h1.58A7.02 7.02 0 0 0 74 7.71v1.58a7 7 0 0 0 0 13.42v1.58a7 7 0 0 0 0 13.42v1.58a7 7 0 0 0 0 13.42v1.58a7 7 0 0 0 0 13.42v1.58a7 7 0 0 0 0 13.42v1.58a7 7 0 0 0 0 13.42v1.58a7.01 7.01 0 0 0-4.71 4.71h-1.58A7 7 0 0 0 61 99zM12 12h53v83H12V12zm51 81H14V14h49v79z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
  }

  section {
    display: flex;
    flex-direction: column;
    width: 100%;
    gap: 1rem;
  }

  #piliers {
    background: linear-gradient(to bottom, #166534, #052e16);
    box-shadow: 0rem 1rem 1rem rgba(0, 0, 0, 30%);
    border: 4px double white;
  }

  h2 {
    margin: 0;
    background-color: #16a34a;
    padding: 0.5rem;
    text-align: center;
  }

  ul {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 1rem;
    margin-left: 0;
    padding-left: 0;
  }

  ul li {
    text-align: justify;
    margin-left: 0;
    padding-left: 1rem;
    padding-right: 1rem;
  }

  ul li b {
    display: flex;
    align-items: center;
    font-size: 1.5rem;
    margin-bottom: 0.4rem;
    border-bottom: 2px solid white;
  }

  b :global(svg) {
    margin-left: auto;
  }

  .row {
    display: flex;
    gap: 2rem;
    flex: 1 1 0;
  }

  blockquote.verset {
    text-align: left;
    font-weight: bold;
    margin-left: 0;
    margin-right: 0;
    padding: 1rem;
    background: #166534;
    border-bottom: 0.2rem double white;
    box-shadow: 0rem 1rem 1rem rgba(0, 0, 0, 30%);
  }

  .author {
    text-align: right;
    font-style: italic;
    font-weight: 100;
  }

  h1 {
    margin-top: 0;
    margin-bottom: 0;
    font-size: 3.5rem;
    border-bottom: 2px solid white;
  }
</style>
