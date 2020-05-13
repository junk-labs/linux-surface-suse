# linux-surface opensuse用パッケージ

上流 https://github.com/linux-surface/

## kernel本体
releaseページから落としてインストールしてください。

タッチパネルはペン又はシングルタッチの切り替え式となります。
切り替え方法　https://github.com/linux-surface/linux-surface/wiki/Installation-and-Setup

自分でビルドする場合はkernel-sourceパッケージをインストールし、このリポジトリのファイルを上書きしてビルドしてください。

- kernel-source-5.6.12-1.1.g9bff61b.src.rpm OBSのパッケージそのままです。
- kernel-default-5.6.12-1.2.x86_64.rpm Surface向けパッチ適用済みkernel
- kernel-default-devel-5.6.12-1.2.x86_64.rpm いわゆるkernel-headers

## libwacom
OBSでビルドしたのでインストールしてください
https://software.opensuse.org//download.html?project=home%3Asor593%3Alinux-surface&package=libwacom

## firmware-ipts
パッケージ化するのめんどくさいので自分でファイルを配置してください。
https://github.com/linux-surface/surface-ipts-firmware