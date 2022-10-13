# flutter
All file

---   

## ☢︎ Image Address. 

[Download](https://drive.google.com/file/d/1uax6KiUI6W8AxFSlEx-G7EZvrMeUXETi/view?usp=sharing)

---    


## ☢︎ File: SizeConfig() ใช้เพื่อกำหนด ขนาด Font

[Download](https://drive.google.com/file/d/1_Y-8hwHWLrPAPEyrxDaegnMoML8FG2aG/view?usp=sharing)  

STEP 1. Declare...

🔨 Must Declare: this code in Parent Widget

`  SizeConfig().init(context);  `

STEP 2. Usage

``` dart

SizedBox(  
  height: SizeConfig.screenHeight,
  width: SizeConfig.screenWidth,
  child: Container(),
),

```    

---    

## ☢︎ Layout   

จัดให้ Child เรียงเต็ม พื้นที่ Stretch

```dart 
Column(
  mainAxisAlignment: MainAxisAlignment.center,
  crossAxisAlignment: CrossAxisAlignment.stretch,
  children: [
    const Text("Create To Firebase"),
    TextFormField(),
    const SizedBox(
      height: 20,
    ),
    ElevatedButton(
      onPressed: () {},
      child: const Text("Send"),
    ),
  ],
)

```  
<img width="314" alt="Screen Shot 2565-10-13 at 12 04 06" src="https://user-images.githubusercontent.com/10919051/195506225-273379fd-273b-473b-8313-417f46acf7ef.png">

---   


