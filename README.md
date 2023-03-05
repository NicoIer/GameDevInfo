# LearningUnity

`个人Unity学习记录,记录自2022年秋开始的游戏开发学习过程,为将来面试工作,等等做记录`

## 2DSkipGame

`2D平台跳跃`

- 手感优秀的平台跳跃优秀
- 粒子系统,基本音效

| ![Skip1](./Images/Skip.png)  |
| ---------------------------- |
| ![Skip2](./Images/Skip2.png) |


## PokemonUI

`宝可梦UI+Json数据存储`

主要是对UGUI的搭建

| ![pokemon1](./Images/pokemon1.png) |
| ---------------------------------- |
| ![pokemon2](./Images/pokemon2.png) |
| ![pokemon3](./Images/pokemon3.png) |



## SimpleBag

`简单的背包系统`

简单的道具拾取功能+UGUI的栅格系统+Json数据存储

| ![bag1](./Images/bag1.png) |      |
| -------------------------- | ---- |
|                            |      |



## SimpleTalk

`简单的对话系统`

Json对话数据存储+UGUI对话

| ![talk1](./Images/talk1.png) |
| ---------------------------- |



## CricketMaster

`平台跳跃+2.5D回合制宝可梦战斗`

- 实现回合制战斗流程(主要是协程和异步)
- TileMap创建场景
- 使用`UITookit`拓展`Editor`进行快捷技能编辑

| ![CricketMaster-5](./Images/CricketMaster-5.png)        |
| ------------------------------------------------------- |
| ![CricketMaster-5](./Images/CricketMaster-4.png)        |
| ![CricketMaster-2](./Images/CricketMaster-3.png)        |
| ![CricketMaster-UITookit](./Images/CricketMaster-7.png) |

## 随机地图生成

`随机地图数据的生成`

- 地图数据组成形式`Land`->`Region`->`Terrain`->`LandMark`
- 主要是算法层面
  - 柏林噪声+细胞自动机生成网格
  - BFS获取陆地
  - DFS连接陆地
  - 聚类算法分割陆地为区域
  - 聚类算法划分区域地皮
  - 随机漫步选择地标

| ![RandomMap1](./Images/RandomMap1.png) |
| -------------------------------------- |
| ![RandomMap](./Images/RandomMap.png)   |

## Excel转SO工具

`通过读取Excel表格的信息自动生成C#代码,并且将数据读取到So中便于后续使用`

| ![ExcelToSo1](./Images/excelToSo1.png) | _![ExcelToSo2](./Images/excelToSo2.png) |
| ------------------------------------- | -------------------------------------- |
| ![ExcelToSo3](./Images/excelToSo3.png) |                                        |

## 多武器系统

`便捷的多武器系统`

类似死亡细胞的攻击系统,通过读表来实现武器数据和逻辑的分离,只切换武器ID即可完成不同武器的切换

> <font color=gray>通过监听SpirteRenderer的SpriteChange事件来实现单一动画控制器,多种不同武器动态切换</font>

![多武器](./Images/MulWepon1.png)

## 宝藏猎人

`开发中的2D横版闯关游戏`

鉴于对应美术资源的完备性以及展现个人能力的需求,应运而生的一个展示型游戏



>**期望是使用该套美术资源,完成一个完整的游戏demo**

![多武器](./Images/Hunter1.png)
