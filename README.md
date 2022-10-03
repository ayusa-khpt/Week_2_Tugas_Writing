# Writing and Presentation Week 2
## **JavaScript Dasar**
### **JavaScript Introduction**
- **Javascript** Javascript adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website. Javascript juga dapat membuat website menjadi interaktif dan dinamis.
- Cara menjalankan javascript adalah melalui berbagai browser pada device setiap user. Umumnya browser Chrome dan Mozilla yang sudah support untuk semua fitur Javascript. 
- Pada Javascript dikenal dengan istilah **Syntax** dan **Statement**
> **Syntax** bisa dianalogikan seperti kosa kata (vocabulary) dan tata cara (grammar) pada bahasa pemograman. dengan kata lain syntax adalah sesuatu yang dapat diibaratkan sebagai kamus dan berperan dalam mengatur tata cara dalam bahasa pemrograman.

> **Syntax** tertentu digunakan untuk membuat statement program, instruksi untuk djalankan/dieksekusi oleh web browser, compiler, ataupun intrepreter. 

- Contoh Syntax dalam Java Script 
  - Alert 
  - Prompt
  - confirm
  
- **Console Log** adalah hal yang krusial bagi developer web. Console log adalah tempat untuk cek logic pemograman web yang kita kembangkan. Console log juga tempat kita untuk melakukan debugging (mengetahui error pada code) pada pemograman web.

- **Comments** adalah sintaks yang digunakan untuk memberi keterangan tentang suatu statement. Menggunakan bahasa inggris atau bahasa indonesia. Comments tidak akan dijalankan oleh program karena hanya untuk dibaca oleh sesama programmer ataupun diri sendiri untuk memahami maksud dan tujuan sebuah statement/syntax.
  - Single Comments: `` // ``
  - Multiline Comments:  `` /* */``
  
- **Tipe Data** adalah klasifikasi yang kita berikan untuk berbagai macam data yang digunakan dalam programming. Ada 6 macam tipe data fundamaental pada javascript yaitu :
  - Number : tipe data yang mengandung semua jenis angka termasuk angka desimal.
  Tipe data number ada 2 macam yaitu **integer** (terdiri dari bilangan bulat positif atau negatif) dan **float** (terdiri dari bilangan desimal)
  - String : adalah grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya. Harus diawali dan diakhiri dengan single quotes ‘ … ‘ ataupun double quotes “ … “.
  - Boolean : tipe data yang hanya mempunyai 2 buah nilai. 2 buah nilai tersebut adalah TRUE (benar) or FALSE (salah). Analoginya adalah seperti tombol/button ON/OFF dan juga seperti sebuah jawaban antara YES/NO.
  - Null : tipe data yang diartikan bahwa sebuah variable/data tidak memiliki nilai. Tipe data null biasanya diperoleh dalam kondisi normal dan sudah kita rencanakan.
  - Undefined : tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai. Tipe data undefined biasanya didapat dari hasil kesalahan program (error), kelalaian programmer, dan tidak direncanakan.
  - Object : adalah koleksi data yang saling berhubungan (related). Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya). Tipe data object mempunyai key dan value.
  
- **Variabel** disemua bahasa pemograman, variable adalah container/tempat untuk menyimpan sebuah nilai. 
3 hal yang dapat dilakukan pada variabel:
  - variabel harus dibuat dengan nama yang jelas dan menggabarkan tentang data tersebut
  - variabel dapat menimpan dan mengupdate informasi data yang disimpan
  - variabel digunakan untuk menampilkan atau mendapatkan data yang tersimpan
  
- Ada 3 cara untuk mendefinisikan variabel :
  - var
    ```
    var myName = 'Desi';
    console.log(myName);
    // Output: Desi
    ```
  
  - let
    ```
    let food = 'milk';
    console.log(food); // Output: milk
    milk = 'susu';
    console.log(milk); // Output: susu
    ```

  - const
    ```
    const pi = 3.14;
    console.log(pi); // Output: 3.14
    pi = 10;
    console.log(pi); // Output: Uncaught TypeError: Assignment to constant variable
    ```
  
