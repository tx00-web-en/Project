# Sprint 2

**Deadline: September 17, 2026**

## Sprint 2 Goal

The goal of Sprint 2 is to develop the **frontend and backend of your application independently** and prepare them for integration in Sprint 3.

During this sprint:

* The **frontend team** will develop the React application, including its pages, components, navigation, forms, and responsive design.
* The **backend team** will develop the server-side application following the MVC structure introduced in class.
* The frontend and backend teams will **agree on the interface between them**, including the API endpoints and the JSON data structures that will be used when the application is connected.
* The frontend and backend **will not be connected during Sprint 2**.
* The backend will initially use mock/array data and will later be refactored to use MongoDB/Mongoose when these technologies are introduced.
* Authentication will **not** be implemented during this sprint.
* AI is **optional**. Groups that choose to include AI will develop the relevant backend functionality when it is covered in class.

> **Important:** This document is a **student-facing overview of Sprint 2, not the complete Sprint 2 specification**. More detailed instructions, examples, common requirements, and guidance will be provided during the two class meetings dedicated to Sprint 2.

---

# Two Important Things NOT to Do

Please pay particular attention to the following:

### 1. Do not deliver more than what is requested for Sprint 2.

Do not implement functionality that belongs to Sprint 3.

For example, **do not**:

* connect the frontend to the backend;
* implement real authentication;
* implement JWT, sessions, or password authentication;
* implement Swagger/OpenAPI documentation;
* implement Supertest/API automated testing;
* implement other Sprint 3 functionality before it is requested.

The purpose of Sprint 2 is to build the frontend and backend **independently** and prepare them for integration later.

### 2. Do not introduce technologies that have not been covered in the course without full group agreement.

If your group wants to use a technology, library, framework, or tool that has not been covered in the course, **all group members must agree to its use before it is introduced into the project**.

---

# Deliverables

## 1. Front-End Code

Submit all code related to the frontend development of your application.

The frontend should include, as appropriate:

* React components;
* the main pages of the application;
* navigation and routing;
* a working navbar;
* responsive design;
* lists of products/services or other application data;
* forms required by the application;
* login and registration pages;
* appropriate styling;
* mock/static data where backend data would normally be used.

The frontend should provide a functional representation of the application, even though it is **not connected to the backend yet**.

---

## 2. Back-End Code

Submit all code related to the backend development of your application.

The backend should follow the MVC concepts introduced in class and should include the appropriate:

* server setup;
* models/data structures;
* routes;
* controllers;
* middleware;
* CRUD functionality;
* mock/array data;
* MongoDB/Mongoose implementation when covered in class;
* error handling and other concepts covered during the sprint.

### Data persistence

During the first part of the sprint, you will work with mock/array data.

After MongoDB and Mongoose are introduced in class next week, you will **refactor the data model/persistence layer** to use MongoDB/Mongoose.

The goal is to make this transition with as little modification as possible to the rest of your backend application.

### API testing

During Sprint 2, API endpoints should be tested using **Postman** or similar alternative, as demonstrated in class.

> **Note:** Automated API testing and API documentation are part of Sprint 3, and should not be implemented during Sprint 2.

---

## 3. Frontend/Backend Interface

Although the frontend and backend will not be connected during Sprint 2, the two teams must **agree on the interface that will be used when they are connected in Sprint 3**.

At a minimum, the teams should agree on:

* the required API endpoints;
* HTTP methods;
* the data required by each endpoint;
* the JSON structure of requests;
* the JSON structure of responses;
* the data fields and their expected types.

For example:

```text
GET /api/products

Response:
[
  {
    "id": 1,
    "name": "Laptop",
    "price": 1200
  }
]
```

The frontend team can use mock data that follows the agreed structure while developing the React application.

The backend team can independently implement the corresponding API endpoints.

> **Important:** Defining the interface does **not** mean connecting the frontend and backend. The actual integration will take place in Sprint 3.

---

## 4. Sprint Ceremony Insights

Share your team's insights and experiences from the following Scrum ceremonies:

### Daily Scrum

Reflect on your team's Daily Scrums, including how they helped the team:

* communicate progress;
* identify blockers;
* coordinate work;
* adapt the plan when necessary.

### Sprint Review

Describe what your team completed during the sprint and demonstrate the results.

### Sprint Retrospective

Reflect on your sprint using the **4Ls format**:

* **Liked** – What did you enjoy?
* **Learned** – What did you learn?
* **Lacked** – What was missing?
* **Longed for** – What would you have liked to have?

Consider both factual and emotional aspects of your experience.

