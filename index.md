# Welcome!

The `sBART` code [Silva et al 2022] estimates radial velocities (RV) using a
semi-Bayesian template-matching approach (see below for details). It was
developed for ESPRESSO data in particular, with the goal of deriving very high
precision RVs.

You can use the form below to request RVs for a given ESPRESSO GTO target. The
code will use the outputs from the ESPRESSO DRS (obtained from DACE), calculate
the RVs, and send you the resulting file by email.  
This will typically be ready within 1 or 2 working days.

### Request target data

<form class="request-form" id="request-form" method="post" action="https://forms.un-static.com/forms/06476cbd515be88b4f5cd6fbfae894e8437f9691">
  <input type="text" name="name" placeholder="Your Name" required>
  <input type="email" name="email" placeholder="Your Email" required>
  <input type="text" name="star" placeholder="Target" id="star" required>
  <p>can use any Simbad identifier</p>
  <!-- <textarea name="message" cols="40" rows="15"></textarea> -->
  <button type="submit">Submit</button>
  <p id="submitted-text" class="submitted">form submitted!</p>
</form>
<small>
Powered by <a rel="nofollow" href="Un-static Forms">Un-static Forms</a>
</small>

<script>
  const form = document.getElementById("request-form");
  form.addEventListener("submit", (e) => {
    // e.preventDefault();
    console.log("submitted!");
    const text = document.getElementById("submitted-text");
    text.style.color = 'green';
  })
</script>


### Details on the method

sBART does this and that...

Veniam reprehenderit non sunt consectetur culpa est et id. Adipisicing ex enim elit fugiat ex duis exercitation aliqua consectetur nulla incididunt nisi duis et. Proident ex consectetur consectetur veniam cupidatat in ex. Aute elit nisi cupidatat occaecat excepteur nulla quis eiusmod nostrud ea magna mollit occaecat et. Proident minim tempor dolore voluptate culpa Lorem.

Nulla esse duis tempor ad deserunt aute occaecat ea cupidatat exercitation. Quis ipsum amet do tempor amet. Irure magna officia laborum nisi ipsum laboris velit incididunt. In dolore mollit dolor aute proident aliquip do voluptate ea commodo minim. Nulla aliqua dolor ad amet deserunt amet. Culpa cupidatat quis amet aute duis magna dolor. Incididunt laborum aliquip ullamco velit qui Lorem anim enim nostrud nostrud ex.

Anim Lorem consequat esse in proident eu officia dolore non ea quis do non. Enim anim excepteur non Lorem. Amet dolore voluptate laborum reprehenderit et duis. Et ipsum deserunt ipsum dolor dolor. Anim quis velit exercitation cupidatat cupidatat et Lorem id.

Quis duis adipisicing minim laborum fugiat officia eu id ad nostrud cillum. Commodo labore enim adipisicing adipisicing mollit consequat duis dolor magna dolore eu. Amet sunt adipisicing irure consectetur esse sit labore aute velit laborum deserunt est minim eu. Officia non exercitation laborum laborum fugiat. Mollit est do elit dolore. Ex consectetur ea anim deserunt consequat. Velit in nostrud ea eiusmod Lorem consequat labore esse sunt anim aliquip reprehenderit consequat laboris.