- Aturan Penamaan variabel :
  - Harus mendeskripsikan dengan jelas tentang data yang disimpan
  - Tidak bisa menggunakan angka diawal variabel 
  - Menggunakan camelcase untuk nama variabel yg lebih dari 1 kata
  
- **Operator**
- **Assignment Operator (=)** digunakan untuk menyimpan sebuah nilai pada variabel
 contohnya : `` let myName = 'Indri'``
 
- **Mathematical Assignment Operator**
- contohnya : 
  ```
    let x = 5 ; 
    x *= 2 ; 
    console.log(x) // Output: 10
  ```
  
- **Increment dan Decrement** digunakan untuk menambah atau mengurangi sebesar 1 nilai
- contohnya :
  ```
  let a = 10;
  a++;
    console.log(a) // output: 11
  
  let b = 20;
  b--;
    console.log(b) // output: 19
  ```
  
- **Arithmetic Operator** digunakan apabila melibatkan operasi matematika
  - Pertambahan (+)
  - Pengurangan (-)
  - Perkalian (*)
  - Pembagian (/)
  - Modulus (%)
  
- **Comparism Operator** digunakan untuk membandingkan suatu nilai 
  - Lebih Besar (>)
  - Lebih Kecil (<)
  - Lebih kecil atau samadengan (<=)
  - Lebih besar atau samadengan (>=)
  - Samadengan (===)
  - Tidak Samadengan (!==)
  
- **Logical Operator** digunakan untuk sebuah kondisi
  - AND operator (&&)
  - OR operator (||)
  - NOT operator (!)
  
### **Conditional**
- **Conditional** merupakan *statement percabangan* yang menggabarkan suatu *kondisi*
- Conditional statement akan melakukan pengecekan pada kondisi fisik dan menjalankan perintah berdasarkan kondisi tersebut
- Yang dicek adalah apakah kondisi tersebut TRUE (benar). Jika TRUE maka code didalam kondisi tersebut dijalankan.
- Contoh Conditional
- IF Statement: 
- contoh conditional **if statement** :
  - Jika cuaca hari ini cerah, maka kita akan pergi keluar
  - jika saya lapar, maka saya makan
  - Jika lelah, maka kita akan istirahat
  
- contoh if statement 
  ```
  let nilai = 10;
  if (nilai === 10){
    console.log('variabel nilai yang disimpan adalah benar 10');
  }
  ```
- IF ... ELSE Statement: Else akan mengeksekusi sebuah statement/code jika suatu kondisi bernilai FALSE
- contoh conditional **if else statement**
  ```
  let lapar = false;
  if (lapar){
    console.log("Yuk makan"); // Program tidak akan menampilkan statement ini
  } else {
    console.log("Tidak makan") // Program akan menampilkan statement ini
  }
  ```
- IF ... ELSE IF Statement: dapat kita gunakan jika kita mempunyai berbagai kondisi.
- contoh conditional **if else if statement**
  ```
  let stopLight = 'Yellow';
  if (stopLight === 'red'){
      console.log('Stop!');
  } else if (stopLight === 'Yellow'){
      console.log('Slow down.');
  } else if (stopLight === 'Green'){
      console.log('Go!');
  } else {
      console.log('Caution, unknow!')
  }
  ```

- Switch Case Conditional digunakan jika kondisi dan percabangan terlalu banyak
- contoh conditional **switch case**

  ```
	let warna = "hijau";
 
		switch (warna){
			case "biru":
				console.log ("warna biru");
				break;
			case "merah":
				console.log ("warna merah");
				break;
			case "kuning":
				console.log ("warna kuning");
				break;
			default:
			    console.log ("warna tidak terdeteksi");
		}
  ```
- Ternary Operator merupakan short-syntax dari statement if … else.
- contoh ternary operator
  ```
  let isNowSale = true;
  isNowSale ? console.log('Let's shopping now) : console.log('Shopping later);
  ```
