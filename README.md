# Exception-types
ArrayIndexOutOfBoundsException Kotlin mein ek runtime exception hai, jo tab aati hai jab aap kisi array ke index ke bahar ka access karne ki koshish karte hain. Ye hota hai jab aap ek array ke maanak boundary ke bahar ke index ko access karne ki koshish karte hain. Yeh exception asal mein Java mein bhi hoti hai, aur Kotlin Java ka interoperability support karta hai, isliye Kotlin mein bhi wahi exception hoti hai. Yeh ek common error hai jab aap programming mein array indexing ki galti karte hain.
Kotlin mein bhi ArithmeticException ki similar concept hai. Jab koi arithmetic operation mein kuch unexpected hota hai, jaise ki division by zero, toh Kotlin runtime ek ArithmeticException throw karta hai.

Yahan ek example hai Kotlin mein division by zero ke sath ArithmeticException ka use karke:
Is example mein, agar denominator zero hai, toh ArithmeticException throw hoga aur catch block mein control jayega, jahan aap error message print kar sakte hain.
