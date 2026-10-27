# Hi, I'm Sunbin Kim

MIT LGO Fellow (MBA, MIT Sloan + SM, Civil and Environmental Engineering).
Before MIT, six-plus years on simulation and testing for autonomous driving and perception.
Lately I build tools around AI hardware and AI agents, and write about what I learn.

## Building
- **[paper2video](https://github.com/SunandBean/paper2video)**: a Claude Code skill that turns an arXiv paper into a narrated explainer video. Every number on screen is checked against the paper before it renders.
- **Generative models on one Tenstorrent p100a**: seven open image, video, and music models on a single Blackhole card, three with no earlier Tenstorrent implementation.
  [FLUX.2 klein](https://github.com/SunandBean/tt-flux2-klein) · [Z-Image Turbo](https://github.com/SunandBean/tt-z-image-turbo) · [Wan 2.2](https://github.com/SunandBean/tt-wan22) · [Qwen-Image-Edit](https://github.com/SunandBean/tt-qwen-image-edit) · [HiDream-O1](https://github.com/SunandBean/tt-hidream-o1) · [ACE-Step](https://github.com/SunandBean/tt-acestep) · [DiffRhythm](https://github.com/SunandBean/tt-diffrhythm) · [What I learned](https://sunbin.kim/tenstorrent-p100a-series-look-back/)
- **MIT Driverless**: MIT's student autonomous racing team, where I co-lead sponsorship.
- **[Sunbin in the Paddock](https://sunbin.kim)**: writing on motorsports, mobility, MIT, and building with AI.

## How I work
- **Check before shipping.** Each port was validated against a CPU reference, first with random weights and then real ones. paper2video ties every claim to a quote or table row.
- **License first.** Anything public uses commercially usable models and assets. I dropped a research-only model once that mattered.
- **Fit the hardware you have.** Most official demos assume four chips, so I rewrote them for one card and let several services [share it with a lock file](https://sunbin.kim/tenstorrent-p100a-sharing-one-card-lock-file/).
- **Write it down.** A 14-part devlog covers the p100a work, including [what went wrong when publishing](https://sunbin.kim/publishing-p100a-ports-git-history/).

## Before MIT
Hyundai Motor Company (research engineer, AV simulation and regulatory compliance) · Seoul Robotics (simulation and infrastructure) · Mando (simulation-based testing)

## Interests
AV simulation and testing · running generative models on new AI hardware · autonomous racing · agent tooling · making research easier to understand

## Contact
[LinkedIn](https://www.linkedin.com/in/sunbin-kim) · [Blog](https://sunbin.kim)
