**Sprint 2** | **Backlog**

| Tasks | Task Description                                                                                                                                                                                       |
|-------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| T.2.1 | Development of a layer two and layer three Packet Tracer simulation for building 1, encompassing the campus backbone. Integration of every member’s Packet Tracer simulation into a single simulation. |
| T.2.2 | Development of a layer two and layer three Packet Tracer simulation for building 2, encompassing the campus backbone.                                                                                  |
| T.2.3 | Development of a layer two and layer three Packet Tracer simulation for building 3, encompassing the campus backbone.                                                                                  |
| T.2.4 | Development of a layer two and layer three Packet Tracer simulation for building 4, encompassing the campus backbone.                                                                                  |


**Sprint Master**

- Rúben Freitas (1231267) will be the Sprint 2 Master.


**General technical decisions**

- Cisco Packet Tracer Version: 8.2.2.0400
- VLANIDs range: 382 - 403
- VTP Domain Name: r2425dgg1
- IPv4 Address Space: 10.23.160.0/20
- IPv4 Node Address: 87.5.127.173/30

| Building | VLAN ID range |
|:--------:|:-------------:|
|    1     |   382 - 387   |
|    2     |   388 - 392   |
|    3     |   393 - 397   |
|    4     |   398 - 402   |


| Building | VLAN ID |  VLAN Name   |
|:--------:|:-------:|:------------:|
|    1     |   382   | B1_F0_OUTLET |
|    1     |   383   | B1_F1_OUTLET |
|    1     |   384   |   B1_WiFi    |
|    1     |   385   |    B1_DMZ    |
|    1     |   386   |   B1_VOIP    |
|    1     |   387   |   BACKBONE   |
|    2     |   388   | B2_F0_OUTLET |
|    2     |   389   | B2_F1_OUTLET |
|    2     |   390   |   B2_WiFi    |
|    2     |   391   |    B2_DMZ    |
|    2     |   392   |   B2_VOIP    |
|    3     |   393   | B3_F0_OUTLET |
|    3     |   394   | B3_F1_OUTLET |
|    3     |   395   |   B3_WiFi    |
|    3     |   396   |    B3_DMZ    |
|    3     |   397   |   B3_VOIP    |
|    4     |   398   | B4_F0_OUTLET |
|    4     |   399   | B4_F1_OUTLET |
|    4     |   400   |   B4_WiFi    |
|    4     |   401   |    B4_DMZ    |
|    4     |   402   |   B4_VOIP    | 


### IPV4 DETAILS ###


|  Building  | Range Start |   Range End   | Usable IPs |
|:----------:|:-----------:|:-------------:|------------|
|  Backbone  | 10.23.160.0 | 10.23.161.255 | 510        |
| Building 1 | 10.23.162.0 | 10.23.163.255 | 510        |
| Building 2 | 10.23.164.0 | 10.23.167.255 | 1022       |
| Building 3 | 10.23.168.0 | 10.23.171.255 | 1022       |
| Building 4 | 10.23.172.0 | 10.23.175.255 | 1022       |


### UNIQUE IPV4 NODE ADDRESS IN THE BACKBONE FOR EACH BUILDING ###

| Router |     IPV4     |
|:------:|:------------:|
|   MC   | 10.23.160.1  |
|   1    | 10.23.160.10 |
|   2    | 10.23.160.20 |
|   3    | 10.23.160.30 |
|   4    | 10.23.160.40 |

### Device Names ###

- **Router:**
    - Router_MC
    - Router_BN
    - Router_ISP

- **Switch:**
    - Switch_MC
    - Switch_BN_IC
    - Switch_BN_FN_HC
    - Switch_BN_FN_CP_RN

- **PC:**
    - PC_BN_FN_RN

- **Laptop:**
    - Laptop_BN_FN_RN
    - Laptop_BN_FN

- **Phone:**
    - IPPhone_BN_FN_RN

- **Access-Point:**
    - AP_BN_FN_RN
    - AP_BN_FN
    - AP_BN_FN_N

- **Server:**
    - Server_BN

**BN = Building Number**\
**FN = Floor Number**\
**RN = Room Number**
**N = Number**



**Tasks Assigned**
```
T.2.1 - 1231267 - Rúben Freitas
T.2.2 - 1222123 - João Sousa
T.2.3 - 1230927 - José Ribeiro
T.2.4 - 1231031 - Rafael Costa
```
