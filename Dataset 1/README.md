# Created Dataset 

To improve the clarity and transparency of our analysis and selection methods, we carefully documented the micro-services and their corresponding service-based metrics. For a comprehensive assessment, we gathered six distinct service-based maintainability metrics spanning 101 microservices across ten diverse projects. These metrics are detailed in the table presented below and can also be found in Dataset 1/Created Dataset Github.xlsx.

| Project Name              | New Numbers | Microservice Name            | Lines of Code | Number of Methods | Average Complexity | Granularity NoC/MS | Service Call Ratio | Class Dependecy | Label |
|---------------------------|-------------|------------------------------|---------------|-------------------|--------------------|--------------------|--------------------|-----------------|-------|
| Train Ticket              | 1           | AdminBasicInfoService        | 433           | 42                | 2.0000             | 0.1282             | 0.5641             | 20              | M     |
|                           | 2           | AdminOrderService            | 195           | 10                | 2.5000             | 0.1026             | 0.1538             | 4               | H     |
|                           | 3           | ts-admin-route-service       | 149           | 9                 | 2.3333             | 0.1026             | 0.1282             | 3               | H     |
|                           | 4           | ts-admin-travel-service      | 299           | 14                | 3.1667             | 0.1026             | 0.1538             | 4               | H     |
|                           | 5           | ts-admin-user-service        | 155           | 10                | 2.2000             | 0.1282             | 0.0769             | 4               | H     |
|                           | 6           | ts-assurance-service         | 219           | 17                | 2.8409             | 0.2051             | 0.2308             | 8               | M     |
|                           | 7           | ts-auth-service              | 263           | 13                | 2.2750             | 0.4359             | 0.1538             | 4               | M     |
|                           | 8           | ts-basic-service             | 472           | 16                | 4.0800             | 0.1026             | 0.1282             | 3               | M     |
|                           | 9           | ts-cancel-service            | 330           | 15                | 4.0870             | 0.1795             | 0.1026             | 2               | L     |
|                           | 10          | ts-config-service            | 140           | 11                | 2.5769             | 0.1538             | 0.1795             | 5               | H     |
|                           | 11          | ts-consign-price-service     | 120           | 9                 | 2.2857             | 0.1538             | 0.1538             | 4               | H     |
|                           | 12          | ts-consign-service           | 182           | 12                | 2.4286             | 0.2308             | 0.1795             | 8               | H     |
|                           | 13          | ts-contacts-service          | 172           | 15                | 2.6154             | 0.1538             | 0.2308             | 7               | H     |
|                           | 14          | ts-execute-service           | 195           | 10                | 3.5556             | 0.1026             | 0.1026             | 2               | M     |
|                           | 15          | ts-food-delivery(map)-service| 218           | 18                | 2.7429             | 0.2564             | 0.2564             | 8               | L     |
|                           | 16          | ts-food-service              | 345           | 17                | 3.2432             | 0.2308             | 0.2564             | 7               | L     |
|                           | 17          | ts-inside-payment-service    | 420           | 24                | 3.1525             | 0.3590             | 0.2564             | 8               | M     |
|                           | 18          | ts-notification-service      | 216           | 12                | 2.3889             | 0.3077             | 0.2051             | 9               | H     |
|                           | 19          | ts-order-other-service       | 549           | 37                | 3.2237             | 0.2051             | 0.4359             | 16              | M     |
|                           | 20          | ts-order-service             | 546           | 37                | 3.1341             | 0.2051             | 0.4359             | 16              | M     |
|                           | 21          | ts-preserve-other-service    | 378           | 15                | 3.1667             | 0.1538             | 0.0769             | 1               | L     |
|                           | 22          | ts-preserve-service          | 378           | 15                | 3.1667             | 0.1538             | 0.0769             | 1               | L     |
|                           | 23          | ts-price-service             | 195           | 14                | 2.7500             | 0.1538             | 0.2051             | 7               | H     |
|                           | 24          | ts-rebook-service            | 440           | 20                | 4.4286             | 0.1282             | 0.1026             | 2               | L     |
|                           | 25          | ts-route-plan-service        | 336           | 12                | 3.6667             | 0.1026             | 0.1282             | 3               | H     |
|                           | 26          | ts-route-service             | 179           | 13                | 2.7742             | 0.1795             | 0.2051             | 6               | H     |
|                           | 27          | ts-seat-service              | 227           | 8                 | 3.0000             | 0.1026             | 0.1026             | 2               | M     |
|                           | 28          | ts-security-service          | 194           | 14                | 2.4333             | 0.1538             | 0.1795             | 5               | H     |
|                           | 29          | ts-station-service           | 198           | 18                | 2.6923             | 0.1538             | 0.2564             | 9               | H     |
|                           | 30          | ts-train-food-service        | 84            | 6                 | 2.8571             | 0.1538             | 0.1026             | 2               | H     |               
|                           | 31          | ts-train-service             | 194           | 15                | 3.0882             | 0.1538             | 0.2308             | 7               | H     |
|                           | 32          | ts-travel-plan-service       | 321           | 17                | 2.5357             | 0.1795             | 0.1538             | 4               | H     |
|                           | 33          | ts-travel-service            | 628           | 35                | 3.3390             | 0.2564             | 0.3590             | 12              | M     |
|                           | 34          | ts-travel2-service           | 535           | 32                | 3.2909             | 0.2308             | 0.3333             | 11              | M     |
|                           | 35          | ts-user-service              | 219           | 16                | 2.4722             | 0.2051             | 0.1538             | 6               | M     |
|                           | 36          | ts-verification-code-service | 176           | 5                 | 2.9375             | 0.1282             | 0.0769             | 2               | L     |
|                           | 37          | ts-payment-service           | 108           | 8                 | 2.3478             | 0.1795             | 0.1282             | 3               | M     |
|                           | 38          | ts-station-food-service      | 117           | 10                | 2.9286             | 0.1538             | 0.1538             | 4               | M     |
|                           | 39          | ts-wait-order-service        | 190           | 13                | 2.8182             | 0.1795             | 0.1282             | 3               | M     |
| Teastore Project          | 40          | auth (s1)                    | 337           | 8                 | 5.8750             | 0.5000             | 0.5000             | 0               | M     |
|                           | 41          | image                        | 618           | 28                | 2.7500             | 0.5000             | 0.0000             | 7               | L     |
|                           | 42          | persistence                  | 789           | 41                | 3.2927             | 1.3333             | 0.6667             | 40              | L     |
|                           | 43          | recommender                  | 1443          | 57                | 4.0526             | 2.3333             | 0.5000             | 55              | L     |
|                           | 44          | registry                     | 383           | 16                | 2.2000             | 0.8333             | 0.5000             | 10              | H     |
|                           | 45          | webui                        | 1629          | 41                | 4.4634             | 2.8333             | 0.0000             | 128             | M     |
| Observability             | 46          | Calendar_Integration         | 184           | 11                | 2.0000             | 0.5000             | 0.1250             | 15              | H     |
|                           | 47          | Cardiologidt_Api             | 157           | 12                | 2.6667             | 0.5000             | 0.2500             | 4               | M     |
|                           | 48          | Medical_Integration          | 277           | 13                | 2.0000             | 0.7500             | 0.1250             | 46              | H     |
|                           | 49          | Nutrionist_api               | 151           | 11                | 2.7273             | 0.5000             | 0.1250             | 4               | M     |
|                           | 50          | Fitness_api                  | 609           | 54                | 2.2222             | 1.6250             | 0.5000             | 64               | H     |
|                           | 50          | Fitness_api                  | 609           | 54                | 2.2222             | 1.6250             | 0.5000             | 64              | H     |
|                           | 51          | Reactive_calendar_api        | 144           | 9                 | 2.4444             | 0.3750             | 0.0000             | 4               | L     |
|                           | 52          | Social_Network_Integration   | 372           | 19                | 2.1053             | 1.3750             | 0.1250             | 60              | H     |
|                           | 53          | Strava_api                   | 106           | 4                 | 2.7500             | 0.2500             | 0.1250             | 2               | H     |
| Piggymetrics              | 54          | Account-service              | 170           | 13                | 2.0000             | 0.4286             | 1.0000             | 14              | M     |
|                           | 55          | Auth-service                 | 57            | 4                 | 2.0000             | 0.2857             | 0.5000             | 2               | H     |
|                           | 56          | Notification-service         | 63            | 3                 | 3.3333             | 0.1429             | 0.1667             | 1               | M     |
|                           | 57          | Email-service                | 41            | 1                 | 2.0000             | 0.1429             | 0.0000             | 0               | H     |
|                           | 58          | Recipient-service            | 121           | 10                | 2.0000             | 0.2857             | 0.5000             | 7               | M     |
|                           | 59          | Statistics-service           | 116           | 7                 | 2.0000             | 0.2857             | 0.5000             | 3               | M     |
|                           | 60          | ExchangeRates                | 95            | 6                 | 2.0000             | 0.2857             | 0.1667             | 7               | M     |
| Ecommerce-Microservice    | 61          | User-service                 | 194           | 12                | 2.5000             | 0.2727             | 1.4000             | 23              | M     |
|                           | 62          | Favourite-service            | 178           | 14                | 2.0000             | 0.2727             | 0.5000             | 19              | H     |
|                           | 63          | İnventory-service            | 107           | 6                 | 2.6667             | 0.1818             | 0.2000             | 2               | M     |
|                           | 64          | Notify-service-send-email    | 107           | 6                 | 4.0000             | 0.1818             | 0.4000             | 3               | M     |
|                           | 65          | Order-service                | 146           | 14                | 2.0000             | 0.1818             | 0.4000             | 22              | M     |
|                           | 66          | Cart-service                 | 159           | 14                | 2.0000             | 0.1818             | 0.4000             | 22              | M     |
|                           | 67          | Payment-service              | 192           | 14                | 2.0000             | 0.1818             | 0.4000             | 20              | M     |
|                           | 68          | Product-service              | 197           | 14                | 2.1429             | 0.1818             | 0.4000             | 23              | H     |
|                           | 69          | Cathegory-service            | 271           | 18                | 2.5000             | 0.1818             | 0.6000             | 30              | H     |
|                           | 70          | Shipping-service             | 187           | 14                | 2.2857             | 0.1818             | 0.5000             | 20              | H     |
| E-Commerce-Microservice-BE| 71          | Cart-service                 | 114           | 8                 | 2.5000             | 0.3333             | 0.1429             | 4               | H     |
|                           | 72          | File-service                 | 83            | 5                 | 3.6000             | 0.2222             | 0.5714             | 2               | H     |
|                           | 73          | Inventory-service            | 107           | 9                 | 2.0000             | 0.4444             | 0.2857             | 6               | H     |
|                           | 74          | Product-service              | 283           | 21                | 2.0952             | 0.3333             | 1.0000             | 11              | M     |
|                           | 75          | Category-service             | 73            | 6                 | 2.0000             | 0.3333             | 0.1429             | 3               | M     |
|                           | 76          | Order-service                | 173           | 11                | 2.0000             | 0.5556             | 0.2857             | 7               | H     |
|                           | 77          | User-service                 | 625           | 57                | 2.3571             | 1.5556             | 2.2857             | 14              | M     |
|                           | 78          | notification-service         | 66            | 4                 | 2.5000             | 0.2222             | 0.0000             | 1               | H     |
| zlt-business              | 79          | Code-generator               | 319           | 20                | 3.0500             | 0.2727             | 0.3000             | 18              | H     |
|                           | 80          | File-center                  | 345           | 27                | 2.4074             | 0.5455             | 0.3000             | 37              | H     |
|                           | 81          | search-server/Search         | 112           | 4                 | 2.0000             | 0.2727             | 0.2000             | 2               | M     |
|                           | 82          | search-server/Aggregation    | 396           | 13                | 2.5385             | 0.2727             | 0.2000             | 2               | L     |
|                           | 83          | search-server/İndex          | 168           | 8                 | 2.2500             | 0.1818             | 0.5000             | 4               | M     |
|                           | 84          | User-center/Menu             | 249           | 15                | 2.8667             | 0.1818             | 0.9000             | 8               | M     |
|                           | 85          | User-center/Role             | 167           | 11                | 2.5455             | 0.1818             | 0.4000             | 8               | M     |
|                           | 86          | User-center/User             | 533           | 37                | 2.2432             | 0.1818             | 1.9000             | 24              | L     |
|                           | 87          | zlt-uaa/Client               | 155           | 14                | 2.1429             | 0.1818             | 0.6000             | 8               | M     |
|                           | 88          | zlt-uaa/Tokens               | 160           | 5                 | 4.0000             | 0.1818             | 0.3000             | 2               | M     |
|                           | 89          | zlt-uaa/ValidateCode         | 190           | 13                | 2.1538             | 0.1818             | 0.2000             | 6               | M     |
|spring-boot-microservices-series | 90          | catalogservice               | 177           | 11                | 2.4545             | 1.0000             | 1.6667             | 5               | M     |
| Bootiful Microservices with Spring Boot | 91 | beercatalogservice        | 50            | 2                 | 2.0000             | 1.5000             | 0.0000             | 0               | H     |
|                           | 92          | edgeservice                  | 59            | 5                 | 2.0000             | 1.5000             | 1.0000             | 0               | H     |
| vertx-blueprint-microservice | 93       | account/java                | 167           | 14                | 2.0000             | 0.2222             | 0.1111             | 4               | M     |
|                           | 94          | api-gateway                  | 241           | 13                | 3.2308             | 0.1111             | 0.0000             | 0               | M     |
|                           | 95          | cache-infrastructure/java   | 62            | 4                 | 4.0000             | 0.1111             | 0.4444             | 0               | H     |
|                           | 96          | inventory                    | 117           | 7                 | 3.7143             | 0.2222             | 0.2222             | 3               | H     |
|                           | 97          | order/java                   | 126           | 7                 | 2.5714             | 0.2222             | 0.4444             | 2               | M     |
|                           | 98          | payment/java                 | 174           | 15                | 2.6667             | 0.2222             | 0.0000             | 4               | M     |
|                           | 99          | product/java                 | 292           | 33                | 2.1818             | 0.3333             | 0.1111             | 14              | M     |
|                           | 100         | shopping-cart/java           | 451           | 28                | 2.7500             | 0.4444             | 0.5556             | 14              | M     |
|                           | 101         | store/java                   | 179           | 17                | 2.5882             | 0.3333             | 0.3333             | 9               | M     |

