### 1.  How do you create a new repository on GitHub?

*   GitHub'a giriş yapın ve ana sayfanızın sağ üst köşesindeki '+' simgesine tıklayın.
*   Açılır menüde, 'New Repository' seçeneğini seçin.
*   Depo adını ve açıklamasını girin ve depo seçeneklerini yapılandırın.
*   Son olarak, 'Create Repository' düğmesine tıklayarak depoyu oluşturun.

### 2.  How do you copy a repository onto your local machine from GitHub?

*   GitHub'da depoyu açın ve sayfanın sağ üst köşesindeki 'Code' düğmesine tıklayın.
*   'HTTPS' veya 'SSH' bağlantı URL'sini kopyalayın.
*   Daha sonra, yerel makinenizde Git Bash veya Terminal'i açın ve kopyaladığınız bağlantıyı kullanarak 'git clone \[URL\]' komutunu girin.

### 3.  What is the default name of your remote connection?

*   Varsayılan ad 'origin'dir.

### 4.  Explain what origin is in git push origin main.

*   'origin', depoya bağlı uzak bir Git deposunu temsil eder. Bu komut, yerel 'main' dalındaki değişiklikleri uzak 'origin' dalına itmek için kullanılır.

### 5.  Explain what main is in git push origin main.

*   'main', depodaki ana dalı temsil eder. Bu komut, yerel 'main' dalındaki değişiklikleri uzak 'origin' dalına itmek için kullanılır.

### 6.  Explain the two-stage system that Git uses to save files.

*   Git'in dosyaları kaydetmek için kullandığı iki aşamalı sistem, 'staging area' ve 'commit' adı verilen iki aşamalı işlemi içerir. İlk olarak, değişiklikler 'staging area' olarak adlandırılan bir ara bölüme eklenir. Daha sonra, bu değişiklikler 'commit' işlemiyle resmi olarak kaydedilir


### 7.  How do you check the status of your current repository?


*   Depo dizininde Git Bash veya Terminal açın ve 'git status' komutunu girin. Bu komut, depo dizinindeki değişiklikleri ve dosyaların durumunu gösterir.

### 8.  How do you add files to the staging area in git?

*   Depo dizininde Git Bash veya Terminal açın ve 'git add \[file name\]' komutunu girin. Bu komut, belirtilen dosyayı 'staging area'ya ekler. 'git add .' komutu, tüm değiştirilmiş dosyaları otomatik olarak ekleyecektir.

### 9.  How do you commit the files in the staging area and add a descriptive message?

*   Depo dizininde Git Bash veya Terminal açın ve 'git commit -m \[açıklayıcı mesaj\]'

### 10.  Staging alanındaki dosyaları kaydetmek ve açıklayıcı bir mesaj eklemek için nasıl taahhüt edersiniz?

*   Git Bash veya Terminal'de, 'git commit -m \[açıklayıcı mesaj\]' komutunu girin. 'açıklayıcı mesaj' kısmına, kaydettiğiniz değişiklikleri açıklayan bir mesaj yazın. Örneğin, 'git commit -m "Ürün sayfasına yeni bir buton ekledim"'

### 11.  How do you push your changes to your repository on GitHub?


*   Git Bash veya Terminal'de, 'git push' komutunu girin. Bu, yerel deponuzdaki tüm kaydedilmiş değişiklikleri uzak depoya yükler.

### 12.  How do you look at the history of your previous commits?

*   Git Bash veya Terminal'de, 'git log' komutunu girin. Bu komut, önceki taahhütlerinizin listesini ve her bir taahhütün özet bilgilerini gösterir. Ayrıca 'git log --graph' komutu, taahhütlerin bir görselleştirilmiş grafiğini gösterir.
