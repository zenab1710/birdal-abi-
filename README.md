[16, 21, 11, 8, 12, 22] dizisinin Merge Sort'a göre aşamaları şu şekildedir:

Adım 1: Dizi ikiye bölünerek alt dizilere ayrılır.
[16, 21, 11] | [8, 12, 22]

Adım 2: Her alt dizinin kendisi için tekrar ayrıştırma işlemi yapılır.
[16] | [21, 11]
[8] | [12, 22]

Adım 3: Alt diziler sıralanarak birleştirilir.
[16] | [11, 21]
[8] | [12, 22]

Adım 4: Ana dizinin iki alt dizisi birleştirilerek sıralı bir dizi oluşturulur.
[11, 16, 21] | [8, 12, 22]

Adım 5: Son olarak, iki alt dizi birleştirilerek orijinal dizinin sıralı hali elde edilir.
[8, 11, 12, 16, 21, 22]

Big-O gösterimi: Merge Sort algoritmasının zaman karmaşıklığı O(n log n) dir.