### **Truthy and Falsy**
- Truthy and falsy digunakan untuk mengecek apakah variabel telah terisi namun tidak mementingkan nilainya.
- Truthy and Falsy Assignment Analoginya adalah jika kita memiliki sebuah website dan meminta inputan username lalu menampilkannya. Jika usernamenya kosong kita bisa isi nilai tersebut.

### **Looping**
- **Looping** adalah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi stop/berhenti tercapai.
- Ada 3 macam looping yaitu :
  - For Loop 
  - While Loop
  - Nested Loop
- For Loop : merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita kembangkan. Gunakan FOR LOOP jika kita tahu seberapa banyak nilai pasti untuk pengulangannya. Jika kita ingin menampilkan angka 1 - 100 kita menggunakan FOR LOOP. Karena kita sudah tahu bahwa pengulangan akan dilakukan sebanyak 100kali
- contohnya :
```
    let nilai = 1 ; 
    for (nilai; nilai <= 10 ; nilai++){
        console.log(nilai) 
    } 
```
- While Loop : akan menjalankan instruksi pengulangan bernilai TRUE. Gunakan WHILE LOOP jika kita tidak mengetahui jumlah pasti pengulangan.
  Ada 2 macam while loop yaitu while dan do while
- contoh perulangan while :
```
    let count = 1 ; 
    while (count < 10){
        console.log(count);
        count ++ ;
    } 
```
- contoh perulangan do while :
```
    count = 1 ;
    do {
        console.log(count);
        count ++ ;
    } while (count <= 10)
```     
- Nested Loop : jika kita membuat looping didalam looping. Maka ini dinamakan Nested Loop. Looping pertama dianalogikan sebagai baris. Looping kedua dianalogikan sebagai kolom.

### **Scope dan Function**
- **Scope** adalah konsep dalam flow data variabel.
Menentukan suatu variabel apakah bisa diakses pada scope atau tidak.
Analoginya kita semua bisa melihat bintang-bintang dilangit karena bumi bersifat global. Namun jika kamu tinggal di Bandung, kamu tidak akan bisa melihat monas yang berada di jakarta. Monas bersifat local yaitu hanya berada di Jakarta.
- Scope ada 2 macam yaitu global scope dan local scope
- Global scope : berarti variabel yang kita buat dapat diakses dimanapun dalam suatu file. Agar menjadi Global Scope, suatu variabel harus dideklarasikan diluar Blocks.
```
    let myName = "chaca" ; 
    function greeting()
        return myName;
    {
        console.log(myName);
```
- Local scope : berarti kita mendeklarasikan variabel didalam blocks seperti function, conditional, dan looping. Maka variabel hanya bisa diakses didalam blocks saja. Tidak bisa diakses diluar blocks.
```
    function greeting()
       let myName = 'Raisu';
       return myName;
    {
    	console.log(greeting())
        console.log(myName);
```
- **Blocks** merupakan code yang berada dalam curly braces {}. Conditional, function dan looping menggunakan blocks.

- **Function**
- **Function** merupakan sebuah blok kode dalam sebuah grup untuk menyelesaikan 1 task/1 fitur. Saat kita membutuhkan fitur tersebut nantinya, kita bisa kembali menggunakannya.
- Membuat function 
```
   function greeting() {
      return 'Hello World' ;
   };
```
- Cara memanggil function : 
```
 greeting()
 console.log(greeting()); 
 
 ```
- **Parameter dan Argument**
- Argumen adalah nilai yang digunakan daat memanggil function. Jumlah argumen harus sama dengan jumlah parameternya. <br />
- contoh argumen :
```
  function penambahan(a,b){
   return a + b;
}
  console.log(penambahan(5,5))
```
- Parameter berfungsi untuk menerima sebuah inputan data yang digunakan untuk melakukan task. <br />
- contoh parameter :
```
function calculateArea(width,height){
  console.log(width * height);
}
```
- **Function Helper** kita bisa menggunakan function yang sudah dibuat pada function lain.
- contoh penulisan function Helper :
```
 function multyplyByNineFifths(number) {
    return number * (9/5);
};
 function getFahrenheit(celsius) {
    return multyplyByNineFifths(celsiu)+32
};
 getFahrenheit(15);
```
- **Arrow Function** adalah cara lain menuliskan function. Ini adalah fitur terbaru yang ada pada ES6 (Javascript Version)
- contoh penulisan arrow function :
```
 const greeting = (a,b) => {
    return a + b;
}
```
- Short Syntax Function
- **Single Line Block** 
- ``const sumNumbers = number => number + number ; ``
- **Multi Line Block
```
  const sumNumbers = number => {
    const sum = number + number;
    return sum;
  }
```

