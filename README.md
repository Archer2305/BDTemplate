# BDTemplate
All code goes inside the Load function, there are some cases where you dont need to do so but are rare. 
The load function is called once when the function starts, to make a plugin always active use a set interval function.
creating react elements is easy just use 
```javascript
BdApi.React.createElement("input", {
     style: {
           color: "white",   
           background:"#36393f"
            },
            className:"InpArg",
            
          //  value: "what ever you want here"

          })
```
          
just make sure to follow regular JSX 
*Create alerts by using   ` BdApi.alert("TEXT")` you can alert custom JSX elements.
*Create toasts (small notifications) by using  `BdApi.showToast("text")`
