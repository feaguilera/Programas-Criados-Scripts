#!/bin/bash
#
clear
echo -e "_________BASE64___________\n"
echo "Opcoes"
echo "1. Codificar input em base64"
echo "2. Decodificar input em base64"
echo -e "3. Sair\n"
read -p ">> " opt
#
case $opt in
	1)	read -p "Input a codificar: " codinp
		echo $codinp | base64
		read -p "Tecle algo para recomecar" i
		./codif64.sh;;
		#
	2)	read -p "Input a decodificar: " decodinp
		echo $decodinp | base64 -d
		read -p "Tecle algo para recomecar" i
		./codif64.sh;;
		#
	3)	echo "Script finalizado";;
esac
