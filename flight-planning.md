# Flight Planning



## 选择Checkpoint

Sectional Chart

* 用Plotter进行划线来找到

纸上的地图进行

* Waypoint / Checkpoint 10nm - 15nm 

  * 优先选择
    * Airport

    * Interstate Highway (Multi-Way)

    * Stadium

    * VOR

  * 郊区
    * Lake
    * Mountain
    * River

  * 城市

    * Building

    * Landmark

    * Rail Road / Highway

    * Stadium / Football / F1 / Airport Runway number 




## 查各种飞机相关数据

* Cruise & Range Performance Chart![](.\charts\Cruise-Range-Performance-Chart.jpg)*
  * Altitude + RPM -> TAS + Fuel Consumption
* Maximum Rate-Of-Climb Data -> 计算到达TOC的需要的时间
  * Weight + Altitude + Temperature -> IAS + Rate of Climb 
* Landing Data & Takeoff Data
  * Weight + IAS + Headwind + Altitude + Temperature -> Rolling Distance -> 判断Runway 是否够长 注意夏天和冬天的Performance 可能会有很大区别
* Compass Deviation Card
  * 每一个飞机都会有差异，是根据飞机内部



## 查天气数据

* [Aviation Weather Center](https://www.aviationweather.gov/)
  * Wind direction
    * 如果是大机场(有TAF Data) 可以直接看TAF 注意判断是否在覆盖范围之内，大部分都是在5 miles范围之内
    * 如果没有TAF Data的话，需要用 TOOLS -> GFA Tool ->  Winds
  * Cloud Ceiling
    * 直接看地图 是否Clear 可能大部分区域都是直接Clear Visibility > 10 nm
    *  TOOLS -> GFA Tool ->  Clouds



Complete A Nav Log

1. Determine the route and checkpoints
2. Measure true course and distance with plotter
3. Select an altitude and determine winds aloft
4. Look up true airspeed in POH
5. Calculate *wind correction angle* and groundspeed using E6B Calculator 
6. Magnetic variation, magnetic deviation, and compass heading
7. Calculate ETE(Estimated Time Enroute) using E6B
8. Calculate Fuel Usage using E6B
9. Total the Distance, Minutes, and Fuel



自己决定的变量

* POwer

* Altitude

* True Course (用Plotter给不同的Checkpoint 连线确定)

  

需要查表 / 第三方数据(天气 机场 NOTAM)得到的变量

* Weather Information

* Airport Information

  * Frequency: ATIS + Ground + Tower
  * Runway Heading + Length
  * Field Elevation

* TAS - True Airspeed: Cruise & Range Performance Chart

* Fuel Consumption: Cruise & Range Performance Chart

* Magnetic Variation: 在Sectional Chart上根据飞机所在位置找 -E / +W

* Magnetic Deviation: 每个飞机都不一样卡片

  

需要计算的变量

* TH - True Heading: E6B Calculator Wind Direction + Wind Speed + True Course + True Airspeed ->  TH
* CH - Compass Heading: TH True Heading +/- Dev -> CH
* GS - Ground Speed : E6B Calculator Wind Direction + Wind Speed + True Course + True Airspeed -> GS
* ETE -Estimated Time Enroute: Leg Distance / GS -> ETE -> Depareture Time + ETE -> ETA 



Altitude

* 0-179 1 Odd + 500 Feet 
* 180-359 2 Even 
* Airplane Performance
  * Cruise speed / Power setting  2400 RMP 2300RPM -> Fuel Consumption
  * Wind Direction 不同Altitude 会有 tailwind higher airspeed,  



Airspeed

* TAS: True Airspeed
* IAS: Indicated Airspeed
* CAS: Calibrated Airspeed
* Ground Speed



Heading 

* True Course
* True Heading
* Magnetic Heading 



## 其他要注意的

