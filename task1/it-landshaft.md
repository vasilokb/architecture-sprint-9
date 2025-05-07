```mermaid
block-beta
    columns 7
    A["Подразделение / Бизнес-возможность"]:1
    block:Header1:3
        B["Продажа в сети отделений"]:1
        C["Продажа через колл-центр"]:1
        D["Digital-оповещения клиентов"]:1
    end
    block:Header2:3
        E["Обслуживание депозитных процессов"]:1
        F["Обслуживание кредитных процессов"]:1
        G["Управление договорами"]:1
    end

    A1["Управление обслуживанием в сети отделений"]:1
    block:Row11:3
        B1["АБС (Delphi, Oracle)"]:1
        C1["-"]:1
        D1["-"]:1
    end
    block:Row12:3
        E1["АБС, Excel, Email"]:1
        F1["-"]:1
        G1["АБС"]:1
    end

    A2["Колл-центр"]:1
    block:Row21:3
        B2["-"]:1
        C2["Система кол-центра (React.js, Java Spring Boot, PostgreSQL)"]:1
        D2["Система кол-центра, СМС-шлюз"]:1
    end
    block:Row22:3
        E2["Система кол-центра, АБС"]:1
        F2["-"]:1
        G2["-"]:1
    end

    A3["IT-отдел"]:1
    block:Row31:3
        B3["АБС, интернет-банк"]:1
        C3["-"]:1
        D3["СМС-шлюз"]:1
    end
    block:Row32:3
        E3["-"]:1
        F3["-"]:1
        G3["-"]:1
    end

    A4["Управление обслуживанием депозитных продуктов"]:1
    block:Row41:3
        B4["-"]:1
        C4["-"]:1
        D4["-"]:1
    end
    block:Row42:3
        E4["АБС, Excel, Email"]:1
        F4["-"]:1
        G4["АБС"]:1
    end

    A5["Управление обслуживанием кредитных продуктов"]:1
    block:Row51:3
        B5["-"]:1
        C5["-"]:1
        D5["-"]:1
    end
    block:Row52:3
        E5["-"]:1
        F5["АБС, Excel, Email"]:1
        G5["АБС"]:1
    end



%% Стили для заголовков
    style Header1 fill:#228B22,stroke:#333,stroke-width:4px,color:#fff
    style Header2 fill:#228B22,stroke:#333,stroke-width:4px,color:#fff
    style A fill:#228B22,stroke:#333,stroke-width:2px,color:#fff
    style B fill:#228B22,stroke:#333,stroke-width:2px,color:#fff
    style C fill:#228B22,stroke:#333,stroke-width:2px,color:#fff
    style D fill:#228B22,stroke:#333,stroke-width:2px,color:#fff
    style E fill:#228B22,stroke:#333,stroke-width:2px,color:#fff
    style F fill:#228B22,stroke:#333,stroke-width:2px,color:#fff
    style G fill:#228B22,stroke:#333,stroke-width:2px,color:#fff

%% Стили для строк подразделений
    style A1 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style A2 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style A3 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style A4 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style A5 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000

    style Row11 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style Row12 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style Row21 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style Row22 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style Row31 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style Row32 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style Row41 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style Row42 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style Row51 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000
    style Row52 fill:#87CEFA,stroke:#333,stroke-width:2px,color:#000


%% Стили для ячеек с системами
    style B1 fill:#ADD8E6,stroke:#333,stroke-width:1px,color:#000
    style C1 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style D1 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style E1 fill:#FFFF99,stroke:#333,stroke-width:1px,color:#000
    style F1 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style G1 fill:#ADD8E6,stroke:#333,stroke-width:1px,color:#000
    style B2 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style C2 fill:#DDA0DD,stroke:#333,stroke-width:1px,color:#000
    style D2 fill:#DDA0DD,stroke:#333,stroke-width:1px,color:#000
    style E2 fill:#DDA0DD,stroke:#333,stroke-width:1px,color:#000
    style F2 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style G2 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style B3 fill:#ADD8E6,stroke:#333,stroke-width:1px,color:#000
    style C3 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style D3 fill:#FFA500,stroke:#333,stroke-width:1px,color:#000
    style E3 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style F3 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style G3 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style B4 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style C4 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style D4 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style E4 fill:#FFFF99,stroke:#333,stroke-width:1px,color:#000
    style F4 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style G4 fill:#ADD8E6,stroke:#333,stroke-width:1px,color:#000
    style B5 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style C5 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style D5 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style E5 fill:#87CEFA,stroke:#333,stroke-width:1px,color:#000
    style F5 fill:#FFFF99,stroke:#333,stroke-width:1px,color:#000
    style G5 fill:#ADD8E6,stroke:#333,stroke-width:1px,color:#000
