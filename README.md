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
