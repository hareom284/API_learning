# Fetch API in JavaScript

-  Fetch ကို သုံး မယ် ဆို ရင် ပ ထမ ဦ ဆုံး ကို ခေါ် ချင် တယ် URL ကို variable တစ် ခု ထည့် မှာ သိမ်း ထား လိုက် ပါ
` var url = 'url_link'; `
-    data တွေ့ ကို ခေါ် ချင် URL ကို သုံး ပြီး fetch () သုံး ပြီး လုပ် ပါ

``` var promise = fetch(url);
```

- အ ခု ရ လာ သော data က promise အ နေ ရ လာ မှာ ပါ အဲ့ ရ လာ တယ် data ကို  promise ကို သုံး ပြီး JSON type ‌ပြောင်း ဖို့ လို ပါ တယ်


```
     then(function (response){
     var data = response.json();
     return data;

```


- လို ခေါ် လိုက် ရင် API က JSON type ‌နဲ့ ရ လာ ပါ ပြီး Promise အ နေ  နဲ့ ရ လာ မှာ ပါ အဲ့ မှာ PromiseState and PromiseResult ဆို ပြီး parameters နှစ် ခု နဲ့ ရ လာ မှာ ပါ ကိုယ် ရဲ့ data က PromiseResult မှာ ရှိ တာ ပါ

- JSON type ရ လာ သော data ကို ကို က views အ နေ နဲ့ ပြ ချင် ရင် 

```
   .then(function (data){
   const img = document.createElement("img");
   ခေါ် ပြီး သုံး လို ရ ပါ။   တယ်
```


# I hope you will understand it !

