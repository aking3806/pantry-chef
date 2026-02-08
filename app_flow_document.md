# Pantry Chef  
## App Flow & User Journeys

---

## Core User Journey (Happy Path)

1. Open app  
2. See **“What can you cook today?”**  
3. Add ingredients  
4. Instantly see matching recipes  
5. Pick a recipe  
6. View recipe card and instructions
7. Cook 

---

## Entry States

### First-Time User
- No login
- No setup required
- Pantry staples prompt visible (skippable)

### Returning User
- Pantry staples auto-loaded
- Favorites restored
- Session ingredients empty

---

## Pages & Menus

### 1. Home / Ingredient Search  
**(Primary & only MVP page)**

#### Responsibilities
- Ingredient input
- Pantry staples summary
- Recipe results
- Recipe cards 
- Favorites interaction

#### Primary Actions
- Add ingredient
- Remove ingredient
- Pick recipe
- View recipe 

#### Secondary Actions
- Create pantry staples 
- Edit pantry staples
- Favorite recipe
- **“Just pick for me”**

---

### 2. Pantry Staples Editor  
**(Modal / Bottom Sheet)**

#### Entry Points
- Pantry card **“Edit”** button
- First-time user suggestion

#### Responsibilities
- Select common ingredients
- Save to local storage
- Clearly explain purpos

---

## State-Based Flows

### Empty State
- Message explains what to do next
- No dead ends

### No Matches State
- Encourage adding one more ingredient
- Never blame the user

### Error State
- Retry CTA
- Ingredient flow remains usable

---

## Navigation Rules
- No top navigation
- No tabs
- No side menus
- One screen, one goal

---

## Mental Model
> “This app reacts instantly to what I have, not what I search for.”
