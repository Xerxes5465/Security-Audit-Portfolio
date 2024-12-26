```mermaid
flowchart TD
    A[Security Control Framework] --> B[Administrative Controls]
    A --> C[Technical Controls]
    A --> D[Physical Controls]
    
    B --> B1[Password Policies]
    B --> B2[Disaster Recovery]
    B --> B3[Access Control]
    
    C --> C1[Firewall]
    C --> C2[IDS/IPS]
    C --> C3[Encryption]
    
    D --> D1[CCTV]
    D --> D2[Physical Locks]
    D --> D3[Fire Prevention]

    classDef implemented fill:#90EE90
    classDef missing fill:#FFB6C1
    
    class C1,D1,D2,D3 implemented
    class B1,B2,B3,C2,C3 missing
