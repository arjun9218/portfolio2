# Arjun Gururajan — portfolio

A responsive, dependency-free portfolio built with HTML, CSS, and JavaScript. The newsletter architecture case study lives in `newsletter-platform.html`. Every résumé download points to the one-page backend and platform engineer PDF. The site includes a local copy of the portrait from the previous portfolio.

## Preview

Run `python3 -m http.server 8000` in this directory, then open `http://localhost:8000`.

The site can be deployed as static files to GitHub Pages or another static host. Keep both HTML pages, `assets/`, `output/pdf/`, and `CNAME` together when publishing so the case study, portrait, custom domain, and résumé download work. `output/Arjun_Gururajan_GitHub_Pages.zip` contains the deployable files at the correct paths.

To regenerate the downloadable résumé after editing its content, run `tools/generate_staff_resume.py` with a Python environment containing ReportLab. The generated file is `output/pdf/Arjun_Gururajan_Backend_Platform_Engineer.pdf`. The contact email comes from the previous portfolio and should be checked before publishing.
