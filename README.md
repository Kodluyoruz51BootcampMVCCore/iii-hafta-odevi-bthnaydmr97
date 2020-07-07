# III-hafta-odevi


# Threading

Threading, aynı ortamda aynı anda birden fazla işi yapmaya denir. Thread&#39;ler ise bu işlerin her biridir. Thread&#39;ler aynı anda çalıştığında işlemciye process&#39;ler olarak gider ve sıraya alınır. Tek çekirdekli işlemcilerde birden fazla thread çalıştığı zaman sırayla threadlerin processlerini işleme alır ve bir thread diğer thread&#39;in bitişini beklemeden processleri işlemcide işleme girer. Çok çekirdekli işlemcilerde ise farklı thread&#39;ler farklı çekirdeklerde aynı anda çalışabilme durumuna sahiptir.

# Thread neden kullanılıyor?

Thread&#39;ler genel olarak, oyunlar, paralel çalışan task&#39;ler, event handling gibi durumlarda kullanılmaktadır. Ayrıca çok çekirdekli işlemcilerde tam performans yararlanmak için de thread&#39;ler kullanılır. İnsan üzerinden thread&#39;leri açıklamak gerekirse, bir insan aynı anda konuşurken gözleri başka bir yere bakıp elleriyle ayrı işler yapabilmektedir. Bu tam olarak multithreading örneğidir.

Thread&#39;lerin kullanıldığı bir başka alan ise server-client uygulamalar. Günümüzde popüler olarak Whatsapp, forum siteleri, online oyunlar bu mimariyi kullanmaktadırlar. Birden fazla kullanıcı birbirini beklemeden işlerini halletmek durumunda olduğundan her bir kullanıcının işlemleri ayrı threadlerde yönetilmektedir.

# Task

 C# task, ilk olarak .NET Framework 4&#39;te tanıtılan görev tabanlı eşzamansız kalıbın temel öğelerinden biridir.

 C# task nesnesi genellikle ana uygulama iş parçacığı üzerinde eşit olarak yerine bir iş parçacığı havuzu iş parçacığı üzerinde zaman uyumsuz olarak yürütür.

 Her ne kadar, sıra kullanıcı iş öğesi yöntemini kullanarak işi doğrudan iş parçacığı havuzuna yükleyebiliriz. Ancak, bu yöntemin zayıf yönleri vardır, çünkü işlemin bitip bitmediğini veya bir dönüş değerinin ne olduğunu söyleyemeyiz.

 Burada bir C# task yardımcı olabilir. C# görevi, işin tamamlanıp tamamlanmadığını ve işlemin bir sonuç döndürüp döndürmediğini size söyleyebilir. Task, yapılması gereken bazı işleri temsil eden bir nesnedir.

 C# görevleri, aşağıdakiler gibi çeşitli seçenekler sunarak zaman uyumsuzluğu veya paralel işlemi işlemek için karmaşık bir yol sağlar




 -Devam eden bir işlemi iptal edebilme

 -İşlemden elde edilen değeri döndürme (yöntem işlevleri gibi)

 -Kolay İstisna İşleme

 -Paralel döngü gibi üst düzey yapılar

