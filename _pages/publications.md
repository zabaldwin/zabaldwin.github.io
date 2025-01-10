---
layout: archive
permalink: /publications/
author_profile: true
---

<div>
  <h2 style="cursor: pointer;" onclick="toggleVisibility('gluex')">➤ Publications Associated with GlueX</h2>
  <div id="gluex" style="display: none;">
   
  </div>
</div>

<div>
  <h2 style="cursor: pointer;" onclick="toggleVisibility('lhcb')">➤ Publications Associated with LHCb</h2>
  <div id="lhcb" style="display: none;">
    
  </div>
</div>


<script>
function toggleVisibility(id) {
  const section = document.getElementById(id);
  section.style.display = section.style.display === 'none' ? 'block' : 'none';
}
</script>
