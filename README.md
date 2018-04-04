# UAlberta-Course-Check / <i>Véri-Cours-UAlberta</i>
### iOS tool to maybe be better than Academic Requirements | <i>Outil pour iOS peut-être mieux que Academic Requirements</i>

## Background | <i>Mise en scène</i>
The 'Academic Requirements' function was added to the University of ALberta's (UAlberta) BearTracks in early 2017, as a way for students to check their course requirements at their own want and discretion, without an advisor manually configuring a Course Map sheet. This also allowed advisors to reduce their workload by automating the process online, using the most recent database and calendar. And while the aesthetic and overall design of the feature is basic by design, it is a comprehensive tool that, **given the requisite data**, provides an accurate service for all students at UAlberta.

<i>La fonction </i>'Academic Requirements'<i> (Exigences Académiques) fut ajoutée au système BearTracks de l'Université de l'Alberta (UAlberta) au début de 2017. Avec ceci, les élèves sont capables de vérifier leurs exigences de cours quand ils veulent, et sans qu'une conseillère rentre les donnés manuellement dans une feuille de route. En plus, les conseillières ont moins de travail à faire, puisque le processus est digitale et utilise les donnés et calendriers les plus à jours. Même si le client-web est très simple et un peu laide, l'outil est compréhensif, et **avec des données corrects** produit des résultats fiables pour toute étudiant à UAlberta.</i>

## Problem 1: Incomplete data | <i>Problème 1: Données incomplets</i>
While it is apparent that great care was taken to ensure that there was no gaps in the database of course and program information, as is always the case there were some elements that were lost. While it can be argued that advisors would have had more incomplete data for themselves if done manually, it still remains the case that advisors at many faculties are simply not willing to do a manual check of courses until graduation. **Therefore, for many students, Academic Requirements has become a de facto official source for this information**, whether by advisor referral or apathy. Having any gaps in these databases can therefore derail a graduation effort if the problem is not fixed. However, any additions to these databases to fill in the information is subject to enormous bureaucratic overhead, faculty verifications etc. etc.
Our tool hopes to be able to update its own internal database much quicker as changes come up and errors are spotted, via on-the-fly web-pushed updates and App Store updates.

<i>C'est apparent qu'une grande soin a été prise dans la migration des données pour assurer le moindre de perte de données; pourtant, comme il est toujours le cas, certaines éléments ont été perdus. Tout en acceptant l'argument que les conseillères auront peut-être une plus grande perte de données lors d'une feuille de route manuel, de plus en plus ces conseillères refusent de le faire du tout jusqu'au vérification de graduation. C'est alors le cas que **pour une grand nombre d'étudiants l'outil </i>Academic Requirements<i> est une source d'info 'officielle'.** Lors, chaque abscence de données représente une danger à la graduation sans qu'une action est prise pour la corriger. Cependant, les corrections sont difficiles à faire, et ont besoin d'une montant énorme de vérifications, bureaucracie, etc. etc.
Avec notre outil, on espère de pouvoir mettre à date le registre interne de façon immédiat au besoins qui viennent, soit par des mises-à-jour par App Store ou par des données téléchargés par Internet.</i>

## Problem 2: Exceptions to the rule | <i>Problème 2: Des exceptions exceptionelles</i>
/To be added/ | <i>/À être rempli/</i>

## Problem 3: Mobile Woes | <i>Problème 3: Immobile</i>
Like all of BearTracks, navigating the interface of the Academic Requirements on a mobile device is horrendous. In fact, on mobile it is still difficult to even access it: the 'tab' link is hidden in the side menu with no homepage button to access it, meaning a very very cumbersome access on any mobile device. Further, **the layout of the tool itself is entirely Desktop-oriented**, with tiny icons and in-line rendered JavaScript elements for control interfaces. On mobile these are a nightmare to work with. Additionally, given the number of elements being loaded, some mobile browsers lag or partially load the page, leaving blank spaces that eventually get filled as the browser renders the page. This, combined with the bare-bones layout (described in Problem 4) makes the tool undesirable for many students who simply wish to check their course progression on-the-go (along with the entire BearTracks experience; that is outside the immediate scope of this project).
Given that a majority of web traffic is now mobile, and that the digital landscape has heavily shifted to mobile-friendly development, this is unacceptable going into the future, given that it does not satisfy the needs of the present.
Our tool will be inherently mobile-first, and will be navigable on-the-go. It will be future-facing, and will be scaleable to accommodate the future of UAlberta's registrar needs.

