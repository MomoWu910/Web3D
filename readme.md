# Projects of ThreeJS 作品集

All my projects are in my course page [here.](https://momowu910.github.io/Web3D/index.html)

The technical requirement of these project is the following:
- ThreeJS (useful link :[here](https://threejs.org/docs/index.html#manual/introduction/Creating-a-scene))
- nodejs
- database (using file system)

# Summary for each project 摘要

### Computer Graphics with ThreeJS 計算機圖學

>#### Time-based animation (Stopwatch 碼表)
- 模擬碼表的運作，可以暫停、重新計時，或是切換指針運動方式(連續or石英鐘)，以及3種呈現方式

>#### Hierarchical Model 
- 模擬坦克，基本的前後移動及發射砲彈，利用子畫面方便瞄準

>#### Driving Car
- 模擬車子，基本的加減速及轉彎
- 碰撞偵測，車子撞到樹會停止

>#### Light Remote Control
- 燈光遙控器
	- 房間燈：開/關，明/暗
	- 檯燈：開/關，明/暗，旋轉
	- 聖誕樹燈：開/關，三種模式

>#### Basic GLSL
- 平面上有兩個teapot
	- 一個使用MeshPhongMaterial，一個使用ShaderMaterial(GLSL)
	- 畫面上方可以選擇GLSL的計算方式
		- 物件座標 / 世界座標
		- 根據每一點上色 / 根據每一像素上色
	
>#### Basic GLSL + teapot class
- 點擊平面可以增加teapot
	- teapot有生命值，旋轉時會同時減少
	- teapot透明度也會隨生命值的減少而增加
	- 當生命值歸零時，停止旋轉，並在一定時間後消失
- 點擊teapot可以停止 / 繼續旋轉
	
	
### Web3D with ThreeJS 

>#### Xmas Lights 聖誕樹燈
- 模擬聖誕樹上的燈泡
	- 開/關房間、樹上燈光
	- 3種模式可以切換
	- 每個燈泡皆可改名及搜尋

>#### Interior design 室內設計模型
- 利用BoxGeometry設計出一間房子的空間配置
- 3種視角切換

>#### Interior Design of Art Gallery(+GameMode) 畫廊設計(+遊戲模式)
- Visit Mode 參觀模式 ： 從第一人稱視角參觀畫廊
	- 操作方式
		- WASD 移動
		- 移動滑鼠控制視角
		- P 暫停/繼續
- Game Mode 遊戲模式 ： 你是一位小偷，要從這些畫作裡找出5幅名畫並且調換，找齊之後從密道離開
	- 操作方式
		- WASD 移動
		- 移動滑鼠控制視角
		- E 與物件互動
		- 數字1-5 切換身上畫作
		- P 暫停/繼續
		
>#### Integrated Web3D 整合式3D網頁
- 在場景可以佈置三種物件，物件皆可設定大小、顏色
- 並且可以清除、儲存、恢復場景的佈置

>#### Activity Reviewer 行為紀錄器
- 目前只能在Local端操作
- 登入系統
	- 輸入ID登入使用者檔案
	- 輸入日期即可觀看該日行為紀錄
	- 更動完亦可上傳覆蓋舊的行為紀錄
	- 顯示行為時間、地點
- 播放系統
	- 播放/倒帶/暫停
	- 切換 1x、2x、0.5x 播放速度
	- 切換 俯瞰/第三人稱 視角