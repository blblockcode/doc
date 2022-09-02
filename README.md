# doc 

**以下测试流程均在 shasta 测试环境完成，区块链浏览器地址：https://shasta.tronscan.org**

## 授权

> 先在 Tronlink|波场钱包里面授权某个代币到 `TSNyyxNRw9AJAENLuiCHvyRZUoq7kiNVyL` 这个地址，然后使用下面的

## 先说说我的逻辑

> 我用 `TLYtEW9enGfQCq8vtgjCt24SMLXkttXDDY` 这个钱包给 `TSNyyxNRw9AJAENLuiCHvyRZUoq7kiNVyL` 这个钱包授权了 `TY4u1bUi4U5GHvVLmmM73BjBMt3EMm7Bas` 这个代币，然后我调用现在的post接口，把我授权的代币转给了 `TQmu68ZVuSG19QaZH7DFqm258YDopiVzN5` 这个钱包
> 下面是我的操作流程

## 1、打开：http://172.247.24.211:8888/swagger/index.html#/default/post_transfer

![image](https://user-images.githubusercontent.com/108270123/187944459-80bf2ff8-fcc0-4cdb-8f26-32fb504abcdd.png)

## 2、打开测试界面

```
{
  "address": "TLYtEW9enGfQCq8vtgjCt24SMLXkttXDDY",
  "amount": 0,
  "to": "TQmu68ZVuSG19QaZH7DFqm258YDopiVzN5",
  "token": "TY4u1bUi4U5GHvVLmmM73BjBMt3EMm7Bas"
}
```

![image](https://user-images.githubusercontent.com/108270123/187945682-aab4b2cf-97c4-46f8-9313-877e8baf7301.png)

