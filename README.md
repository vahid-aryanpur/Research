<!-- Start of Tabs Section -->
<style>
/* Styles for the tab buttons */
.tab {
  overflow: hidden;
  border-bottom: 1px solid #ccc;
}

.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

.tab button:hover {
  background-color: #ddd;
}

.tab button.active {
  background-color: #ccc;
}

/* Styles for the tab content */
.tabcontent {
  display: none;
  padding: 20px 0;
  border-top: none;
}

</style>

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Research')" id="defaultOpen">Research</button>
  <button class="tablinks" onclick="openTab(event, 'Teaching')">Teaching</button>
</div>

<div id="Research" class="tabcontent">
  <h2>Research</h2>
  <p>My name is Vahid Aryanpur. I teach and study energy systems modelling, energy transition, and energy and climate policy. I use GitHub mostly for modeling, result visualization, data, and teaching material sharing.</p>

  <h3>Research Publications</h3>
  <ul>
      <li>**[Decarbonising Trucks](https://www.nature.com/articles/s41598-024-52682-4)**: V. Aryanpur, F. Rogan. _Nature Scientific Reports_ (2024)</li>
      <li>**[Decarbonising Private Cars](https://www.sciencedirect.com/science/article/pii/S0306261922004676)**: V. Aryanpur et al. _Applied Energy_ (2022)</li>
      <li>**[TIM Documentation Paper](https://gmd.copernicus.org/articles/15/4991/2022/)**: O. Balyk et al. _Geoscientific Model Development_ (2022)</li>
  </ul>
</div>

<div id="Teaching" class="tabcontent">
  <h2>Teaching</h2>
  <p>Details about teaching materials, courses, and lectures will be shared here.</p>
</div>

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none"; 
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Open default tab
document.getElementById("defaultOpen").click();
</script>
<!-- End of Tabs Section -->

