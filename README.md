# ML_Threat-Detection_in_IOT-Devices
Using ML and DL models to detect and classify network traffic on IOT devices into 2, 8 and 34 different classes

We have created a machine learning to identify and classify if a traffic in a network is a malicious attack or a benign data packet.

The Dataset we used in this project is [***CIC-IOT 2023***](https://www.unb.ca/cic/datasets/iotdataset-2023.html)
The dataset has 2 classes, 8 classes and 34 classes.

***2 Classes:***
            Attack, Benign
***8 Classes:***
            DDoS, DoS, Mirai, Recon, Spoofing, Benign, Web, BruteForce
***34 Classes:***
            DDoS-RSTFINFlood, DDoS-PSHACK_Flood, DDoS-SYN_Flood, DDoS-UDP_Flood, DDoS-TCP_Flood, DDoS-ICMP_Flood, DDoS-SynonymousIP_Flood, DDoS-ACK_Fragmentation, DDoS-UDP_Fragmentation, DDoS-ICMP_Fragmentation,DDoS-SlowLoris, DDoS-HTTP_Flood, DoS-UDP_Flood, DoS-SYN_Flood, DoS-TCP_Flood, DoS-HTTP_Flood, Mirai-greeth_flood, Mirai-greip_flood, Mirai-udpplain, Recon-PingSweep, Recon-OSScan, Recon-PortScan, VulnerabilityScan, Recon-HostDiscovery, DNS_Spoofing, MITM-ArpSpoofing, BenignTraffic, BrowserHijacking, Backdoor_Malware, XSS, Uploading_Attack, SqlInjection, CommandInjection, DictionaryBruteForce.

We have used XG Boost, Logistic Regression, Random Forest for ML models, and CNN for DL

| Metric           | Logistic Regression | Random Forest  | XG Boost       | CNN            |
|------------------|---------------------|----------------|----------------|----------------|
| **34 Classes**    |                     |                |                |                |
| Accuracy          | 94.97               | 0.9638554202227452 | 0.9712748307806567 | 0.984714925501810 |
| Recall            | 60.08               | 0.6246373282216164 | 0.7167066142973229 | 0.706248589490101 |
| Precision         | 53.32               | 0.7112239405812282 | 0.6368060561831704 | 0.666563849397882 |
| F1 Score          | 52.95               | 0.6363961881088307 | 0.656139624093135  | 0.670808911580390 |
| **8 Classes**     |                     |                |                |                |
| Accuracy          | 87.53               | 0.982062922759767  | 0.952400773327645  | 0.984787711281534 |
| Recall            | 52.05               | 0.665477053611591  | 0.80367772775367   | 0.635507736260502 |
| Precision         | 46.61               | 0.7589006650481671 | 0.6779048677353534 | 0.596697932247575 |
| F1 Score          | 55.41               | 0.6860710018129402 | 0.7075222357462108 | 0.606842339996746 |
| **2 Classes**     |                     |                |                |                |
| Accuracy          | 98.745              | 0.9879343292428899 | 0.9949756547363402 | 0.992472382869727 |
| Recall            | 85.1147             | 0.8309587865365134 | 0.9369485350646841 | 0.894387828426575 |
| Precision         | 89.397              | 0.9911742586415496 | 0.9564886549162597 | 0.959469564413380 |
| F1 Score          | 87.125              | 0.8943617254202743 | 0.9464931873563651 | 0.924300192530067 |


This is the Reference [Research Paper](https://www.researchgate.net/publication/370611316_CICIoT2023_A_real-time_dataset_and_benchmark_for_large-scale_attacks_in_IoT_environment  )
    

