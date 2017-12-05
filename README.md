# Custom Toast

![API](https://img.shields.io/badge/API-14%2B-blue.svg?style=flat)
- add library gradle : 

```Gradle
    compile 'com.zarinpal:toast:0.0.3'
        
```
`Usage` : 

```Java
     // show custom toast 
      new CustomToast(getApplicationContext())
                .setMessage("create Toast")
                .setIcon(R.mipmap.ic_launcher_round)
                .setColor(Color.GRAY, Color.WHITE)
                .setDurationToast(Toast.LENGTH_SHORT)
                .show();
```