

In the wave of edge computing, AI plays a vital role in edge-cloud and distributed cloud applications. Deploying AI-related tasks on edge devices is becoming inevitable due to their growing performance and widespread adoption. In 2022, Huawei open-sourced the **KubeEdge-Ianvs** project to the CNCF, introducing the first distributed collaborative AI benchmarking platform. This platform supports algorithm and service developers in developing, measuring, and optimizing distributed collaborative AI systems.

### **1. Introduction to the Cloud-Robotics Dataset**

The **Cloud-Robotics** dataset, introduced by Fudan University's Hu Shijing and Huawei's Mao Sitong, Luo Siqi, Huang Zhiwei, Zheng Zimu, Pu Jie, and Wang Feng, is an open-source multimodal dataset collected by smart robotic dogs in Huawei's Shenzhen Industrial Park. It focuses on **single task learning** for semantic segmentation in robot applications. 
---

### **1.1 What is Cloud-Robotics?**

Cloud-Robotics offers:  

- **High-Quality Data**: 2600 meticulously labeled images for semantic segmentation.  
- **Focused Use Cases**: Suitable for delivery and inspection tasks in both indoor and outdoor environments.  
- **Real-World Data**: Captured through the robotic dog’s camera, emphasizing objects like ramps, stairs, and curbs crucial for robotics.

Semantic segmentation assigns semantic labels to every pixel in an image, enabling robots to better perceive their environments. Unlike general image classification, it requires detailed pixel-level understanding, which is essential for tasks like navigation and obstacle avoidance.

**Key Features of the Dataset:**

- Captured at low angles, mimicking a robotic dog’s perspective.  
- Includes rare and challenging scenarios like reflections, blurs, and inclines to improve model robustness.  
- Addresses real-world single task learning scenarios.

---

### **1.2 Why Use Cloud-Robotics for Single Task Learning?**

#### Focused and Real-World Application:  
Compared to datasets like Cityscapes or KITTI, which are designed for autonomous driving, Cloud-Robotics is tailored for robotics applications in confined environments like industrial parks.  

- **Unique Perspective**: Images are captured by a robotic dog, offering a distinct, ground-level view compared to dashcams.  
- **Practical Data**: Emphasizes objects like curbs, stairs, and slopes that are critical for robotics.  
- **High Relevance**: Contains real-world challenges like reflections and blurs.

---

### **1.3 Dataset Distribution**

The dataset includes images grouped into seven categories (30 classes):  

| Group          | Classes                                   |  
|----------------|-------------------------------------------|  
| Flat           | Road, Sidewalk, Ramp                     |  
| Human          | Person, Rider                            |  
| Vehicle        | Car, Bus, Train, Motorcycle              |  
| Construction   | Building, Wall, Stairs                   |  
| Object         | Traffic Light, Pole, Dustbin             |  
| Nature         | Vegetation, Terrain                      |  
| Sky            | Sky                                      |  

---

### **1.4 Cloud-Robotics vs. Other Datasets**

| Feature                     | Cloud-Robotics          | Cityscapes            |  
|-----------------------------|-------------------------|-----------------------|  
| Task Focus                 | Semantic Segmentation   | Semantic Segmentation |  
| Image Count                | 2600                   | 5000                  |  
| Data Collection Device     | Robotic Dog            | Dashcam               |  
| Collection Environment     | Industrial Park        | City Streets          |  
| Key Focus                  | Curbs, Stairs, Slopes  | Roads, Vehicles       |  

---

### **2. Practical Applications in Single Task Learning**

**Delivery Scenario Example:**  

A robotic dog delivering items (e.g., milk tea) across an industrial park uses the semantic segmentation model trained on Cloud-Robotics data.  

- **Input**: Images captured by the robot’s camera.  
- **Output**: Pixel-level semantic labels for navigation.  
- **Goal**: Enhance robot perception for accurate and efficient task completion.  

This focused single task learning dataset ensures that the robot can handle specific challenges, such as uneven surfaces, reflections, and obstructions.

### **2.1 Community Benefits**

- **Algorithm Developers**: Provides high-precision data and benchmarking opportunities.  
- **Application Developers**: Supplies authentic, scenario-specific data for robotics applications.  
- **Community Growth**: Encourages contributions to robotic perception algorithms and applications.

---
