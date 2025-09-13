# Presentations

Below are selected talks, demos, and guest lectures. New uploads will appear on my YouTube channel.

---

## YouTube Presentations

<!-- Replace the src with your YouTube video ID -->
<div class="talk-grid">
  <div class="talk-card">
    <div class="video-wrapper">
      <iframe
        src="https://www.youtube.com/embed/VIDEO_ID_HERE"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>

    <h3>Talk title goes here</h3>
    <p class="talk-meta">
      :material-calendar: 12 Sep 2025 &nbsp;&middot;&nbsp; :material-map-marker: UQ, Brisbane
    </p>

    <!-- Action buttons -->
    [:material-youtube: Watch on YouTube](https://youtu.be/r9Q_59hO4y8&t=446s&ab_channel=ARCCoEforPlantSuccess){ .md-button .md-button--primary }
    [:material-timer-play: Short clip](https://youtu.be/VIDEO_ID_HERE?t=120){ .md-button }
    [:material-chat-question: Q&A timestamps](#qa){ .md-button }

    <details class="abstract">
      <summary>:material-text: Abstract</summary>
      <p>
        One-paragraph summary of the talk. What problem do we solve, why it matters,
        and 2–3 key takeaways for the audience.
      </p>
    </details>

    <details>
      <summary id="qa">:material-comment-quote: Q&A notes</summary>
      <ul>
        <li><strong>05:12</strong> – How SUC interacts with tillering</li>
        <li><strong>12:40</strong> – Linking PSoup to APSIM</li>
        <li><strong>21:03</strong> – Future experiments</li>
      </ul>
    </details>
  </div>
</div>

---

## Slides & Resources

<!-- Add more items as needed -->
<div class="resource-grid">

  <div class="resource-card">
    <h4>:material-file-ppt: Slides (PPTX)</h4>
    <p>Full deck used in the talk.</p>
    [:material-download: Download PPTX](assets/slides/TALK_NAME.pptx){ .md-button }
  </div>

  <div class="resource-card">
    <h4>:material-file-pdf-box: Slides (PDF)</h4>
    <p>Printer-friendly version.</p>
    [:material-download: Download PDF](assets/slides/TALK_NAME.pdf){ .md-button }
  </div>

  <div class="resource-card">
    <h4>:material-file-document-multiple: Handout / One-pager</h4>
    <p>Key figures, equations, and references.</p>
    [:material-download: Download PDF](assets/handouts/TALK_NAME_1pager.pdf){ .md-button }
  </div>

  <div class="resource-card">
    <h4>:material-link-variant: Project page</h4>
    <p>Data, code, and supplementary material.</p>
    [:material-github: Repository](https://github.com/CMits/YourRepo){ .md-button }
  </div>

</div>

---

## More videos

- [:fontawesome-brands-youtube: Full YouTube playlist](https://www.youtube.com/@YourChannelName/playlists)
- [:fontawesome-brands-tiktok: TikTok clips](https://www.tiktok.com/@YourTikTokHandle)

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
