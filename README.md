# Exp 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios

## 1. Aim

To compare different prompting techniques and evaluate their effectiveness in solving real-world engineering problems by using a problem selected from a student's 3rd-year or final-year project work.

---

## 2. AI Tools Required

- ChatGPT
- Generative AI Tools

---

## 3. Experiment Overview

In this experiment, a genuine engineering problem from a student's ongoing or completed project is selected.

The same engineering problem is given to an AI system using different prompting techniques. The generated responses are then compared and evaluated based on:

- Relevance
- Accuracy
- Completeness
- Clarity
- Feasibility
- Usefulness

The purpose of this experiment is to analyse how changing the prompting technique affects the quality of AI-generated solutions.

---

## 4. Project Title

**GIS-Based Seismic Vulnerability Assessment and Structural Response Study of Multi-Storey RC Buildings in Chennai City**

---

## 5. Problem Statement

Chennai contains many multi-storey Reinforced Concrete (RC) buildings constructed under different soil conditions, construction qualities, building ages, and structural configurations.

During an earthquake, some buildings may be more vulnerable due to:

- Building age
- Number of storeys
- Soil conditions
- Construction quality
- Plan irregularity
- Vertical irregularity
- Soft-storey condition

The engineering problem is to develop a **GIS-based method for identifying and mapping the seismic vulnerability of multi-storey RC buildings in Chennai City**.

---

## 6. Selected Engineering Scenario

**Identifying Seismic Vulnerability of RC Buildings Using GIS**

The AI system is asked to develop a methodology for:

1. Collecting building data.
2. Identifying seismic vulnerability parameters.
3. Preparing GIS layers.
4. Assigning vulnerability scores.
5. Performing spatial analysis.
6. Preparing the final seismic vulnerability map.

---

## 7. Base / Naïve Prompt

### Prompt

> How can I identify seismic vulnerability of buildings in Chennai using GIS?

### AI-Generated Output

The seismic vulnerability of buildings can be identified using GIS by collecting building information and combining it with earthquake hazard data.

Important parameters include:

- Building age
- Building height
- Soil type
- Structural condition

These data can be analyzed in QGIS to classify buildings into:

- Low Vulnerability
- Moderate Vulnerability
- High Vulnerability

### Observation

The response is relevant but general. It does not provide a detailed workflow or specific methodology.

---

## 8. Zero-Shot Prompting

### Prompt

> Develop a step-by-step methodology for conducting a GIS-based seismic vulnerability assessment of multi-storey RC buildings in Chennai City. Include data collection, building parameters, soil conditions, seismic hazard information, vulnerability classification, and final map preparation in QGIS.

### AI-Generated Output

The methodology includes:

1. Define the study area.
2. Collect the Chennai administrative boundary.
3. Prepare a building inventory.
4. Collect building parameters.
5. Collect soil and seismic hazard data.
6. Prepare GIS layers in QGIS.
7. Assign vulnerability scores.
8. Perform weighted overlay analysis.
9. Classify buildings into vulnerability categories.
10. Prepare the final seismic vulnerability map.

### Observation

The output is more structured and complete than the naïve prompt.

---

## 9. Persona / Role-Based Prompting

### Prompt

> Act as a structural engineer and GIS specialist. Design a practical methodology for assessing the seismic vulnerability of multi-storey reinforced concrete buildings in Chennai City using QGIS.

### AI-Generated Output

The methodology considers:

- Building age
- Number of storeys
- Building height
- Construction quality
- Occupancy type
- Plan irregularity
- Vertical irregularity
- Soft-storey presence

The required GIS layers include:

- Administrative boundary
- Building footprint
- Soil map
- Geology map
- Seismic hazard map
- Land Use/Land Cover map

### Observation

The role-based prompt provides a more technically relevant and domain-specific response.

---

## 10. Few-Shot Prompting

### Prompt

> Use the following example as a guide:
>
> A flood vulnerability assessment uses parameters such as elevation, slope, rainfall, drainage density, and land use. Each parameter is assigned a weight and combined using GIS weighted overlay analysis.
>
> Now develop a similar GIS-based methodology for seismic vulnerability assessment of multi-storey RC buildings in Chennai City.

### AI-Generated Output

| Parameter | Purpose |
|---|---|
| Building Age | Older buildings may have higher vulnerability |
| Number of Storeys | Influences seismic response |
| Soil Type | Soft soil may increase earthquake effects |
| Construction Quality | Poor quality increases vulnerability |
| Plan Irregularity | Causes uneven seismic response |
| Vertical Irregularity | May increase structural damage |
| Soft Storey | Increases collapse risk |

### Observation

The example helps the AI understand the expected format and methodology.

