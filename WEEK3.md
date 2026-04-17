# 🍁Unit 1 Blueprint of Bits (數位藍圖：進位與編碼) 🏗️ W03
## B.  “Master the Bits, Master the World”
### ASCII  ~ How does 01000001 become 'A'? ~

<img width="667" height="477" alt="image" src="https://github.com/user-attachments/assets/14a7493e-d262-4187-a77f-43ef7feec5cc" />

> ASCII code stands for American Standard Code for Information Interchange. It is a character-encoding system used by computers to represent text using numbers.

> コンピュータは二進数しか扱えないため，文字データも二進数(つまり整数)として表現される．コンピュータは，ある二進数を特定の文字だと思いこんで処理する約束になっている．このような，文字を表現する二進数のことを特に文字コードと呼ぶ．そこで，どの数値とどの文字を対応させるかを決めて，一覧表を作成することなる．現代のコンピュータでは標準的な文字コード表が決まっている．特にアルファベットと記号ではASCII(アスキー)コード表が使用される．

| Character | ASCII value | Binary   |
| --------- | ----------- | -------- |
| A         | 65          | 01000001 |
| B         | 66          | 01000010 |
| a         | 97          | 01100001 |
| 0         | 48          | 00110000 |
| Space     | 32          | 00100000 |

## The Evolution of Bits
### 类比（Analog）与数位（Digital）

<img width="962" height="630" alt="image" src="https://github.com/user-attachments/assets/031af372-8aa1-4322-9bbc-a35fd335edfb" />

> Analog signals vary continuously over time. The values can take any number within a range.  
> アナログは音や温度など連続的に変化する物理量（連続的データ）をそのまま記録し、自然で滑らかな表現が可能ですが、劣化しやすい特徴.

> Digital signals represent information using discrete values, usually 0 and 1 (binary).  
> デジタルは情報を0と1の数字（離散的データ）で表現し、複製・処理・高速伝達に優れる現代の技術基盤.  

**Example {Mercury Thermometer　vs  Digital Thermometer}**

<水銀体温計（Mercury Thermometer）— アナログ / Analog>

- Mechanism  
体温が上がると水銀が膨張し、ガラス管の中を上昇します。  
When body temperature increases, the mercury expands and rises inside the glass tube.

- How it measures  
水銀柱の高さを目盛りで読み取ります。  
The temperature is read by checking the height of the mercury column on the scale.  

- Characteristics  
連続的な変化 → アナログ信号  
Continuous change → analog signal  

<電子体温計（Digital Thermometer）— デジタル / Digital>

- Mechanism  
温度センサーが温度を電気信号に変換し、内部回路が数値に変換して表示します。  
A temperature sensor converts temperature into an electrical signal, and the circuit converts it into numbers displayed on the screen.  

- How it measures  
センサー → 電気信号 → デジタルデータ → 数値表示  
Sensor → electrical signal → digital data → numeric display  

- Characteristics  
数値データで表示  
Shows temperature as numerical data  

測定が速い（約10～60秒)  
Faster measurement (about 10–60 seconds)  

## 🍀C. The Construction (數位施工)
### Part 1: Basic Elite Foundation (20 基礎實驗)

**Lab 1: Binary Decoding (二進位解碼)**  
Translating human-readable text into a language that computers can understand (0s and 1s)   
人間が使う文字を、コンピュータが理解できる言葉（0と1）に翻訳する

<img width="856" height="564" alt="image" src="https://github.com/user-attachments/assets/12d3d784-e61f-48ec-9bd6-bb25910fb92c" />

**Lab 2: Hexadecimal Branding (十六進位色彩)**
defines a function that converts standard RGB (Red, Green, Blue) color values into a Hexadecimal (Hex) color code　　
**RGB（赤、緑、青）の数値を、Webデザインなどで標準的に使われる16進数 HEX**のカラーコードに変換する関数

<img width="730" height="226" alt="image" src="https://github.com/user-attachments/assets/b07e69a8-b0b5-4ca4-883d-3d327fc38a5a" />

**Lab 3: Bitwise AND Flag Check (按位元與：權限檢查)**
Bitmask to isolate specific bits within a status byte　　
ビット演算Bitwise Operationというテクニックを使って、コンピュータの状態をチェックする仕組みを表現しています

<img width="624" height="214" alt="image" src="https://github.com/user-attachments/assets/bd3b8d2d-9857-455e-b42a-f5f894d7a159" />

**Lab 4: Bitwise OR Flag Setting (按位元或：合併狀態)**
<img width="576" height="215" alt="image" src="https://github.com/user-attachments/assets/0873d18f-a25d-480a-8f7f-6fecd0416eba" />

**Lab 5: Bitwise NOT (按位元非：反轉世界)**
<img width="765" height="200" alt="image" src="https://github.com/user-attachments/assets/c3b57303-5f8a-456a-adc1-31c7292af4a3" />

**Lab 6: Bitwise Shift Left (向左位移：硬體加速乘法)**
<img width="599" height="162" alt="image" src="https://github.com/user-attachments/assets/0229a538-11d8-40a6-9fa7-b10f8806e7d8" />

