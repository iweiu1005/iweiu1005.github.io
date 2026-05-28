function showSectionFromHash() {

    const hash = location.hash;

    const sections = document.querySelectorAll(".section");

    sections.forEach(section => {

      section.style.display = "none";

      section.classList.remove("flex-column-center");

    });

    if (hash) {

      const activeSection = document.querySelector(hash);

      if (activeSection) {

        activeSection.style.display = "flex";

        activeSection.classList.add("flex-column-center");

      }

    }

  }

  showSectionFromHash();

  window.addEventListener("hashchange", showSectionFromHash);