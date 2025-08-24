# EdfaPay API Documentation

## Transaction Summary

Retrieve aggregated transaction data (sales, refunds, fees, and balances) for a merchant.

---

### **Endpoint**
`GET` `https://api.edfapay.com/trx/api/transactions/summary`

### **Parms**
* edfapay_merchant_id

### **Authentication**
- Requires client credentials in headers:
  ```http
  x-client-id: <CLIENT_ID>
  x-client-secret: <CLIENT_SECRET>

### **Curl Example**
```
  curl --location 'https://api.edfapay.com/trx/api/transactions/summary?edfapay_merchant_id=<MERCHANT_ID>'
    --header 'x-client-id:<CLIENT_ID>'
    --header 'x-client-secret:<CLIENT_SECRET>'
