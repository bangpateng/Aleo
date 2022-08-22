<p style="font-size:14px" align="right">
<a href="https://t.me/bangpateng_group" target="_blank">Join our telegram <img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
<a href="https://bangpateng.com/" target="_blank">Visit our website <img src="https://user-images.githubusercontent.com/38981255/184068977-2d456b1a-9b50-4b75-a0a7-4909a7c78991.png" width="30"/></a>
</p>

<p align="center">
  <img height="150" height="auto" src="https://user-images.githubusercontent.com/38981255/185994172-0b4e4ea8-f81a-48db-8020-9be619f485b7.png">
</p>

# ALEO TESTNET INCENTIVIZED

## <a name='Daftar Isi'></a>Daftar Isi

* [1. Ikhtisar](#1-Ikhtisar)
* [2. Ikhtisar](#2-Ikhtisar)
* [3a. Run an Aleo Client Node](#3a-run-an-aleo-client-node)
* [3b. Run an Aleo Mining Node](#3a-run-an-aleo-mining-node)
* [4. FAQs](#4-faqs)
* [5. Command Line Interface](#5-configuration-file)
* [6. Development Guide](#6-development-guide)
* [7. License](#7-license)


##  1. Ikhtisar

__snarkOS__ adalah sistem operasi terdesentralisasi untuk aplikasi pribadi. Ini membentuk tulang punggung [ Aleo ](https://aleo.org/) dan
memungkinkan aplikasi untuk memverifikasi dan menyimpan status dengan cara yang dapat diverifikasi secara publik.

## 2. Ikhtisar

Berikut adalah persyaratan **minimum** untuk menjalankan node Aleo:

 -  **CPU** : 16-core (lebih disukai 32-core)
 -  **RAM** : Memori 16GB (lebih disukai 32GB)
 -  **Penyimpanan** : 128GB ruang disk
 -  **Jaringan** : 50 Mbps upload **dan** bandwidth download

# Instal Node

## Update

```
sudo apt-get update
sudo apt install git
```

## Install Rupstup

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## Add Variable

```
source $HOME/.cargo/env
source $HOME/.cargo/bin
```

## Built (Butuh Waktu Sabar Aja)

```
./build_ubuntu.sh
```

## Run (Butuh Waktu Sabar Aja Tunggi Hingga 100% 1 Jaman)

```
./run-client.sh
```

## Create Wallet 

```
cargo run --release -- experimental new_account
```

**Harap ingat untuk menyimpan kunci pribadi akun dan kunci tampilan**
