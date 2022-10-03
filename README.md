# tes_pull-push_req

download git yang standalone v. win bit komputer kalian
https://git-scm.com/download/win

masuk ke folder baru dengan tugas yang baru

buat file (NIM).txt

lalu buka terminal baru dengan "git bash"

login terlebih dahulu ke github
$git config --global user.email "you@example.com"
$git config --global user.name "Your Name"

$git init

untuk membuat sistem .git

$git add .

untuk menambahkan semua perubahan

bila ada masalah dengan add maka set config safe directory

$git config --global --add safe.directory '(nama dir)'

$git commit -m "(isi pesan update)"

untuk membuat branch

$git checkout -b (NIM)

untuk mengganti branch
$git switch (nama branch)

untuk menggabungkan branch swich ke branch yang mana yang mau di gabungkan dengan apa

$git switch master
$git marge (NIM)

lalu sambungkan git dengan github remote
$git remote add origin https://github.com/IndoproGMR/tes_pull-push_req.git

$git push -u origin master

bila tidak dapat mengambil code dari github

$git pull origin master --allow-unrelated-histories

untuk mengambil code dari branch lain

ext :

GitHub Pull Requests and Issues

GitLens — Git supercharged

Todo MD
