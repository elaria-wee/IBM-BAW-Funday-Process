# 🎉 Company Fun Day & Game Night

### IBM Business Automation Workflow (BAW) — Business Process Project

## 📌 Project Overview

**Company Fun Day & Game Night** is a business process project developed as part of the **NTI HireReady Program — Application Development & Integration Track**.

The project focuses on designing a structured workflow for managing company event requests, from the initial employee submission through reviews, approvals, booking activities, and final event confirmation.

The main challenge was translating detailed business requirements into a workflow that handles different scenarios, conditional decisions, parallel activities, and approval rules.

## 🎯 Project Objectives

* Organize the company event request process.
* Define responsibilities for the different departments involved.
* Automate review and approval stages.
* Apply business rules to determine which reviews and approvals are required.
* Coordinate multiple activities before confirming an event.
* Ensure that the process follows the defined business requirements.

## 🔄 Workflow Overview

The process follows these main stages:

1. **Event Request Submission**
   An employee submits a request to organize a company event.

2. **Department Manager Review**
   The department manager reviews the request and decides whether it can proceed.

3. **Parallel Reviews**
   Finance and Event Operations review the request. A Safety review is also initiated when the event meets the defined safety conditions.

4. **Conditional Safety Review**
   A Safety review is required when the event is outdoors, has more than 100 attendees, or includes a mechanical ride.

5. **Review Results Evaluation**
   The process evaluates the completed reviews and determines whether the request can proceed, must be returned for modification, or should be rejected.

6. **Director Approval**
   Requests with a total estimated cost exceeding 100,000 require Department Director approval.

7. **Booking Activities**
   The process creates the required booking activities and coordinates them according to the event requirements.

8. **Final Event Confirmation**
   Once the required approvals and booking activities are complete, the process proceeds to final event confirmation.

## 🧩 Main Business Rules

| Business Rule        | Description                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Safety Review        | Required for outdoor events, events with more than 100 attendees, or events involving a mechanical ride.                   |
| Director Approval    | Required when the total estimated event cost exceeds 100,000.                                                              |
| Conditional Bookings | Only the booking activities required for the specific event are created.                                                   |
| Parallel Reviews     | Finance and Event Operations reviews can proceed in parallel.                                                              |
| Review Decisions     | The process evaluates review outcomes to determine the next step.                                                          |
| Review Priority      | If rejection and return-for-modification decisions occur together in the completed review stage, rejection takes priority. |

*Note: The cost threshold is expressed in the units defined by the project requirements.*

## 👥 Main Roles

The workflow involves the following participants:

* **Employee** — Submits the event request.
* **Department Manager** — Reviews the request.
* **Finance** — Evaluates financial aspects of the event.
* **Event Operations** — Reviews operational requirements.
* **Safety** — Reviews events that meet the defined safety conditions.
* **Department Director** — Approves requests that exceed the specified cost threshold.

## 🛠️ IBM BAW Concepts Applied

This project explores several important workflow automation concepts:

* Business process modeling
* User tasks and service activities
* Conditional routing and decision logic
* Exclusive gateways
* Parallel gateways and concurrent activities
* Business rules and approval conditions
* Process coordination and completion
* Translating business requirements into workflow logic

## 📸 Project Documentation & Screenshots

This repository section showcases the project requirements document and screenshots illustrating the workflow.

The documentation provides insight into the expected business behavior, while the screenshots help visualize the process design and implementation.

> **Project walkthrough video:** Add your video link here if available.

## 📚 Key Learnings

Working on this project helped me better understand that business process automation requires more than designing a sequence of tasks.

It involves analyzing business requirements, identifying decision points, handling different scenarios, coordinating parallel activities, and ensuring that every process path follows the intended business rules.

This project strengthened my understanding of **IBM Business Automation Workflow (BAW), Business Process Management (BPM), and workflow automation**.

## 🙏 Acknowledgements

My sincere thanks to the engineers who guided us throughout the NTI HireReady training, shared their expertise, and supported us during the practical work.

Special thanks to my friend for the collaboration, teamwork, and support throughout this project. I'm grateful for the opportunity to learn and grow together.

## 👩‍💻 Author

**Elaria Basher**
Computer Science Graduate | ECM & BPM | IBM BAW | Full Stack Development

* GitHub: [elaria-wee](https://github.com/elaria-wee)

---

*This repository documents a training project and its business process requirements. Refer to the included artifacts and screenshots to determine which implementation components are available.*
