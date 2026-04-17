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



























