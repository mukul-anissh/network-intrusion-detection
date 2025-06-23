# network-intrusion-detection
This project applies ensemble techniques to classify network traffic into multiple attack categories using the UNSW-NB15 dataset.

Models used:
1. XGBoost
2. LightGBM

final metrics achieved:
| Class            | Precision | Recall | F1-score   | Support |
| ---------------- | --------- | ------ | ---------- | ------- |
| Analysis				 | 0.7619    | 0.2850 | 0.4148     | 393     |
| Backdoor         | 0.8556    | 0.2139 | 0.3422     | 360     |
| DoS              | 0.4026    | 0.3059 | 0.3476     | 2370    |
| Exploits         | 0.6820    | 0.8712 | 0.7651     | 6772    |
| Fuzzers          | 0.9507    | 0.8754 | 0.9115     | 3570    |
| Generic          | 0.9954    | 0.9844 | 0.9899     | 8079    |
| Normal           | 0.9934    | 0.9937 | 0.9936     | 11169   |
| Reconnaissance   | 0.9247    | 0.7374 | 0.8205     | 2098    |
| Shellcode        | 0.7125    | 0.7339 | 0.7230     | 233     |
| Worms            | 0.7647    | 0.5200 | 0.6190     | 25      |
| **Accuracy**     |           |        | **0.8760** | 35069   |
| **Macro Avg**    | 0.8043    | 0.6521 | 0.6927     | 35069   |
| **Weighted Avg** | 0.8793    | 0.8760 | **0.8710** | 35069   |
