```mermaid
  graph TD;
    subgraph Operators
      CB(Cloud Broker)
      zCEE(z/OS Connect)
      Dev(Wazi Developer)
      Sandbox(Waxi Sandbox)
    end

    subgraph Suboperators   
      zpm(z/OS Package Manager)
      python(Python)
      go(Go)
      node(Node.js)
      Java(Java)
      ZOAU(Z Open Automation Utilities)
      
      zpm --> python --> go --> node --> Java --> ZOAU
    end
    
    CB --> zpm
     
```
