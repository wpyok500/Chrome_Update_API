# Chrome_Update_API


1、chrome 安装[Talend API Tester - Free Edition](https://chrome.google.com/webstore/detail/talend-api-tester-free-ed/aejoelaoggembcahagimdiliamlcdmfm)插件；

2、Talend API Tester - Free Edition插件中导入获取chrome安装包更新.json

3、选择你要更新的chrome版本并发送请求获取更新地址

3、获取到的更新地址格式为urls.url+packages.name，如：http://edgedl.me.gvt1.com/edgedl/release2/chrome/mymwdbo5qihdtrc2wv5f62iywy_98.0.4758.82/98.0.4758.82_chrome_installer.exe

```
<?xml version="1.0" encoding="UTF-8" ?>
<response protocol="3.0" server="prod">
    <daystart elapsed_days="5522" elapsed_seconds="69005"/>
    <app appid="{8A69D345-D564-463C-AFF1-A69D9E530F96}" cohort="1:gu/i19:" cohortname="Stable Installs &amp; Full Version Pins" status="ok">
        <updatecheck status="ok">
            <urls>
                <url codebase="http://edgedl.me.gvt1.com/edgedl/release2/chrome/mymwdbo5qihdtrc2wv5f62iywy_98.0.4758.82/"/>
                <url codebase="http://redirector.gvt1.com/edgedl/release2/chrome/mymwdbo5qihdtrc2wv5f62iywy_98.0.4758.82/"/>
                <url codebase="https://edgedl.me.gvt1.com/edgedl/release2/chrome/mymwdbo5qihdtrc2wv5f62iywy_98.0.4758.82/"/>
                <url codebase="https://redirector.gvt1.com/edgedl/release2/chrome/mymwdbo5qihdtrc2wv5f62iywy_98.0.4758.82/"/>
                <url codebase="http://dl.google.com/release2/chrome/mymwdbo5qihdtrc2wv5f62iywy_98.0.4758.82/"/>
                <url codebase="https://dl.google.com/release2/chrome/mymwdbo5qihdtrc2wv5f62iywy_98.0.4758.82/"/>
                <url codebase="http://www.google.com/dl/release2/chrome/mymwdbo5qihdtrc2wv5f62iywy_98.0.4758.82/"/>
                <url codebase="https://www.google.com/dl/release2/chrome/mymwdbo5qihdtrc2wv5f62iywy_98.0.4758.82/"/>
            </urls>
            <manifest version="98.0.4758.82">
                <actions>
                    <action arguments="--verbose-logging --do-not-launch-chrome --channel=stable" event="install" run="98.0.4758.82_chrome_installer.exe"/>
                    <action Version="98.0.4758.82" event="postinstall" onsuccess="exitsilentlyonlaunchcmd"/>
                </actions>
                <packages>
                    <package fp="1.6392c07e5c4c481f65d1bdf1a2d5e31a3b2762b6ad8905de33ce715317062fc7" hash="qErbbJiBr/xtKIUrzk/MFiwo1So=" hash_sha256="6392c07e5c4c481f65d1bdf1a2d5e31a3b2762b6ad8905de33ce715317062fc7" name="98.0.4758.82_chrome_installer.exe" required="true" size="82022504"/>
                </packages>
            </manifest>
        </updatecheck>
    </app>
</response>
```

## 在线版
Stable版本在线下载地址：
https://dl.google.com/tag/s/appguid={8A69D345-D564-463C-AFF1-A69D9E530F96}&iid={A63D0365-99BE-2CC1-A0CF-155D5582D720}&lang=zh-CN&browser=4&usagestats=1&appname=Google%20Chrome&needsadmin=prefers&ap=x64-stable-statsdef_1&installdataindex=empty/update2/installers/ChromeSetup.exe

Beta版本在线下载地址：
https://dl.google.com/tag/s/appguid={8237E44A-0054-442C-B6B6-EA0509993955}&iid={AECBACB7-EE1E-F027-867D-559237CAEFA8}&lang=zh-CN&browser=4&usagestats=1&appname=Google%20Chrome%20Beta&needsadmin=prefers&ap=-arch_x64-statsdef_1&installdataindex=empty/update2/installers/ChromeSetup.exe

Dev版本在线下载地址：
https://dl.google.com/tag/s/appguid={401C381F-E0DE-4B85-8BD8-3F3F14FBDA57}&iid={FF6B7218-7B91-016C-18D2-3976BD3F17FF}&lang=zh-CN&browser=4&usagestats=1&appname=Google%20Chrome%20Dev&needsadmin=prefers&ap=-arch_x64-statsdef_1&installdataindex=empty/update2/installers/ChromeSetup.exe

Canary版本在线下载地址：
https://dl.google.com/tag/s/appguid={4EA16AC7-FD5A-47C3-875B-DBF4A2008C20}&iid={2E1C9C74-B7B7-A102-6D5B-C694B0FD0375}&lang=zh-CN&browser=4&usagestats=1&appname=Google%20Chrome%20Canary&needsadmin=false&ap=x64-canary-statsdef_1&installdataindex=empty/update2/installers/ChromeSetup.exe

## 离线版
Stable版本离线下载地址： https://www.google.cn/intl/zh-CN/chrome/thank-you.html?standalone=1&statcb=1&installdataindex=empty&defaultbrowser=0&platform=win64

Beta版本离线下载地址： https://www.google.cn/intl/zh-CN/chrome/beta/thank-you.html?standalone=1&statcb=1&installdataindex=empty&defaultbrowser=0&platform=win64

Dev版本离线下载地址：https://www.google.cn/intl/zh-CN/chrome/dev/thank-you.html?installdataindex=empty&platform=win64&standalone=1&statcb=1&defaultbrowser=0

Canary版本离线下载地址：无离线版
