# Demo Git Repository

This is the first repository

command git -add : add stage (tambah perubahan bukan file)
command git commit -m "comment" : utk commit apapun yg sudah disave
command git commit -am "comment" : shortcut biar gak add modified file dulu

command git add . : utk add semua file
command git checkout -- file : utk restore versi sebelumnya

command git checkout : waktu dicoba gak bisa utk restore
command git restore --staged file : utk unstaged
command git restore file : utk restore file versi sebelumnya

command git log --oneline --graph --decorate --color : utk menampilkan log history yg lebih menarik
command git revert id : utk mengembalikan ke id commit tersebut, tapi harus menambahkan comment dulu kalo di vscode
