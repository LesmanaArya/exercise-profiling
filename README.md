## Test Plan 2 Before Optimize (student-name)
![Jmeter](https://github.com/LesmanaArya/exercise-profiling/blob/main/img/test_result_2_jmeter.png)
![cmd](https://github.com/LesmanaArya/exercise-profiling/blob/main/img/test_result_2_cmd.png)

## Test Plan 2 After Optimize (student-name)
![Jmeter](https://github.com/LesmanaArya/exercise-profiling/blob/optimize/img/test_result_2_jemeter_after_optimize.png)
![cmd](https://github.com/LesmanaArya/exercise-profiling/blob/optimize/img/test_result_2_cmd_after_optimize.png)

## Test Plan 3 Before Optimize (highest-gpa)
![Jmeter](https://github.com/LesmanaArya/exercise-profiling/blob/main/img/test_result_3_jmeter.png)
![cmd](https://github.com/LesmanaArya/exercise-profiling/blob/main/img/test_result_3_cmd.png)

## Test Plan 3 After Optimize (highest-gpa)
![Jmeter](https://github.com/LesmanaArya/exercise-profiling/blob/optimize/img/test_result_3_jmeter_after_optimize.png)
![cmd](https://github.com/LesmanaArya/exercise-profiling/blob/optimize/img/test_result_3_cmd_after_optimize.png)

---
## Reflection 5
1. Menurut saya, Jmeter lebih digunakan untuk mengetahui secara keseluruhan sample time dan beban load dari aplikasi kita secara keseluruhan. Intellij Profiler lebih ke secara spesifik mengukur performa dari setiap method atau bahkan line dari kode kita lengkap dengan CPU time dan total time nya. Dengan Profiler, kita dapat mengetahui secara detail bagian mana dari kode kita yang memiliki waktu paling lama. Dengan Jmeter, hanya mengukur keseluruhan dari time sample yang kita berikan, tidak menunjukkan bagian mana yang run time nya paling lama. Sehingga, Profiler lebih ke menganalisis secara dalam, sedangkan Jmeter adalah memberikan kesimpulan perkiraan secara keseluruhan program kita
2. Profiler sendiri memberi tahu CPU time dan total time dari program kita. Dengan Profiling, kita dapat mengetahui bagian mana dari program kita yang memiliki waktu sangat lama. Karena profiler dapat mem-point out bagian mana dari program kita yang sangat lama, kita dapat menentukan bagian mana yang diperlukan optimize
3. Ya. Intellij Profiler dapat menunjukkan waktu dan run time dari method yang memiliki waktu terlama. Dengan Profiler, kita jadi tahu bagian mana dari program kita yang perlu di optimize
4. Tantangan terbesar menurut saya adalah menentukan cara meng-optimize kode kita. Menentukan bagian yang perlu di optimize mungkin mudah, tetapi memikirkan bagaimana cara meng-optimize nya terkadang merupakan tantangan sendiri. Apalagi jika bagian yang perlu di optimize adalah bagian yang paling dasar dari aplikasi kita sementara kode kita sudah panjang dan banyak dependensinya. Cara untuk menangani masalah tantangan tersebut tentu adalah banyak berlatih dan mencari referensi-referensi mengenai clean code dan optimize code
5. Keunggulan tersendiri dari Profiler menurut saya adalah integrasinya dengan Intellij Ultimate. Kita mudah mengoperasikannya sambil analisis kode di Intellij. Intellij profiler juga memberikan detail mengenai performance dan run time program. Dan tentu saja, Profiler dapat menunjukkan method yang memiliki waktu terlama sehingga mudah untuk menentukan bagian mana yang harus di optimize. Profiler juga mudah untuk dipelajari apalagi jika sudah sering mengoperasikan Intellij. 
6. Kita bisa menganalisis dan melakukan run ulang kode. Tetapi perlu diketahui juga perbedaan dari Jmeter dan Profiler. Jmeter lebih ke menganalisis overall program aplikasi. Intellij profiler lebih ke analisis secara detail setiap performa dan run time kode kita. Jika ada perbedaan di antara hasil Jmeter dan Profiler tetapi perbedaannya masih masuk akal, kemungkinan itu adalah karena perbedaan lingkungan dan cara analisis keduanya. Jika ingin kebih aman, mungkin bisa menggunakan testing performance dari aplikasi ketiga
7. Diperlukan kemampuan analisis yang baik dalam membaca kode program. Saya pribadi perlu membaca dan memahami berulang kali cara bekerja dari student-names dan highest-gpa sebelum memahami cara optimization nya. Untuk memastikan bahwa perubahan yang terjadi tidak memengaruhi, kita dapat membuat unit test dan bisa juga melakukan test-tes tambahan secara manual untuk memastikan bahwa tidak terjadi masalah pada aplikasi kita.
