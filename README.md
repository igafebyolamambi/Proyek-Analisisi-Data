# Cara Menjalankan Dashboard

Pertama kita buka Visual Studio Code dan cari file bernama dashboard.py

terus kita buka terminal visual studio code seperti gambar dibawah ini

![image.png](attachment:image.png)

lalu kita buka Command Prompt seperti gambar dibawah ini

![image.png](attachment:image.png)

sebelum menjalankan dokumen dashboard.py terlebih dahulu kita menginstall package/library yang diperlukan

dengan perintah **pip install [package/library python]**

disini saya akan install pandas, matplotlib, seaborn, dan streamlit

karna saya tidak bisa langsung menginstall package/library python **pip install [package/library]**. Saya harus menjalankan perintah **python -m venv myenv**

Perintah **python -m venv myenv** digunakan untuk membuat lingkungan virtual baru di Python. Lingkungan virtual adalah cara untuk mengisolasi proyek Python, yang memungkinkan Anda untuk mengelola dependensi proyek tanpa mempengaruhi instalasi Python global atau proyek lain.

Berikut adalah penjelasan singkat tentang komponen perintah ini:

- python: Menunjukkan bahwa Anda akan menjalankan Python.
- -m venv: Menunjukkan bahwa Anda akan menggunakan modul venv yang disertakan dalam Python standar untuk membuat lingkungan virtual.
- myenv: Nama dari direktori di mana lingkungan virtual akan dibuat. Anda bisa mengganti myenv dengan nama lain sesuai keinginan Anda.

![image.png](attachment:image.png)

lalu saya menjalankan perintah **myenv\Scripts\activate**


![image.png](attachment:image.png)

setelah itu saya baru bisa install library/package yang di perlukan

1. Install library pandas **pip install pandas**

![image.png](attachment:image.png)

2. Instal library matplotlib

![image.png](attachment:image.png)

3. Install library seaborn **pip install seaborn**

![image.png](attachment:image.png)

4. Terakhir install streamlit **pip install streamlit**, streamlit gunanya untuk menjalankan dashboard.py dalam visual studio code

![image.png](attachment:image.png)

![image.png](attachment:image.png)

setelah menginstall library yang diperlukan. Maka itu kita bisa menjalan dashboard.py dengan perintah **streamlit run dashboard\dashboard.py**
dashboar(folder penyimpanan file dashboard.py), bisa dilihat gambar diawah ini

![image.png](attachment:image.png)

![image.png](attachment:image.png)

Setelah muncul Local URL seperti gambar diatas kita bisa mengklik Follow Link dan kita akan arah ke web server, seperti gambar dibawah ini

![image.png](attachment:image.png)

![image.png](attachment:image.png)

![image.png](attachment:image.png)


