# calamares PKGBUILD 

I'm using manjaro version, we need before to install from AUR:

* ttf-comfortaa
* ckbcomp
* mkinitcpio-openswap

after, we can build calamares

# PROCEDURE

## ttf-comfortaa
git clone https://aur.archlinux.org/ttf-comfortaa.git
cd ttf-comfortaa
makepkg -srcCi

## ckbcomp
git clone https://aur.archlinux.org/ckbcomp.git
cd ckbcomp
makepkg -srcCi

## mkinitcpio-openswap
git clone https://aur.archlinux.org/mkinitcpio-openswap.git
cd mkinitcpio-openswap
makepkg -srcCi

## calamares
git clone https://gitlab.manjaro.org/packages/extra/calamares
cd calamares
makepkg -srcCi
