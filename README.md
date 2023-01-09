# -LT-5_Variabel

Variabel adalah suatu tempat di memori komputer yang digunakan untuk menyimpan sebuah nilai. Nilai tersebut dapat berupa string, angka, boolean, atau tipe data lainnya. Dalam JavaScript, variabel dideklarasikan dengan menggunakan keyword let. Misalnya:

    let name = "John";
    let age = 30;
    let isCold = true;
    
Variabel juga dapat diubah nilainya kapan saja. Misalnya:

    let name = "John";
    console.log(name); // Output: "John"

    name = "Jane";
    console.log(name); // Output: "Jane"
    
Variabel juga dapat dideklarasikan dengan keyword const, yang berarti bahwa nilai dari variabel tersebut tidak dapat diubah. Misalnya:

    const PI = 3.14;
    console.log(PI); // Output: 3.14

    PI = 3.14159; // Akan menyebabkan error