### Data Type

### **DOM HTML**
- DOM merupakan cara memanipulasi html agar website lebih dinamis dan interaktif
- Cara memanggil DOM Value yaitu :
  - Memanggil tag HTML berdasarkan ID
  `` console.log(document.getElementByID("header))``
  - Memanggil tag HTML berdasarkan Class Name 
  `` console.log(document.getElementByClassName("text-color-blue"))``
  - Memanggil tag html berdasarkan query selector
  `` console.log(document.querySelector("#header "))`` 
  `` console.log(document.querySelector(".text-color-blue"))``
- Memanipulasi content
  Cara memanipulasi content :
  1. Deklarasi varible header sebagai wadah untuk menyimpan tag HTML
  `` let header = document.getElementById("header"); ``
  2. Memanipulasi Content pada Header Content dari pemilik element dengan ID Header dengan text.Content
  `` document.getElementById("header").textContent = "Teks Heading" `` <br />
     Memanipulasi Content didalam sebuah element dengan .innerHTML
  ```
  <ul id= "list"></ul>
  document.getElementById("list").innerHTML = "<li> item1 </li> <li> item2 </li>"
  ```
- Membuat Element HTML
- Contoh :
  ```
  <div id ="header"></div>
  //untuk membuat sebuah elemnt heading
  const heading = dosument.createElement("h1)
  heading.textContent = "Ini Heading"
  document.getElemntByID("header").appendChild(heading)
  ```

- **DOM Events** merupakan object model yang bertugas untuk membantu interaksi user dengan document HTML
- Contoh HTML DOM events
  - Click
  - Scroll
  - Change
  - Focus
  - Hover
  - Submit
  - Blur
- Menangkap Interaksi User
  - Element.addEventListener("event)
  - Element.onevent
- EventListener <br />
  Dengan menggunakan Element.addEventListener("event") dapat menerapkan beberapa hal yaitu :
  - Bisa dihilangkan
  - Bisa ada beberapa event listener yang sama untuk 1 element
  - Memiliki argument tambahan {options}
- Contoh EventListener :
  - EventListener - Click 
    `` <input id="user-input"/> ``
    `` <button id="alert-button">show</button> ``
    Memanggil element berdasarkan id
    `` const input = document.getElementById("user-input") ``
    `` const button = dosument.getElementById("alert-button") ``

    ```
     button.addEventListener("click", function()) {
      alert(input.value)
    } 
    ```
- EventListener - Blur : event dimana sebuah element kehilangan fokus dari user 
- Contoh EventListener - Blur <br />
  Misalkan saat ingin memvalidasi isi dari ``<input id = "username" />`` agar panjangnya minimal 6 karakter

  `` const input = document.getElementById("username") ``

  ```
  input.addEventListener("blur", () => {
    if(input.value.length < 6) alert("Panjang username minimal 6")
  })
  ```
- EventListener - Form Submission
- Contoh EvenListener - Form Submission <br />
  Misalkan terdapat beberapa input dalam sebuah form `` <input name="email"/> `` dan ``<input type="password" name="password"/>`` <br />
  Untuk mendapatkan isi dari kedua inputan tersebut terdapat 2 cara :
  - Memasang event listener di kedua input dan tombol submit, lalu saat tombol diklik, baca value dari kedua input tersebut
  - Memasang event listener di form, lalu gunakan FormData untuk menggambil data dari masing-masing input
  ``` 
    const form = document.getElementById("form")
    form.addEventListener("submit", function(event)){
    event.preventDefault()
    const formData = new FormData(form)
    const values = Object.fromEntries(formData) {
      email: ....
    }
  })
  ```
