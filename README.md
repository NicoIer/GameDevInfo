# LearningUnity

`个人Unity学习记录,记录自2022年秋开始的游戏开发学习过程,为将来面试工作,等等做记录`

## 2DSkipGame

`2D平台跳跃`

- 手感优秀的平台跳跃优秀
- 粒子系统,基本音效

| ![Skip1](https://github.com/NicoIer/AboutUnityLearning/blob/main/Images/images/Skip.png)  |
| ---------------------------- |
| ![Skip2](https://github.com/NicoIer/AboutUnityLearning/blob/main/Images/images/Skip2.png) |


## PokemonUI

`宝可梦UI+Json数据存储`

主要是对UGUI的搭建

| ![pokemon1](.\images\pokemon1.png) |
| ---------------------------------- |
| ![pokemon2](.\images\pokemon2.png) |
| ![pokemon3](.\images\pokemon3.png) |



## SimpleBag

`简单的背包系统`

简单的道具拾取功能+UGUI的栅格系统+Json数据存储

| ![bag1](.\images\bag1.png) |      |
| -------------------------- | ---- |
|                            |      |



## SimpleTalk

`简单的对话系统`

Json对话数据存储+UGUI对话

| ![talk1](https://github.com/NicoIer/AboutUnityLearning/blob/main/Images/images/talk1.png) |
| ---------------------------- |



## CricketMaster

`平台跳跃+2.5D回合制宝可梦战斗`

- 实现回合制战斗流程(主要是协程和异步)
- TileMap创建场景
- 使用`UITookit`拓展`Editor`进行快捷技能编辑

| ![CricketMaster-5](https://github.com/NicoIer/AboutUnityLearning/blob/main/Images/images/CricketMaster-5.png)        |
| ------------------------------------------------------- |
| ![CricketMaster-5](https://github.com/NicoIer/AboutUnityLearning/blob/main/Images/images/CricketMaster-4.png)        |
| ![CricketMaster-2](https://github.com/NicoIer/AboutUnityLearning/blob/main/Images/images/CricketMaster-3.png)        |
| ![CricketMaster-UITookit](https://github.com/NicoIer/AboutUnityLearning/blob/main/Images/images/CricketMaster-7.png) |

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

| ![RandomMap1](https://github.com/NicoIer/AboutUnityLearning/blob/main/Images/images\RandomMap1.png) |
| ---------------------------------------------------------- |
| ![RandomMap](https://github.com/NicoIer/AboutUnityLearning/blob/main/Images/images\Images\RandomMap.png)   |

