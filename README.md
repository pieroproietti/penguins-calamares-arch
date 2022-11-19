# calamares PKGBUILD 

I'm using manjaro version, we need before to build it to build and install from AUR the follow packages:

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

# Binaries
It would be very useful to have the binaries for penguins-eggs and calamares freely created and shared by the community from the PKGBUILDs in AUR, if anyone wants to help can contact [me](https://t.me/penguins_eggs).
