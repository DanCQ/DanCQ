# My GitHub Profile

<!-- Your other README content -->

<!-- Add a placeholder for the profile summary cards -->
<div id="profile-summary-cards-placeholder">
  Loading profile summary cards...
</div>

<!-- Include the script to delay the loading of profile summary cards -->
<script>
  // Function to load profile summary cards
  function loadProfileSummaryCards() {
    const placeholder = document.getElementById('profile-summary-cards-placeholder');

    // Your GitHub profile summary cards code
    const profileCards = `
      [![Profile Details](https://raw.githubusercontent.com/DanCQ/DanCQ/master/profile-summary-card-output/noctis_minimus/0-profile-details.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)
      [![Repos per Language](https://raw.githubusercontent.com/DanCQ/DanCQ/master/profile-summary-card-output/noctis_minimus/1-repos-per-language.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)
      [![Most Commit Language](https://raw.githubusercontent.com/DanCQ/DanCQ/master/profile-summary-card-output/noctis_minimus/2-most-commit-language.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)
      [![Stats](https://raw.githubusercontent.com/DanCQ/DanCQ/master/profile-summary-card-output/noctis_minimus/3-stats.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)
      [![Productive Time](https://raw.githubusercontent.com/DanCQ/DanCQ/master/profile-summary-card-output/noctis_minimus/4-productive-time.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)
      [![GitHub Streak](https://streak-stats.demolab.com/?user=DanCQ&theme=highcontrast&ring=4675b8)](https://git.io/streak-stats)
    `;

    // Replace the placeholder content with the profile summary cards
    placeholder.innerHTML = profileCards;
  }

  // Attach the loadProfileSummaryCards function to the window.onload event
  window.onload = loadProfileSummaryCards;
</script>
