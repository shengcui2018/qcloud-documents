### 移动直播基础版 License 和移动直播企业版 License 有什么区别？
移动直播基础版 License 即可解锁直播推流和播放功能，也包含基础的美颜功能（美白、磨皮等）。
移动直播企业版 License 是在其之上，增加了高级美颜（大眼、瘦脸）、绿幕功能、动效贴纸、AI抠图等能力，还可以配合美妆和手势素材实现额外的功能。

SDK 下载中的3个版本的 SDK 均可用移动直播基础版 License 来解锁直播推流和播放功能，但是企业版中的高级美颜相关功能只能通过移动直播企业版 License 来解锁。


### 移动直播 License 是必须购买的吗？
需要使用移动直播 SDK 的直播推流功能，就需要购买移动直播 License 进行解锁，短视频 License 无法解锁移动直播相关功能。


### 一个账号下能创建多个 License 吗？
同一个账号下创建 License 的数量没有限制，不过为了方便您的管理，相同包名的 License 建议直接续期来延长有效时间。


### 相同包名可以创建多个 License 吗？
可以，多个 License 填写相同的包名不会影响使用，不过同时创建多个 License 有效期会各自计算，一般不建议创建多个相同包名的 License 。

### License 可以修改吗？
移动直播 License 可通过续期来延长有效时间，包名信息不支持修改，请您在添加 License 先核对包名在应用商店里是否被占用，提交后不支持修改和替换。

### 为什么我创建了多个 License ，但是 licenseurl 和 key 都是一样的？
同一个账号下移动直播的 licenseurl 和 key 默认是相同的。这样保证了测试 License 、正式 License、不同包名的 License 均可以复用相同的接口信息。

我们不建议客户使用免费测试的 License 发布到线上运行，但客户可以通过添加新的正式版 License，即无需再修改接口中的 licenseurl 和 key ，就切换到正式版 License。


### 关联 License 的资源包是不是只能这个 License 使用？
该账号下的标准直播播放域名产生的日结流量后付费消耗均可抵扣。资源包关联只是用于同步有效期，里面的流量不限于 License 使用。（流量用尽也不影响 License 的使用）
例：
用户甲是日结流量后付费计费，购买了一个10TB标准直播流量包和50TB标准直播流量包，分别创建了 License A 和 License B：
   - License A 对应的 App 使用的是`abc.com`域名播放，产生了20TB的播放流量
   - License B 对应的 App 使用的是`def.com`域名播放，产生了30TB的播放流量

只要`abc.com`和`def.com`这两个是标准直播的播放域名，且属于用户甲的云直播账号下，即可使用购买的10TB + 50TB来抵扣，抵扣后用户甲的标准直播流量包剩余10TB流量。  
