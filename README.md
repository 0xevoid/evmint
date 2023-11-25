# evm-mint

Anda dapat mencetak semua rantai EVM. Sederhananya, Anda dapat mencetak semua rantai yang baru dirilis.

# Instalasi lingkungan

- Buka instalasi lingkungan https://zhuanlan.zhihu.com/p/611141762
- Gunakan CMD atau terminal untuk memeriksa apakah go berhasil diinstal `go version`
- Beberapa komputer mungkin tidak memiliki Git dan perlu menginstal lingkungan Git. https://zhuanlan.zhihu.com/p/242540359
- Unduh kode sumber menggunakan CMD atau terminal
-  
  `git clone https://github.com/0xevoid/evmint.git`
  
- `cd evmint`
- `go mod init evm`
- `go mod tidy`
- Ganti kunci pribadi dan informasi rantai（https://chainlist.org/）Seperti alamat RPC, ID rantai, data yang memerlukan mint (tidak menggunakan heksadesimal)
- `go run mint.go`

# SU...........

