<header class="masthead">
  <h1>GRIZZLY</h1>
  <p>Your AI development OS 🐾</p>
</header>

<div class="artwork-stage" aria-label="Grizzly mascot artwork">
  <img class="bear" src="assets/grizzly-boot.png" alt="Grizzly mascot wearing glasses and a hoodie" width="240" />
</div>

<section class="idea-card" aria-labelledby="idea-title">
  <p class="eyebrow"><strong>01 / THE IDEA</strong></p>

  <h2 id="idea-title">Built for focus</h2>
  <p>Grizzly is an opinionated OS aiming to maximize AI development productivity by removing nearly all normal desktop GUI and keeping only what's truly important: 100% focus on your work.</p>
  <p>The tiling concept makes your windows not dock into place, and you can have up to 10 workspaces pre-configured for how you work.</p>
  <p>This is fundamentally a much better way to work for developers than the broken desktop metaphor.</p>
  <p>Grizzly is built on Debian, inheriting decades of rock-solid Linux, with performance optimized out of the box.</p>
  <p>Our main goal is to release Grizzly as a quality product that's easy to live with yet flexible so you can make it your own.
</p>

  <p>Grizzly ships with</p>
  
  - Native:
    - TileToShare which makes it super easy to share specific tiles during online meetings.
    - The grizzly cli which makes it wonderfully simple to work with and save the state of Grizzly and also has built in extensibility to support your own workflows. The cli has first class support for many things out of the box, e.g. apt package management with transactional commit/rollback.
    - Theming
    - System settings, updates etc.
  - Hyprland + Quickshell
  - VS Codium
  - Firefox
  - 1Password
  - Foot
  - git
  - Lazygit
  - docker, compose and sandbox
  - Openssh, disabled and locked down to you can configure it however you want
  - Dolphin and Double Commander filemanagers
  - paint.software (blazingly fast really nice paint.net alternative for Linux)
  - Easy Effects for full control of your audio stream in meetings, recordings etc
  - 7zip
  - Libre Office
  - Keybindings
  - And more...

  We have deliberately chosen not to ship with
  - Any AI harness
  - Any docker management frontend. We like Portainer rather than Docker desktop. We like Dozzle too to view the docker logs.

  Future plans
  - Bundles that you can install using the cli
  - A net installer that let's you pick those bundles at install time 
  
  Grizzly installs extremely fast!

  - lab tests from iso on disk to VM disk: < 1 minute
  - Clean USB-3 install to real hardware: TBD

  Shipping soon!
</section>
