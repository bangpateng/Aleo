<p style="font-size:14px" align="right">
<a href="https://t.me/bangpateng_group" target="_blank">Join our telegram <img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
<a href="https://bangpateng.com/" target="_blank">Visit our website <img src="https://user-images.githubusercontent.com/38981255/184068977-2d456b1a-9b50-4b75-a0a7-4909a7c78991.png" width="30"/></a>
</p>

<p align="center">
  <img height="150" height="auto" src="https://user-images.githubusercontent.com/38981255/185994172-0b4e4ea8-f81a-48db-8020-9be619f485b7.png">
</p>

# ALEO TESTNET INCENTIVIZED

##  1. Ikhtisar

__snarkOS__ adalah sistem operasi terdesentralisasi untuk aplikasi pribadi. Ini membentuk tulang punggung [ Aleo ](https://aleo.org/) dan
memungkinkan aplikasi untuk memverifikasi dan menyimpan status dengan cara yang dapat diverifikasi secara publik.

## 2. Spesifiksi Minimal

Berikut adalah persyaratan **minimum** untuk menjalankan node Aleo:

 -  **CPU** : 16-core (lebih disukai 32-core)
 -  **RAM** : Memori 16GB (lebih disukai 32GB)
 -  **Penyimpanan** : 128GB ruang disk
 -  **Jaringan** : 50 Mbps upload **dan** bandwidth download

# Instal Node

## Update

```
sudo apt-get update
```
```
sudo apt install git
```
```
sudo apt screen
```

## Open Port

```
ufw allow 22 && ufw allow 4130/tcp && ufw allow 4180/tcp && ufw enable
```

## Install Rupstup

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## Add Path

```
source $HOME/.cargo/env
source $HOME/.cargo/bin
```

## Clone Repository

```
git clone https://github.com/AleoHQ/snarkOS.git --depth 1 && cd snarkOS
```


## Built (Butuh Waktu Sabar Aja)

```
./build_ubuntu.sh
```

## Run (Butuh Waktu Sabar Aja Tunggi Hingga 100% 1 - 2 Jaman)
```
screen -R aleo
```

Ketik CTRL A Agar Jalan di Screen Karena Lama Ini di Tahap Ini, Untuk Balik Screen Ketik `screen -Rd aleo`

```
./run-client.sh
```

**Note :** Pada Saat Ada Tulisan Logo ALEO Ada Your Address, Itu Salin Aja Addressnya Simpen Bang

### Done Untuk Saat Ini Hanya Client Saja Yang Jalan, Untuk Buat Wallet dan Runing Prover Next Step Tunggu Pharse 2 (Nanti Tutorial Ini Akan di Update, Bila Sudah Ada Pembaharuan)