**Lab 7: Bitwise Shift Right (向右位移：數據解鎖)**
<img width="598" height="157" alt="image" src="https://github.com/user-attachments/assets/5aa23e36-178c-4ee7-b6dd-1096d2db1628" />

**Lab 8: ASCII Table Exploration (ASCII 探索)**
<img width="472" height="264" alt="image" src="https://github.com/user-attachments/assets/abd88531-a648-4687-8dcd-4bf82ed81ebf" />

**Lab 9: Unicode & Emojis (萬國碼與 Emoji)**
<img width="858" height="189" alt="image" src="https://github.com/user-attachments/assets/1ba3720f-abe4-40e4-ac17-d2223e859bf3" />

**Lab 10: Big5 vs. UTF-8 (Legacy vs. Modern)**
<img width="635" height="298" alt="image" src="https://github.com/user-attachments/assets/9087937a-bdc1-485c-93d5-15a5b096ccfd" />

**Lab 11: Base64 Encoding (網路傳輸編碼)**
<img width="539" height="187" alt="image" src="https://github.com/user-attachments/assets/24de221b-918a-4e01-9a8c-59cf11c23951" />

**Lab 12: Simple Parity (奇偶校驗：最簡保衛戰)**
<img width="623" height="218" alt="image" src="https://github.com/user-attachments/assets/0c14c67f-3203-4908-9ad9-dd4665003e46" />

**Lab 13: Checksum (總和校驗：封包保險)**
<img width="513" height="169" alt="image" src="https://github.com/user-attachments/assets/09cc0cf7-9a10-4552-815d-c25b15c78b53" />

**Lab 14: RLE Compression (Run-Length Encoding)**
<img width="676" height="191" alt="image" src="https://github.com/user-attachments/assets/09b63b5b-84fe-48fe-99ae-2016a8aec68b" />

**Lab 15: Magic Numbers (檔案身分證)**
<img width="408" height="198" alt="image" src="https://github.com/user-attachments/assets/fa5431b0-4b5f-4a2c-8f5d-9fce128a0a3c" />

**Lab 16: Logical AND Gate (邏輯與：雙重保險)**
**Lab 17: Logical OR Gate (邏輯或：警報系統)**  
<img width="511" height="243" alt="image" src="https://github.com/user-attachments/assets/906af27e-4a8d-426c-a9cb-4e9afeace88f" />

**Lab 18: Logical NOT Gate (邏輯非：電路反轉)**
**Lab 19: Logical NAND Gate (通用邏輯閘：數位建築之母)**  
<img width="631" height="346" alt="image" src="https://github.com/user-attachments/assets/bc920c6e-72e7-47bb-98cb-caf580d482d1" />

**Lab 20: Digital Sampling (數位採樣：現實轉數位)**
<img width="620" height="188" alt="image" src="https://github.com/user-attachments/assets/400b86d7-deaa-4be1-a62d-af541e1004e4" />

### 🔴 Part 2: Advanced Elite Spire (Option)
**Lab 21: The XOR Scrambler (XOR 加密)**

<img width="517" height="184" alt="image" src="https://github.com/user-attachments/assets/d0d48272-a4d4-4ee9-aefd-4bfcbd61dc02" />

**Lab 22: XOR Swap Trick (不需暫存器交換位元)**

<img width="482" height="184" alt="image" src="https://github.com/user-attachments/assets/9a12b57e-5654-484a-94f0-51bc6c430a25" />

**Lab 23: Hamming Distance (噪音測量)**

<img width="649" height="159" alt="image" src="https://github.com/user-attachments/assets/2e733377-f8f9-4807-bd94-2a751415eb14" />

**Lab 24: IP Address to 32-bit Integer**

<img width="767" height="216" alt="image" src="https://github.com/user-attachments/assets/4ae47924-6a4c-44a6-abfc-8ec913b1427a" />

**Lab 25: Subnet Masking (數位分層邊界)**

<img width="530" height="161" alt="image" src="https://github.com/user-attachments/assets/81ad922f-baaa-454f-8ef7-757cf0284695" />

**Lab 26: QR Code Layout (視覺二進位)**

<img width="810" height="201" alt="image" src="https://github.com/user-attachments/assets/88b5bdb4-4e29-4e17-80d2-28a0a1930801" />

**Lab 27: Gray Code (防錯旋轉編碼)**

<img width="514" height="188" alt="image" src="https://github.com/user-attachments/assets/d6458e71-f985-4ba8-814a-f6da80ff37f9" />

**Lab 28: Fixed-point Calculation (財務精算)**

<img width="624" height="190" alt="image" src="https://github.com/user-attachments/assets/f18aa4a8-3f9e-4c9d-9749-718ee14d001c" />

**Lab 29: Parity Matrix (2D 錯誤修正修復)**

<img width="507" height="158" alt="image" src="https://github.com/user-attachments/assets/03e1c0bf-0daf-42f6-9e24-4cef057d8372" />

**Lab 30: Final Synthesis - IoT Secure Packet 🏗️**

<img width="818" height="256" alt="image" src="https://github.com/user-attachments/assets/c350c799-5c36-49f3-a7fc-9dc347dfa9ba" />
