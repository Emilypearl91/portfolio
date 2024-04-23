<script>
  import Footer from "../lib/footer/Footer.svelte";
</script>

<body>
  <h1 class="text-pink-500 text-center text-4xl">About Me</h1>
  <section class="m-auto flex flex-row">
    <img
      class="w-60 h-60 rounded-full bg-zinc-400 m-auto"
      src="/photo-of-me.JPG"
      alt=" a photo of Emily"
    />
    <!--about me description-->
    <p class="max-w-4xl m-auto text-xl">
      Hello! My name is Emily and I am from Calgary, Alberta. My background in
      the arts is how I found a passion for coding. I have been a classically
      trained flutist for the past 10 years. While in highschool I graduated
      with a certificate of excellence in the arts, from there I chose to branch
      out and try something new. I went into digital design where I learned to
      design branding, logos, website design mockups, wireframes and write
      copywriting for brands. Through that I got to see the beginning steps in
      creating and coding a portfolio website using html, css and javascript, I
      really enjoyed the whole process and coding and chose to pursue that
      passion further at SAIT in the web developer program.
    </p>
  </section>

  <!--project section-->
  <h1 class="text-pink-500 text-center text-4xl">Projects</h1>
  <section class="m-auto p-2">
    <!--Tossed salad shop project-->
    <h2 class="text-3xl text-center font-bold p-4">Tossed</h2>
    <article class="w-24 m-auto">
      <a href="https://tossed.netlify.app/"
        ><h4 class=" text-xl font-bold text-violet-400 hover:text-pink-500">
          Live Site
        </h4></a
      >
    </article>
    <section class=" flex flex-row justify-around">
      <img
        src="/tossed-project-photo.png"
        alt="purple website with a variety of salad photos"
        class="w-[500px] m-auto"
      />

      <p class="text-xl w-[60ch] m-auto">
        The project Tossed is a salad shop that is built with SvelteKit,
        Skeleton UI and Tailwind. This was a project for my program at Sait
        originally, creating a layout using svelte components and SkeletonUI. I
        chose to come back to this project and make it into a more functional
        website. Tossed is a salad shop that strives to create healthy lunches
        and meals for those on the go, while also being customizable to meet the
        customers dietary needs.
      </p>
    </section>
    <!--Book prompt generator-->
    <h2 class="text-3xl text-center font-bold p-4">Book Prompt Generator</h2>
    <article class="w-24 m-auto">
      <a href="https://emilypearl91.github.io/book-reading-prompt/"
        ><h4 class=" text-xl font-bold text-violet-400 hover:text-pink-500">
          Live Site
        </h4></a
      >
    </article>
    <section class=" flex flex-row">
      <img
        src="/book-prompt-project.png"
        alt="website with a grey rectangle and black text of book prompts"
        class="w-[500px] m-auto mt-4"
      />

      <p class="text-xl p-2 w-[60ch] m-auto">
        This project is made using vanilla HTML, CSS and JavaScript to create a
        basic random generator for your next read. I wanted to create something
        that I would use in my everyday life and that would combine my passion
        for coding with my love of reading.
      </p>
    </section>
  </section>

  <Footer></Footer>
</body>

<style>
  :global(body) {
    background-color: black;
    color: white;

    height: 100vh;
    padding: 0;
    margin: 0;

    font-family: Arial, Helvetica, sans-serif;
  }
  h1 {
    text-shadow: #ec4899 3px 0 8px;
    color: lightpink;
  }
</style>
