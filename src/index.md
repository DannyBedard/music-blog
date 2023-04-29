---
# This is a full listing of available Frontmatter options, available for any content (.md) file.
title: Danny Bédard
layout: page
excerpt: # used for page excerpts and META (will be overwritten if SEO used below)
author: shane-robinson # only displayed on Post lists and detail views. Defaults to _data/meta.authorURL
eleventyNavigation: # Required if want to display in Main Nav Bar
  key: main # "main" is required
  title: Accueil # as it will appear in the nav
  order: 1 # order to display in the nav (index = 1)
seo: # SEO values are used for OG and will overwrite 'title' and 'excerpt' above
  title:
  description:
  image: # used for OG:image and Twitter:image. Overrides default set in _data/meta.siteImage
hero: split # options: carousel, graphic, video, split (text & image)
heroSettings:
  height:
    mobile: # options = h-1/1 (default = full screen), h-1/2, h-1/3, h-3/4, h-9/10, h-48 (12rem, 192px), h-56 (14rem, 224px), h-64 (16rem, 256px)
    desktop: # leave blank to inherit "mobile" height (default = full screen)
  bg:
    color: # default bg-black
    image: home/danny.jpg # relative to /assets/images/
    imagePosition: # options = bg-center (default), bg-left, bg-right
    video: pixabay-john-macdougall.mp4 # local relative /assets/video/, or full https://... if remote?
    opacityMobile: opacity-50 # options opacity-n, 5, 10, 15, 20, 25, 50, 75, 100 (default)
    opacityDesktop: opacity-75 # Leave blank to inherit opacityMobile, use same options as opacityMobile
  headingText: Danny Bédard - Du piano au clavier
  headingTextColor: # default = text-white (can use any TailwindCSS text-[color]-[xxx])
  headingTextCase: # default = as typed - options: uppercase, lowercase, capitalize
  subheadingText: Plongez dans l'univers musical de ce musicien passionné
  subheadingTextColor: # Leave empty to inherit headingTextColor or default (text-white) or use any text-[color]-[xxx]
  buttonText: Contact # no button generated if left blank
  buttonURL: /contact/ # full url required. Example: https://thisdomain.com/somepage/
  buttonTextColor: # leave blank to inherit from /src/_data/colors.buttonCustom or buttonDefault
  buttonBgColor: # leave blank to inherit from /src/_data/colors.buttonCustom.bg or buttonDefault.bg
  buttonBgHover: # leave blank to inherit from /src/_data/colors.buttonCustom.bgHover or buttonDefault.bgHover
  buttonBorder: # leave blank to inherit from /src/_data/colors.buttonCustom.border or buttonDefault.border
  carousel:
    images:
      - home/danny.jpg
      - home/danny1.jpg
      - home/danny2.jpg
      - home/danny3.jpg
---

  <p>Danny Bédard est un musicien accompli, polyvalent et créatif, originaire de la belle province canadienne de Québec. Né dans une famille mélomane, Danny a grandi dans un environnement musical et a commencé à jouer de la batterie à l'âge de douze ans. Au fil des années, il a également appris à jouer de la guitare, de la basse et à chanter avant de tomber amoureux du piano.  Il a poursuivi des études en musique au Collège Lionel Groulx, situé à Sainte-Thérèse au Québec, Canada.</p>

  <p>Au collège, Danny Bédard a étudié avec des professeurs de musique renommés et a perfectionné ses compétences en jouant du piano et du clavier. Il a également eu l'occasion de jouer dans diverses formations musicales, notamment des ensembles de jazz et des groupes de musique pop.</p>

  <p>C'est au Collège Lionel Groulx que Danny Bédard a commencé à se faire un nom dans le monde de la musique. En plus de ses études, il a commencé à jouer dans des bars des clubs locaux et des évènements privés, acquérant une expérience précieuse sur scène.</p>

  <p>En tant que pianiste, claviériste, compositeur et arrangeur, Danny a la capacité de travailler dans plusieurs genres musicaux, de la pop au rock, en passant par le jazz et le classique. Il a commencé sa carrière en tant que musicien pigiste, jouant aux côtés de plusieurs artistes québécois. Avec son talent exceptionnel, il a tranquillement construit sa place sur la scène musicale, et est devenu de plus en plus demandé.</p>

  <p>Actuellement, il travaille sur un album piano solo, ce qui mettra en valeur sa sensibilité musicale unique et sa maîtrise du piano. Il participe également à plusieurs projets créatifs, où il continue à innover et à explorer de nouvelles avenues musicales, tout en offrant son savoir-faire en tant que musicien. Il est un artiste qui continue à inspirer les mélomanes de partout avec sa musique intemporelle et émouvante.</p>

