# BLE-based Distance Estimation System
---

![image](https://github.com/user-attachments/assets/eacc2448-5f2b-42dd-8d00-088eed0ae6fa)
<img width="1313" alt="KakaoTalk_Photo_2025-05-20-12-55-50" src="https://github.com/user-attachments/assets/46945ead-2b3c-4d60-86a7-951d13eb8261" /> 

We developed a BLE-based system that estimates distance using the following model:

```
distance (m) = 10 ^ ((txPower - RSSI) / (10 * n))
```

This model provides reasonably accurate distance estimates in indoor environments.

---

### Results

* **Stable estimation** within 1–5 meters.
* **LED control** based on estimated distance was successful.
* **web server** display on web with estimated distance.

### Evaluation

* **Accuracy**: Acceptable for short-range proximity detection.
* **Limitation**: Accuracy drops with obstacles or signal reflection.

---

It shows pretty well result.  
![0519(1)](https://github.com/user-attachments/assets/d9294ef2-594e-4a73-a007-1d4b6739463c)

so we can control LED light with estimated distance  


https://github.com/user-attachments/assets/46f56950-790a-4a2b-b0ac-a4f2633bb76d

