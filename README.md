# AGI game

Simple web-based AGI simulation game where the player guides the development of an Artificial General Intelligence (AGI). The player manages resources (Compute, Data, Research) and makes decisions through various events that impact the AGI's Intelligence, Alignment with human values, and overall Risk level. The goal is to achieve a beneficial outcome (e.g., a highly intelligent and aligned AGI) while avoiding pitfalls like catastrophic risk or an unaligned superintelligence.

![image](https://github.com/user-attachments/assets/940699e5-8296-49c6-9729-afe66f8a1658)

## How to Play

1.  **Open the Game:** Open agi-game.html.
2.  **Understand the Interface:**
    * **Resources:** At the top, you'll see your current levels of Compute, Data, and Research.
    * **AGI Status:** Progress bars show the AGI's Intelligence, Alignment, and Risk Level (0-100%). Pay attention to the colors, especially for Alignment and Risk.
    * **Event Area:** This box displays the current situation, event description, or status messages.
    * **Choices Area:** When an event requires a decision, buttons will appear here.
    * **Next Turn Button:** Click this to advance the game turn after resolving any choices or reading event outcomes.
    * **Turn Counter:** Shows the current turn number.
    * **Message Box:** A pop-up at the bottom provides feedback on actions and events.
3.  **Gameplay Loop:**
    * Click "Next Turn".
    * Resources are consumed/generated passively.
    * An event *may* trigger based on the current game state (AGI stats, resources, turn number).
    * If an event triggers:
        * Read the event text.
        * If choices are presented, click the button corresponding to your desired action. The effects will be applied immediately.
        * If it's an informational event (no choices), read the outcome.
    * Click "Next Turn" again to continue.
4.  **Goal:** Reach a high Intelligence level (e.g., 100%) while keeping Alignment high (e.g., >= 70%) and Risk low. Avoid reaching 100% Risk or specific negative outcomes detailed in the game over conditions.

## Features

* **Resource Management:** Balance Compute, Data, and Research.
* **Status Tracking:** Monitor AGI Intelligence, Alignment, and Risk via progress bars.
* **Event-Driven Gameplay:** Random and conditional events present choices and challenges.
* **Decision Making:** Choices directly impact game state and potential outcomes.
* **Multiple Endings:** Different game over scenarios based on AGI stats and resource levels (e.g., Beneficial Singularity, Catastrophic Risk, Unaligned Superintelligence, Project Stalled).
* **Simple UI:** Clear interface using Tailwind CSS.

## Future Enhancements (Ideas)

* More diverse and complex events.
* Deeper resource interaction (e.g., research unlocking new abilities or resource types).
* More nuanced AGI stats or attributes.
* Visual indicators for resource trends.
* Saving/Loading game state.
* More sophisticated win/loss conditions.
