<template>
  <div>
    <div class="lg:max-w-5xl mx-auto md:px-4 p-4">
      <h1 class="text-4xl font-bold">Canada COVID-19 Tracker</h1>
      <h4 class="text-xs">
        Source:
        <a
          class="border-b border-dotted text-blue-600 border-blue-600 hover:text-blue-800 hover:border-blue-800"
          target="_blank"
          href="https://www.canada.ca/fr/sante-canada.html"
        >Canada Deptartment of Health</a> &middot; Last updated 8/25/2020 7:01 p.m.
      </h4>
    </div>
    <main class="alert">
      <span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span>
      <strong>
        <i class="fas fa-exclamation-triangle"></i> Attention!
      </strong> For the most up to date information regarding COVID-19 in Canada, please consult
      <a
        href="https://www.canada.ca/fr/sante-canada.html"
      >Canada Deptartment of Health</a>. This site should not be used for life saving information - instead, rather, a source for numbers and statistics.
    </main>
    <br />
    <iframe
      src="https://experience.arcgis.com/experience/4ab8757241cc4d3fab81c8f86a501ce9"
      height="550"
      width="90%"
    ></iframe>
    <br />
    <iframe
      src="https://ourworldindata.org/grapher/total-cases-covid-19?tab=map"
      width="90%"
      height="550px"
    ></iframe>
    <p>
      Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus.
      Most people who fall sick with COVID-19 will experience mild to moderate symptoms and recover without special treatment.
    </p>
    <strong>HOW IT SPREADS</strong>
    <p>
      The virus that causes COVID-19 is mainly transmitted through droplets generated when an infected person coughs, sneezes, or exhales. These droplets are too heavy to hang in the air, and quickly fall on floors or surfaces.
      You can be infected by breathing in the virus if you are within close proximity of someone who has COVID-19, or by touching a contaminated surface and then your eyes, nose or mouth.
    </p>
    <hr style="width:100%;text-align:left;margin-left:0">
    <div class="pb-4">
      <h4 class="text-xs">
        Developed by Joey Cadieux &middot;
        <a
          class="text-blue-600"
          href="mailto:joeycadieux161@gmail.com"
        >Contact Me</a> &middot;
        <a class="text-blue-600" href="https://forms.gle/Z3mfTuL72Tt4HrKm7">Found an issue?</a>
      </h4>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {}
};
</script>

<style>
main {
  padding: 100px;
}
.alert {
  padding: 20px;
  background-color: #f44336;
  color: white;
}
.closebtn {
  margin-left: 15px;
  color: white;
  font-weight: bold;
  float: right;
  font-size: 22px;
  line-height: 20px;
  cursor: pointer;
  transition: 0.3s;
}
.closebtn:hover {
  color: black;
}
</style>