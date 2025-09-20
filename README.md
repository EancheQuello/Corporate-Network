# Simple-Office-Network

1.Съдържание:
Проект за проектиране на корпоративна мрежова инфраструктура, включително:
- Разпределение на работните места
- Централни и регионални сървърни помещения
- LAN мрежа и IP адресиране
- Предлагани услуги (DHCP,Mail и DNS)
- Мрежов мониторинг


  
2.Схема на изградената компютърна мрежа:
  
  

  
<img width="1886" height="713" alt="ттт" src="https://github.com/user-attachments/assets/7cbfc7cd-9427-4f2e-84a5-c7ba2c3d0157" />
3. Обяснение на схемата
!! No Routing!! Layer 2 Router

-Статични IP адреси:
Офис 1:
Main router:Gateway 192.168.1.1 
Servers:
DNS server:  IP :192.168.1.3 SubMask : 255.255.255.0 Gateway:192.168.1.1
DHCP server: IP :192.168.1.2 SubMask : 255.255.255.0 Gateway: 192.168.1.1 
Mail server: IP :192.168.1.10 SubMask :255.255.255.0 Gateway:192.168.1.1
Switch: 2бр
PC:4бр получаване на IP автоматично
Printers:3бр,автоматично получаване на IP
Офис 2:
Main Router second port:Gateway 192.168.2.1
PC:3бр получават автоматично от DHCP сървър






