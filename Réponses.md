# UE génétique médicale examen 2018-06-14
Nicolas Ionescu 
https://frama.link/nicolasionescu2018
## Exercice 1
### Q1
Le syndrome de Rett dans sa forme typique est majoritairement associé à un variant dans le gène *MECP2*. Il existe également des formes atypiques qui impliquent principalement des variants dans les gènes *CDKL5* et *FOXG1*.
### Q2
Les deux variants NM_004992.3:c.502C>T  et NM_004992.3:c.1335G>A se trouvent dans le gène *MECP2*.
### Q3
Le gène *MECP2* se situe sur le chromosome X.
### Q4
Le mode de transmission associé au syndrome de Rett lié à ce gène est dominant lié à l'X.
### Q5
Elle s'exprime lorsqu'un des deux allèles chez une femme ou l'unique allèle chez un homme est muté sur le chromosome X.
### Q6
Elle se transmet lorsque l'enfant hérite seulement d'un allèle muté sur l'X de sa mère ou de son père (ici, les individus mâles hémizygotes de l'allèle muté ne sont pas viables). 
### Q7
La notation protéique de ces variants est :
- NM_004992.3:c.502C>T : NM_004992.3(MECP2_i001):p.(Arg168*)
- NM_004992.3:c.1335G>A : NM_004992.3(MECP2_i001):p.(=)
### Q8
- NM signifie mRNA (il s'agit donc d'un transcrit)
- 004992 est le numéro de ce transcrit
- 3 est sa version
- *MECP2* est le nom du gène et i001 son numéro d'isoforme (peu utilisé)
- p signifie qu'il s'agit d'une notation protéique
- Arg168* signifie que l'arginine en position 168 a été remplacée par un codon stop, aboutissant à une protéine tronquée à cet endroit dans le premier variant.
- = signifie qu'il n'y a aucun changement d'acide aminé dans le cas du second variant
### Q9
Le premier variant est un variant non-sens car il entraîne l'apparition d'un codon stop, alors que le second est un variant synonyme car il n'entraîne pas de modification de la séquence en acides aminés.
### Q10
Il s'agit du premier variant (502C>T). Sur Rettbase, beaucoup de citations lui attribuent le phénotype "Rett syndrome - classical", tandis que pour le second (1335G>A) on retrouve principalement la mention phénotypique "Not Rett synd. ..." (pas étonnant car le premier est un non-sens alors que le second est synonyme).
### Q11
Voici l'URL de la visualisation : http://genome.ucsc.edu/cgi-bin/hgTracks?db=hg19&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chrX%3A153296767%2D153296787&hgsid=676702813_SX1VfhbnicFpcIbym4ahH0TUmPMP
### Q12
Le gène se trouve sur le bras anti-sens ("Strand: -" sur UCSC)
### Q13
Le transcrit NM_004992.3 comporte 4 exons au total (dont 1 non-codant)
### Q14
Le variant se situe dans le 4ème et dernier exon.
## Exercice 2
### Q1
a) OMIM signifie "Online Mendelian Inheritance in Man" et est une base de données informatique qui liste toutes les maladies génétiques humaines connues et les met en relation avec des gènes et les variations dans ces derniers qui peuvent être mises en cause.
b) Developmental Disorders Genotype-Phenotype Database (DDG2P) est également une base de données mais elle est plus spécifique puisque, comme son nom le laisse deviner, elle dresse un catalogue des gènes impliqués dans les troubles du comportement, en fonction du degré de certitude qui permet de les relier à la maladie, de la conséquence des variants et du statut allélique.
### Q2
La méthode Plon *et al.* classe les variants en 5 catégories en fonction de leur probabilité de pathogénicité, de 1 à 5 avec 1 "Non-pathogène ou aucun impact clinique" (p<0.001) et 5 "Clairement pathogène" (p>0.99). Il existe d'autres classifications, comme celle d'Ambry (https://www.ambrygen.com/clinician/our-scientific-excellence/variant-classification)
### Q3
a) NM_001190274.1 est la notation HGVS du transcrit de référence du gène *FBXO11*.
b) HGVS est le nom de la nomenclature proposée par l'Human Genome Variation Society (on l'appelle aussi Sequence Variant Nomenclature) pour classer et échanger des informations sur des variants aussi bien au niveau génomique, transcriptomique ou protéique. Il s'agit de la nomenclature de référence au niveau international.
c) GRCh37 signifie "Genome Reference Consortium Human Build 37", il s'agit simplement du nom de la séquence de référence du génome humain. GRCh37 était la 19ème version, on l'appelait donc également simplement hg19 (human genome 19) en vigueur jusqu'en Décembre 2013, suite à quoi la 20ème version lui fût substituée et pour uniformiser les notations GRCh et hg, on l'appela hg38.
### Q4
La technique utilisée pour explorer les deux patients 1 et 2 était le WES ou Whole Exome Sequencing. Il s'agit d'une technique de séquençage haut débit de l'exome d'une personne, c'est-à-dire uniquement les séquences codantes. Il implique une capture par hybridation spécifique, une purification de ces exons ou parties d’exons capturés et le séquençage haut-débit de ceux-ci. Son intérêt est qu'il est beaucoup moins cher qu'un séquençage du génome complet car l'exome représente une infime portion de ce dernier, alors que son intérêt clinique reste très élevé.
### Q5
Un séquençage de Sanger a été effectué à la fois chez les patients ainsi que chez leur parents afin de vérifier les deux éléments suivants :
- Les patients présentent bien un variant sur le gène *FBXO11* .
- Leurs parents ne l'ont pas, confirmant ainsi le caractère *de novo* de ce variant chez les patients.
### Q6
Pour le patient 1, on a démontré que le variant, situé à l'extrémité distale de l'exon 3, occasionnait avec certitude un épissage aberrant aboutissant à la rétention de ce dernier (ce qui modifie de manière très importante la structure de la protéine.). De plus, ce variant a été confirmé comme étant délétère par l'intermédiaire d'une cohorte de 311 sujets ayant tous des déficits intellectuels non-expliqués, et aucun autre variant *de novo* ne répond de manière satisfaisante aux critères pour être retenu comme délétère. 
Chez le patient 2, le variant situé dans l'exon 23 entraîne un décalage du cadre de lecture aboutissant à l'apparition d'un codon stop prématuré en position 913 dans la séquence peptidique, ce qui est en faveur de sa pathogénicité. Un autre variant a été identifié lors de cette étude sur l'exon 6 mais il est hérité de la mère et par conséquent certainement bénin. Il n'y a eu pour ce patient encore une fois aucun autre variant *de novo* répondant aux critères.
### Q7
Les variants rapportés dans cette études sont extrêmement rares : un seul autre patient possédant à la fois une mutation délétère sur le gène *FBXO11* et un tableau clinique de déficience intellectuelle accompagné d'autres signes caractéristiques a été identifié, or cette mutation est la même que celle portée par le patient 2 de l'étude. Au total, on retrouve dans les publications neuf patients possédant une mutation *de novo* sur le gène *FBXO11* accompagnée d'un tableau clinique moins sévère ou moins bien renseigné. Ces multiples occurrences de variants dans le gène *FBOX11* chez des patients atteints de déficience intellectuelle à divers degrés en font un bon candidat pour la déficience intellectuelle.
