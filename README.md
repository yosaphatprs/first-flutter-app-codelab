# first-flutter-app-codelab
My first flutter app for Mobile Programming assignment

Nama: Josafat Pratama Susilo

NIM : 2141720031

Kelas : TI-3F


## Daftar Isi

- [Create a project](#create-a-project)
- [Add a button](#add-a-button)
- [Make the app prettier](#make-the-app-prettier)
- [Add functionality](#add-functionality)
- [Add navigation rail](#add-navigation-rail)
- [Add a new page](#add-a-new-page)

## Create a project

Setelah berhasil membuat sebuah project flutter, maka langkah selanjutnya adalah mengedit pubspec.yaml. File ini berfungsi untuk memberikan informasi dasar mengenai project yang kita buat seperti versi aplikasi tersebut, dependencies yang digunakan, beserta asset-assetnya.

![Screenshot pubspec.yaml](my_awesome_namer/docs_images/01.png)

Kemudian konfigurasi analysis_options.yaml untuk mengatur bagaimana Flutter menganalisis kode yang ditulis.

![Screenshot analysis_options.yaml](my_awesome_namer/docs_images/02.png)

Kemudian mengubah isi main.dart, sehingga output dari aplikasi menjadi seperti berikut

![Screenshot main.dart](my_awesome_namer/docs_images/03.png)

## Add a button

First Hot Reload. 
Ketika diubah, dan di save maka fitur hot reload akan jalan dengan output berubah menjadi seperti berikut:

![Screenshot main.dart](my_awesome_namer/docs_images/04.png)

Kemudian menambahkan button seperti berikut.

![Screenshot main.dart](my_awesome_namer/docs_images/05.png)

Setelah itu menerapkan sebuah behavior supaya ketika button ditekan, maka kata random akan berubah seperti berikut.

![Screenshot main.dart](my_awesome_namer/docs_images/06.png)

## Make the app prettier

Langkah pertama yang dilakukan adalah melakukan ekstraksi widget. Cara yang dilakukan adalah refactor widget, sebuah fitur helper untuk melakukan ektraksi. Dengan mengubah kode main.dart menjadi seperti berikut akan membuat ```Text``` widget tidak lagi terreferensi dengan appState.

![Screenshot main.dart](my_awesome_namer/docs_images/07.png)

Setelah melakukan ekstraksi dan wrapping dengan padding pada Text widget, maka akan menghasilkan output seperti berikut.

![Screenshot main.dart](my_awesome_namer/docs_images/08.png)

Kemudian wrap text tadi dengan card supaya menjadi seperti berikut.

![Screenshot main.dart](my_awesome_namer/docs_images/09.png)

## Add functionality

## Add navigation rail

## Add a new page