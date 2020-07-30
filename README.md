# osx_qemu_rpi

Emuler un Raspberry Pi sous macOS (testé sur Catalina 10.15.6)

Pour faire une nouvelle Machine Virtuelle totalement indépendante, juste retélécharger le repo dans un dossier indépendant et lancer les commandes $ ./setup ; et $ ./run

# Requirements

	$ xcode-select --install # install command line tools
	$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" # install brew
	$ brew install qemu wget unzip
	
# Setup

	$ git clone https://github.com/adann0/osx-qemu-rpi
	$ cd osx-qemu-rpi
	$ chmod +x setup run
	$ ./setup # télécharge l'image et les cposants
	$ ./run	# lance la vm
