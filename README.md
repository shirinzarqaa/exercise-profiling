<details>
<summary>Tutorial 5</summary>
  
**Hasil Jmeter test plans**
1. HTTP REQUEST /all-student
  ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/8b49bcae-b627-48f4-98da-61140975ab3b)

2. HTTP REQUEST /all-student-name
  ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/034380ad-9580-40b6-80d1-a719deb69ac2)

3. HTTP REQUEST /highest-gpa
  ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/55207699-cdfa-4953-a3fe-c0949db61be5)

**Hasil Jmeter test plans dengan CLI**
  1. HTTP REQUEST /all-student
    ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/d94a793f-ffe4-44d5-adc3-d413d27b94dd)

  2. HTTP REQUEST /all-student-name
    ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/b36e9453-9c10-4cfe-bb54-3e5e996023a7)

  3. HTTP REQUEST /highest-gpa
     ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/c3e6e86a-4fbf-4dea-bf7a-b4e7136c2b68)

**Profiling & Optimization**
- **sebelum optimisasi**
  ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/54afdb47-a376-4856-87a3-2e4e540b52ab)
  ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/5ec971bf-961b-42d0-aa94-99435eeb91cd)
  ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/eaee4da4-18fe-4ef8-a937-c687208541db)

  
- **setelah optimisasi dengan profiling**
  ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/5b9fdc48-f1db-423d-a741-cd929cbaa71a)
  ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/e7ae8c68-59bf-45ab-a8ef-75f9db6ac336)
  ![image](https://github.com/shirinzarqaa/exercise-profiling/assets/110030938/56438b8a-4678-424c-a411-91e773e6ce9c)
- **setelah optimisasi dengan Jmeter**
  
**Reflection**
1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
  - JMeter digunakan untuk mengevaluasi kinerja aplikasi melalui simulasi beban kerja yang tinggi pada aplikasi.
  - Intellij profiler digunakan untuk mengidentifikasikan bagian pada aplikasi yang menyebabkan penurunan kinerja suatu aplikasi.
2. How does the profiling process help you in identifying and understanding the weak points in your application?
  - proses profiling sangat berguna untuk mengidentifikasikan bagian pada aplikasi yang menyebabkan penurunan kinerja suatu aplikasi. Hal tersebut karena profiler mengumpulkan data dan melakukan analisis terhadap bagian yang menyebabkan penurunan kinerja. Informasi yang saya peroleh bermacam-macam mulai dari CPU usage, memory allocation,garbage collection activity hingga thread concurrency. 
3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
  - Ya, Profiler Intellij sudah efektif dalam membantu menganalisis dan mengidentifikasikan bottlenecks dalam kode aplikasi. Hal tersebut memudahkan karena fitur yang tersedia mulai dari Method List yang berisi informasi waktu eksekusi, perubahan Diff execution time jika mengoptimisasi suatu method.Sehingga kita bisa melihat secara otomatis persentase peningkatan yang diperoleh.
4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
  - Main challenges saya yaitu pada saat melakukan refactoring pada bottleneck agar performa aplikasi dapat lebih ditingkatkan. cara saya mengatasi tantangan trsebut dengan memahami kerja kode sebelum me refactor.
5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
  - salah satu manfaatnya yaitu Intellij profiler memungkinkan mengidentifikasi masalah dengan lebih efisien dan terintegrasi dengan baik karena tidak memerlukan aplikasi atau sistem tambahan untuk mengidentifikasinya.
6. How do you handle situations where the results from profiling with Inte	lliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
 - inkonsisten belum saya temukan pada saat menggunakan Jmeter dan profiling dengan intellij. Namun, untuk mengantisipasi hal tersebut jika terjadi langkah pertama yang akan saya gunakan yaitu memeriksa kembali metode pengujian dan skenario yang digunakan oleh alat tersebut dan membandingkan metrik yang diukur oleh kedua alat tersebut agar dapat mengidentifikasi perbedaan ruang lingkup yg digunakan.
7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
   Setelah menganalisis hasil dari pengujian kinerja dari Jmeter maupun profiling intellij, langkah-langkah optimalisasi dengan mengidentifikasi penyebab masalah performance testing yang lemah dan melakukan perbaikan algoritma. Setelah implementasi perubahan, verifikasi fungsionalitas aplikasi dengan pengujian regresi dan pemantauan kinerja, serta pastikan bahwa perubahan tersebut memberikan peningkatan yang diinginkan tanpa memengaruhi fungsionalitas aplikasi.




</details>

