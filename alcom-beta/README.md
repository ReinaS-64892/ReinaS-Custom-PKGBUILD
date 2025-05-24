# alcom-beta

もともとのコード

- https://aur.archlinux.org/cgit/aur.git/tree/PKGBUILD?h=alcom
- https://aur.archlinux.org/alcom.git

commit hash `f900a6f135fb8e9fd60c79880842cda08907ba6d`

## 何がされている？

コンフリクトしてうざいから makedepends: nodejs-iron-lts -> nodejs

pkgver の内容に `_` が入っている時に `-`  に置き換えて `vx.x.x_beta.x` といった指定で beta のバージョンを引っ張ってこれるようにした。
