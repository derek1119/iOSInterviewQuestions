# π NSOperationQueue μ GCD Queue μ μ°¨μ΄μ μ μ€λͺνμμ€



### **<u>λκΈ°</u>**

- μ½λκ° "μμ°¨μ "μΌλ‘ μ€νλλ κ².
- λκΈ°μ μΌλ‘ μ€νλ  λ νμΌ μμΆλ ₯ λ± μκ°μ΄ μ€λ κ±Έλ¦¬λ μμμ΄ μ§νλλ€λ©΄, ν΄λΉ μ½λμμ λͺ¨λ  μμμ΄ λλ  λκΉμ§ κΈ°λ€λ Έλ€κ° λ€μ μ½λλ₯Ό μ€ννλ€.

### **<u>λΉλκΈ°</u>**

- μ½λκ° μμ°¨μ μΌλ‘ μ€νλλ κ²μ λ³΄μ₯νμ§ μλλ€. λΉλκΈ°μ μΌλ‘ μ€ννλ μ½λκ° μλ€λ©΄, μ°μ  λ€μ μ½λλ₯Ό μ€ννκ³ , λΉλκΈ° μ½λκ° λλλ©΄ μ½λ°±μ λ°μ μ€ννλ€.
- μ€λ λλ λ‘μ° λ λ²¨μ ν΄μ΄κΈ° λλ¬Έμ κ°λ°μκ° μ§μ  μ μ΄νλ κ²μ κΉλ€λ‘­λ€. iOSμμλ μ€λ λλ₯Ό μ§μ  λ§λλ λμ μ μ±μμλ νΉμ  νμ€ν¬λ§ μ μνκ³  μμ€νμ΄ μ€λ λλ₯Ό κ΄λ¦¬νλ€.



### GCD(Grand Central Dispatch) Queue - DispatchQueue

- μ±μ κΈ°λ³Έ μ€λ λ λλ λ°±κ·ΈλΌμ΄λ μ€λ λμμ μμ μ€νμ serial λλ concurrent λ°©μμΌλ‘ κ΄λ¦¬νλ κ°μ²΄
- κ°λ°μκ° μ€νν  μμμ μμ±νκ³  Dispatch Queueμ μΆκ°νλ©΄ GCDλ μμμ λ§λ μ€λ λλ₯Ό μλμΌλ‘ μμ±ν΄μ μ€ννκ³  μμμ΄ μ’λ£λλ©΄ ν΄λΉ μ€λ λ μ κ±°
- FIFO

- λΈλ‘ ννμ νμ€ν¬κ° λ€μ΄μ¨λ€
- Serial Queue(νλ²μ νμ€ν¬ νλ)μ Concurrent Queue(νλ²μ μ¬λ¬ νμ€ν¬ μ²λ¦¬)κ° μ‘΄μ¬νλ€.
- μμ€νμ μν΄ κ΄λ¦¬λλ μ€λ λ νμμ νμ€ν¬κ° μ€νλλ, λ©μΈ νλ₯Ό μ μΈνκ³  μ΄λ€ νμ€ν¬κ° μ΄λ μ€λ λμμ μ€νλλ μ§λ λ³΄μ₯νμ§ μλλ€.
- λκΈ°μ  / λΉλκΈ°μ μΌλ‘ νμ€ν¬λ₯Ό μ²λ¦¬ν  μ μλ€.

- μ± μ€νμ μμ€νμμ 2κ°μ Queueλ₯Ό λ§λ€μ΄μ€λ€. 
  - Main queue λ©μΈ μ€λ λμμ μ¬μ©λλ Serial queueλ‘ λͺ¨λ  UIμ²λ¦¬
  - Global Queue Concurrent Queue qosνλΌλ―Έν° μ κ³΅. λ³λ ¬μ μΌλ‘ λμμ μ²λ¦¬νκΈ° λλ¬Έμ μμ μλ£μ μμλ μ ν  μ μμ§λ§ μ°μ μ μΌλ‘ μΌμ μ²λ¦¬νκ² ν  μ μλ€.

### Async / sync (λΉλκΈ° / λκΈ°)

- λκΈ°sync - νλμ μμμ΄ λλ  λκΉμ§ κΈ°λ€λ¦Ό,  λΉλκΈ° async - κΈ°λ€λ¦¬μ§ μμ

### Serial/Concurrent

- νλ²μ μ€ννλ μμμ μ



### NSOperation Queue

- Obj-CκΈ°λ°μΌλ‘ λ§λ€μ΄μ§ API
- λΉκ΅μ  μ€λ²ν€λκ° μλ€
- λ€μν μμλ€ κ°μ΄λ° μμ‘΄μ± μΆκ°, μ¬μ¬μ©, μ·¨μ, μ€μ§ κ°λ₯



# -> λ΅λ³

GCD

- μ½κ³  νΈν λ©ν° μ€λ λ© μ²λ¦¬λ₯Ό μν΄ μ κ³΅λλ api

- μμμ΄ λ³΅μ‘νμ§ μκ³  κ°λ¨νκ² μ²λ¦¬



NSOperationQueue - μ€λ²ν€λ λ°μ, λλ¦¬λ€. μμλμ§ μμ μμμ μ·¨μν  μ μλ€. 

λμμ μ€νν  μ μλ operationμ μ΅λ μλ₯Ό μ§μ ν  μ μμ.

