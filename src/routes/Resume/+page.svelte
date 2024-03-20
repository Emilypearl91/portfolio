<script>
  import Footer from "../../lib/footer/Footer.svelte";
</script>

<body>
  <article>
    <section>
      <h1>Emily Seafoot</h1>
      <ul>
        <li><a href="/">github</a></li>
        <li><a href="/">linkedIn</a></li>
      </ul>

      <h3>education</h3>

      <h2>SAIT, Web Development — Certificate 2023</h2>
      <p>
        Fast track program for web development, building the foundation of
        skills to develop useful and accessible websites.
      </p>
      <h3>experience</h3>
      <h2>Cole International, Calgary AB — Temporary Receptionist 2023</h2>

      <ul>
        <li>
          Answering phone calls and transferring them to another location or
          person based on the needs of the client.
        </li>
        <li>Sending out packages and mail in a timely fashion.</li>
      </ul>

      <h2>Dogtopia, Calgary AB — Canine Coach 2023</h2>

      <ul>
        <li>Taking care of up to 30 dogs in a roommate a time.</li>
        <li>keeping the dogs engaged and safe.</li>
        <li>maintaining a clean enviroment.</li>
        <li>Breaking up scuffles and conflicts.</li>
        <li>
          meeting each dogs needs and adapting quickly to every possible
          situation.
        </li>
      </ul>

      <h2>Amazon, Calgary AB — Warehouse Associate 2023</h2>
      <p>Working in a warehouse maintaining a safe environment while :</p>

      <ul>
        <li>Building pallets</li>
        <li>Wrapping and digitally closing a container</li>
        <li>Trailer docking and releasing</li>
        <li>
          Spotting out in the yard and maintaining a safe distance from trucks
        </li>
      </ul>
    </section>
    <section>
      <ul>
        <li>CALGARY, AB</li>
        <li>(587) 707-9193</li>
        <li>Emilypearl9193@gmail.com</li>
      </ul>
      <h3>technical skills</h3>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>Java Script</li>
        <li>Tailwind</li>
        <li>Svelte</li>
      </ul>
      <h3>other skills</h3>

      <ul>
        <li>Adobe:</li>
        <ul>
          <li>Photoshop</li>
          <li>Illustrator</li>
          <li>xd</li>
          <li>Indesign</li>
        </ul>
        <li>Branding and Copywriting</li>
        <li>Logo design</li>
        <li>UX and UI design</li>
      </ul>

      <h3>extra curriculars</h3>
      <h2>Web Witches Club</h2>
      <ul>
        <li>Women in tech focused.</li>
        <li>Creating a fun eviroment to learn and help each other.</li>
        <li>Weekly meet ups.</li>
      </ul>
    </section>
  </article>
  <Footer></Footer>
</body>

<style>
  :global(body) {
    background-color: black;
    color: white;

    font-family: "Times New Roman", Times, serif;
    margin: auto;
  }
  article {
    margin: auto;
    padding: 30px;
    border: 1px solid #ec4899;

    max-width: 1100px;
  }
  section {
    display: inline-grid;
    max-width: 80ch;
    margin: auto;
    padding: 1.5rem;
  }

  h1 {
    font-size: 60px;
  }

  h3 {
    font-size: 24px;
    font-weight: bold;
    text-transform: uppercase;
    padding: 0.5rem;
  }
  h2 {
    font-size: 20px;
    font-weight: bold;
    padding: 1rem;
  }

  ul {
    list-style-type: none;
  }

  a {
    text-decoration: none;
    color: #ec4899;
  }
</style>
