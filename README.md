# msfukui/vagrantbox

vagrant on VirtualBox を開発環境として使う人のための vagrant box 集

## 概要

開発環境を vagrant on VirtualBox で構築して使っている人に、比較的安全な vagrant box image を提供します。

開発環境としてインストールしたい Box file がここに来るとある状態を目指します。

## 方針

* イメージは OS 公式のインストールイメージをダウンロード、チェックサム検証後にインストールしたものを使います。

* Chef などの構成管理ツールを使ってセットアップすることを想定し、Box file の作成に必要な設定を除いて、極力デフォルトそのままの設定として最低限の設定のみを行います。

## 用意しているファイル

* Scientific Linux 6.5

作成環境: vagrant 1.6.2/VirtualBox 4.3.12
作成日  : 2013/11/25
作成日  : 2014/10/05
設定内容: boot disk/text mode install, TZ: Asia/Tokyo, SELinux: Off
設定方法の詳細はメモ(scientificlinux.txt)を参照してください。

[EOF]
