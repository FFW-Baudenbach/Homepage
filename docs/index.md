---
title: News
hide: 
  - footer
  - toc
---

# Herzlich willkommen
![Logo](assets/logo_ffw_neu.png){ loading=lazy }

## Letzter Einsatz
<div id="iframe-wrapper-131" style="position: relative; width: 540px;">
   <iframe
      id="e-view-131"
      src="https://www.firemanager.de/portal/einsatze/ZEej568Ipc"
      style="width: 100%; border: none; height: 700px;">
   </iframe>
   <!-- Click overlay -->
   <a
      href="Eins%C3%A4tze/Eins%C3%A4tze/"
      style="
      position: absolute;
      inset: 0;
      z-index: 10;
      text-decoration: none;
      cursor: pointer;
      ">
   </a>
</div>
<script>
   (function () {
     const iframe = document.getElementById("e-view-131");
     const wrapper = document.getElementById("iframe-wrapper-131");
     window.addEventListener("message", (event) => {
       if (event.data?.type === "resize" && !isNaN(event.data.height)) {
         const height = event.data.height + "px";
         iframe.style.height = height;
         wrapper.style.height = height; // 🔑 keep overlay in sync
       }
     });
})();
</script>

## Aktuelle News