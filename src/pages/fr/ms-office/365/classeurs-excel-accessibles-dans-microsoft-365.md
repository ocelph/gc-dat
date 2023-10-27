---
title: Classeurs Excel accessibles dans Microsoft 365
description: Pratiques accessibles pour la création de documents Microsoft Excel.
layout: layouts/base.njk
toggle: accessible-excel-workbooks-in-microsoft-365
fontIcon: fa-file-excel
---

<h2>Vérificateur d’accessibilité</h2>
<p>Microsoft Office (Word, Excel, PowerPoint) comporte un programme intégré de vérification de l’accessibilité. Le vérificateur ne détecte pas tous les problèmes, mais recherche des éléments, comme les textes de remplacement manquants, les titres de diapositive en double et les problèmes potentiels d’ordre de lecture.</p>


<p>Comment utiliser le vérificateur d’accessibilité&nbsp;:</p>
<ol>
	<li>Activez l’onglet <strong>Fichier</strong> &gt; <strong>Informations</strong> &gt; <strong>Vérifier l’absence de problèmes</strong> &gt; <strong>Vérifier l’accessibilité.</strong></li>
	<li>Examinez les résultats dans le volet <strong>Vérificateur d’accessibilité</strong>.</li>
	<li>Corrigez les problèmes énumérés. Au bas du volet, vous trouverez des renseignements pratiques pour comprendre et résoudre les différents problèmes.</li>
</ol>

<div class="row">
	<div class="col-md-7 mrgn-bttm-md">
		<img class="img-responsive"  src="{{ rootPath }}img/fr/office365/excel-365-001.jpg" alt="Capture d’écran de menu vérification de l’accessibilité" />
	</div>
</div>

<p>Le <strong>vérificateur d’accessibilité</strong> peut aussi être accédé dans le ruban du haut sous le l’onglet «&#8201; <strong>Révision</strong> &#8201;» &gt; <strong>Vérifier l'accessibilité</strong>. Ensuite, cocher l’option «&#8201; vérificateur d’accessibilité conserver en cours d’exécution pendant que je travaille &#8201;» afin de vérifier l’accessibilité en temps réel.</p>

<h2>Tableaux</h2>
<p>Évitez les structures de tableau complexes dans tous les documents. Si les tableaux comprennent des tableaux imbriqués, des cellules fusionnées, des cellules fractionnées, des lignes ou des colonnes vides, ces tableaux entravent la navigation des lecteurs d’écran. Lorsque vous utilisez un tableau, concevez-le aussi simplement que possible. Donnez des titres évocateurs aux colonnes et aux lignes afin de faciliter la navigation de l’utilisateur.</p>

<h2>Onglets des feuilles de calcul</h2>
<p>Donnez des noms uniques et évocateurs à toutes les feuilles de votre document. Veillez à ce que le nom donné à chaque onglet décrive avec précision le contenu de la feuille de
	calcul. Cela facilitera la navigation à l’intérieur du classeur. Il est préférable de supprimer toutes les feuilles vierges de votre document. </p>

<h2>Polices</h2>
<p>Choisissez des polices et des styles faciles à lire. </p>

<ul>
	<li>Utilisez des polices «&#8201;sans empattement&#8201;» (sans serif) avec suffisamment d’espace entre les lettres&nbsp;:<br />
		Par exemple : Arial, Verdana, Calibri.</li>
	<li>Utilisez des tailles de police de 11 à 14 points.</li>
</ul>

<h3>Utilisation de la couleur</h3>
<p>Utilisez un <a href="https://webaim.org/resources/contrastchecker/">outil de vérification du contraste (en anglais seulement)</a> pour vérifier le contraste du texte (en premier plan) par rapport à l’arrière-plan. Pour la plupart des textes, le rapport de contraste doit être de 4,5:1. Pour les polices de grandes tailles et en caractère gras (caractère gras de 14 points ou régulier de 18 points), cette exigence est assouplie à 3:1. Comme il est très probable que la feuille soit visualisée à un zoom faible (pour en voir plus), tout le texte doit respecter un rapport minimum de 4,5:1. Visez l’exigence WCAG AAA de 7:1.</p>
<p><strong>Évitez d’utiliser</strong> uniquement la couleur pour donner un sens ou une importance à un mot, une cellule ou un bloc de texte. Il est possible d’ajouter un motif à la couleur pour les utilisateurs daltoniens. Les champs obligatoires doivent être identifiés par un astérisque (*) et le mot «&nbsp;requis&nbsp;» plutôt qu’inscrits en rouge.</p>

