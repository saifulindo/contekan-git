contekan-git
============

Contekan-*Git* diambil secara ngawur dari translate *Cheatsheet*, mungkin lebih kearah karena dibuat dalam selembar atau dua lembar yang biasanya berisi *tips and trick*, tapi secara kegunakan juga tidak salah dikatakan sebagai contekan meskipun tidak terlalu enak didengar.

Contekan-*Git* ini dibuat dalam format *.docx, saya berharap ada ikut yang berkontribusi, kemudian beralih menggunkan OpenOffice atau LibreOffice.

`contekan-git` sudah saya bukukan dengan format yang mudah dikembangkan, pada sebuah penyedia layanan pembuatan buku [GitBook](https://www.gitbook.com/), yang anda juga dapat turut serta mengembangkan di tautan repositori GitHub `https://github.com/saifulindo/gitbook-contekan-git` atau klik [gitbook-contekan-git](https://github.com/saifulindo/gitbook-contekan-git).

Cara ikut berkontribusi dalam pengembangan contekan-*Git* :
----------------------

*Forking* (penggandaan repositoy ke *Account GitHub* anda) berikutnya *clone* untuk menggandakan *repository* contekan-*Git* yang akan digunkan untuk clone ke komputer lokal, seperti berikut :
```
$ git clone git@:github.com:[account_anda]/contekan-git.git`
$ cd contekan-git
```
buka file contekan-git.docx, Edit tata bahasa yang digunakan agar lebih enak didengarkan, dengan melihat file [salesforce_git_developer_cheatsheet.pdf][s].

```
$ git add .
$ git commit - m "Isikan Pesan Perubahan"
$ git pull origin master
$ git push origin master
```
berikutnya `pull request` ke repository `:saifulindo/contekan-git.cit`, oke and enjoy.

[s]:https://github.com/saifulindo/contekan-git/blob/master/salesforce_git_developer_cheatsheet.pdf
