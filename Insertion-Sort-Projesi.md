# Insertion Sort Projesi

## Proje 1

---

### Soru 

**[22, 27,16,2,18,6]** Dizisi için,  

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: 
   1. Average Case: Aradığımız sayının ortada olması,
   2. Worst Case: Aradığımız sayının sonda olması,
   3. Best Case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısının hangi Case  kapsamına girer? Yazınız.
5. **[7,3,5,8,2,9,4,15,6**] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

---

---

### Cevaplar

---

#### <u>**1. Insertion Sort**</u>

1. Adım : 22, 27, 16, ***2***, 18, 6
2. Adım : ***2***, 22, 27, 16, 18, **6**
3. Adım: ***2***, ***6***, 22, 27, **16**, 18
4. Adım: ***2***, ***6***, ***16***, 22, 27, **18**
5. Adım: ***2***, ***6***, ***16***, ***18***, ***22***, ***27***

---

#### **<u>2. Big-O</u>**

- O(n) x O(n)
- O(n^2)

---

#### **<u>3. Time Complexity</u>**

-- ***2***, ***6***, ***16***, ***18***, ***22***, ***27***

* **Quick Sort**:
  * *Worst Case*: <u>n^2</u>
  * *Best Case*: <u>n</u>
  * *Average Case:* <u>n log n</u>
* **Merge Sort**:
  * *Worst Case*: <u>**"Aranılan sayının en sonda olması"**</u> - - - 27
  * *Best Case*: <u>**"Aranılan sayının en başında olması"**</u> - - - 2 
  * *Average Case:*  <u>**"Aranılan sayının ortasında olması"**</u> - - - 16 / 18

---

#### <u>**4. Cevap**</u>

* 18 sayısı dizi sıralandıktan sonra ***Average Case*** kapsamına girer.

----

#### **<u>5.Insert Sort</u>**

* [**7,3,5,8,2,9,4,15,6**]
  1. Adım: ***2***, **3**, 7, 5, 8, 9, 4, 15, 6
  2. Adım: ***2***, ***3***, **4**, 5, 7, 8, 9, 15, 6
  3. Adım: ***2***, ***3***, ***4***, ***5***, 7, 8, 9, 15, 6
  4. Adım: ***2***, ***3***, ***4***, ***5***, ***6***, 7, 8, 9, 15





























