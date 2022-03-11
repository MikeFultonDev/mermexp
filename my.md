```mermaid
  graph TD;
    subgraph B
      CB(Cloud Broker)
      zCEE(z/OS Connect)
      Dev(Wazi Developer)
      Sandbox(Waxi Sandbox)
    end
    
  graph TD;
    subgraph B
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
