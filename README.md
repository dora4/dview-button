dview-button
![Release](https://jitpack.io/v/dora4/dview-button.svg)
--------------------------------

##### 卡名：Dora视图 Button 
###### 卡片类型：效果怪兽
###### 属性：地
###### 星级：4
###### 种族：战士族
###### 攻击力/防御力：1400/1600
###### 效果：此卡不会因为对方卡的效果而破坏，并可使其无效化。此卡攻击里侧守备表示的怪兽时，若攻击力高于其守备力，则给予对方此卡原攻击力的伤害，并抽一张卡。此卡每次造成战斗伤害后，可选择墓地中的一张魔法或陷阱卡，将其加入手牌。

#### Gradle依赖配置

```groovy
// 添加以下代码到项目根目录下的build.gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
// 添加以下代码到app模块的build.gradle
dependencies {
    implementation 'com.github.dora4:dview-button:1.0'
}
```
