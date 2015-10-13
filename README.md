# COSMO-beamer-template
A template for presentation with LaTeX Beamer class

This is a template to use LaTeX Beamer-class to build presentations, derived from modification of the "Torino" theme by M. Barisione. To use it, you can download and directly compile the MAIN.tex file, which includes the actual content (to be put in CONTENT.tex).

The only "flaw" of the first version of this template is about the logo: there are two layouts for the title page. The "alternative" one (set with \usetheme[alternativetitlepage=true]{...}). If you want to use the "normal" layout, you have to:
  1. set "alternativetitlepage" to false
  2. UNCOMMENT the lines starting with "\titlegraphic{...}" in MAIN.tex, otherwise you won't get any logo in the title page.
This flaw will be fixed soon.
