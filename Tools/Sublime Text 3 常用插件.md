
#### Sublime Text 3 常用插件

(以下网址可能需要科学上网)

##### 常用插件
1. Package Control
地址：https://packagecontrol.io/
安装方法1：*ctrl+shift+p* 输入 *Install Package Control*
安装方法2：*ctrl+\`* 输入
```
import urllib.request,os,hashlib; h = 'df21e130d211cfc94d9b0905775a7c0f' + '1e3d39e33b79698005270310898eea76'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

2. SFTP
地址：https://packagecontrol.io/packages/SFTP
安装方法：*ctrl+shift+p* 输入 *Package Control：Install Package* 选择 *SFTP*

3. Markdown Preview
地址：https://packagecontrol.io/packages/Markdown%20Preview
安装方法：*ctrl+shift+p* 输入 *Package Control：Install Package* 选择 *Markdown Preview*

4. Emmet
地址：https://packagecontrol.io/packages/Emmet
安装方法：*ctrl+shift+p* 输入 *Package Control：Install Package* 选择 *Emmet*

5. Sublime​Linter
地址：https://packagecontrol.io/packages/SublimeLinter
安装方法：*ctrl+shift+p* 输入 *Package Control：Install Package* 选择 *Sublime​Linter*

6. Sublime​Linter-php
地址：https://packagecontrol.io/packages/SublimeLinter-php
安装方法：*ctrl+shift+p* 输入 *Package Control：Install Package* 选择 *Sublime​Linter-php*

7. Sublime​Linter-csslint
地址：https://packagecontrol.io/packages/SublimeLinter-csslint
安装方法：*ctrl+shift+p* 输入 *Package Control：Install Package* 选择 *Sublime​Linter-csslint*

8. Sublime​Linter-jshint
地址：https://packagecontrol.io/packages/SublimeLinter-jshint
安装方法：*ctrl+shift+p* 输入 *Package Control：Install Package* 选择 *Sublime​Linter-jshint*

9. Git
地址：https://packagecontrol.io/packages/Git
安装方法：*ctrl+shift+p* 输入 *Package Control：Install Package* 选择 *Git*