<h2>Éléments non textuels</h2>
<h3>Texte de remplacement</h3>
<p>Les éléments visuels comme les photos, les captures d’écran, les icônes, les vidéos et les modèles 3D doivent tous comprendre un texte de remplacement. Le texte de remplacement permet aux personnes qui ne peuvent pas voir l’image, de comprendre le message et ce qui est important. Un bon texte de remplacement est concis et pertinent. Il ne doit pas être plus long qu’une ou deux phrases et doit indiquer l’information importante transmise par l’image. Lors de la création d’un texte de remplacement, évitez de commencer par «&#8201;ceci est une image de&#8201;». Par contre, pour les captures d’écran, commencez par «&nbsp;capture d’écran de&nbsp;».</p>
<p>Pour attribuer du texte de remplacement aux images&nbsp;:</p>
<ol>
	<li>Sélectionner l’image.</li>
	<li>Activez <strong>Format de l’image</strong>dans le menu du hau.</li>
	<li>Activez l’outil <strong>Texte de remplacement</strong>.</li>
	<li>Si l’image est importante, communiquez en mots le sens, la fonction ou l’objectif transmis par l’image. </li>
	<li>Si une image ne transmet aucune information (c’est-à-dire qu’elle est décorative ou redondante), activer la boite «&nbsp;image décoratif&nbsp;» sous le champ <strong>Description</strong>.</li>
	<li>Activez le bouton <strong>Fermer</strong>.</li>
</ol>

<div class="row">
	<div class="col-md-7">
		<img class="img-responsive"  src="{{ rootPath }}img/fr/office365/excel-365-002.jpg" alt="Capture d’écran de Outil Format de l’image" />
	</div>
</div>

<h3>Graphiques et diagrammes</h3>
<p>Veillez à ce que les images et les graphiques complexes comportent de longues descriptions. Les images complexes comprennent : les schémas, les plans, les diagrammes ou toute autre image véhiculant une grande quantité d’informations. Une telle description est nécessaire, car les utilisateurs qui ne sont pas en mesure de voir l’image complexe ne comprendront pas suffisamment sa valeur ou son objectif.</p>
<p>Pour ajouter une description longue aux diagrammes et aux graphiques, décrire l’objet de façon concise (voir l’exemple du diagramme avec titre) comme est définis ci-dessus. Ensuite, inclure une description plus longue et détaillée en dessous de l’objet</p>

<p>Consultez la page <a href="https://www.w3.org/WAI/tutorials/images/complex/">Images complexes (en anglais seulement)</a> pour d’autres recommandations.</p>

<h2>Hyperliens</h2>
<p>Les utilisateurs de lecteurs d’écran parcourent parfois la liste des liens. Veillez donc à ce que le titre des liens soit pertinent dans le contexte du document. Le titre du lien doit transmettre avec précision l’intention et l’objectif du lien. Si aucun texte n’est fourni avec le lien, les utilisateurs devront suivre le lien pour en déterminer l’objectif, ce qui peut présenter des difficultés pour les utilisateurs de technologies adaptées. Un exemple de titre de lien pertinent comprend le titre complet de la destination plutôt qu’un lien vers le texte «&#8201;Cliquez ici&#8201;».</p>

<p>Pour ajouter des hyperliens avec un titre pertinent&nbsp;:</p>
<ol>
	<li>Saisissez ou collez une adresse Web dans votre documentet appuyez «&#8201;l’espace&#8201;» ou «&#8201;entrer&#8201;» pour convertir en lien hypertexte.</li>
	<li>Sélectionnez le lien et ouvrez le menu contextuel.</li>
	<li>Activez <strong>Lien hypertexte</strong>.</li>
	<li>Modifiez le <strong>Texte à afficher</strong> par un texte pertinent.</li>
</ol>

<div class="row">
	<div class="col-md-7">
		<img class="img-responsive"  src="{{ rootPath }}img/fr/office365/excel-365-003.jpg" alt="Capture d’écran de Insérer un lien hypertexte" />
	</div>
</div>

<h2>Ressources supplémentaires</h2>
<ul>
	<li><a href="https://support.office.com/en-us/article/make-your-excel-documents-accessible-to-people-with-disabilities-6cc05fc5-1314-48b5-8eb3-683e49b3e593">Microsoft : Rendre vos documents Excel accessibles aux personnes atteintes de handicaps</a></li>
	<li><a href="https://support.office.com/fr-fr/article/prise-en-charge-de-l-accessibilit%C3%A9-dans-excel-0976b140-7033-4e2d-8887-187280701bf8">Microsoft : Prise en charge de l’accessibilité dans Excel</a></li>
</ul>