
## 更新说明

#### v2.0.2
    banner bug修复
 * 有朋友想要在引导页使用banner，所以增加了is_infinite_loop属性来控制是否能无限循环
 * 增加了设置开始轮播位置的方法
 * 修复圆角裁剪和首次设置开始位置不对的bug
 * demo中增加了类似淘宝详情banner的案例，第一个放视频，不能无限循环
 * 设置指示器方法调整，demo增加自定义数字指示器案例
 * 对ProxyLayoutManger进行的优化

#### v2.0.1
    banner bug修改
 * 解决一系列嵌套banner的事件冲突和解决方案
 （如果我没有考虑到的场景，大家再反馈或者提交方案）

#### v2.0.0
    banner 正式版发布
 * 改变banner圆角实现方式，兼容低版本
 * 新增两种指示器效果，基本能满足大部分需求了

#### v2.0.0-beta
    banner 测试版发布
 * 修改banner内部轮播逻辑
 * 增加设置画廊效果方法
 * 内置有2种官方Transformer效果，更多效果你可以自定义
 * 优化切换事件和点击事件,去掉onBannerChanged方法
 * 新增轮播滑动时间控制，感谢zguop，这里的具体实现方法来自zguop的项目
 * 支持多PageTransformer组合设置

#### v2.0.0-alpha03
    banner 预览版使用中的问题优化。
    这里要感谢BoldFruit朋友修复了一个bug；我爷爷得了癌症住院了需要照顾，公司事情也多，所以更新频率会慢很多。希望大家理解！
    不过我更希望大家要是发现bug，亦可以自己修复提交，有什么想法新增的功能也可以提交过来。可以提供一个良好的开源环境哈！
    还有不要一直夺命连环催，大家都有自己的事情，多多理解！
    
 * 增加支持布局文件中使用自定义指示器了（自己发挥）
 * 增加支持Android5.0以上的设置banner圆角方法
 * 其他问题修复（有些实在是不好复现加上有点忙，只修改了部分bug）

#### v2.0.0-alpha02
    banner 预览版使用中的问题优化
 * #666 修改orientation自定义属性与其他库冲突问题：改成banner_orientation
 * 增加RecyclerView嵌套banner和ConstraintLayout中使用banner测试demo
 * #669 RecyclerView嵌套banner 轮播优化代码建议，demo中可以查看
 * 其他问题修复

#### v2.0.0-alpha
    banner 2.0全新基础升级，目前是预览版，使用中的问题慢慢迭代
 *  使用了ViewPager2为基础控件  
 * 支持了androidx兼容包
 * 方便了UI、Indicator自定义（现在还是基础版本，后面再提升）
 * 依赖包目前只需要导入了ViewPager2
