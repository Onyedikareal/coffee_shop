# Coffee Shop Full Stack

## Full Stack Nano - IAM Final Project

Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. But they need help setting up their menu experience.

You have been called on to demonstrate your newly learned skills to create a full stack drink menu application. The application must:

1. Display graphics representing the ratios of ingredients in each drink.
2. Allow public users to view drink names and graphics.
3. Allow the shop baristas to see the recipe information.
4. Allow the shop managers to create new drinks and edit existing drinks.

## Tasks

There are `@TODO` comments throughout the project. We recommend tackling the sections in order. Start by reading the READMEs in:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)

## About the Stack

We started the full stack application for you. It is designed with some key functional areas:

### Backend

The `./backend` directory contains a partially completed Flask server with a pre-written SQLAlchemy module to simplify your data needs. You will need to complete the required endpoints, configure, and integrate Auth0 for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. You will only need to update the environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app.

[View the README.md within ./frontend for more details.](./frontend/README.md)

### barister bearer token 
`eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6Ijl1bERCNlBOa1A5ZGplZ2NkNWJKSCJ9.eyJpc3MiOiJodHRwczovL2Rldi02bC01bmpqaS51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NjMyZTU5MmU2N2VjN2UzOTZhMDMyNmUzIiwiYXVkIjoiY29mZmVlc2hvcCIsImlhdCI6MTY2NDkzMTI1NCwiZXhwIjoxNjY1MDE3NjUzLCJhenAiOiJ6S0lSekMwYmhwSkd3TnY2dG1sbm13WDE0WUFVMEo0byIsInNjb3BlIjoiIiwicGVybWlzc2lvbnMiOlsiZ2V0OmRyaW5rcyIsImdldDpkcmlua3MtZGV0YWlsIl19.pba6p-7k1CQrl85j5RN2bUpGIsLMvFAmrSY8-8w4ma6PTdcH4jX2ExQTgNnSTYTsQhcIIT26qqyhy13o9IzmihM4Z78t7oY1poogNv42xaPrFvvi8DDWZixDEhj4k4-Co8nfG6INhypSPmxdZJ4aZuPCDFj2XWIy0UalYJsq5ZHSpDxUniLYX9qLgJT_yFQVyVMTM221jIyUyCyfm-9Muliw-QSiXYMAJdfYfa1BChBDn7lbMsFrZXTbL9lP0zMjfsCq16lcRK70wxJDdpmpLGSpxI5KQJ-OzwZEVrB2WhuAvW7gZ8JoD1wJ6AK1GZt4fRYMaOe5lrswQgE_MasV5w`

### manager bearer token
`eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6Ijl1bERCNlBOa1A5ZGplZ2NkNWJKSCJ9.eyJpc3MiOiJodHRwczovL2Rldi02bC01bmpqaS51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NjMyZTU5NWViOGIxNDI0Y2E0NjJiYzllIiwiYXVkIjoiY29mZmVlc2hvcCIsImlhdCI6MTY2NDkzMTM3NCwiZXhwIjoxNjY1MDE3NzczLCJhenAiOiJ6S0lSekMwYmhwSkd3TnY2dG1sbm13WDE0WUFVMEo0byIsInNjb3BlIjoiIiwicGVybWlzc2lvbnMiOlsiZGVsZXRlOmRyaW5rcyIsImdldDpkcmlua3MiLCJnZXQ6ZHJpbmtzLWRldGFpbCIsInBhdGNoOmRyaW5rcyIsInBvc3Q6ZHJpbmtzIl19.x0ayGsTFSdQyCKDCuvwQhRshQih420e1d7bCZY4mnfVus5_2crTROkKah6wKvMx1JkkoNRjRE5UzAAe4ssknmPO_imwuf_aAJoE9IS21oosnMiUzsEzA9DMQEfCLSieaYJnuwMEX_PD0ArzTznN5kv0a8XMrK7KeMOS4q9en3IR6ELPCOUN1WIHhre0UXXUFMhNytuMuTTmSqYvROwvLifWUGfZoP1n4BDMt3I5bgUXO2pcsyAGny2GB2f2g81DWONr0FIDMKhUBjXwV0sHUZ-Z-KQGaXfza1UMFKqf7pGXK_vsJO8tZEbOXs0JGaYE5KWAoWESBN0wtTF_x9Knkew`
