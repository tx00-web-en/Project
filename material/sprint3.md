# Sprint 3: Deadline 2025-12-10

<!-- 
- [Before Starting This Sprint](#before-starting-this-sprint)
- [Deliverables](#deliverables)
- [Considerations](#considerations)
- [Assessment Criteria](#assessment-criteria-total-150-points--bonus)

---

# Before Starting This Sprint

After completing two sprints, it’s essential to review key team metrics to optimize the performance for this sprint:

1. **Team Velocity**: Evaluate how much work your team has completed in previous sprints to set realistic goals for this sprint.
2. **Team Capacity**: Assess the availability of your team members for this sprint. Ensure to leave a 10% buffer in your sprint commitment to avoid overcommitting and under-delivering. This buffer allows room for unexpected obstacles or additional tasks.
3. **Workload Distribution**: Review each team member’s workload. Ensure it is balanced and that everyone is contributing effectively. Adjust as needed to ensure fair participation and efficient progress.
4. **Sprint Goal Completion**: Look back at the goals set for previous sprints. Identify what worked, what didn’t, and how you can adapt for this sprint to achieve a more successful outcome.
5. **Sprint Satisfaction**: Conduct a brief team survey or discussion to gauge overall satisfaction with the previous sprints. Use this feedback to improve team dynamics, communication, and productivity.

> *Note*: Additional metrics such as cycle time, defect rate, and lead time can provide further insights, but they are *out of the scope* of this sprint. You can explore them at [links](#links) for more information.

---

## Deliverables

1. **Front-End Code**:
   - Submit the completed code related to the front-end of your application. Ensure the code is clean, follows best practices, and includes appropriate comments for clarity.
   - Incorporate responsive design and optimize the user interface for accessibility and usability.

2. **Back-End Code**:
   - Submit all back-end code, including the implemented API, database interactions, and any server-side logic.
   - Include thorough testing for each API endpoint to ensure robustness and reliability.

3. **Sprint Ceremony Insights**:
   - **Daily Scrum**: Document key points from your daily stand-ups. Highlight what was accomplished, what is planned for the next day, and any blockers encountered.
   - **Sprint Review**
   - **Sprint Retrospective**: Reflect on team performance, sprint metrics.
   - More on [Scrum](https://www.scrum.org/learning-series/what-is-scrum/)

4. **Team Contributions**:
   - Clearly outline each team member's contributions, including coding and testing. Use commit history and self-assessments as evidence.

5. **Presentation**:
   - **Prototype Showcase**: Begin by demonstrating the prototype developed during Sprint 1. Highlight key changes or enhancements since then.
   - **Progress Discussion**: Discuss the objectives of Sprint 3, challenges faced, solutions implemented, and the overall progress made. Focus on how the sprint outcomes align with your original prototype and goals.
   - Here’s a [template for a 10-12-minute presentation](./ppt-template3.md) to help you structure your content effectively.

6. **Self-assessment** of the backend code using your favorite LLM.

7. **Self-assessment** of the frontend code using your favorite LLM. 
    - You can use the [following template](./template.md).

---

## Considerations

> Suggested Workflow for Weeks 5-7 and the Start of Week 8:

### **Week 5: Connecting Front-End and Back-End**

1. **Conduct Sprint Planning**  
2. By the end of this week, you should be able to connect the front-end React app to the back-end API. Up to now, you have worked on these components separately.  

   - **Reference Material**:  
     - [MERN Stack Crash Course Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iJ_KkrkBZWZRHVwnzLIoUE): Videos 1–7 review backend concepts, while videos 8–10 focus on connecting the React app to the backend.  
     - [Source Code on GitHub](https://github.com/iamshaunjp/MERN-Stack-Tutorial): Use this repository as a reference.

### **Week 6: Implementing Authentication**

By the end of this week, you should have user authentication fully integrated into your application:

- **Back-End**:
  - Design and implement a user registration and login system.
  - If needed, Implement role-based access control to manage permissions for different user roles (e.g., admin vs. standard user). This helps restrict access to certain functionalities based on user privileges.
- **Front-End**:
  - Integrate JWT (JSON Web Token) authentication for secure communication between the client and server.
  - Use custom hooks.
- **Deployment**:
  - Deploy the back-end. 
  
### **Week 7: Front-End Enhancements and Backend Testing**

- **Back-End Testing**:
  - Conduct comprehensive integration testing for the back-end, ensuring API endpoints function correctly. Aim for high testing coverage to maintain code quality and prevent future issues.
- **Deployment**:
  - Deploy both the front-end and back-end components. 

### **Week 8:**

- **Bonus (15 points)**:  If you manage to create documentation **`for the API`**.
- (**Bonus 15points**) If you manage to introduce `useContext()`. 

---
 
## Assessment Criteria (Total: 150 Points + Bonus)

Your performance for Sprint 3 will be evaluated as follows:

### 1. **Artifacts (90 Points)**
   - Quality and completeness of both front-end and back-end code.
   - **Breakdown**:
     - **Front-End Code (45 Points)**: Self-assessment of code quality (15), functionality and UI responsiveness (30).
     - **Back-End Code (45 Points)**: Self-assessment of code quality (15), testing and functionality  (30).

### 2. **Adherence to Scrum Process (30 Points)**
   - Participation in Scrum ceremonies and adherence to Scrum practices.
   - **Breakdown**:
     - **Daily Scrums (10 Points)**: Consistent participation in daily stand-ups.
     - **Sprint Review (10 Points)**: Clear presentation of accomplishments.
     - **Retrospective Insights (10 Points)**: Reflective analysis, actionable improvements, and team reflection on sprint satisfaction.

### 3. **Group Presentation (30 Points)**
   - Delivery, clarity, and teamwork during the 10-12-minute presentation.
   - **Breakdown**:
     - **Clarity and Structure (10 Points)**: Clear explanation, logical flow, and effective communication.
     - **Coverage of Sprint Outcomes (10 Points)**: Highlighting progress, addressing goals, showing functionality.
     - **Team Collaboration (10 Points)**: Demonstration of equal participation, team coordination, and handling of Q&A.

### 4. **Alignment with Sprint 1 Prototype**
   - Alignment of current sprint outcomes with the original Sprint 1 prototype.
   - **Breakdown**:
     - **Functional Alignment**: Features implemented match the planned functionality.
     - **Design/Visual Alignment**: Consistency with the original design and UI elements.

### **Important Notes:**
- **Equal Contributions**: All team members must contribute equally. Unequal contributions will result in a penalty for those who do not participate fully.
- **On-Time Submission**: Late submissions incur penalties, as adherence to deadlines is critical in Agile environments.
- **Team Communication**: Effective collaboration is key. Ensure transparency and active involvement of all members.
- **Troubleshooting**: Be proactive in solving technical challenges. Problem-solving is a crucial skill in web development.

---

## Summary of Point Allocation:

| **Criteria**                              | **Points** |
|-------------------------------------------|------------|
| Artifacts of Sprint 3                     | 90 Points |
| Adherence to Scrum Process                | 30 Points  |
| Group Presentation                        | 30 Points  |
| Alignment with Sprint 1 Prototype         | Mandatory  |
| **Total**                                 | **150 Points** |
| **Bonus**                                 | **30 Points** |

### **Tips for Meeting the Criteria:**

- **Artifacts**: Ensure your code is clean and efficient. The UI should be visually appealing, user-friendly, and and include self-assessment of your code.
- **Scrum Process**: Conduct daily scrums consistently, hold meaningful sprint reviews, and provide actionable insights during retrospectives.
- **Member Contributions**: Document individual contributions thoroughly, using commit history and retrospectives to show evidence of collaboration.
- **Presentation**: Prepare to clearly present progress, highlight challenges, and demonstrate how your team addressed them.
- **Alignment**: Regularly review your prototype to ensure your sprint outcomes closely match in both functionality and design.

---

## Links

- [Scrum Metrics 101 | Atlassian](https://www.atlassian.com/agile/scrum/scrum-metrics) 
- [11 Scrum Metrics and Their Value to Scrum Teams - Sealights](https://www.sealights.io/software-development-metrics/11-scrum-metrics-and-their-value-to-scrum-teams/)
- [The Essentials of Scrum Metrics: A Comprehensive Guide](https://deeprojectmanager.com/scrum-metrics/)
- [Excel templates to help you manage and visualize scrum metrics](https://academy.agiledigest.com/template/scrum-metrics-excel-template/)

-->





<!-- - API documentation. -->
<!--
- **Alignment with Sustainable Development Goals**:
  - Evaluate how your project aligns with the [Sustainable Development Goals at Metropolia University](https://www.metropolia.fi/kestavakehitys/en/Home). Consider aspects like accessibility, sustainability, and societal impact.

 -  Scrum Metrics – Excel Template - Agile Digest. https://agiledigest.com/scrum-metrics-excel-template/ 



 - **Front-End**:
  - Introduce `useContext()` for prop drilling avoidance, enhancing your app’s management.  
  - `useReducer()` for managing complex state logic 
 
 ---


> **When a group is making a sprint presentation, members from two other groups will be required to ask questions to the presenting group.**

-->