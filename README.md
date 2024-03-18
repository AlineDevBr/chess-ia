# Developed a Chess game in Unity and an AI capable of playing with several turns calculated ahead, based on the Minimax Alpha-Beta algorithm that defeated Garry Kasparov.



    Board Setup: Asset Import (itch.io); Creation of Logic Board; Controls with Mouse and Singletons;

    Controls and State Machine: Asynchronous Programming, Use of Tasks, Queue, Pooling and ContextMenu.

    Part Movement: Polymorphism, Object Orientation, Enums and DOTWeen.

    Special Movements: Delegates, Events, Buttons, TaskCompletionSource and DOTween with Actions.

    Artificial Intelligence: Recursive programming, Minimax Algorithm, Use of background threads, 
    Saving and reloading states, Alpha-Beta Pruning, Square Table Evaluation and Code optimization 


https://github.com/alfredo1995/chess-ia/assets/71193893/bb865754-cb95-4f67-a72a-f039c9aabd39

When developing the Chess game in Unity, I implemented advanced artificial intelligence (AI) based on the Minimax algorithm with Alpha-Beta Pruning. This algorithm is widely used in strategy games, such as Chess, to make movement decisions based on assessments of possible future scenarios.

The development process involved several aspects of artificial intelligence and code optimization. I used recursive programming to calculate multiple turns in advance, allowing the AI to plan its moves in depth and efficiently.

To improve AI performance and ensure a smooth gaming experience, I made use of background threads to process intensive calculations without blocking the main game execution. This allowed the AI to analyze and pick your plays quickly and responsively.

Additionally, I implemented a state save and reload system to allow players to save their game progress and pick up where they left off later. This is essential for strategy games like Chess, where games can be long and complex.

Board evaluation has been carefully designed using a combination of techniques, including square table evaluation, where each position on the board is assigned a value based on factors such as piece mobility, territory control, and positional advantage.

The application of the Minimax algorithm with Alpha-Beta Pruning was crucial to the AI's effectiveness in making intelligent and strategic decisions in the game of Chess. The use of these advanced artificial intelligence and code optimization techniques contributed to creating a challenging AI capable of competing at a high level, demonstrating its potential by defeating even experienced players like Garry Kasparov.
