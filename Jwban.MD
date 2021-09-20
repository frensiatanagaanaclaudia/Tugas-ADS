### Jawaban :

### 1.Input Temp  // masukan temperatur 
### Input Type // masukan tipe suhu
### If type Is "fahrenheit" THEN  // jika fahrenheit maka
### SET result = (temp-32) * (5/9)  // lakukan ini
### DISPLAY result  // tunjukan hasil 
### Else If type IS "kelvin" THEN  // jika kelvin maka
### SET RESULT = (TEMP-273.15) // lakukan ini
### DISPLAY RESULT  //tunjukkan hasil
### ELSE   // jika bukan kelvil atau fahrenheit
### DISPLAY temp  // maka tunjukkan temperatur awal 
### ENDIF  //selesai

### 2.Number =  0  //inisialiasi awal
### WHILE Number is less than or equal to 20  //jika number kurang atau sama dgn 20 
### OUTPUT Number //keluarkan  number 
### IF Number is divisible by 3  // jika number % 3 =0 maka
### OUTPUT “Fizz” //keluarkan Fizz
### ENDIF //selesai
### IF Number is divisible by 5  // jika number % 5 =0 maka
### OUTPUT “Buzz” // keluarkan Buzz
### ENDIF
### IF Number is divisible by 3 && 5   // jika number % 3 dan % 5 = 0
### OUTPUT “FizzBuzz” // keluarkan FizzBuzz
### ENDIF // selesai
### increase Number by 1 // tambhkan 1 angka
### ENDWHILE


### 3.SET INPUT text  //atur input awal 
### F0R ( i = 0; i < text ; i++) { //looping sesuai kondisi
### SET palindrome = text [text.length]  // Split ke array
### text.length -- 1   // decrement (nilai berkurang/menurun)
### ENDFOR 
### IF text == palindrome  // cek kondisi 
### OUTPUT "True" // keluarkan True
### ENDIF
### IF text != palindrome  // cek kondisi
### Output "False"  " // keluarkan false
### ENDIF

### 4.INPUT Grade  // masukan nilai 
### set "a" = INPUT % 5   // %5 artinya modulus 
### IF "Grade" <70 THEN   //cek kondisi
### SET result = Grade  //atur result
### DISPLAY Grade  // tunjukan grade
### IF "a" < 3 THEN   // cek kondisi
### SET result = Grade  //atur result
### DISPLAY result  // tunjukan result
### ELSE IF "a" >=3 THEN  // cek kondisi
### SET result = Grade + (5-a)  // grade ditambah (5-a)
### DISPLAY result  // tunjukan result
### ENDIF // selesai
