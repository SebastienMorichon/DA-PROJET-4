<h1>Réalisez une étude de santé publique avec R ou Python</h1>
<h3>Scénario</h3>
<p>Félicitations&nbsp;! Vous avez récemment rejoint une équipe de chercheurs de la <a href="http://www.fao.org/home/fr/">Food and Agriculture Organization of the United Nations (FAO)</a>, en tant que data analyst.</p>
<figure><a href="https://user.oc-static.com/upload/2020/11/23/16061289311922_Capture%20d%E2%80%99e%CC%81cran%202020-11-23%20a%CC%80%2011.06.07.png" class="oc-imageLink oc-imageLink--disabled"><img src="https://user.oc-static.com/upload/2020/11/23/16061289311922_Capture%20d%E2%80%99e%CC%81cran%202020-11-23%20a%CC%80%2011.06.07.png" alt="Food and Agriculture Organization of the United Nations"></a>
<figcaption>Food and Agriculture Organization of the United Nations</figcaption>
</figure>
<p>Son rôle&nbsp;? C’est l’un des organes qui composent l’ONU et dont l’objectif est «&nbsp;d’aider à construire un monde libéré de la faim&nbsp;».&nbsp;</p>
<p>Le responsable de l’équipe, Marc, un chercheur en économie de la santé, est particulièrement enthousiaste à l’idée de votre arrivée au sein de son équipe. En effet, ce recrutement tombe à pic car Julien, l'ancien data analyst, a récemment été muté dans une autre équipe, et la vôtre vient de se voir confier la mission de réaliser une étude de grande ampleur sur le thème de la sous-nutrition dans le monde.</p>
<p>Dès votre arrivée, vous trouvez un mail de Marc dans votre boîte mail&nbsp;:</p>
<p>&nbsp;</p>
<blockquote>
<p><strong>Objet&nbsp;</strong>: Bienvenue<br><strong>De</strong>&nbsp;: Marc<br><strong>À</strong>&nbsp;: Vous</p>
<p>Hello et bienvenue au sein de la FAO. J’espère que tu te plairas parmi nous. En tous cas, sache que je suis très content de t’accueillir au sein de mon équipe.</p>
<p>Tu es probablement au courant, mais nous avons une grosse tâche qui nous attend, et nous comptons particulièrement sur toi pour nous donner un panorama de l’état de la malnutrition dans le monde, à partir des données que tu trouveras dans le dossier en pièce jointe. Je t’invite d’ailleurs fortement à lire le <a href="https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DAN_V2_P4/Lexique+des+donne%CC%81es.pdf"><strong>Lexique des données</strong></a> qui s’y trouve, écrit par Julien. Dans ce document, tu trouveras le descriptif des différents fichiers ainsi que des notes qui te sont adressées. Nous souhaitons que tu poursuives ses recherches en répondant aux questions qu'il t'a laissé.</p>
<p>Les données sur lesquelles j’aimerais particulièrement avoir des informations sont, pour l’année 2017 :</p>
<ul>
<li>la proportion de personnes en état de sous-nutrition ;</li>
<li>le nombre théorique de personnes qui pourraient être nourries. Tu devrais pouvoir calculer ça à partir de la disponibilité alimentaire mondiale ;</li>
<li>idem pour la disponibilité alimentaire des produits végétaux ;</li>
<li>l’utilisation de la disponibilité intérieure, en particulier la part qui est attribuée à l’alimentation animale, celle qui est perdue et celle qui est concrètement utilisée pour l'alimentation humaine. Je crois que Julien avait trouvé un moyen de facilement calculer ces proportions.</li>
</ul>
<p>&nbsp;Ce sont les informations principales dont on aimerait que tu puisses nous rendre compte, mais toute idée additionnelle est bonne à prendre&nbsp;!&nbsp;</p>
<p>Il y a aussi Mélanie, une autre chercheuse de l’équipe qui avait quelques demandes. Elle devrait prendre contact avec toi rapidement à ce sujet.</p>
<p>N’hésite pas à venir me voir si tu as la moindre question&nbsp;!</p>
<p>Marc.</p>
<p>PJ&nbsp;:&nbsp;<a href="https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/DAN-P4-FAO.zip"><strong>données FAO.zip</strong></a>&nbsp;</p>
</blockquote>
<p>&nbsp;</p>
<p>À peine le temps de préparer votre café matinal, que vous recevez un message de Mélanie par messagerie instantanée&nbsp;:</p>
<p>&nbsp;</p>
<div class="oc-tableContainer"><table>
<tbody>
<tr>
<td>
<p><strong>Mélanie : </strong>Hello, j’espère que tout va bien et que t’intègres bien. En tout cas, je te souhaite à mon tour la bienvenue dans notre équipe.</p>
</td>
</tr>
<tr>
<td>
<p><strong>Vous :&nbsp;</strong>Merci&nbsp;! Je prends mes marques petit à petit. Marc m’a dit que tu avais une demande particulière&nbsp;?</p>
</td>
</tr>
<tr>
<td>
<p><strong>Mélanie :&nbsp;</strong>Tout à fait&nbsp;! Je souhaiterais avoir une étude un peu plus fine pour chacun des pays. Par exemple, j’aimerais que tu puisses nous donner les pays pour lesquels la proportion de personnes sous-alimentées est la plus forte en 2017, ceux qui ont le plus bénéficié d’aide depuis 2013, ceux ayant le plus/le moins de disponibilité/habitant, etc., et toutes les infos que tu trouverais utiles pour mettre en relief les pays qui semblent être le plus en difficulté, au niveau alimentaire.</p>
</td>
</tr>
<tr>
<td>
<p><strong>Vous :&nbsp;</strong>OK pas de soucis, je vais regarder ça.</p>
</td>
</tr>
<tr>
<td>
<p><strong>Mélanie :&nbsp;</strong>Super, bon courage !</p>
</td>
</tr>
<tr>
<td>
<p><strong>Vous</strong> :&nbsp;Merci, à bientôt !</p>
</td>
</tr>
</tbody>
</table></div>
<p>Vous gardez en tête toutes ces requêtes, et attaquez immédiatement votre «&nbsp;exploration&nbsp;».</p>
<aside data-claire-semantic="information">
<p>Dans ce projet, vous êtes libre d’utiliser le langage de programmation de votre choix entre <strong>R et Python</strong> pour mener à bien votre analyse. Vous pouvez utiliser choix Jupyter (pour R et pour Python) ou R Markdown (pour R).</p>
</aside>
<h3>Livrable</h3>
<ul>
<li>Le notebook R Markdown ou Jupyter vous ayant permis de calculer/trouver l’ensemble des résultats demandés.</li>
</ul>
