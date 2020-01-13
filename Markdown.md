EXO N1: La famille
mkdir cli_tmp
cd cli_tmp
touch je_suis_dans_tmp.text
touch in_cli_tmp
mkdir in_cli_tmp 
cd ../..
rm cli_tmp
mkdir grand_parent parent grand_frere grande_soeur ami connaissances
cd grand_frere
touch bachir
mv bachir ami
cp ami parent 
rm bob 
pwd
cd ../..
rm cli_tmp

EXO N2: Mon conteneur
cd
ls
mkdir conteneur
cd conteneur
touch voitures ustensiles electronique
cd voitures 
touch voitures.txt
open voitures.txt 
add benz toyota honda
cd ../..
cd ustensiles 
touch cuisines.txt
cd ../..
ls -alt

Exo N3: Le journal
cd
ls
mkdir -p actualites/politiques
cd politiques
mkdir elections
cd elections
touch candidats.txt
add Larwana Houssein Esaie
cd ..
cd ..
cd actualites
mkdir buzz

Exo N4: Le dessin
cd
touch .dossier_caché configuration 
ls -alt
mkdir -p creation/crayons 
cd crayons 
touch couleurs.txt
cp couleur.txt colors.text
cd .. 
cd ..
cd creation
touch gomme.txt
mv -rf gomme.txt crayons 
cd ../..
cd creation

Exo N5: Ma classe
mkdir ma classe 
touch mes_camarades.txt
add Rainatou Aziz Haissatou Haoua Wahab
echo "mes_camarades.txt"
touch .fichier_cache surveillant
ls -alt
rm -rf .fichier_cache surveillant
cd ..
rm ma_classe
