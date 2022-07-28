```mermaid
flowchart TD;
    A[Do you have have time for volunteering?] --> |No| B[Do you want to make a donation?]
    B -->|No| E(Please let us know how you want to support and share this article if you find it useful)
    B -->|Yes| C[Do you want to donate physical items?]
    C -->|No| D[Do you want to donate money?]
    D -->|No| E
    D -->|Yes, helping Animals| F[Past Link to the animal fundraisers]
    D -->|Yes, humanitarian Cause| G[Past link to organizations]
    D -->|Yes, medicine| H[Past link to medicine]
    D -->|Yes, military| I[Past link to military]
    C -->|Yes| J[Are there refugees in your city?]
    J -->|No| (Check which items worth sending to help Ukraine)
    J -->|Yes| (Check local refugee welcoming centers for the items they need. Please make sure to bring them sorted as it will save time for volunteers)
    A -->|Yes| K[Do you want to volunteer from home?]
    K -->|No| L[Do you want to come-in on a regular basis to one of the places in your city?]
    L -->|Yes| (Here is the list of places in Berlin, where you can help)
    L -->|No| M[Are you employed?]
    M -->|No| E
    M -->|Yes| (You can research if there are any job opennings in your company which could be suitable for refugees, ask your company to organize trainings for refugees, see if there is any budget available to make high-impact donations or support refugees with legal assistance)
    K -->|Yes| N[Are you a software engineer/IT specialist?]
    N -->|Yes| (Checkout this resource, which helps to cover for Ukrainian IT specialists, who unfortunately cannot perform their duties due to the military service or war in general)
    N -->|Yes| O[Have you considered organizing a tech conference and run a fundraiser? Check out success story here: ]
    N -->|Yes| (Have you thought of organizing a hackaton and building a thing, that can help solve problems for refugees? This might be a sign to consider it)
```







    
```
