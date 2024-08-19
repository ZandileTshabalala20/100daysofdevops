The game's code is stored in GitHub, and we set up an S3 bucket for static website hosting. A continuous deployment pipeline is then established using AWS CodePipeline to automatically deploy the code whenever updates are pushed.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
Game Overview
This is a basic memory matching game where players click on two cards (displaying meme images) to find a matching pair. If a match is found, the cards are removed from the board. If the cards don't match, they flip back to their blank side, allowing the player to try again.

The game is built using HTML, CSS, and JavaScript.

Ideas for Additional Features:

Scoring system
Timer
Additional cards
Multiplayer mode to compare scores

The Deployment Environment
The code will be deployed and hosted in S3.

The Deployment Pipeline
The pipeline is created using AWS Code Pipeline. The pipeline pulls the code from GitHub, and deploys it to S3 whenever a change is detected in the code.
