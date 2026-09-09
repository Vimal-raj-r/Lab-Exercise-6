# UX Design Core Techniques: A Practical Guide

### Name: VIMALRAJ R
### Reg no: 212223040242

## 1. Solution Ideation (Crazy 8s)

**Problem:** Booking an appointment in a hospital app is slow and confusing.

### 🎯 Aim
To rapidly generate a high volume and wide variety of ideas to solve a specific problem, pushing past the most obvious solutions.

### ⚙️ Algorithm (Process)
1.  **Define the Problem:** Clearly state the user problem (e.g., "Users are frustrated by the confusing hospital appointment booking process").
2.  **Prepare Materials:** Get a single sheet of paper and a pen/marker.
3.  **Fold:** Fold the paper in half three times to create 8 sections.
4.  **Set Timer:** Set a timer for 8 minutes.
5.  **Ideate:** Sketch or write one distinct idea in each of the 8 boxes. The goal is one idea per minute.
6.  **No Filtering:** Focus on quantity, not quality. Do not erase or second-guess. Capture all ideas, even "bad" or "crazy" ones.
7.  **Present & Discuss:** After 8 minutes, share the ideas with the team.

### 📤 Output
A sheet of paper filled with 8 distinct, low-fidelity solution sketches or notes.

**Example Ideas:**
1.  AI chatbot to book the appointment.
2.  Symptom-first triage (tap on a body part).
3.  "Book Again" quick button for past doctors.
4.  Scan insurance card to auto-filter in-network doctors.
5.  "Save My Spot" virtual queue for urgent care.
6.  Calendar-first view showing the user's available times.
7.  Family profiles to easily book for a child or parent.
8.  Visual availability map (a week at a glance).

### 🏆 Result
A wide pool of creative and diverse solutions. This breaks the team out of rigid thinking and provides multiple starting points for prototyping and testing.

---

## 2. Creating User Stories

**Context:** Writing requirements for a new application.

### 🎯 Aim
To define a feature or requirement from the end-user's perspective. It anchors the team's work in user value, answering *who*, *what*, and *why*.

### ⚙️ Algorithm (Process)
1.  **Identify the Persona:** Who is the user? (e.g., a new user, a student, a busy professional).
2.  **Identify the Goal:** What does the user want to *do*? (e.g., sign up, find information, buy a product).
3.  **Identify the Benefit:** What is their underlying *motivation* or desired outcome? (e.g., to save time, to stay on budget, to get a workout plan).
4.  **Write the Story:** Combine these elements into the standard format:
    > "As a [user], I want to [goal], so that [benefit]."

### 📤 Output
A list of user stories, which form the project's backlog.

**Example Stories:**
```

1.  As a new user of a fitness app, I want to go through a simple setup wizard, so that the app can recommend a relevant workout plan for me.

2.  As a budget-conscious student, I want to see the total cost (including fees) before the final checkout page, so that I can easily check if I am staying within my budget.

3.  As a busy professional, I want to receive a daily email summary of my high-priority tasks, so that I can plan my day effectively.

4.  As a visually impaired user, I want the news app to support my phone's text-to-speech function, so that I can listen to the articles.

5.  As a parent, I want to filter product reviews by "verified purchaser," so that I can trust the feedback and make an informed decision.

<!-- end list -->

```

### 🏆 Result
A clear, user-centric backlog that ensures the development and design teams understand the *purpose* of every feature they build.

---

## 3. Creating Scenarios

**Context:** Using a user story to explore its real-world application.

### 🎯 Aim
To provide rich, narrative context to a user story. A scenario explores the user's environment, emotional state, and the sequence of events, helping to build empathy and uncover potential design challenges.

### ⚙️ Algorithm (Process)
1.  **Select a User Story:** Choose one user story to focus on (e.g., the "budget-conscious student" from above).
2.  **Define Context:** Establish the *who, what, where, when,* and *why*.
3.  **Include Emotion:** Describe the user's feelings (e.g., stressed, tired, anxious, hopeful).
4.  **Narrate the Task:** Write a short story describing the user's journey as they attempt to complete their goal. Include the *trigger* (what starts the process) and the *outcome*.

### 📤 Output
A short, descriptive narrative paragraph.

