# Librepremium
LibrePremium是一个代理端验证插件。它被设计为JPremium插件的免费替代版本，当然也有自己的特色功能。以下是LibrePremium支持的特色功能。
本页完全是从SpigotMC论坛页面翻译过来的，你可以在上面的原文链接中访问SpigotMC页面查看英文版本。 
本页从Markdown转到BBCode的，所以可能有部分内容很奇怪，请在GitHub或者Gitee中查看本文。  
    
**!!LibrePremium需要Java17或者更高Java版本才能正常运行!!**  
  
插件的特色功能，使用指南，和其它一些内容都在Wiki中（Wiki正在翻译中）。  
想为LibrePremium添加新功能？还是插件运行不如常（报错）？不要犹豫，立即在[GitHub Issue](https://github.com/kyngs/LibrePremium/issues)反馈！  
  
 - 正版玩家自动登录
 正版玩家可以选择是否需要自动登录。
 你也可以在配置文件中为正版玩家启用默认自动登录功能！  
 - TOTP 2FA  
 LibrePremium是目前（市面上）唯一一个提供TOTP 2FA（Authy、Google Authenticator等软件）功能的代理端验证插件。想要使玩家的账户更加安全吗？启用2FA功能是个不错的选择。  
在Wiki中查看如何启用TOTP 2FA（翻译中）。  
- 名称验证  
- 会话  
如果玩家不小心退出登录后，使用相同的IP访问服务器则不必重新登录，将自动恢复上一次的会话。你可以在配置文件中自定义每次会话的持续的持续时间。  
- 数据迁移  
LibrePremium会自动检测正版玩家（自动登录）是否修改了它们的用户名，并且自动迁移这些数据。你也可以通过手动输入命令完成数据迁移。  
- 负载均衡  
当玩家登录后，它们会被送到Limbo服务器进行身份验证。验证通过后，他们将自动选择并传送到玩家最少的服务器。（你可以通过API对此进行修改。）  
所有服务器将周期进行Ping来确保它们的在线状态。  
- API  
LibrePremium提供了大量的API。这就意味着你可以毫不费力地让LibrePremium兼容你的服务器。  
在Wiki中查看这些API！  
- 记录  
LibrePremium的每一个操作都会被记录。  
在Wiki中查看全部内容！  
- 从其它插件迁移到LibrePremium  
LibrePremium支持从其它许多验证插件迁移数据！  
如果你想要了解如何从其它插件迁移数据到LibrePremium，请查看Wiki。  
如果你有任何其它未支持的插件想要迁移到LibrePremium，请查看Wiki。  
- 开源  
LibrePremium插件永久开源，因此你无需担心LibrePremium的代码安全。  
  
本页面正在更新中，也在进行Wiki翻译工作。  
