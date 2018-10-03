# Hook

[POST] https://bus.servicechain.ru/

```
{
  "token":"${authToken}",
  "to": "ServiceChainKey" 
  "data": {
    "id":"${FromId}", -- ID заявки в системе отправителя
    "extId": "${ToID}", -- ID заявки в системе получателя
    "status":"${Status}", -- статус в системе отправителя
    "response": "${реплика}"
}
```

to -- Ключ получателя в системе ServiceChain !!! не равен ID клиента в личном кабинете для предотвращения инъекций