**Example Scenario (for User Story #2):**
> **User:** Alex, a 20-year-old college student.
> **Environment:** It's 8:00 PM on a Tuesday, and Alex is in their dorm room studying for a midterm. The dining hall is closed.
> **Narrative:**
> Alex is **stressed** from studying and **hungry**. They feel **anxious** about their bank account, which only has $20 left until Friday. They open a food delivery app (the *trigger*) to find something cheap. They find a taco place with a $10 special and add it to their cart. They feel **frustrated** as they can't see the total cost. They click "Checkout," and after adding a tip, they finally see the real total is $19.75 due to hidden fees. **Annoyed**, Alex abandons the order, closes the app, and decides to just eat instant noodles.

### 🏆 Result
A shared understanding and deep empathy for the user's real-world context. This helps designers create solutions that address the user's emotional state and environment, not just the task itself.

---

## 4. Flow Diagrams / Flow Mapping

**Task:** Mapping the process of ordering food via an app.

### 🎯 Aim
To visually map the steps a user takes to complete a specific task, identifying decision points, actions, and screens along the way.

### ⚙️ Algorithm (Process)
1.  **Define the Task:** Set a clear start and end point (e.g., Start: "Opens app," End: "Order confirmation screen").
2.  **Use Standard Symbols:**
    * **Ovals:** Start / End points.
    * **Rectangles:** Actions or steps (e.g., "Select restaurant").
    * **Diamonds:** Decision points (e.g., "Is user logged in?").
    * **Arrows:** Show the path and direction.
3.  **Map the Flow:** Start at the beginning and map out every step and decision.
4.  **Consider Branches:** Map out the different paths a user can take (e.g., "Log in" vs. "Continue as guest").
5.  **Review and Refine:** Trace the flow to find any logical gaps, dead ends, or overly complex paths.

### 📤 Output
A user flow or task flow diagram.



**Simplified Flow Example:**
> (Start) → [Open App] → (Decision: Logged in?) → [Enter Address] → [View Restaurants] → [Select Restaurant] → [Browse Menu] → [Add Item to Cart] → (Decision: Add more?) → [Go to Cart] → [Proceed to Checkout] → [Confirm Payment & Address] → [Place Order] → (End)

### 🏆 Result
A "blueprint" of the user's journey. It identifies bottlenecks, redundant steps, and opportunities for simplification *before* any screens are designed, saving time and development effort.

---

## 5. Information Architecture (IA)

**Context:** Organizing the content for a university website.

### 🎯 Aim
To organize, structure, and label content in a way that is intuitive for users, allowing them to find information and complete tasks easily.

### ⚙️ Algorithm (Process - Open Card Sort)
1.  **Inventory Content:** List all major pages and content pieces on individual "cards" (e.g., "Tuition Fees," "Course Catalog," "Basketball Schedule," "Dormitory Info").
2.  **Recruit Users:** Find participants who represent the target audience (e.g., prospective students, current students).
3.  **Conduct the Sort:** Give a user the shuffled stack of cards. Ask them to sort the cards into groups that make sense *to them*.
4.  **Label the Groups:** After they've created their groups, ask them to create a name or label for each group (e.g., "Money Stuff," "Student Life").
5.  **Analyze:** Repeat with several users. Look for common patterns, popular group names, and items that are frequently grouped together.

### 📤 Output
* **From Card Sort:** Photos or screenshots of the user-defined groups and their labels.
* **From Analysis:** A **Site Map**, which is the resulting hierarchical structure for the website's navigation.

**Example Site Map (Resulting Structure):**
```

Home
├── Admissions & Aid
│   ├── Apply for Undergrad
│   ├── Tuition Fees
│   ├── Financial Aid Office
├── Academics
│   ├── Course Catalog
│   ├── Professor Directory
│   ├── Library Hours
├── Campus Life
│   ├── Dormitory Info
│   ├── Student Clubs
│   ├── Basketball Schedule
├── About
│   ├── University History
│   ├── Campus Map
│   ├── Alumni Donations

```

### 🏆 Result
A user-validated navigation and content structure. This ensures the final product's layout is based on the user's mental model, not the organization's internal structure, which dramatically improves usability.
