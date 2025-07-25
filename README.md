# Soundness-Cli

## Cara Install Soundness CLI

### Update
```
Sudo apt update -y && Sudo apt upgrade -y
```

### Install Rust
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh  && source $HOME/.cargo/env
```

### Install Cli Soundness
```
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```

### Setelah install, jalankan perintah ini agar command-nya bisa dipakai
```
source ~/.bashrc
soundnessup install && soundnessup update 
```
### Jika Instalasi nya sudah selesai lanjutkan dengan import mnemonic yang pernah dibuat untuk daftar Soundness
```
soundness-cli import-key --name <name> --mnemonic "<mnemonic>"
```
hapus ganti <name> dengan nama yang ingin kamu pakai rubah juga "<mnemonic>" dengan mnemonic kamu Contoh :
``` soundness-cli import-key --name KangJP --mnemonic "24 kata mnemonic" ```
lalu akan di minta password yang sebelumnya pernah di buat saat generate mnemonic dan pubkey

### Buka DM kamu dari bot dan Copy bagian ini <img width="530" height="752" alt="image" src="https://github.com/user-attachments/assets/9b5d0889-efff-4a9a-8142-c11b9ad2f777" /> Dan edit bagian <your-key-name> menjadi nama yang kamu buat pada step sebelumnya Contoh : KangJP,
### Tunggu hingga Succes Maka akan muncul File key_store.json di storage kamu, Download File nya dan simpan DONE !! 

