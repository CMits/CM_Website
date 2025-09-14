# Presentations

Below are selected talks, demos, and guest lectures. New uploads will appear on my YouTube channel.

---

## YouTube Presentations

<!-- Replace the src with your YouTube video ID -->
<div class="talk-grid">
  <div class="talk-card">
    <div class="video-wrapper">
      <iframe
        src="https://www.youtube.com/embed/r9Q_59hO4y8"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>

    <h3>Leveraging Parsimonious Model PSoup for Cross-Scale Plant Modeling</h3>
  </div>
</div>

---

## Slides & Resources

### Science Web


These slides present the idea behind my **Science Web** project — a vision for connecting research as living, executable apps.  
For more details, deep dives, and protocols, see **[Science_Web](Science_Web.md)**.

<iframe src="../assets/slides/Living_Research_Web_Pitch.pdf" width="100%" height="600" style="border:none;"></iframe>

[⬇️ Download PPTX](assets/slides/Living_Research_Web_Pitch.pptx){ .md-button .md-button--primary }

---

<!-- Lightweight styles just for this page -->
<style>
  .talk-grid, .resource-grid {
    display: grid;
    gap: 1.2rem;
  }
  .talk-grid { grid-template-columns: 1fr; }
  .resource-grid { grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); }

  .talk-card, .resource-card {
    background: var(--md-default-bg-color);
    border: 1px solid var(--md-code-bg-color);
    border-radius: 14px;
    padding: 1rem 1.1rem;
    box-shadow: 0 8px 24px rgba(0,0,0,.06);
  }

  .video-wrapper {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    margin-bottom: .8rem;
    border-radius: 12px;
    overflow: hidden;
  }
  .video-wrapper iframe {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
  }

  .talk-meta {
    opacity: .75;
    margin-top: -0.25rem;
    margin-bottom: .6rem;
  }

  .abstract summary {
    font-weight: 600;
    cursor: pointer;
    margin-top: .4rem;
    margin-bottom: .25rem;
  }

  /* Button spacing */
  .md-button { margin-right: .4rem; margin-bottom: .4rem; }
</style>
