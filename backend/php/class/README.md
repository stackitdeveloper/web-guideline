## Class & Object
Object-oriented programming (OOP) adalah paradigma pemrograman yang berdasarkan pada Object, yang berisi data dalam bentuk **field/attribute**, serta dalam bentuk **function, procedure** atau **method**
### Class
**class** adalah kumpulan atas definisi data dan fungsi-fungsi dalam suatu unit untuk suatu tujuan tertentu, simplenya **class** adalah blueprint.

katakanlah **class** sebagai **blueprint** dari **rumah**. **Blueprint** itu sendiri bukanlah rumah, tapi ia dalah detail dari rencana perancangan **rumah**.

### Object
**object** adalah hasil instace dari **class** atau hasil konkrit dari **class**

Berikut adalah contoh penulisan **class** dengan penambahan **property** dan **method**
```php
class Cat{

	// property dari class
	public $name;
	public $color;
	public $owner;

	// method dari class
	public function sound(){

	}
}
```  

### Property 
**property** atau sering disebut **attribute** adalah data yang terdapat pada sebuah **class**, semisal nama, warna dan lain-lain.

Berikut contoh penulisan **property**
```php
public $name;
public $color;
```

### Method
**method** adalah tindakan dari suatu **object** atau yang bisa dilakukan dari **class**

Berikut contoh penulisan **method**
```php
public function sleep(){

}

public function walk(){

}
```
Setiap obejct memiliki atribut(attribute) dan aksi(method), katakanlah seekor **kucing**, **kucing** memiliki warna, umur, berat dan lain-lain, semua itu disebut **attribute**, kemudian **kucing** juga makan, tidur, lari dan lain-lain, semua itu disebut aksi**(method)** 