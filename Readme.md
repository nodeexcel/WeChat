# Node.js ![git start](https://img.shields.io/github/stars/silencehvk/wechatbynode.svg?style=social&label=Star) ![git fork](https://img.shields.io/github/forks/silencehvk/wechatbynode.svg?style=social&label=Fork) [![](https://img.shields.io/github/issues/silencehvk/wechatbynode.svg?style=social&label=Issues)](https://github.com/silencehvk/wechatbynode/issues) [![](https://img.shields.io/github/release/silencehvk/wechatbynode.svg?style=social&label=Releases)](https://github.com/silencehvk/wechatbynode/releases)

![node version](https://img.shields.io/badge/node-7.5.0-brightgreen.svg)
![npm version](https://img.shields.io/badge/npm-4.1.2-brightgreen.svg)
![express version](https://img.shields.io/badge/express-4.15.3-blue.svg)
![xml2js](https://img.shields.io/badge/xml2js-0.4.17-orange.svg)

# Project structure

<pre>
.
├── README.md           
├── package.json
├── config.json
├── app.js
├── wechat
│   ├── access_token.json
│   ├── menus.json       
│   ├── msg.js          
│   └── wechat.js      
</pre>


 1. clone
    ```
    git clone git@github.com:SilenceHVK/wechatByNode.git
    ```

 2. config.json
 
    
    Modify the configuration parameters token, appID, and appSecret in the file. The token, appID, and appSecret parameters are located in the 'Basic Configuration' section of the left menu on the WeChat Official Account Platform.


 3. app.js
    ```
    cd wechatByNode && node app.js  // Server runs at localhost:3000
    ```

 4. Map the service address to the external network or deploy it to a server. Here, I demonstrate using intranet penetration.

    Open the software of Peanut Shell, click on Intranet Penetration

     
5. Access authentication


    Click "Submit". You will receive a prompt indicating successful submission, confirming that access authentication has been completed.

    (http://img.blog.csdn.net/20170527141056778?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHZrQ29kZXI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

6. Scan the WeChat QR code, follow the official account, and you can start playing.

    !(http://img.blog.csdn.net/20170608184008076?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHZrQ29kZXI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

    !(http://img.blog.csdn.net/20170606161743505?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHZrQ29kZXI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

    !(http://img.blog.csdn.net/20170608183907918?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHZrQ29kZXI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

    !(http://img.blog.csdn.net/20170608183936497?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHZrQ29kZXI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

    !(http://img.blog.csdn.net/20170608160434723?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaHZrQ29kZXI=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

