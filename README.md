# Fertile Egg Detector Dataset [CH2-PS266]

Bangkit Batch 2 2023

**Designing a Deep Learning-Based Mobile Application for Egg Candling**

*Theme: Food Accessibility, Agribusiness, and Food Security*

**Team Member**

1.  (ML) M466BSX1032 – Brilian Herda – Universitas Sains Al-Qur’ an - [Active]
2.  (ML) M466BSY1195 – Ahmad Ma'ruf – Universitas Sains Al-Qur’an - [Active]
3.  (ML) M123BSY1353 – Habibi Ahmadi Muslim – Politeknik Elektronika Negeri Surabaya - [Active]
4.  (CC) C182BSY3830 – Fathin Cahyo Ramadhan – Universitas Amikom Purwokerto - [Active]
5.  (CC) C182BSY3969 – Yuntafa Ulkhaq – Universitas Amikom Purwokerto - [Active]
6.  (MD) A182BSY2566 – Sandhya Nugraha Qusnur Aulia - Universitas Amikom Purwokerto - [Active]
7.  (MD) A548BKY4459 - Zulfahmi M. Ardianto - UIN Sunan Kalijaga Yogyakarta - [Active]

In this project, we've leveraged a cloud-based machine learning model for egg classification. This model, trained on diverse egg stage data, enables real-time analysis of images from the camera or gallery within the mobile app. It accurately categorizes eggs into early, mid, late, or non-viable stages, enhancing its functionality significantly.


## Folder Structures

```
- test
    |
    - _classes.csv
    - <<list of images>>
- train
    |
    - _classes.csv
    - <<list of images>>
- valid
    |
    - _classes.csv
    - <<list of images>>
- README.md
...
```


## Classes

```
' Pertengahan',
' Tahap Akhir',
' Tahap Awal',
' Telur Mati',
```

 **Inside file `_classes.csv`
```
filename, Pertengahan, Tahap Akhir, Tahap Awal, Telur Mati
20220630_220618_jpg.rf.0177f625400430cf3acfd535fa6ff22b.jpg, 1, 0, 0, 0
20220625_012803_jpg.rf.03468ab90e12c35f8c37feae038822fb.jpg, 0, 0, 1, 0
....
```

