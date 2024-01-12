# IT-VGA2_UTILITY-0
Clone des commandes de la disquette de la carte vidéo IT-VGA2 d'InformTech écrit en Pascal (Turbo Pascal et/ou Free Pascal).

<h2>Liste des fichiers</h2>

Voici la liste des différents fichiers proposés dans IT-VGA2_UTILITY-0 :

<table>
		<tr>
			<th>Nom</th>
			<th>Description</th>	
		</tr>
		<tr>
			<td><b>FLOAD.PAS</b></td>
			<td>Cette commande permet de charger une police de caractères à partir d'un fichier de format «.FNT» en mémoire vidéo. Cette commande est inspiré de la disquette «IT-VGA2 UTILITY» d'InformTech.</td>
		</tr>  
		<tr>
			<td><b>VDIAG.PAS</b></td>
			<td>Cette commande permet de lancer le test de diagnostique vidéo. Cette commande est inspiré de la commande fournit avec les pilotes de la carte vidéo IT-VGA2 d'InformTech.</td>
		</tr>
</table>

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler FLOAD.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> FLOAD</pre>
	
<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/IT-VGA2_UTILITY-0//blob/master/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/IT-VGA2_UTILITY-0//blob/master/LICENSE">MIT</a>.</li>
</ul>
