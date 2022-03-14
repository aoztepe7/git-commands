<h2>Git Komutları</h2>

<div>
<span><h3> Git Konfigurasyonlar </h3></span></br> 
<span> git config -l  </span>
</div>
</br> 

<div>
<span><h3> Kullanıcı Adı Ayarlama </h3></span> </br> 
<span> git config --global user.name "kullanıcı_adı"  </span>
</div>
</br> 

<div>
<span><h3> E-Posta Ayarlama </h3></span> </br> 
<span> git config --global user.email "eposta@adresi.com"  </span>
</div>
</br> 

<div>
<span><h3> Giriş Bilgilerini Ön Belleğe Alma </h3></span> </br> 
<span> git config --global credential.helper cache </span>
</div>
</br> 

<div>
<span><h3> İlk Kurulumda Repo Kurulumu </h3></span> </br> 
<span> git init </span>
</div>
</br> 

<div>
<span><h3> Spesifik Bir Dosyayı Stage'e Ekleme </h3></span> </br> 
<span> git add file_name </span>
</div>
</br> 

<div>
<span><h3> Tüm Değişiklik İçeren Dosyaları Stage'e Ekleme </h3></span> </br> 
<span> git add . </span>
</div>
</br> 

<div>
<span><h3> Sadece Dosya Adı İle Başlayan Dosyaları Stage'e Ekleme </h3></span> </br> 
<span> git add comp* </span>
</div>
</br> 

<div>
<span><h3> Repo Durum Kontrolü </h3></span> </br> 
<span> git status </span>
</div>
</br> 

<div>
<span><h3> Commit İşlemi (Mesajsız)</h3></span> </br> 
<span> git commit </span>
</div>
</br> 

<div>
<span><h3> Commit İşlemi (Mesajlı)</h3></span> </br> 
<span> git commit -m "YOOOO!!! Bu Bir Mesaj" </span>
</div>
</br> 

<div>
<span><h3> Commit Geçmişi</h3></span> </br> 
<span> git log </span>
</div>
</br> 

<div>
<span><h3> Değişiklikler ile Commit Geçmişi </h3></span> </br> 
<span> git log -p </span>
</div>
</br> 

<div>
<span><h3> Spesifik Commit Geçmişi </h3></span> </br> 
<span> git show commit_id </span>
</div>
</br> 

<div>
<span><h3> Commit'den Önce Yapılan Değişiklikler </h3></span> </br> 
<span> git diff </span> </br>
<span> git diff some_file.js </span> </br>
<span> git diff --staged </span> </br>
</div>
</br> 

<div>
<span><h3> En Son Commit'e Resetleme </h3></span> </br> 
<span> git revert HEAD </span>
</div>
</br> 

<div>
<span><h3> Spesifik Commit'e Resetleme </h3></span> </br> 
<span> git revert comit_id_here </span>
</div>
</br> 

<div>
<span><h3> Yeni Branch Oluşturma </h3></span> </br> 
<span> git branch branch_name </span>
</div>
</br> 

<div>
<span><h3> Branchleri Listeleme </h3></span> </br> 
<span> git branch </span>
</div>
</br> 

<div>
<span><h3> Branch Oluşturup Oluşturulan Branch'e Geçme </h3></span> </br> 
<span> git checkout -b branch_name </span>
</div>
</br> 

<div>
<span><h3> Branch silme </h3></span> </br> 
<span> git branch -d branch_name </span>
</div>
</br> 

<div>
<span><h3> Branch Merge </h3></span> </br> 
<span> git merge branch_name </span>
</div>
</br> 

<div>
<span><h3> Conflict Olan Merge İptali </h3></span> </br> 
<span> git merge --abort </span>
</div>
</br> 

<div>
<span><h3> Remote Repo Ekleme </h3></span> </br> 
<span> git add remote https://repository_name.com </span>
</div>
</br> 

<div>
<span><h3> Remote Repo URL Görme </h3></span> </br> 
<span> git remote -v </span>
</div>
</br> 

<div>
<span><h3> Detaylı Repo Bilgisi </h3></span> </br> 
<span> git remote show origin </span>
</div>
</br> 

<div>
<span><h3> Değişiklikleri Remote'a Gönderme </h3></span> </br> 
<span> git push </span>
</div>
</br> 

<div>
<span><h3> Remote'dan Çekme </h3></span> </br> 
<span> git pull </span>
</div>
</br> 

<div>
<span><h3> Anlık İzlenen Remote'u Görme </h3></span> </br> 
<span> git branch -r </span>
</div>
</br> 

<div>
<span><h3> Remote'daki Değişiklikleri Alma </h3></span> </br> 
<span> git fetch </span>
</div>
</br> 

<div>
<span><h3> Localde Bulunan Repo'yu Remote'a Gönderme </h3></span> </br> 
<span> git merge origin/main </span>
</div>
</br> 

<div>
<span><h3> Remote'da Bulunan İçerikleri Alma </h3></span> </br> 
<span> git remote update </span>
</div>
</br> 

<div>
<span><h3> Remote'a Yeni Branch Gönderme </h3></span> </br> 
<span> git push -u origin branch_name </span>
</div>
</br> 

<div>
<span><h3> Remote'da Bulunan Branch'i Silme </h3></span> </br> 
<span> git push --delete origin branch_name </span>
</div>
</br> 

<div>
<span><h3> Force Push </h3></span> </br> 
<span> git push -f </span>
</div>