---

## 11. Step-by-Step Prompting

### Prompt

> Solve the following engineering problem step by step. First identify the seismic vulnerability parameters for RC buildings. Then explain how each parameter can be represented as a GIS layer. Next suggest a scoring and weighting method. Finally, explain how to combine the layers in QGIS.

### AI-Generated Output

**Step 1: Identify Vulnerability Parameters**

- Building age
- Number of storeys
- Soil condition
- Construction quality
- Plan irregularity
- Vertical irregularity
- Soft-storey condition

**Step 2: Prepare GIS Layers**

Each building is represented as a spatial feature in QGIS with attribute information.

**Step 3: Assign Scores**

| Vulnerability Level | Score |
|---|---:|
| Low Risk | 1 |
| Moderate Risk | 2 |
| High Risk | 3 |

**Step 4: Assign Weights**

Important parameters are assigned higher weights based on engineering importance.

**Step 5: Perform GIS Analysis**

Use weighted overlay analysis or a vulnerability index to combine the parameters.

**Step 6: Final Classification**

The final map is classified into:

- Low Vulnerability
- Moderate Vulnerability
- High Vulnerability

### Observation

This technique produces a highly organized and detailed response.

---

## 12. Comparison and Evaluation

| Prompting Technique | Relevance | Accuracy | Completeness | Clarity | Feasibility | Usefulness |
|---|---|---|---|---|---|---|
| Naïve Prompt | Medium | Medium | Low | Medium | Medium | Medium |
| Zero-Shot Prompt | High | High | High | High | High | High |
| Persona Prompt | High | High | High | High | High | Very High |
| Few-Shot Prompt | High | High | Very High | Very High | High | Very High |
| Step-by-Step Prompt | Very High | High | Very High | Very High | Very High | Very High |

---

## 13. Evaluation Based on Quality, Accuracy and Depth

| Technique | Quality | Accuracy | Depth |
|---|---|---|---|
| Naïve Prompt | ⭐⭐ | ⭐⭐ | ⭐⭐ |
| Zero-Shot Prompt | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| Persona Prompt | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| Few-Shot Prompt | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| Step-by-Step Prompt | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |

---

## 14. Analysis and Observations

The naïve prompt produced a basic response but lacked sufficient technical details.

The zero-shot prompt produced a more structured methodology because the requirements were clearly specified.

The persona-based prompt produced more technically relevant suggestions.

The few-shot prompt produced a clearer response because an example guided the AI.

The step-by-step prompt produced the most systematic and detailed response.

---

## 15. Final Selected Prompting Technique

**Step-by-Step Prompting Combined with Persona Prompting**

This technique was selected because it provided:

- Better structure
- Greater completeness
- Clear engineering methodology
- Practical implementation steps
- Higher usefulness
- Better technical relevance

---

## 16. Refined / Final Prompt

> Act as a structural engineer and GIS specialist. Develop a detailed step-by-step methodology for conducting a GIS-based seismic vulnerability assessment of multi-storey reinforced concrete buildings in Chennai City. Identify important building vulnerability parameters, explain the required GIS layers and data sources, suggest a scoring and weighting methodology, and provide a QGIS workflow to generate a final seismic vulnerability map classified into Low, Moderate, and High vulnerability zones.

---

## 17. Engineering Validation

The methodology can be validated using:

- Field survey of selected RC buildings
- Building inventory data
- Rapid Visual Screening (RVS)
- Soil and geological information
- Seismic hazard information

Representative RC buildings can be analyzed to evaluate:

- Base shear
- Storey displacement
- Storey drift
- Natural time period

The GIS vulnerability classification can then be compared with structural analysis results.

---

## 18. Learning Outcome

Through this experiment, students learn:

1. How different prompting techniques affect AI responses.
2. The importance of prompt clarity.
3. How examples improve AI-generated outputs.
4. How role-based prompts provide domain-specific responses.
5. How structured prompts improve completeness and depth.
6. How Generative AI can support engineering project development.

---

## 19. Conclusion

Different prompting techniques produced different levels of response quality.

The **Naïve Prompt** produced a general response, while improved prompts produced more structured, detailed, and useful engineering solutions.

Among the techniques tested, **Step-by-Step Prompting combined with Persona Prompting** provided the best results for this engineering scenario.

This experiment demonstrates that **prompt clarity, context, examples, and structured instructions significantly improve the quality, accuracy, and depth of AI-generated outputs**.

---

## 20. Result

**RESULT: The prompts for the selected engineering problem were executed successfully using different prompting techniques.**

The AI-generated responses were compared and evaluated based on:

- Quality
- Accuracy
- Completeness
- Clarity
- Feasibility
- Usefulness
