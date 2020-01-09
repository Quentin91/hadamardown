
<!-- README.md is generated from README.Rmd. Please edit that file -->

# hadamardown

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
<!-- badges: end -->

The **hadamardown** package provides a handy template for writing a
thesis for **Ecole doctorale de mathématiques Hadamard** with R and
markdown. It is based of the
[thesisdown](https://github.com/ismayc/thesisdown) package.

**As of now, documentation is not finished.**

Example for **Université
Paris-Saclay**:

|                Front page                 |                Back cover                 |
| :---------------------------------------: | :---------------------------------------: |
| <img src="inst/img/output_saclay_1.jpg"/> | <img src="inst/img/output_saclay_2.jpg"/> |

Example for **Institut Polytechnique de
Paris**:

|               Front page               |               Back cover               |
| :------------------------------------: | :------------------------------------: |
| <img src="inst/img/output_ipp_1.jpg"/> | <img src="inst/img/output_ipp_2.jpg"/> |

Official EDMH templates are provided
[here](https://www.universite-paris-saclay.fr/fr/formation/doctorat/ecole-doctorale-de-mathematiques-hadamard-edmh#page-de-garde-des-theses-de-l-edmh).

These entities are available by default with their logo:

  - Établissement de regroupement :
      - [Université
        Paris-Saclay](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/edmhsaclay.jpg)
      - [Institut Polytechnique de
        Paris](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/edmhipp.jpg)
  - Établissement inscripteur
        :
      - [Centrale-Supélec](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/centralesupelec.jpg)
      - [École des Hautes Études Commerciales de
        Paris](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/hec.jpg)
      - [École
        Polytechnique](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/polytechnique.jpg)
      - [École Nationale de la Statistique et de l’Administration
        Économique](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/ensae.jpg)
      - [École Nationale Supérieure de Techniques
        Avancées](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/ensta.jpg)
      - [École Normale
        Supérieure](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/ensulm.jpg)
      - [École Normale Supérieure
        Paris-Saclay](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/ensparissaclay.jpg)
      - [Télécom
        Paris](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/telecomparis.jpg)
      - [Télécom
        SudParis](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/telecomsudparis.jpg)
      - [Université d’Évry-Val
        d’Essonne](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/ueve.jpg)
      - [Université
        Paris-Sud](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/upsud.jpg)
      - [Université de Versailles
        Saint-Quentin-en-Yvelines](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/uvsq.jpg)
  - Établissement d’accueil
        :
      - [AgroParisTech](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/agroparistech.jpg)
      - [Commissariat à l’Énergie Atomique et aux Énergies
        Alternatives](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/cea.jpg)
      - [Institut des Hautes Études
        Scientifiques](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/ihes.jpg)
      - [Institut National de la Recherche
        Agronomique](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/inra.jpg)
  - Laboratoire d’accueil :
      - [Centre de Mathématiques Appliquées de Polytechnique, UMR 7641
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/cmap.jpg)
      - [Centre de Mathématiques et de leurs Applications, UMR 8536
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/cmla.jpg)
      - [Centre de Mathématiques Laurent Schwartz, UMR 7640
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/cmls.jpg)
      - [Centre de Recherche en Économie et Statistique, UMR 9194
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/crest.jpg)
      - [Département de Mathématiques et Applications, UMR 8553
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/dma.jpg)
      - [Fédération de Mathématiques, FR 3487
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/fdm.jpg)
      - [Groupement de Recherche et d’Études en Gestion (GREGHEC), UMR
        8071
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/greghec.jpg)
      - [Institut de Physique Théorique de Saclay, URA 2306
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/ipht.jpg)
      - [Laboratoire Alexander Grothendieck (ERL 9216
        CNRS)](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/lag.jpg)
      - [Laboratoire de Mathématiques et Modélisation d’Évry, UMR 8071
        CNRS-INRA](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/lamme.jpg)
      - [Laboratoire de Mathématiques d’Orsay, UMR 8628
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/lmo.jpg)
      - [Laboratoire de Mathématiques de Versailles, UMR 8100
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/lmv.jpg)
      - [Laboratoire Traitement et Communication de l’Information, UMR
        5141
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/ltci.jpg)
      - [Mathématiques et Informatique Appliquées du Génome à
        l’Environnement, UR
        1404](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/maiage.jpg)
      - [Mathématiques et Informatique Appliquées, UMR 518
        INRA](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/mia.jpg)
      - [Services Répartis, Architectures, Modélisation, Validation,
        Administration des Réseaux, UMR 5157
        CNRS](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/samovar.jpg)
      - [Unité de Mathématiques Appliquées,
        ENSTA-CNRS-INRIA](inst/rmarkdown/templates/edmh_thesis/skeleton/logos/uma.jpg)

Please feel free to open an issue or contact me if you notice a typo or
a lack of updates in graphics guidelines.
