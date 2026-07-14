# Product Backlog - Cloth AI Outfit Recommender

## 1. User Stories

### US-01: User Registration and Login
**As a** new user  
**I want to** create an account and log in  
**So that** I can save my style preferences and outfit history  
**Use-Case Link**: [UC-01 User Authentication](./docs/use-cases/UC-01.md)

#### Acceptance Criteria
**Given** I am on the registration page  
**When** I enter a valid email and password and click "Sign Up"  
**Then** my account is created and I am redirected to the dashboard  
**MoSCoW**: Must Have

### US-02: Upload Photo for Style Analysis
**As a** user  
**I want to** upload a photo of myself  
**So that** the AI can analyze my body type and current style  
**Use-Case Link**: [UC-02 Photo Upload](./docs/use-cases/UC-02.md)
#### Acceptance Criteria
**Given** I am logged in and on the dashboard  
**When** I upload a JPG/PNG image under 5MB  
**Then** the image is stored and I see "Analysis Complete"  
**MoSCoW**: Must Have

### US-03: Get AI Outfit Recommendations
**As a** user  
**I want to** get 3 outfit recommendations based on occasion and weather  
**So that** I can decide what to wear quickly  
**Use-Case Link**: [UC-03 Get Recommendations](./docs/use-cases/UC-03.md)
#### Acceptance Criteria
**Given** I have uploaded a photo and selected "Work" and "Rainy"  
**When** I click "Get Outfit Ideas"  
**Then** I receive 3 text recommendations within 10 seconds  
**MoSCoW**: Must Have

### US-04: Save Favorite Outfits
**As a** user  
**I want to** save outfit recommendations to my favorites  
**So that** I can refer back to them later  
**Use-Case Link**: [UC-04 Save Favorites](./docs/use-cases/UC-04.md)
#### Acceptance Criteria
**Given** I have received outfit recommendations  
**When** I click the "Save" button  
**Then** the outfit is added to my "Favorites" page  
**MoSCoW**: Should Have

### US-05: Share Outfit to Social Media
**As a** user  
**I want to** share my recommended outfit to Instagram  
**So that** I can get feedback from friends  
**Use-Case Link**: [UC-05 Share Outfit](./docs/use-cases/UC-05.md)
#### Acceptance Criteria
**Given** I am viewing a saved outfit  
**When** I click "Share to Instagram"  
**Then** an image of the outfit description is prepared  
**MoSCoW**: Could Have
