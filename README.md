# System Setup Steps
## VCStool for tracking different repositories
https://github.com/dirk-thomas/vcstool
Follow installation guide on link above to setup vcs tool to track different repos and the specific commits used for strethcer project. Once install is complete run, assuming you have already cloned stretcher_project to your [ros workspace]/src directory.
```bash
cd [your ros workspace]/src && \
vcs import < stretcher_project/stretcher.repos
```