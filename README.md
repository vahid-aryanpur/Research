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
  <button class="tablinks" onclick="openTab(event, 'Contact')">Contact</button>
</div>

<div id="Research" class="tabcontent">
  <h2>About Me</h2>
  <p>My name is Vahid Aryanpur. I teach and study energy systems modelling, energy transition, and energy and climate policy. I use GitHub mostly for modelling, result visualisation, data, and teaching material sharing.</p>

  <h3>Recent Studies</h3>
  <ul>
    <!--* **[Accelerated vs Delayed Climate Action](https://www.nature.com/articles/s41598-024-52682-4)**: V. Aryanpur et al. _npj Climate Action_ (2024) -->
    <li><strong><a href="https://www.nature.com/articles/s41598-024-52682-4">Decarbonising Trucks</a></strong>: V. Aryanpur, F. Rogan. <em>Nature Scientific Reports</em> (2024)</li>
    <li><strong><a href="https://www.sciencedirect.com/science/article/pii/S0306261922004676">Decarbonising Private Cars</a></strong>: V. Aryanpur et al. <em>Applied Energy</em> (2022)</li>
    <li><strong><a href="https://gmd.copernicus.org/articles/15/4991/2022/">TIM Documentation Paper</a></strong>: O. Balyk et al. <em>Geoscientific Model Development</em> (2022)</li>
    <li><strong><a href="https://github.com/MaREI-EPMG/times-ireland-model">TIMES-Ireland Model (TIM)</a></strong>: Model database is available on GitHub and archived on <a href="https://zenodo.org/records/13497444">Zenodo</a></li>
  </ul>

  <h4>Research Profiles</h4>
  <ul>
    <li><a href="https://www.ucc.ie/en/epmg/people/">Energy policy and modelling group</a></li>
    <li><a href="https://www.linkedin.com/in/vahidaryanpur/">LinkedIn</a></li>
    <li><a href="https://scholar.google.com/citations?user=AE1CRXgAAAAJ&hl=en">Google Scholar</a></li>
    <li><a href="https://www.researchgate.net/profile/Vahid-Aryanpur">ResearchGate</a></li>
    <li><a href="https://orcid.org/0000-0001-7390-704X">ORCID</a></li>
  </ul>
</div>

<div id="Teaching" class="tabcontent">
  <h2>Teaching</h2>
  <p>Details about teaching materials, courses, and lectures will be shared here.</p>
</div>

<div id="Contact" class="tabcontent">
  <h2>Contact</h2>
  <p><strong>E-mail:</strong> vahid.aryanpur@ucc.ie</p>
  <p><strong>Address:</strong> Energy Policy and Modelling Group, MaREI, UCC, Lee Rd, Sunday's Well, Cork, T23 XE10</p>
  <ul>
    <li><a href="https://www.ucc.ie/en/epmg/people/">Energy policy and modelling group</a></li>
    <li><a href="https://www.linkedin.com/in/vahidaryanpur/">LinkedIn</a></li>
    <li><a href="https://scholar.google.com/citations?user=AE1CRXgAAAAJ&hl=en">Google Scholar</a></li>
    <li><a href="https://www.researchgate.net/profile/Vahid-Aryanpur">ResearchGate</a></li>
    <li><a href="https://orcid.org/0000-0001-7390-704X">ORCID</a></li>
  </ul>
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


