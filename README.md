# Finite-Element-analysis-of-brake-pedals

## Finite Element Analysis of Brake Pedal: Comparison Between Aluminum and Carbon Composite

This project aims to perform a finite element analysis (FEA) on brake pedals made from two different materials: aluminum and carbon composite. The analysis focuses on comparing the performance, durability, and efficiency of these materials under various operating conditions.

## Technical Description

This project explores two distinct cases of brake pedals, highlighting their materials and geometric configurations:

- **Case 1:** Standard brake pedal made of aluminum
- **Case 2:** Brake pedal made of carbon composite

## Aim of Analysis

The primary goal is to investigate the impact of transitioning from aluminum to carbon composite for brake pedals under various conditions. Specific objectives include:

1. **Understanding the effects of different operational conditions on brake pedal performance.**
2. **Evaluating the benefits of using carbon composite over aluminum.**
3. **Identifying opportunities for improving brake pedal design.**

## Description of Cases and Operating Conditions

### Case 1: Aluminum Brake Pedal

- **Scenario 1: Standard Braking**
  - Force Applied: 300 N
  - Ambient Temperature: 20°C

- **Scenario 2: Emergency Braking**
  - Force Applied: 700 N
  - Ambient Temperature: 20°C

- **Scenario 3: Impact of Temperature**
  - Scenario 3a: High Temperature (60°C)
  - Scenario 3b: Low Temperature (-30°C)
  - Force Applied: 300 N

- **Scenario 4: Braking in High Heels**
  - Force Applied: 300 N distributed between two points.
  - Ambient Temperature: 20°C

- **Scenario 5: Pedal Obstruction**
  - Force Applied: 300 N with additional obstruction load of 100 N.
  - Ambient Temperature: 20°C

### Case 2: Carbon Composite Brake Pedal

- **Scenario 1: Standard Braking**
  - Force Applied: 300 N
  - Ambient Temperature: 20°C

- **Scenario 2: Emergency Braking**
  - Force Applied: 700 N
  - Ambient Temperature: 20°C

- **Scenario 3: Impact of Temperature**
  - Scenario 3a: High Temperature (60°C)
  - Scenario 3b: Low Temperature (-30°C)
  - Force Applied: 300 N

- **Scenario 4: Braking in High Heels**
  - Force Applied: 300 N distributed between two points.
  - Ambient Temperature: 20°C

- **Scenario 5: Pedal Obstruction**
  - Force Applied: 300 N with additional obstruction load of 100 N.
  - Ambient Temperature: 20°C

## Model of Geometry

### Aluminum Brake Pedal

#### Render Image:
<p align="center">
  <img width="446" alt="image" src="https://github.com/oliwiakruczyk/Finite-Element-analysis-of-brake-pedals/assets/150608343/6e28817b-9cc9-4f14-820f-d7bfd59c0ffb">
</p>


### Carbon Composite Brake Pedal

#### Render Image:
<p align="center">
  <img width="441" alt="image" src="https://github.com/oliwiakruczyk/Finite-Element-analysis-of-brake-pedals/assets/150608343/7eb14283-49f8-4bb7-a459-b2753fb453f6">
</p>


## Results of FEA Simulations

### Case 1: Aluminum Brake Pedal

#### Scenario 1: Standard Braking
- **Maximum Deformation:** Within acceptable limits
- **Equivalent Stress:** Within acceptable limits

<p align="center">
  <img width="303" alt="image" src="https://github.com/oliwiakruczyk/Finite-Element-analysis-of-brake-pedals/assets/150608343/2624ca7c-20ba-441f-bae4-3ae9b28d48bc">
</p>

#### Scenario 2: Emergency Braking
- **Maximum Deformation:** Significant deformation observed
- **Equivalent Stress:** High stress indicating the need for design modifications

<p align="center">
  <img width="296" alt="image" src="https://github.com/oliwiakruczyk/Finite-Element-analysis-of-brake-pedals/assets/150608343/c09c7d9f-9230-40b9-a935-ec04c2cd9693">
</p>

#### Scenario 3: Impact of Temperature
- **High Temperature (60°C):**
  - **Stress and Deformation:** Minimal variation compared to standard conditions
- **Low Temperature (-30°C):**
  - **Stress and Deformation:** Minimal variation compared to standard conditions

<p align="center">
  <img width="303" alt="image" src="https://github.com/oliwiakruczyk/Finite-Element-analysis-of-brake-pedals/assets/150608343/d5e6d024-2a82-4920-9698-154c619f71cb">
</p>

#### Scenario 4: Braking in High Heels
- **Maximum Deformation:** Pedal effectively handles localized intense loads

<p align="center">
  <img width="329" alt="image" src="https://github.com/oliwiakruczyk/Finite-Element-analysis-of-brake-pedals/assets/150608343/2442ba18-3d0f-44ac-b550-73e0f7178806">
</p>

#### Scenario 5: Pedal Obstruction
- **Performance:** Pedal maintains functionality under complex loading conditions but shows stress and deformation indicating areas for improvement

<p align="center">
  <img width="260" alt="image" src="https://github.com/oliwiakruczyk/Finite-Element-analysis-of-brake-pedals/assets/150608343/09dac2e6-665a-4992-aaaa-b89937c2f5be">
</p>

### Case 2: Carbon Composite Brake Pedal

#### Overall Performance
- **Deformation:** Improved performance compared to aluminum pedal
- **Stress Handling:** Better stress distribution and handling under all tested scenarios

<p align="center">
  <img width="265" alt="image" src="https://github.com/oliwiakruczyk/Finite-Element-analysis-of-brake-pedals/assets/150608343/7a6b2a57-18b0-479e-b1ac-e66e381b9bf8">
</p>

## Final Conclusions

The finite element analysis conducted in this study reveals several key insights into the performance of brake pedals made from aluminum and carbon composite materials. The results indicate that carbon composite brake pedals offer substantial advantages over their aluminum counterparts across various metrics:

- **Strength and Durability:** Carbon composite brake pedals exhibit superior strength and durability, maintaining structural integrity under higher stress and deformation conditions. This makes them more reliable, particularly in emergency braking scenarios where the applied forces are significantly higher.
- **Weight Reduction:** One of the most significant benefits of using carbon composite materials is their lightweight nature. This reduction in weight can contribute to overall vehicle efficiency and performance, providing an edge in applications where weight savings are critical.

### Recommendations for Further Research

Given the high cost of carbon composite materials, it is crucial to explore cost-effective alternatives to achieve the desired performance enhancements. The following recommendations are proposed:

- **Design Optimization for Aluminum Pedals:** Further studies should focus on optimizing the design of aluminum brake pedals. This could include increasing the thickness or modifying the geometry to improve strength and durability. Such design changes could potentially bring the performance of aluminum pedals closer to that of carbon composite pedals while keeping costs lower.
- **Reducing Safety Margins for Carbon Composite Pedals:** The carbon composite pedals exhibited high safety factors. Future research should investigate the possibility of reducing these safety margins to achieve weight reduction without compromising safety. This could make carbon composite pedals even