<i>Comme tout outil sur BearTracks, la navigation du client Exigences Académiques est affreuse. Même accéder l'outil est un défi sur mobile, puisque le lien d'accès est caché dans le menu de navigation, et il n'y a pas de moyen d'accès sur la page principale. En plus, **l'organisation de l'outil est entièrement conçu pour les desktops**, y inclus les boutons minuscules et beaucoup d'éléments de contrôle JS, qui sont horribles sur mobile. Additionellement, puisqu'on télécharge beaucoup d'éléments, certaines navigateurs mobiles ont des difficultés à afficher la page entière à la fois, ce qui laisse des espaces vides qui s'affichent après un délai. Combiné avec l'organisation basique (discuté au Problème 4) l'outil devient indésirable pour grand nombre d'étudiants qui veulent simplement voir leur progrès académique sur demande (y compris BearTracks au complèt; ceci fut hors du vision de ce projet).
Puisque la majorité de l'accès Internet se fait sur mobile, et que l'environnement digitale fut dirigée envers une inclusion des clients mobiles, ceci démeure inacceptable pour le futur, vu que les exigences modernes fut non-satisfaites.
Notre outil sera d'avantage pour les mobiles, pour faciliter la navigation mobile. L'outil sera préparé pour le futur, y compris le futur des besoins du registrar à UAlberta.</i>

## Problem 4: Limitations of existing design | <i>Problème 4: Limitations du style</i>
The current interface, much like the rest of BearTracks, is extremely basic and simple. While this may have helped to deploy the feature in good time, the current Academic Requirements layout, aesthetic, and design leaves a lot to be desired. Moreover, it seems like **this is a failing of the engine powering BearTracks**, as this seems to be the most advanced it can get without separating the tool from the engine. Given the likely license agreements for the engine and legal shenanigans that would occur if a new system was developed internally by the registrar, an independent work-around would seem like the only way to truly spur changes to the system, were said workaround to gain enough traction.
The design should be easily navigable, easy to understand, and should allow multiple perspectives on the same information, so that the end-user can get the best picture possible of how their courses are fulfilling their Academic Requirements. That is, after all, the goal for the tool in general. However, the existing tool has a confusing layout, with useful information buried in submenus and no holistic overview available. Therefore, reading through the academic requirements is nowhere near as intuitive as the Course Outline sheets of old, and impedes a student's ability to dissect the information being offered in a useful way.
Our tool aims to redesign the entire interface, giving perspectives like 'remaining credits' and 'fulfilments by course' to allow a better understanding. Better collapsible menus and potentially search should help data to be viewed and dissected as per a student's need. Potentially, course suggestions could be added in the future (to help fill out incomplete sections).

<i>Le client actuel, bien comme BearTracks en général, est basique et entièrement simple. Pour une implémentation rapide, cela fait beaucoup de sens. Pourtant, ca ne devrait pas être le style finale de l'outil, puisque c'est inadéquat. Pourtant, il nous semble que **ceci est une faillite du logiciel sur laquelle opère BearTracks**, et c'est peut-être le plus avancée que l'outil pourrait être, sans enlever l'outil du logiciel. Alors qu'un logiciel provenant d'une développement interne aurait probablement des complications de licence et alors de légalité, une solution indépendante est une opportunité de forcer l'innovation, si cette solution ait une adoption assez large.
La conception et le style de l'outil devrait être facile à naviger, facile à comprendre, et devrait permettre une grand nombre de perspectives dans lesquels on peut voir l'information, alors que quand qu'on l'utilise on peut voir le mieux que possible le progrès dans les Exigences Académiques; d'ailleurs, ceci est l'objectif principale de l'outil. Pourtant, l'outil actuel est en format confusante, et manque une survol adéquat. On peut conclure alors que le système est beaucoup moins utile qu'une feuille de route, et pourrait bloquer une interprétation conclusive des informations fournis.
Notre outil veut complètement rebâtir le client, pour faciliter les nombreuses perspectives des infos nécessaires pour faire ses propres conclusions comme étudiant. Quelques exemples de perspective pourrait être 'crédit non-satisfaites' et 'exigences satisfaites par cours'. On pourrait même ajouter des suggestions pour remplir des crédits dans le futur.</i>
