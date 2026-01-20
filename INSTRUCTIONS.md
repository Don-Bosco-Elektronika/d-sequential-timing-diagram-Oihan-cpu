# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram



**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| D | 74100,74175,74164,74165,74595             | <img width="228" height="354" alt="Captura de pantalla 2026-01-20 080457" src="https://github.com/user-attachments/assets/b767fa2a-a98b-443b-ae96-a442f65c1e95" />
 
  
  | D motako flip-flop batek bere D sarrera kopiatu egiten du Q irteerara bakarrik erlojuaren pizkundean, eta balio hori mantentzen du hurrengo pultsurarte. |  



---

## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

---

## 🔲 Circuitos a Simular / Simulatzeko Zirkuituak / Circuits to Simulate

*(Añade aquí la captura de proteus)*

<img width="681" height="414" alt="Captura de pantalla 2026-01-20 082651" src="https://github.com/user-attachments/assets/49f191b1-b0b1-4b74-94c1-46779d87cb11" />
<img width="754" height="408" alt="Captura de pantalla 2026-01-20 082634" src="https://github.com/user-attachments/assets/8ee4be88-1a36-493c-8568-ebee7e9d4908" />
<img width="553" height="430" alt="Captura de pantalla 2026-01-20 082616" src="https://github.com/user-attachments/assets/aaa2cb0d-5f75-423d-aeb2-86e02659469f" />
<img width="724" height="427" alt="Captura de pantalla 2026-01-20 082554" src="https://github.com/user-attachments/assets/0f6a6bda-8af6-4c36-96cf-db0129aa4a52" />
<img width="748" height="409" alt="Captura de pantalla 2026-01-20 082530" src="https://github.com/user-attachments/assets/34588555-ff31-434d-bb9d-dbbe626b00f5" />


---

## 🔲 Resultado del Cronograma / Kronogramaren Emaitza / Timing Diagram Result
Circuito A

<img width="819" height="490" alt="4  Ariketa - D" src="https://github.com/user-attachments/assets/7c432734-f5d6-41ee-bcd1-7fd78f21a318" />
<img width="775" height="492" alt="3  Ariketa -D" src="https://github.com/user-attachments/assets/00c969cb-bc7d-4ab9-842f-0f4e8bf7a716" />
<img width="805" height="521" alt="2  Ariketa - D" src="https://github.com/user-attachments/assets/cab53ecc-4f74-414c-a723-2a5922212f6f" />
<img width="810" height="489" alt="1 Ariketa -D" src="https://github.com/user-attachments/assets/143f40a0-0bf2-43b2-9a65-a9709071b923" />
<img width="814" height="513" alt="Captura de pantalla 2026-01-19 110002" src="https://github.com/user-attachments/assets/7d8ce7eb-2a09-4e23-b691-d9e67ea8a613" />


---


## 🔲 Código del Cronograma / Kronogramaren Kodea / Timing Diagram Code
1.Arikenta (D asíncrono)

{signal: [

  {name: 'D', wave: 'hl….hl.h..lhl.h'},
  
   {},
   
  {name: 'Q', wave: '10..10.1..010.1'},
  
  {name: '-Q', wave: '01..01.0..101.0'}
  
]}


2.Ariketa(D flanco ascendente)


{signal: [

  {name: 'clk', period:2, wave: 'P........'},
  
  {name: 'D', wave: '0101..0..1.0..1.0'},
  
  {},
  
  {name: 'Q', wave: '01..........0...1'},
  
  {name: '-Q', wave: '10..........1...0'}
  
]}

3.Ariketa(D flanco descendente)

{signal: [

  {name: 'clk',period:2, wave: 'N........'},
  
  {name: 'D', wave: '10101..0.10.1..01'},
  
  {},
  
  {name: 'Q', wave: '1.0...1.0.1.0.1.0'},
  
  {name: '-Q', wave: '0.1...0.1.0.1.0.1'}
  
]}

4.Ariketa(D nivel alto)

{signal: [

  {name: 'clk', period:2, wave: 'p........'},
  
  {name: 'D', wave: '10101..0.10.1..01'},
  
  {},
  
  {name: 'Q', wave: '1.......0...1....'},
  
  {name: '-Q', wave: '0.......1...0....'}
  
]}

5.Ariketa(D nivel bajo)

{signal: [

  {name: 'clk', period:2, wave: 'n........'},
  
  {name: 'D', wave: '10101..0.10.1..01'},
  
  {},
  
  {name: 'Q', wave: '1.......0...1....'},
  
  {name: '-Q', wave: '0.......1...0....'}
  
]}




---


## 📤 Entrega / Igo / Upload  

➡️ **Instrucciones:**  

- **ES:** Sube los siguientes archivos. Todos los archivos subidos han de tener tu nombre.  
  - Una foto del símbolo.  
  - El archivo en Proteus y una captura de imagen de cada circuito en Proteus.  
  - Capturas de cada resultado del Wavedrom (solo el gráfico).  
  - **ATENCIÓN:** El código del cronograma TIENE que ser código, no una imagen.

- **EU:** Igo hurrengo fitxategiak. Igotako fitxategi guztiek zure izena eduki behar dute.  
  - Sinboloaren argazki bat.  
  - Proteus fitxategia eta zirkuitu bakoitzaren irudia (captura) Proteusen.  
  - Wavedrom bakoitzaren emaitzaren kaptura (grafikoa bakarrik).  
  - **KONTUZ:** Kronogramaren kodea kodea izan behar da, ez irudi bat.

- **EN:** Upload the following files. All uploaded files must include your name.  
  - A photo of the symbol.  
  - The Proteus file and an image capture of each circuit in Proteus.  
  - Uno capture of each Wavedrom result (graph only).  
  - **ATTENTION:** The schedule code MUST be real code, not an image.