More information about the 4Ls format is available [here](https://www.teamretro.com/retrospectives/).

More information about Scrum is available [here](https://www.scrum.org/learning-series/what-is-scrum/).

---

## 5. Team Contributions

Clearly document the contribution of **each team member** during Sprint 2.

Your documentation should make it possible to understand:

* what each member worked on;
* which frontend/backend tasks they contributed to;
* how they collaborated with other team members;
* any important responsibilities they took during the sprint.

Evidence may include commit history, pull requests, task boards, sprint activities, and other relevant project evidence.

---

## 6. Group Presentation

Your group will give a **10–12-minute presentation**.

The presentation should:

1. Begin by briefly showcasing the prototype developed during Sprint 1.
2. Explain what has been implemented during Sprint 2.
3. Demonstrate the progress of both the frontend and backend.
4. Explain how the frontend and backend teams have defined their interface.
5. Explain what remains to be completed in Sprint 3.
6. Reflect on challenges and important lessons learned during the sprint.

A [10–12-minute presentation template](./ppt-template2.md) is available to help you structure your presentation.

---

## 7. Frontend Code Self-Assessment Using an LLM

Each team member must complete a self-assessment of the **frontend code they contributed** using an LLM of their choice.

Use the provided [self-assessment template](./template.md).

The purpose of this activity is to help you:

* critically review your own code;
* identify possible problems or improvements;
* learn from the feedback provided by an LLM;
* improve the quality of your code.

Remember that an LLM is a **reviewing and learning tool**, not an authority. You are responsible for evaluating its suggestions and deciding which changes are appropriate.

---

## 8. Backend Code Self-Assessment Using an LLM

Each team member must complete a self-assessment of the **backend code they contributed** using an LLM of their choice.

Use the provided [self-assessment template](./template.md).

You should critically evaluate the feedback and identify improvements that can make your code clearer, more maintainable, efficient, or robust.

---

# Scope of Sprint 2

Sprint 2 is intentionally divided into **two parallel development tracks**.

### Frontend

The frontend team develops the React application independently.

```text
React
  ↓
Components
  ↓
Pages
  ↓
Routing
  ↓
Forms
  ↓
Mock/Static Data
```

### Backend

The backend team develops the server independently.

```text
Express
  ↓
Routes
  ↓
Controllers
  ↓
Models / Data
  ↓
Mock/Array Data
  ↓
MongoDB/Mongoose
```

### Frontend ↔ Backend

The teams **define the interface**, but do not connect the two systems.

```text
Frontend                  Backend
   │                         │
   │                         │
   │   Agreed API Interface  │
   │─────────────────────────│
   │                         │
   X      NO CONNECTION      X
```

The actual connection between the frontend and backend will take place in **Sprint 3**.

Integration activities will also take place during the Coding Marathons and the full-stack activities in weeks 7 and 8.

---

# Suggested Workflow

The following provides a general direction for the sprint. More detailed instructions and common requirements will be provided during the two Sprint 2 class meetings.

## Week 3–4

### Sprint Planning

Establish your Sprint Goal and decide:

* what needs to be completed;
* which team members will work on which tasks;
* which functionality belongs to the frontend;
* which functionality belongs to the backend;
* what interface the frontend and backend will need.

### Frontend

Begin developing:

* the main React components;
* application pages;
* navbar and navigation;
* routing;
* responsive layouts;
* lists of products/services or other application data;
* mock/static data.

If your application is based on an existing HTML template, convert the HTML into React components following the approach demonstrated in class.

You may use vanilla CSS or CSS libraries covered/allowed in the course.

### Backend

Begin developing the backend using the MVC structure introduced in class.

Develop:

* mock/array data;
* models/data structures;
* controllers;
* routes;
* middleware;
* CRUD functionality;
* the API endpoints required by your application.

Test your API endpoints using Postman.

---

# Week 4–5

### Frontend

Continue developing and refining the frontend.

Complete:

* application routing;
* required pages;
* forms;
* login and registration interfaces;
* responsive design;
* mock data and application interactions.

### Login and Registration

Login and registration are **simulations only** during Sprint 2.

For example, submitting a form may produce:

```text
Login successful
```

or

```text
Registration successful
```

in the console or through an appropriate UI message.

**Do not implement real authentication during Sprint 2.**

Real authentication will be implemented in Sprint 3.

### Backend

After MongoDB/Mongoose is introduced in class:

* refactor the existing data model/persistence approach;
* replace the appropriate array/mock-data operations with MongoDB/Mongoose;
* keep the rest of the application structure as stable as possible;
* continue testing your endpoints with Postman.

### AI

AI is **optional**.

If AI is a feature of your application, you will receive guidance on implementing the AI functionality when it is covered in class.

The AI functionality should be developed on the backend as appropriate.

The frontend does **not** need to connect to the AI endpoint during Sprint 2.

---

# Assessment Criteria for Sprint 2

**Total: 100 points**

## 1. Sprint 2 Artifacts — 50 Points

The quality and completeness of the artifacts produced during the sprint.

| Artifact                                       | Points |
| ---------------------------------------------- | -----: |
| Front-End Code                                 |     25 |
| Back-End Code + AI-related Code, if applicable |     25 |
| **Total**                                      | **50** |

Assessment will consider factors such as:

* completeness;
* functionality;
* code quality;
* appropriate use of concepts taught in class;
* alignment with the Sprint 1 prototype.

---

## 2. Adherence to Scrum Process — 25 Points

How effectively your team followed the Scrum framework during the sprint.

This includes:

* participation and effectiveness of Daily Scrums;
* effectiveness of the Sprint Review;
* quality of Sprint Retrospective insights;
* ability to communicate progress and blockers;
* collaboration and adaptation during the sprint.

---

## 3. Group Presentation — 25 Points

The quality of the **10–12-minute group presentation**.

Assessment will consider:

* clarity and structure;
* explanation of Sprint 2 outcomes;
* demonstration of progress;
* explanation of next steps;
* team collaboration and participation.

---

## 4. Alignment with Sprint 1 Prototype — Mandatory

Sprint 2 work must remain aligned with the original prototype developed during Sprint 1.

This includes both:

* **Functional alignment** – the implemented functionality should correspond to the application's intended functionality.
* **Design/visual alignment** – the frontend should remain consistent with the prototype's intended design and user experience.

Alignment with the Sprint 1 prototype is a **mandatory requirement** and is considered as part of the assessment of the Sprint 2 artifacts.

If your application has changed significantly from the original prototype, the change should be explained and justified.

---

# Important Notes

### Equal Contribution

All team members are expected to contribute meaningfully to Sprint 2.

Unequal contributions may result in a penalty for a member who does not participate fully.

### Scope

Do not rush to implement Sprint 3 functionality.

A successful Sprint 2 is **not** the one that implements the most features. It is the one that successfully completes the Sprint 2 objectives while maintaining good code quality and following the Scrum process.

### Submission

All deliverables must be submitted by:

**September 17, 2026**

Late submissions will incur penalties according to the course policy.


---

## **Useful Links**

**CSS Review:**
- **Flexbox**: [Flexbox Guide](https://internetingishard.netlify.app/html-and-css/flexbox/), [Flexbox Tutorial](https://youtu.be/3YW65K6LcIA)
- **Responsive Design**: [Responsive Design Guide](https://internetingishard.netlify.app/html-and-css/responsive-design/)

**Tailwind CSS:**
- [Tailwind CSS From Scratch - Learn by Building Projects](https://metropolia.finna.fi/Record/nelli15.5680000000060713?sid=4846325380)
- [Book: Tailwind CSS, Ivaylo Gerchev](https://learning.oreilly.com/library/view/tailwind-css)

**CSS Libraries:**
- [Top CSS Frameworks for React in 2023](https://www.lambdatest.com/blog/best-css-frameworks-for-react/)
- [23 Best CSS Frameworks for React](https://dev.to/scofieldidehen/23-best-css-frameworks-for-react-in-2023-4pcg)
- [Best CSS Frameworks for React](https://www.codewalnut.com/learn/best-css-frameworks-for-react)

**Scrum:**
- [Scrum Metrics 101 | Atlassian](https://www.atlassian.com/agile/scrum/scrum-metrics)
- [Scrum](https://www.scrum.org/learning-series/what-is-scrum/)



---

# Sprint 2 at a Glance

|                               | Sprint 2                  |
| ----------------------------- | ------------------------- |
| Frontend                      | Build                     |
| Backend                       | Build                     |
| CRUD                          | Build                     |
| Mock/Array Data               | Initially                 |
| MongoDB/Mongoose              | After taught in class     |
| Frontend Routing              |                           |
| Login/Register UI             | Simulation                |
| API Interface Agreement       |                           |
| Postman API Testing           |                           |
| AI                            | Optional                  |
| AI Backend Functionality      | If applicable and covered |
| Scrum Ceremonies              |                           |
| LLM Code Self-Assessment      |                           |
| Presentation                  |                           |

<!-- - For Sprint 3 (**not sprint 2**), the use of Scrum metrics will be part of the assessment criteria. Please refer to the links provided for more information. -->


<!-- When a group is making a sprint presentation, members from two other groups will be required to ask questions to the presenting group. -->