Initialisation du projet et création de l'espace Git

Création des fichier index.html et style.css

Ajout de Bootstrap v5.0 dans index.html

Ajout de JQuery

Added JQuery and Bootstrap files to .gitignore 

Added Navbar and Logo to Header

Added Footer with newsletter and footer Menu

Changes in Grid layout for better reponsive behaviour (mobile-first)
Added nos-evenements.html and nous-contacter.html to the project

Added navbar and breadcrumb to new pages / removed search bar from all pages due to lack of PHP

Modified visual ascept of navbar and breadcrumb and added style.css to the project

Added content to nous-contacter.html, including: card, form (with popup) and google maps

Added content to nos-evenements.html, including: card with collapse for the main event, thumbnails for future events and CSS style 

Deployed the website to jordanfndz.fr (OVH) with FileZilla 

Modified Forms with Submit fonction but using popup as a return. This is causing forms to submit even with empty fields as a result but PHP and JS are required otherwise

Modified CSS for: the modals with h4 in uppercase + icon, thumbnails and Team font-size for mobile is now easier to read

Modified Titles wording

Removed local bootstrap and replaced by CDN for better loading time (as advised by Google PageSpeed Insights) and removed those files from 
.gitignore

Corrected minor bugs in navbar menu on aria-controls value that was incorrect. Reviewed indentation on all html pages.

!!! WARNING : images are not uploaded on the server on purpose because of the 10mo free plan offered by OVH. Using links that is slowing the loading time !!!

!!! WARNING : Newsletter subscription and Contact form will submit even if fields are left empty.. This is made on purpose to simulate a response with a modal when submitting. Once PHP and Js are included, normal responce will be expected as they all have a "required" attribut !!!

Added SSL certificate to website via OVH and htpps via .htaccess file

Modified issue with multiple H1 in carousel and corrected id names for better URL design in index.hmtl

Added missing label to Newsletter form-group