### Pengertian Git
---

Jadi, sebenarnya apa yang dimaksud dengan Git? Ini adalah bagian penting untuk dipahami, karena jika anda memahami apa itu Git dan cara kerjanya, maka dapat dipastikan anda dapat menggunakan Git secara efektif dengan mudah. Git adalah teknologi version control system yang digunakan untuk mengelola dan mengembangkan proyek secara bersama-sama, dengan menggunakan git ini pengembang aplikasi dapat mengetahui perubahan source code tanpa bentrokan dari rekan-rekan kerja.

---
### Cara Kerja Git
---

Cara kerja git ini memanfaatkan repositori online dan offline, contohnya kita punya folder/directory project di lokal (offline), folder tersebut bisa kita upload ke repositori online yang sudah disediakan banyak pihak, setelah di upload rekan-rekan bisa meng-clone(istilahnya sih copas) lalu setelah di clone kita, rekan-rekan yang lain bisa mengubah isi file pada project tersebut secara lokal. Jika rekan-rekan ingin menambah atau mengurangi code yang ada pada file, mereka harus upload ke repository terlebih dahulu, kemudian rekan-rekan yang lain nanti jika ingin mendapatkan update harus mendownload lagi repositorinya, namun file yang di download ini sesuai dengan perubahan yang dilakukan oleh kita.

  <img src="https://github.com/lilyastri/git-sendiri-tim/blob/master/pi1.jpg" alt="gb52"/>

Nah didalam git terdapat branch, yang dimana fungsi branch ini adalah meletakkan workspace atau istilahnya tempat kerja khusus. Biasanya saya membuat branch ini berdasarkan masing-masing orang yang terlibat project, jika ada 5 orang yang terlibat project tersebut, maka akan ada 5 branch pada project tersebut.

Tujuannya agar setiap orang bisa memiliki versi sendiri dalam bekerja dan bisa fokus ke fitur yang sedang dia kerjakan, ada juga yang menyediakan branch berdasarkan versi rilis aplikasi juga, jadi semua tergantung bagaimana teman-teman mengatur git itu sendiri.

---
### Ada beberapa perintah dasar yang biasanya digunakan dalam git, perintah dimulai dari kata “git”, yaitu :
---

- git init 
    untuk membuat repositori lokal di dalam folder project.
- git clone
    meng-clone atau meng-copy projek dari repositori.
- git add
    menambah file baru pada repositori yang dipilih.
- git commit
    menyimpan perubahan, dan setiap perubahan ini wajib memberikan keterangan pada setiap perubahan.
- git push
    upload/mengirimkan perubahan file setelah di commit ke repositori.
- git pull
    mendownload/mengambil file yang sudah di ubah dan di upload.
- git branch
    melihat branch yang tersedia pada repositori.
- git merge
    menggabungkan semua branch yang ada pada repositori.

---
### Alur kerja dasar Git adalah seperti ini:
---

- Anda mengubah berkas dalam direktori kerja anda.
- Anda membawa berkas ke stage, menambahkan snapshotnya ke staging area.
- Anda melakukan commit, yang mengambil berkas seperti yang ada di staging area dan menyimpan snapshotnya secara permanen ke direktori Git anda.

---
### Layanan Git
---

Salah satu layanan GIT yang terkenal dan sering digunakan adalah Github. Apa itu Github?????????

  <img src="https://github.com/lilyastri/git-sendiri-tim/blob/master/pi2.jpg" alt="gb82"/> 

    Github adalah  software Hosting untuk proyek open source  yang menggunakan Tool  System revisi 
    kontrol Git. Jadi Git adalah tool untuk melakukan revisi code, sedangkan github adalah webhostingnya. 
    Mudahnya Github adalah Webhosting untuk proyek proyek software seperti Google code atau sourceforge.net. 
    Lebih singkatnya, Github adalah jejaring social untuk software developer.

---
### Fitur Sosial Github
---

- Github user profile.
- Follow, Kita bisa memfollow profil progammaer lain di github.
- Star, fungsinya sama dengan Bookmark.
- Watch, memonitor repository tertentu. Setiap ada perubahan di Repo, maka kita akan dikirim notifikasi.
- Fork, mengcopy keseluruhan code repository ke repo kita sendiri.

---
**Menambahkan Anggota Tim di Github**
---

Biasanya ada dua cara menyiapkan Github untuk kolaborasi tim:
- Organizations ~~ Pemilik organisasi dapat membuat banyak tim dengan tingkat izin yang berbeda untuk berbagai repositori
- Collaborators ~~ Pemilik repositori dapat menambahkan kolaborator dengan akses Baca + Tulis untuk satu repositori

---
### Organizations
---

Jika Anda mengawasi beberapa tim dan ingin menetapkan tingkat izin yang berbeda untuk setiap tim dengan berbagai anggota dan menambahkan setiap anggota ke 
repositori yang berbeda, maka Organization akan menjadi pilihan terbaik. Akun pengguna Github apa pun sudah dapat membuat Organizations  gratis untuk repositori kode sumber terbuka.
Untuk mengakses halaman tim untuk Organization Anda, Anda cukup pergi ke URL dibawah untuk melihatnya

    http://github.com/organizations/[organization-name]/teams
    https://github.com/organizations/[organization-name]/teams/new

kemudian untuk membuat tim baru (dapat diakses di URL no 2) dengan anggota dari 3 tingkat izin yang berbeda seperti:
- Pull Only: Fetch and Merge dengan repositori lain atau salinan lokal. Akses hanya baca.
- Push and Pull: (1) bersama dengan pembaruan reparasi jarak jauh. Baca + Akses tulis.
- Push, Pull & Administrative: (1), (2) bersama dengan hak atas info penagihan, membuat tim serta membatalkan akun Organization. Baca + Tulis + akses Admin

---
### Collaborators 
---

Collaborators digunakan untuk memberikan akses Read + Write access ke satu repositori yang dimiliki oleh akun pribadi. Untuk menambahkan Collaborators, (akun pribadi Github lainnya), cukup buka 
    
    https://github.com/[username]/[repo-name]/settings/collaboration:

Setelah itu selesai, masing-masing Collaborator kemudian akan melihat perubahan dalam status akses pada halaman repositori. Setelah kita memiliki akses Write ke repositori, kita dapat melakukan **git clone**, bekerja pada perubahan, membuat **git pull** untuk mengambil dan menggabungkan setiap perubahan dalam repositori jarak jauh dan akhirnya **git push**, untuk memperbarui repositori jarak jauh dengan perubahan kita sendiri.

---
### Sumber
---

- https://code.tutsplus.com/id/articles/team-collaboration-with-github--net-29876
- https://git-scm.com/book/id/v1/Memulai-Git-Memperoleh-Pertolongan
- https://medium.com/aisy-rozsidhy/menggunakan-teknologi-git-untuk-mengelola-proyek-dengan-banyak-orang-20b368537528
- https://klikfadhil.blogspot.com/2017/03/apa-itu-github-fungsi-dan-cara.html










