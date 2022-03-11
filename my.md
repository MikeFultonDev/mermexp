```mermaid
  graph TD;
    subgraph B
      graph LR;
      CB(Cloud Broker)
      zCEE(z/OS Connect)
      Dev(Wazi Developer)
      Sandbox(Waxi Sandbox)
    end
    
  graph TD;
    subgraph B
      graph LR;
      zpm(z/OS Package Manager)
      python(Python)
      go(Go)
      node(Node.js)
      Java(Java)
      ZOAU(Z Open Automation Utilities)
      
      zpm --> python --> go --> node --> Java --> ZOAU
    end
    
    graph TD;
    
    CB --> zpm
     
```
