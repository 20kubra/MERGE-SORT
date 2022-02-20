# MERGE-SORT
>>Merge Sort birleştirme sıralaması olarak bilinen ve "Divide and Conquer" (Böl ve Fethet) mantalitesine dayanan bir sorting algoritmasıdır. Lineer değildir. Lineer algoritmalara göre çok daha hızlı olduğu için genellikle çok büyük verilerde kullanılır. Daha hızlı olmasının sebebi Time Complexity'nin Merge Sort'da nlogn olmasıdır. Temel mantığı "en küçük parçalara ayır, birleştirirken sırala" şeklindedir.
>>
>>Worst case, Best case ve Average case için time complexity O(nlogn)'dir.
>>
>>Örnek : [16,21,11,8,12,22]
>>
>>1. adım :   |16,21,11|         |8,12,22|
>>
>>2. adım : |16,21|    |11|       |8,12|    |22|
>>
>>3. adım : |16|  |21|  |11|  |8|  |12|  |22|  
>>
>>Buraya kadar olan kısım algoritmanın "Divide" bölümünü,devamındaki kısım ise "Conquer" yani birleştirirken sırala kısmını oluşturmaktadır.
>>
>>4. adım :  |16,21|  |11|      |8,12|  |22|
>>
>>5. adım : |11,16,21|        |8,12,22|
>>
>>6. adım :     |8,11,12,16,21,22|    
