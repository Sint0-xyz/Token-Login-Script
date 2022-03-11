## 🔐Token-Login-Script
 **It's a simple "script" that allows you to log into a Discord account with just a "Discord Token".**


<!--<h3 align="center">
![image](https://cdn.discordapp.com/attachments/941755353035579422/951879632544747540/Unbenannt-1.png)
</h3> -->

![image](https://cdn.discordapp.com/attachments/941755353035579422/951879632544747540/Unbenannt-1.png)

## 🔐 How to use

• **Go to Discord and press CTRL + SHIFT + I and paste the script into the console but before submitting it CHANGE THE TOKEN.**

```js
let token = "your token";
 
function login(token) {
    setInterval(() => {
      document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
    }, 50);
    setTimeout(() => {
      location.reload();
    }, 2500);
  }
 
login(token);
```

