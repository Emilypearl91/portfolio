<script>
</script>

<body
  class=" bg-gradient-to-t bg-[#CDCDCD] from-[#AA4465] rounded-md
"
>
  <h1 id="projects" class="m-auto text-center text-xl">Projects</h1>
  <p class="max-w-[80ch] m-auto">
    The projects showcased are ones that I am most proud of and are currently
    working on. I started learning web development a year ago and since then I
    have been learning something new everyday that I can implement into my
    projects, making them more user friendly and useful. I really enjoyed making
    these projects and really enjoy the debugging process and obstacles I have
    faced while building these projects.
  </p>
  <section class="cards">
    <!-- yarn project helper -->
    <a href="https://yarn-project-helper.netlify.app/" class="m-12"
      ><img
        src="/yarn-project-helper.png"
        alt="light blue knit object and website description"
        class="hover:shadow-black hover:shadow-lg max-w-[600px]"
      /></a
    >
    <div class="max-w-[500px] h-96 m-2 bg-[#DCC9AF] rounded-md one m-auto">
      <p class=" m-auto max-w-[60ch] p-2">
        The yarn project helper was created with friend and family in mind, it
        is meant to replace the random sheets of paper and notebooks filled with
        tally marks to mark where you are in a fiber art projects. Allowing for
        your project to be transportable. Another feature that is included is a
        calculator of sorts that allows for the user to determine how much the
        finished project is worth if they were looking to sell it. This project
        was created using vite, svelte, tailwind css, skeleton ui and creating a
        skeleton ui custom theme. Challenges I faced while working on this
        project was fixing the NAN error and saving the row counter to local
        storage.
      </p>
    </div>

    <!-- blog project -->
    <a
      href="https://www.figma.com/proto/7hzvU9sBXftqr8wsXhTmKK/blog-project?page-id=0%3A1&node-id=1-2&t=hOXjMqUIlJN7S5jR-1"
      class="blog-image m-12"
      ><img
        src="/homepage-blog-project.png"
        alt="homepage of blog"
        class="hover:shadow-black hover:shadow-lg max-w-[600px]"
      /></a
    >
    <div class="max-w-[500px] h-98 m-2 bg-[#DCC9AF] rounded-md two m-auto">
      <p class=" m-auto p-2">
        The blog project was created to work with supabase and svelte by
        creating a website that renders data from supabase. It was also created
        to share knowledge, opinions and advice on the hobbies I share with
        friends and family. This project was created with svelte, supabase,
        skeleton ui and tailwind css.
      </p>
    </div>

    <div class="max-w-[500px] h-64 m-2 bg-[#DCC9AF] rounded-md three">
      <p
        class="text-center text-center m-24
      "
      >
        coming soon...
      </p>
    </div>

    <div
      class="max-w-[500px] h-64 m-2 bg-[#DCC9AF] rounded-md three opacity-0 hover:opacity-100 hover:shadow hover:shadow-black hover:shadow-lg"
    >
      <p class=" m-auto p-2">
        A project that is currently in the works is getting the burger if the
        day from the bob's burger api and rendering it to be on a sheet of
        paper. Another is a book journal project that uses a database and user
        authentication. This project will allow for readers to keep track of
        their reading goals and journal their thoughts and catalog their own
        books. Another feature would have a book prompt generator that would
        help give an idea for the user to find what to read next.
      </p>
    </div>
  </section>
  <h1 id="about" class="m-auto text-center text-xl">About me</h1>
  <img
    src="/photo-of-me.JPG"
    alt="photo of emily"
    class="max-w-52 max-h-52 rounded-full m-auto"
  />
  <p class="max-w-[80ch] m-auto">
    Hello! My name is Emily and I am from Calgary, Alberta. My background in the
    arts is how I found a passion for coding. I have been a classically trained
    flutist for the past 10 years. While in highschool I graduated with a
    certificate of excellence in the arts, from there I chose to branch out and
    try something new. I went into digital design where I learned to design
    branding, logos, website design mockups, wireframes and write copywriting
    for brands. Through that I got to see the beginning steps in creating and
    coding a portfolio website using html, css and javascript, I really enjoyed
    the whole process and coding and chose to pursue that passion further at
    SAIT in the web developer program.
  </p>
</body>

<style>
  body {
    font-family: "Newsreader", serif;
    font-size: 20px;
    font-weight: 500;
    font-style: normal;
  }
  .cards {
    display: grid;
    grid-template-columns: auto;
    grid-template-rows: auto;
    margin: 2rem;
  }
  .one {
    grid-column-start: 3;
    grid-column-end: 5;
  }
  .two {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 3;
  }
  .blog-image {
    grid-column-start: 3;
    grid-column-end: 5;
    grid-row-start: 3;
  }
  .three {
    grid-column-start: 3;
    grid-column-end: 5;
    grid-row-start: 4;
  }
</style>
