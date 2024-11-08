剪輯自: [https://www.ithome.com.tw/tech/154820](https://www.ithome.com.tw/tech/154820)  
液態冷卻是資料中心發展的重要技術，雲達日前自主研發結合氣冷與液冷的伺服器機櫃，耗電量減少68%，PUE可降至1.07

![Exported image](Exported%20image%2020241106113451-0.png)

因應龐大而密集的運算需求，再加上能源價格飆漲，資料中心環境正面臨冷卻成本暴增的挑戰，在此同時，新一代伺服器CPU、GPU的熱設計功耗（TDP）節節高升，不僅需要更多電力，如何有效散熱也面臨重大挑戰。為此，伺服器廠商幾年前就投入進階資料中心冷卻技術的發展與合作，例如，針對鎖定高運算密度、高頻交易等應用的產品當中，導入所謂的直達晶片液態冷卻（D2C）設計；與3M、台達等機房冷卻設備業者合作，共同推廣浸沒式液態冷卻技術（Immersion Cooling）。  
從去年底到現在，有幾家伺服器廠商宣布推出自主設計的進階液態冷卻解決方案。去年4月，微軟宣布與緯穎科技合作開發雙相液態冷卻解決方案，已建置於微軟美國華盛頓州昆西市（Quincy）的資料中心，12月鏡周刊報導；今年11月，技嘉科技發表自主研發的單相浸沒式液冷方案，推出兩款浸沒式液冷冷卻液槽。  
12月7日，在英特爾舉行Intel Sustainability Taiwan Day的大會，現場有多家廠商展出此類型產品。例如，英業達基於英特爾5月發表開放智財浸沒式冷卻解決方案，設計出一款可容納48U伺服器機架空間的設備，以及一體式邊緣運算浸沒式冷卻系統。  
另一家是廣達電腦旗下的雲達科技（Quanta Cloud Technology，QCT），他們展示了機櫃級的直達晶片液態冷卻方案QoolRack。該公司總經理楊麒令強調，採用水冷板（Cold Plate）設計的產品，是目前最能滿足客戶需要的解決方案，更重要的是，QoolRack已經是準出貨的狀態（Ready to Ship），可大大節省機櫃層級用於冷卻的功耗，幅度將近70%，能在不啟動暖通空調（HVAC）的情況之下運作，降低隨之而來的大量用電負擔，並在這樣的環境配置之下，能將電力使用效率（PUE）降低至1.07。  
在這套解決方案中，雲達設計了冷卻液分配單元（CDU），裡面設置資料中心安全控制模組（DC-SCM），能根據實際工作負載來執行智慧化的耗電量管理。在此同時，QoolRack也能與資料中心既有的氣冷型機櫃並存，目前已準備通過英特爾驗證，可用於搭配最新推出的第四代Xeon Scalable系列處理器。  
而在雲達隔週後舉行的年度活動Q.synergy Taiwan 2022，這款機櫃再度亮相，該公司也進一步解說箇中關鍵。

### **看好水冷板結合氣冷設計的效益，現在就能設置於資料中心**

今年下半以來，QoolRack已陸續在全球多場大型活動公開亮相，例如，9月底舉行的Intel Innovation年度大會、10月舉行的OCP全球高峰會，11月舉行的SC超級電腦大會，並且發表演講，而在12月舉行的Intel Sustainability Taiwan Day與Q.synergy Taiwan 2022，臺灣終於也能一睹這款進階液冷機櫃的廬山真面目。  
為何他們要發展液態冷卻產品？何以獨鍾Cold Plate液態冷卻技術？雲達資深經理駱威先表示，液態冷卻解決方案已經在業界出現一段時間，他們認為這是現在馬上需要的技術。  
根據他們的觀察與實測分析，若以每個晶片插槽對應三年總成本，在氣冷（Air Cooling）環境下，當每顆晶片的熱設計功耗是300瓦以下，成本上升的斜率仍在合理範圍內，然而，每插槽的熱設計功耗如果是300瓦、350瓦以上，成本會以指數直線上升的方式激增，以每插槽熱設計功耗400瓦為例，可承受的溫度是攝氏70度，每瓦冷卻成本大於0.05美元，顯然已無法繼續單靠氣冷這樣的架構來進行散熱。  
而在雲達設計的Cold Plate解決方案當中，可支援每插槽熱設計功耗700瓦的晶片，可承受的溫度是攝氏75度，每瓦冷卻成本低於0.05美元。根據該公司最新實測結果，此項設備可支援每插槽熱設計功耗800瓦、甚至更高的晶片。  
雲達另一個考量是立即可用的程度。駱威先強調，假如明天就要採用液態冷卻方案，Cold Plate會是最好的選擇。為此，他們列出成本、效能、使用擔保等層面的評估，突顯其優勢。

[![Cooling Solution Comparison 00 | ing Type Heat Transition Coolant ( 〔 0 , USD/liter) (Volume: L/42U rack) Required Facility Performance ( 1 Unit) PUE Warranty Infrastructure Assessment CAPAX (Est.) QCT Liquid c00 | i " 9 Cold Plate L2L Cost: $ 3.5 Volume: 30L Immersion S 0 Phase L2L Cost: $ 150 or Hot Oil $ 3 Volume: 500L Chiller/ Outside Air Pipes Cooling Tower Chiller / Outside Air Pipes Cooling Tower Up to 850w TDP Up to 250w TDP 13 一 1.6(Chiller) < t07 (Un-chiller < 1.1 13 一 1.6 (Chiller) < 1.12 (Un-chiller Air) X <1.12 X ntel/AMD/Nvidia POR As air 〔 00 而 g Reuse standard Facility water servers & racks •GWP: Global Warming Potential RoboticArm/ Hot 0 Ⅱ Burning Points Risk Immersion Two Phase L2L Cost: $ 150 Volume: 500L Pipes Cooling Tower >800WTDP < 1.09 X Robotic Arm / Fluorocarbon Recycling Condenser / High GWP New design from systems to DC infrastructure RESHAPING THE FUTURE 1 , Pow “ ndDi Tran 「 m · 0 " QCT Li uid Cooin Solution LeadDa en r 0 an brma On withEnergyefficiency& TCO/CFP Reduction System Design fo 「 Power Reduction Reduce 50 % Fan Duty Save 70 % System Thermal Power Delivery Thermal Capability Leadership Increase 2-3 times system density with 60kW cooling capability OptimizedGreen Datacenter Operating under high ambient with un-chiller air to reach PUE 07 , and further reduce OPEX. 3 ](Exported%20image%2020241106113452-1.jpeg)](https://s4.itho.me/sites/default/files/images/QCT%20LC-1.jpg)

首先從冷卻成本來比較，根據雲達的觀察與分析，Cold Plate、D2C搭配的是一般冷卻液，價格便宜（1公升3.5美元），而且由於只放在熱鰭管裡面，不需太多，30公升就夠了；浸沒式冷卻，無論是單相或雙相，冷卻液的成本都相對很高，每公升要價150美元，而且，這些冷卻液要放在容納伺服器的槽體裡，所以需要置入大量液體，以42U的槽體而言，需要近500公升，此外，有些雙相浸沒式液冷的液體會蒸散，需要再花錢補充。  
關於效能的部分，雲達認為Cole Plate液態冷卻的效果會越來越好，因為已有多家廠商投入、鑽研；雙相浸沒式液態冷卻是目前公認效果最好的，不過，浸沒式液冷的單相與雙相尚未達到最理想的狀態，這是因為，現行的資料中心基礎設施是基於氣冷架構所設計出來的，並未對浸沒式液冷進行優化，未來這類技術應有更好的表現。  
在PUE的表現上，雙相浸沒式液冷做得很好，單相浸沒式液冷略遜一籌，至於Cold Plate液冷應用，雲達表示，假如是搭配來自冰水機（Chiller）的空氣時，PUE可做到1.3和1.6；若搭配一般空氣（Un-chiller Air），PUE則降至1.07。  
接下來是保固，對於浸沒式液冷的使用，晶片廠商大多並未提供使用擔保的標準，這意味著，如果要用浸沒式液冷，晶片可能就沒有保固，除此之外，IC晶片、PCB板、網路介面卡、電源供應器等其他周邊元件，甚至是光纖網路收發器、光纖纜線，能否浸在冷卻液維持正常運作狀態，也有待釐清。因此，雲達認為，如果明天就要導入液態冷卻設備，採用Cold Plate設計的解決方案就沒有上述的問題。  
關於導入液冷對資料中心基礎架構層面的影響，若採用浸沒式液冷，會帶來較大的改變。例如，我們須處理可服務程度（Serviceability）的議題，若要對伺服器的硬體元件進行維護時，必須把這些運算設備從冷卻槽拉出、進行吊掛，之後等待瀝乾，需要10到15分鐘，甚至20分鐘之久，而且往往需透過機器手臂的幫忙，以便將伺服器從冷卻液槽體中搬出。  
冷卻液的材質也需要注意，例如，單相浸沒式液冷設備所用的冷卻液，具有燃點低的特性，目前尚無相關規範能確保、去除這種潛在的風險；而在雙相浸沒式液冷的應用上，目前面臨的挑戰是碳氟化合物（Fluorocarbon）的處理，由於牽涉到相位轉換、可能會釋出有毒氣體，而且，氟化物是很難被分解的，進到大氣之後，可能要1千年才會被中和，比起碳的處理更為棘手，因此，目前大家仍聚焦在單相浸沒式液冷的應用上。  
對比之下，雲達認為，若採用Cold Plate液冷，基本上，不會帶來任何基礎架構方面的衝擊，維護資料中心的IT人員不需改變原本的做法。  
在資本支出的考量上，如上所述，若導入浸沒式液冷，整個資料中心環境可能需要進行較大規模的調整或更新。導入Cold Plate、D2C液冷，雖然在機櫃上需要多花一些費用，但機房的基礎架構層面不需變動；所以。相較之下，明天如果要用的話，後者是個比較好的選擇。  
從務實、確保既有投資的角度而言，企業與組織導入液態冷卻的另一層考量，在於如何與現行設備與環境並存、共容，因為資料中心基礎架構存在的伺服器都是仰賴氣冷，無法因為導入液冷而在短時間內進行全面更換，機房原有的伺服器仍要繼續使用，所以，雲達提供資料中心不需大幅修改就能繼續使用的液冷設計。  
除此之外，為了因應部署於現行機房環境的需求，雲達的Cold Plate液態冷卻解決方案提供兩款機型：一款是液態對氣態（Liquid-to-Air，L2A）機櫃，也是該公司目前主要公開展示的設備，另一種是液態對液態（Liquid-to-Liquid，L2L）機櫃，可適用於本身已有冷熱水管配置的資料中心。

### **搭配自行設計的CDU、冷熱歧管，以及設置熱交換器的背門**

關於QoolRack機櫃內部配置，在上述國內外的大型活動當中，駱威先也透過演講方式一一介紹。  
以L2A RDHx Rack這款混合液態與氣態冷卻的機櫃而言，在42U機架空間中，最上方設置1臺1U高度的置頂（TOR）管理交換器，，連接機櫃的每一臺伺服器節點，能將這些運算設備的負載資訊傳送到CDU，再用CDU內部的DC-SCM去分析每臺伺服器節點的運作狀態，從而自動調整CDU搭載的泵浦轉速，以及機櫃背門風扇的轉速。

![uopnIOS (IZV S!LP u! ](Exported%20image%2020241106113454-2.jpeg)

最底部是1臺4U高度的CDU，，裡面有兩個可彼此備援且支援熱插拔的泵浦，以及支援熱插拔的過濾器。而CDU上方的設備是1臺1U高度的Power Sled，支援機櫃背門的全部風扇運作。

![Exported image](Exported%20image%2020241106113455-3.jpeg)

而位居這些設備之間的30U機架空間可擺設大量伺服器，目前可安裝15臺2U高度的QuantaGrid D54Q-2U（此款機型搭配2顆英特爾即將發表的第四代Xeon Scalable系列處理器）。  
依照這樣的設計，若將機櫃換成48U或52U高度的規格，理論上，可置入更多臺伺服器，駱威先表示，這款機櫃現在的電力配置，足以支撐30U、36U、38U的伺服器，但Power Jump可能會面臨限制。

![QUANTAGROD D54Q=2U SERVERS ](Exported%20image%2020241106113457-4.jpeg)

而在機櫃背門，雲達設置了16臺寬96公分、採用DC48V電力配置的風扇，提供強大的風力與能源使用效益；若打開背門，可看到底部的CDU、連接的冷熱岐管（Manifold），以及設置在背門上的冷卻器（Radiator）與熱交換器（Rear Door Heat Exchanger，RDHx）。

[![~ NVMIVI K.6xeuKsO •H -108 -1 ~ n033 ~ MP 一 03 01 ~ MIOH 0 PPO 0000000 i i00000000 , P 5 , Odnt (st) 100 ](Exported%20image%2020241106113501-5.jpeg)](https://s4.itho.me/sites/default/files/images/QoolRack%20TW-1%20%E5%9C%96%E7%89%87%E4%BE%86%E6%BA%90%EF%BC%8F%E9%9B%B2%E9%81%94%E7%A7%91%E6%8A%80.jpg)

雲達在QoolRack的L2A機型當中，結合了液冷與氣冷技術，前者的關鍵在於機櫃底部的CDU與設置於機櫃側邊的冷熱岐管，後者則是背門設置的兩大片散熱器與16臺強力風扇。  
這款機櫃會如何進行冷卻？冷卻液由CDU的泵浦送出，沿著冷歧管傳到所有系統裡面，使冷卻液流入覆蓋在伺服器處理器的水冷板，當這些液體吸收到處理器的熱之後，溫度會提高，而從熱歧管流出，再送到機櫃的最上方，轉至機櫃背門的冷卻器往下流，過程當中，機櫃背門最外側的風扇會將散熱器所傳導出來的熱排出，使液體溫度逐漸降低，之後再從冷水管回到CDU的泵浦裡面，後續重新進行另一次循環，等於在機櫃裡面就完成冷熱交換的過程。  
若單從伺服器的位置來細部檢視系統散熱方式，我們可看到機櫃背部左側設有冷熱歧管，而在2U伺服器配置的兩顆處理器，包覆了後面接著冷水管、熱水管的水冷板，由CDU泵浦送上來的冷卻液會從冷水管進入伺服器處理器上面的水冷板，之後從另一條熱水管流出，將處理器散發的熱帶走，後續再往機箱背門的方向流動。

![Exported image](Exported%20image%2020241106113503-6.jpeg) ![View in Rack with QuantaGrid D54Q-2U Leading Silicon in testing: Next generation 丨 ntel Xeon Scala ble processors - codenamed Sapphire Rapids QC QuantaGrid 054q U RESHAPING THE FUTURE ThePowerBehindDigitaITransformation System levelliquid tube ](Exported%20image%2020241106113504-7.jpeg)

至於另一款液態對液態版本的機櫃，基本上，是將冷卻器與風扇背門換成一般的背門，再加上板式熱交換器（Plate Heat Exchanger），讓內部循環的液體能夠和外部循環的水進行交換。

[![TAIWAN ~ 022 Q9ynergy Ready for Liquid-to-Liquid HotWatertoRadiat" issame * h A L2L L2A Re 08 He Flow ro | 0 Plate Heat CDUtOColdManifold DU DCW in / 0 *L2LReqL.nred facilitywaterto maintain PH6-8. Intel G C T ](Exported%20image%2020241106113506-8.jpeg)](https://s4.itho.me/sites/default/files/images/QoolRack%20TW-2%20%E5%9C%96%E7%89%87%E4%BE%86%E6%BA%90%EF%BC%8F%E9%9B%B2%E9%81%94%E7%A7%91%E6%8A%80.jpg)

QoolRack目前提供兩種冷卻組態選擇，其中的液態對氣態（L2A）是目前最常公開展示的機型，以及另一種液態對液態（L2L）是基於L2A機型而來，加裝流量控制閥、板式熱交換器，以及直流的冷熱水進出口。  
這些機櫃的散熱處理流程，不過，D2C在高效能運算（HPC）領域行之有年，為何雲達會認為自己發展的系統比其他廠商更具優勢？駱威先表示，雲達與其他廠商設計的最大差異在於CDU，主要有兩個考量，首先是可服務性（Serviceability），他們會確保這是完美被實現的特色。  
舉例來說，泵浦是CDU的重要元件，日常使用時會需要更換，為了做到熱插拔，最簡單的方法是在泵浦後面放置一個快速接頭（quick connector），然而，這會造成冷卻液傳輸的阻抗，降低泵浦運作效率，進而導致不足以支持整個機櫃的散熱需求，對此，雲達內部進行設計，在此提供了泵浦備援的機制，使其兼顧不漏水、快接，以及不降低泵蒲的效能等要求。

![PUMP ](Exported%20image%2020241106113507-9.jpeg)

駱威先表示，在今年他們參與的Intel Innovation、OCP全球高峰會、SC超級電腦大會等活動，雲達都是會場唯一能做到泵蒲備援的Live Demo廠商。

[![TAIWAN 2022 Qsynergy Front and Rear View— CDU Rear View Front View CD Module sensor HighTank SMBus F Pump#O Pump # LowTank Temperature 0 let Module Liquid Sensor Intel 13 ](Exported%20image%2020241106113511-10.jpeg)](https://s4.itho.me/sites/default/files/images/QoolRack%20TW-3%20%E5%9C%96%E7%89%87%E4%BE%86%E6%BA%90%EF%BC%8F%E9%9B%B2%E9%81%94%E7%A7%91%E6%8A%80.jpg)

圖中為雲達QoolRack的CDU外觀配置，機箱正面設有提供備援能力的泵浦、可顯示機櫃與伺服器節點狀態的LCD螢幕，以及過濾模組，而機箱背面有冷卻液的進出口、電源供應器，以及DC-SCM遠端管理模組等元件。

### **配備DC-SCM，可即時掌控伺服器工作負載與動態調整冷卻機制**

另一個考量則是可管理性（manageability），而在伺服器與機櫃管理的應用上，則是遙測（telemetry）、遠端控管，相較於目前CDU大多採用傳統PLC的方式進行類比型態的管控，雲達的作法是將伺服器等級的BMC晶片放在遵循OCP DC-SCM規格的模組裡面，並將DC-SCM置於CDU，所以，很多管控功能都可藉由這個模組做到。  
同時，雲達在這個架構中也採用OpenBMC開放韌體，能以此與機櫃內部設置的全部伺服器進行溝通，可得知所有伺服器的負載與散熱狀態，從而調整泵樸流速與風扇轉速，避免過度冷卻、浪費能源的狀況發生。  
而在操作管理介面上，雲達也基於上述的技術堆疊而提供網頁使用介面，由於這套管理機制是與伺服器對連，因此能直接與其溝通，IT人員能即時掌握機櫃冷卻液的溫度、流量壓力、流速、是否出現外洩，以及背門風扇狀態，也能了解伺服器節點的處理器溫度、運作狀況、IP位址。

![DMTF ㄖ , , Redfish Sensor monitor Node Server Sensors : 15 18 t 80 0 0 Node Server ㄗ Settings 37 RPM' 、 LIA01 RPM' 129S RPM' d151 ~ 110 ](Exported%20image%2020241106113512-11.jpeg) [![DC-SCM Remote Management Interface RESHAPING THE FUTURE nePowerBehind Digital 'Ii•a " 0 「 m · d01 Redfish API Provide standardAPItoprogram simple configuration andmaintenance t05k5 Manage user accounts and privileges Get thermal / power/ sensor data Get Rear door fan status Node Serverl P Configuration Get Health Event Logs SCM Firmware Update /redfish/v1/AccountService/Accounts(GET/POST/PATCH/DELETE) CDU user account management. /redfish/v1/Chassis/1/Power(GET) Powersled PSU status and information / re 覀 , Ⅳ VI / C , / 1 / nso 「 GET ) All monitoring sensorinformation nodes, liquid pressure, leakage temperatures … )· / 「 e 覀 / VI / C , / 1 ma GET ) Rear 面 0 「 f speed (RPM) and status / re 覀 / VI / M a 「 CDU / 051 / N pset g ( POST ) Upload the setting file (CSV) ofmanagement BMC IP and | 0 n name/password /redfish/v1/Managers/CDU/LogServices (GET/POST) CDU e | 0 /redfish/v1/UpdateService (POST) Update CDU firmware. 20 ](Exported%20image%2020241106113517-12.jpeg)](https://s4.itho.me/sites/default/files/images/QCT%20LC-5.jpg)

對於本身已有系統管理工具的企業與組織而言，上述管理機制也提供Redfish API，能讓這些工具從中擷取需要的狀態資料與執行管控作業。

 [![CDU Smart Management Dynamical Coolant Adjust: · Baseon 0g9 「 egatedp 「 0ce550 ' WO 「 k ad · D am 0 yadju eCOO 0 / Independent 2 ~ 4 Fan Zones Control · Baseon nodes'workload Dynamicallybalancecoolanttemperature Decreasepowerconsumptionforidlenodes Coolant Pump RESHAPING THE FUTURE ThePowerBehind Digital T n · 「 m io " Smart Commute: A 0- de c se Ⅳ e B Cd 0 · Monitornodes'overheat& ㄥ ea 09e errors ](Exported%20image%2020241106113518-13.jpeg)](https://s4.itho.me/sites/default/files/images/QCT%20LC-4.jpg)[![In-Rack Communication for Smart Control TOR managementSwitch Smart Link Sco r servernodes QCT Remote Control Redfish API WeblJ/ Read Sensor do CDU TAIWAN 2022 Qsynergy Smart Fan Control for L2A (Control Valve for L2L) Readcoo / Sy em temperature Contro / 戺 0rd00 「 c00 9 n power Balance sudden preheat condition byspecificfanzone 15 ](Exported%20image%2020241106113520-14.jpeg)](https://s4.itho.me/sites/default/files/images/QoolRack%20TW-4%20%E5%9C%96%E7%89%87%E4%BE%86%E6%BA%90%EF%BC%8F%E9%9B%B2%E9%81%94%E7%A7%91%E6%8A%80.jpg)

可管理性是QoolRack的一大特色，雲達在此提供智慧型連接與遠端管控能力，範圍可橫跨機櫃的管理交換器、CDU、背門的風扇，以及櫃內安裝的伺服器節點。  
除此之外，CDU本身也設置了一小排LCD螢幕，當機房人員親自走到機櫃進行維護服務時，可透過這個螢幕查看問題發生的位置。

![Event ](Exported%20image%2020241106113523-15.jpeg) [![DC-SCM Remote Management Interface RESHAPING THE FUTURE 1 , wer ndDi | Tra " 0 「 m io " LCD Display with Hotkey Quick MonitoringforPump/LiquidCondition Eventlogerrorcounts Button 1 CDU Inlet/Outlet Flow pressure InLeLP Button 1 Button 2 比 - P Rear d00 「 FAN RPM (Highest) R F 3470RPM CDU Coolant Flow Rate F10 , 丨 40.1 LPM Button 2 Button 3 Main / 2nd Pump RPM Pump—2 24RP Button 3 Pump-1 24 Button 4 RDHX Inlet Coolant Temperature (Hot side) RDHx 27.6 ' 0 Button 4 COLI 2 CDU InletCoolantTemperature(Cold side) 1 2 3 4 5 Button 5 Button 5 LCD Button Ambient Temperature RO X 一 L 1 Low Level sensor (H igh/Midd/LOW) 21 QC ](Exported%20image%2020241106113524-16.jpeg)](https://s4.itho.me/sites/default/files/images/QCT%20LC-3.jpg)

### **可大幅節省冷卻與基礎設施空調耗電，是此款機櫃最大賣點**

關於導入QoolRack的成效，雲達也在這些活動公布他們實測結果。  
以伺服器處理器溫度變化而言，在氣冷環境是攝氏68度，已具有很好的熱量餘裕（thermal margin），而在雲達水冷板液冷機櫃則是56.2度，等於將CPU溫度再往下降了11.8度，可獲得額外的熱量上限，能有足夠熱量空間、更低的接面溫度（Junction Temperature）去因應未來新推出的CPU。  
若以單座機櫃的冷卻耗電來比較，氣冷機櫃內設置15臺伺服器，所有系統風扇的總耗電量是2,790瓦，而雲達採用水冷板液冷機櫃，結合系統風扇、CDU裡面的泵蒲，以及背門上所有風扇的總耗電量為927.8瓦，省電比例高達66.8%。

[![Advanced Cooling Capability with RESHAPING THE FUTURE 1 , w " dDi | T 「 , " 0 「 , tio " Superior Power Efficiency Real stress test result to showcase lower power consumption with liquid cooling solution. CPU Temperature (C) Cooling Power per Rack (W) 8 7 7 6 0 5 0 5 3000 2500 66.8 % Power Saving 2000 11.8CTemp Gap 90w 1500 68c 60 1000 55 , 56.2 927.8 50 58 AirCooling Liquid Cooling Liquid Cooling* ' Air Cooling Liquid Cooling •AirCooling 丨 Liquid Cooling** •AirCooling Ambient Temperature ( 0 ••lncluding m fans. 〔 DU pumps, RDHx power. 35c ](Exported%20image%2020241106113525-17.jpeg)](https://s4.itho.me/sites/default/files/images/QCT%20LC-6.jpg)

除了機櫃本身的冷卻耗電差異，另一個關鍵則是基礎設施耗電。  
由於L2A RDHx Rack在實際設置時，可支援不啟動冰水機的狀態，因此，雲達也為此比較兩種組態的PUE數值。駱威先表示，一般標準系統的入口溫度可能是25、30度，好一點是35度，由於這款機櫃能有效帶走CPU的熱，所以，可容許整個系統的入口溫度上升到40度，有些狀況可到45度，基於這個前提，冷暖空調系統是無需啟動的，而能省下許多耗電。  
因此，單就基礎設施的耗電而言，QoolRack在啟動冰水機的環境當中，PUE是0.37，而在不需啟動冰水機的環境，PUE可降至0.07，省電幅度之大，更勝於機櫃冷卻耗電，而這是真正幫助大家節省最多能耗的部分，也是讓整個系統PUE降到1.07的關鍵之一。

[![L2A PUE Optimization The 0 戺 poweryou 0 om HVAC, the more op m 0 on you / e on PUE & CFP. Ambient:40C Chilled Air No Chilled Alr PUE.' 1.37 PUE: 1.07 | i power: Rack 十 ( 27 C ( 92 》 Server powe 210w 》 0 · 87 f stru u power 0 · ( ch / non e 0 , 37 HVAC + f 「 as u u 「 0 Air COO Liquid Cooling ](Exported%20image%2020241106113527-18.jpeg)](https://s4.itho.me/sites/default/files/images/QoolRack%20TW-A%20%E5%9C%96%E7%89%87%E4%BE%86%E6%BA%90%EF%BC%8F%E9%9B%B2%E9%81%94%E7%A7%91%E6%8A%80.jpg)

在省電成效呈現上，雲達QoolRack可支援不啟動冰水機的環境組態，由於能大幅節省基礎設施電力（橘色），PUE可降至1.07。