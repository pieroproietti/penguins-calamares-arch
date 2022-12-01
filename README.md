# calamares PKGBUILD 

We are using **unchanged** [manjaro PKGBUILD](https://gitlab.manjaro.org/packages/extra/calamares). Before to build calamares we need to build and install the follow packages from AUR:

* ttf-comfortaa
* ckbcomp
* mkinitcpio-openswap

after, we can build calamares

# PROCEDURE

## ttf-comfortaa
```
git clone https://aur.archlinux.org/ttf-comfortaa.git
cd ttf-comfortaa
makepkg -srcCi
cd ..
```
## ckbcomp
```
git clone https://aur.archlinux.org/ckbcomp.git
cd ckbcomp
makepkg -srcCi
cd ..
```
## mkinitcpio-openswap
```
git clone https://aur.archlinux.org/mkinitcpio-openswap.git
cd mkinitcpio-openswap
makepkg -srcCi
cd ..
```
## calamares
```
git clone https://gitlab.manjaro.org/packages/extra/calamares
cd calamares
makepkg -srcCi
cd ..
```

# Binaries
It would be very useful to have the binaries for penguins-eggs and calamares freely created and shared by the community from the PKGBUILDs in AUR, if anyone wants to help can contact [me](https://t.me/penguins_eggs).
