# JuPix – Specifications

## 1. Overview
Interactive pixel-art map of Jussieu campus with online study rooms.

## 2. Goals
- Let students explore the campus map in 2D
- Let students join online study rooms (voice chat)
- Let students take breaks (gaming rooms)
- Make it simple and fast to use

## 3. Users
- Students (main users)
- Tourists (visitors without an account)
- Admins (manage rooms and map data)

## 4. Features
### Must have
- Interactive 2D pixel-art map of Jussieu
- Create / join a study room
- Tourist mode
- Basic authentication (id, password)
- Room capacity
- Custom pixel avatars

### Should have
- See who is currently studying (presence)
- Text chat in rooms
- Study timer (pomodoro)

### Nice to have
- Voice chat
- Online gaming rooms

## 5. User stories
- As a tourist, I want to visit the Jussieu campus without an account.
- As a student, I want to pick a free room to study alone or with friends, and take a break in a gaming room with built-in games (e.g. chess)
- As an admin, I want to edit rooms and map data so the campus stays up to date.

## 6. Technical constraints
- Web app (desktop)
- Real-time updates (WebSockets)
- Stack: React, Node.js, MongoDB

## 7. Non-functional requirements
- Loads in under 3 seconds
- Works on recent browsers
