<script>
  import Footer from "../../components/Footer.svelte";
</script>

<main>
  <h1>Le Califat</h1>
  <section>
    <div class="row" style="margin-top: 1rem">
      <div class="paragraph">
        <b
          >L'une des plus grandes faveurs dont juit la Jama'at musulmane
          Ahmadiyya est qu'elle a été bénie de l'institution du Califat en
          islam.</b
        >
        Après le décès du fondateur de la communauté, ses califes servent à unir
        la Communauté sur une unique et même base.
      </div>

      <div class="paragraph">
        Le successeur de Hadrat Mirza Ghulam Ahmad fut <b
          >Hadrat Maulvi Nooruddin</b
        >, exégète du Saint Coran de grand renom et éminent médecin. En 1914, il
        fut succédé par <b>Hadrat Mirza Bashiruddin Mahmud Ahmad</b>, un génie
        en sciences aussi bien religieuses que séculières. Le troisième
        successeur fut <b>Hadrat Mirza Nasir Ahmad</b> pédagogue distingué qui
        attacha une grande
        <b>importance au service de l'Afrique.</b> En 1982,
        <b>Hadrat Mirza Tahir Ahmad</b> fut élu quatrième calife, et sous son
        leadership, lancat de nombreux projets communautaires <b>dont</b> la création
        d'une chaîne de télévision mondiale, la MTA (Muslim Television Ahmadiyya).
      </div>

      <div class="paragraph">
        Le cinquième et actuel calife est Sa Sainteté <b>Mirza Masroor Ahmad</b
        >, qui réside au Royaume-Uni. Sous la direction du Califat Ahmadiyya, la
        Jama'at musulmane Ahmadiyya a maintenant construit plus de
        <b>16 000 mosquées</b>, <b>500 écoles</b>
        <b>30 hôpitaux</b> à travers le monde. Elle a traduit le Saint Coran en
        plus de
        <b>70 langues</b>. Elle propage les vrais enseignements d'islam et le
        message de paix et de tolérance à travers la MTA 24 heures sur 24, sur
        Internet (<span style="text-decoration: underline">www.alislam.org</span
        >
        et
        <span style="text-decoration: underline">www.islam-ahmadiyya.org</span>)
        et une maison d'édition (Islam International Publications). La Jama'at
        musulmane Ahmadiyya a été à l'avant-garde des secours en cas de
        catastrophe dans le monde grâce à une organisation caritative
        indépendante, Humanity First.
      </div>
    </div>
    <div class="row" style="justify-content: center">
      <img class="row-image" alt="" src="/calif.png" />
      <blockquote class="calif">
        Vous avez une tâche difficile à accomplir dans ce climat tendu. Soyez
        sincères dans votre foi et fermes dans votre conviction. Etablissez une
        relation personnelle avec Dieu. Afin de prouver Son existence aux
        autres, démontrez-leur qu'Il ne cesse d'écouter ceux qui Le cherchent.
        <div class="calif">Sa Sainteté Mirza Masroor Ahmad</div>
      </blockquote>
    </div>
  </section>

  <Footer />
</main>

<style>
  main {
    color: white;
    position: relative;
    padding: 3rem;
    background-color: #1e293b;
    box-sizing: border-box;
    height: 100%;

    background-color: #1e293b;
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='152' height='152' viewBox='0 0 152 152'%3E%3Cg fill-rule='evenodd'%3E%3Cg id='temple' fill='%23334155' fill-opacity='0.4'%3E%3Cpath d='M152 150v2H0v-2h28v-8H8v-20H0v-2h8V80h42v20h20v42H30v8h90v-8H80v-42h20V80h42v40h8V30h-8v40h-42V50H80V8h40V0h2v8h20v20h8V0h2v150zm-2 0v-28h-8v20h-20v8h28zM82 30v18h18V30H82zm20 18h20v20h18V30h-20V10H82v18h20v20zm0 2v18h18V50h-18zm20-22h18V10h-18v18zm-54 92v-18H50v18h18zm-20-18H28V82H10v38h20v20h38v-18H48v-20zm0-2V82H30v18h18zm-20 22H10v18h18v-18zm54 0v18h38v-20h20V82h-18v20h-20v20H82zm18-20H82v18h18v-18zm2-2h18V82h-18v18zm20 40v-18h18v18h-18zM30 0h-2v8H8v20H0v2h8v40h42V50h20V8H30V0zm20 48h18V30H50v18zm18-20H48v20H28v20H10V30h20V10h38v18zM30 50h18v18H30V50zm-2-40H10v18h18V10z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
  }

  section {
    display: flex;
    width: 100%;
    gap: 2rem;
  }

  .row {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    flex: 1 1 0;
  }

  .row-image {
    object-fit: contain;
    width: 100%;
    border: 1rem double white;
    margin-left: auto;
    box-sizing: border-box;
  }

  .paragraph {
    text-align: justify;
    height: fit-content;
    font-size: 0.9rem;
  }

  blockquote.calif {
    margin-left: 0;
    margin-right: 0;
    padding: 1em;
    border-bottom: 0.2rem double white;
    background-color: #475569;
    text-align: justify;
    font-style: italic;
  }

  blockquote .calif {
    margin-top: 1rem;
    text-align: right;
    font-weight: bold;
    font-style: normal;
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
