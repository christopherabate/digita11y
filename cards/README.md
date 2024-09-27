# Digita11y Cards
[A card based game about accessibility](https://christopherabate.github.io/digita11y/cards/)

# Card Game: Web Accessibility

## Game Objective
The goal is to become the player with the fewest invalid criteria by the end of the game while progressing through the various stages of a web development project. Participants must use tools and collaborate to overcome accessibility criteria while considering the specific responsibilities related to their roles.

---

## Materials

### 1. Disability Cards (7 cards)
- **Visual:** Difficulties perceiving visual information, including individuals with blindness, vision impairments, or color blindness.
- **Auditory:** Inability to hear or understand audio content, often affecting deaf or hard-of-hearing individuals.
- **Motor:** Limitations in using limbs, which can affect interaction with devices like mice or keyboards.
- **Psychological:** Difficulties related to mental disorders, which can impact concentration and comprehension.
- **Intellectual:** Challenges in understanding information and instructions, often associated with cognitive or learning disabilities.
- **Dyslexia:** Includes specific difficulties such as dyslexia, dyscalculia, or dyspraxia, affecting reading, writing, or coordination.
- **Chronic Illness:** Chronic or disabling health conditions that may impact access to information or interaction with digital content.

### 2. Tool Cards (9 cards)
- **Syntax Checker:** Tool that identifies and corrects errors in code, thus facilitating content accessibility.
- **Continuous Testing:** Ongoing evaluation of accessibility throughout the project.
- **Monitoring:** Tool for tracking accessibility changes during development.
- **Contrast Checker:** Tool that analyzes the contrast between text and background to ensure optimal readability.
- **Browser Extension:** Tools integrated into browsers to assist in evaluating accessibility.
- **Scripted Bookmark:** Tool that allows saving accessibility check points in the code.
- **Code Inspector:** Tool that examines a page’s source code to identify accessibility issues.
- **Keyboard:** Essential tool for users with motor difficulties, enabling navigation without a mouse.
- **Assistive Technology:** Various tools (screen readers, alternative pointing devices, etc.) that facilitate access to digital content.

### 3. Criteria Cards (14 cards)
- **Contrast:** The contrast between text and background must be sufficient to ensure readability (WCAG 1.4.3).
- **Name, Role, and Value:** Interactive elements must have appropriate names, roles, and values to be accessible via assistive technologies (WCAG 4.1.2).
- **Information and Relationships:** Content structure must be correct, allowing users to understand the relationships between different elements (WCAG 1.3.1).
- **Non-Text Content:** Images and other non-text content must have alternative descriptions (WCAG 1.1.1).
- **Focus Order:** The order in which elements receive focus must follow a logical order for smooth navigation (WCAG 2.4.3).
- **Keyboard:** All elements must be accessible via keyboard without requiring the use of a mouse (WCAG 2.1.1).
- **Focus Visibility:** The focus of an interactive element must be clearly visible to users (WCAG 2.4.7).
- **Non-Text Content Contrast:** Images and graphics must meet contrast standards to ensure readability (WCAG 1.4.11).
- **Use of Color:** Information should not be conveyed solely through color (WCAG 1.4.1).
- **Logical Sequential Order:** Content must be presented in an order that facilitates understanding (WCAG 3.2.1).
- **Labels or Instructions:** Forms must contain clear labels and instructions for each field (WCAG 3.3.2).
- **Bypass Blocks:** Users should be able to bypass repetitive blocks of content to navigate more quickly (WCAG 2.4.1).
- **Page Title:** Each page must have a clear title that describes its content (WCAG 2.4.2).
- **Language of the Page:** The primary language of the page must be specified to assist users of assistive technologies (WCAG 3.1.1).

### 4. Player Tokens (Roles)
- **Project Manager (PM)**
- **Developer (Dev)**
- **Designer**
- **Expert**
- **Manager**
- **Tester**

### 5. Game Board
Representing the different stages of a project (with numbered spaces from 1 to N).

---

## Game Rules

### 1. Setup
- Each player chooses a role from the list (PM, Dev, Designer, Expert, Manager, Tester).
- The dealer places the Tool and Criteria cards in the center of the board.

### 2. Turn Sequence
- Players take turns moving one space on the board and drawing a Criteria card.
- Players must manage their Criteria card based on the options available:
  - **Use a Tool:** If the player has a tool to counter the criteria, they can discard it into the forge and advance one step.
  - **Draw a Tool:** The player can choose to draw a tool. If they obtain the appropriate tool, they can use it to advance.
  - **Take a Tool from the Forge:** The player can choose a tool from the forge but must wait until their next turn to use it.
  - **Ask for Help from an Expert:** If the player cannot find the necessary tool, they can ask another player for assistance. If that player has the required tool, they can give it in exchange for one step of advancement.

### 3. Second to Last Step – The Recipe
- During this step, the player in the recipe phase can continue to draw cards or ask for expert opinions without being required to advance.

### 4. Final Step – The Audit
- The player draws a Disability card and keeps it hidden.
- Once all players reach this step, each reveals their Disability card and the Criteria cards they possess.
- If at least one invalid criterion corresponds to a player's Disability, that player has lost.

### 5. Winner
- The winning player is the one with the fewest invalid criteria at the end of the game.

---

## Role Talents

- **Developer (Dev):** Has the ability to correct a criterion of their choice at the time of the audit, choosing from "Name, Role, Value" or two other criteria.
  
- **Designer:** Is unaffected by the contrast and color use criteria.
  
- **Expert:** Can look at another player's hand before their turn.
  
- **Tester:** Draws a first tool at the beginning of the game.
  
- **Project Manager (PM):** Can exchange one of their criteria for another drawn from the deck.

---

## Conclusion
This game is designed to raise awareness of web accessibility issues in a fun way while promoting collaboration and the exchange of ideas. Enjoy overcoming the challenges of a project while considering the various responsibilities and tools at your disposal!
