# Justification
[//]: # (This section is an example of justifying your design and development decisions.)

## Overview
Our client has tasked us with making a firstperson shooter template whcih requires two guns a granade and a AI that tracks the player they will be using this to teach a class so a gray box and basic models from i.e. sketchfab this will allow the client to have a good bases of work to continue their leason
### Brief
[//]: # (What was the client's brief?)
The client is seeking a proof of concept for a game that is simple, yet a leader in its class
* The Template should be used within a classroom enviroment
* The game should have two weapons and ability to shoot with a granade as a leathal projectile 
* The game should have a AI to walk around and look at player

### Communication
* When do you need this prototype by?
> I need the prototype by 01/06/2026

* Since you only need a prototype, are you happy for us to focus on gameplay and use based geometry for art assets?
> Yes perfect, the prototype is a proof of concept, please don't waste time on creating art assets; if the game is fun with simple art assets, that is perfect. At least change the colour palette to be aesthetically pleasing though.

these are two questions we'd ask ourselves and the client and further commuications would be through email.


## Project Understanding

### Requirements
[//]: # (What are the requirements of the finished project?)
* Needs the product in 5 weeks.
* The project is a template and so must be able to be taught to a class

### Expectations
[//]: # (What are the client's expectations?)
* Project delivered on time
* Weekly updates on progress
* Communication with the client when design issues encountered
* Quality transparent project management (add the client)
* Does **not** require audio
* Does **not** require high quality art
* Can use basic geometry
* Should still look nice using colour palettes

### Assumptions
[//]: # (What are you assuming based on client responses)
* the game just needs to be a basic template/prototype with the intention to teach students
* having basic AI is only needed as this will allow the teacher to go more in depth with the project to give the prototype more life
* the client is a former dev meaning they have coding knowledge and would be able to easily edit and teach students and build from our prototype

---

# Risk Management & Development Workflow

As the project is being developed by a newly formed team using Unity, GitHub, and Trello, several technical, workflow, communication, and scheduling risks were identified throughout development. This document outlines the potential risks, their impact on the project, and the strategies used to reduce or manage them during production.

---

# Risk Management Table

| Risk | Potential Impact | Likelihood | Risk Management Strategy |
|------|------------------|------------|--------------------------|
| Poor communication between new team members | Tasks may be duplicated, misunderstood, or forgotten | High | Conduct regular team meetings and use Trello to assign and track responsibilities clearly |
| Inconsistent coding standards | Code becomes difficult to read, debug, and maintain | High | Establish shared coding conventions including naming, comments, formatting, and modular structure |
| GitHub merge conflicts | Systems may break or work may be overwritten | High | Use feature branches, commit regularly, pull before pushing, and communicate before merging |
| Incorrect Unity scene or prefab changes | Scene references or gameplay objects may break | High | Use prefab-based workflows and avoid simultaneous scene editing where possible |
| Missing prefab references in Unity Inspector | Systems may fail during runtime | Medium | Perform regular testing and use debug validation checks in scripts |
| Team unfamiliarity with GitHub workflow | Lost progress or incorrect repository usage | Medium | Research GitHub workflows and provide simple team guidelines for commits, pulls, and branches |
| Poor Trello task management | Workflow becomes difficult to track | Medium | Keep Trello updated regularly and move tasks through workflow stages consistently |
| Delayed feature integration | Independent systems may not function correctly together | Medium | Integrate and test features incrementally throughout development |
| Tight coupling between systems | Small changes may break multiple scripts | Medium | Use component-based architecture and separation of concerns |
| Lack of documentation | Team members may struggle to understand systems | Medium | Use code comments, summaries, and detailed Trello task descriptions |
| Unrealistic scope or feature creep | Project may exceed deadlines or become unstable | Medium | Prioritize core gameplay systems before optional features |
| Poor testing practices | Bugs may remain undiscovered until late development | Medium | Schedule dedicated testing periods after milestones |
| Version mismatch in Unity | Some team members may not be able to open the project correctly | Medium | Ensure all team members use the same Unity version and project settings |
| Accidental deletion or corruption of files | Important project files may be lost | Low | Maintain frequent GitHub commits and backups |
| Dependency on one developer’s knowledge | Progress may slow if a team member becomes unavailable | Medium | Share documentation and explain systems during team discussions |
| Performance issues from unoptimized scripts | Gameplay performance and FPS may decrease | Medium | Use Unity profiling tools and optimize scripts regularly |
| Incomplete modularity | Systems become difficult to expand or maintain | Medium | Continuously refactor systems into reusable modular components |
| AI behaviour not functioning correctly | Gameplay experience may feel incomplete | Medium | Prototype AI systems early and iterate through testing |
| Poor time management | Deadlines may not be achieved | Medium | Break tasks into milestones and track weekly progress through Trello |
| Lack of repository organization | Assets and scripts become difficult to locate | Low | Maintain consistent folder structures and naming conventions |
| Limited experience with Unity systems | Development may slow due to unfamiliar tools or workflows | High | Allocate time for tutorials, documentation research, and experimentation |
| Team members unfamiliar with component-based architecture | Systems may become tightly coupled and difficult to debug | Medium | Research modular programming practices and refactor progressively |
| Research time affecting development schedule | Features may take longer than expected to complete | High | Include schedule buffer time for learning and troubleshooting |
| Inexperience with AI programming | Enemy systems may require additional iteration and debugging | Medium | Research AI behaviours early and prototype before full implementation |
| Difficulty debugging Unity-specific issues | Bugs may delay milestone completion | Medium | Use Unity Console logs, debugging tools, and collaborative troubleshooting |
| Learning new collaborative workflows | Initial productivity may decrease | Medium | Practice GitHub and Trello workflows consistently throughout development |
| Knowledge silos within the team | Only one member may understand certain systems | Medium | Share research findings and document implementations clearly |
| Hardware or software compatibility issues | Some systems or builds may not function correctly | Low | Test builds across multiple machines and maintain consistent software versions |
| Internet outages affecting GitHub access | Team members may be unable to sync work | Low | Commit work locally regularly and sync once connection is restored |

---

# Workflow Tools

## Trello

Trello is used to:
- Assign development tasks
- Track progress
- Organize milestones
- Monitor debugging and testing
- Reduce communication issues
- Improve workflow visibility

### Workflow Structure

Backlog → To Do → In Progress → Testing → Done


---

## Constraints

### Constraints
[//]: # (What are the constraints of this project)
* We have a tight timeframe, so we will need to make fast decisions, which may be less than perfect

---

## Justification
We have read through your breif many times and have gotten a fair idea of what you are after having it be simlar to the great fps titles such as DOOM and Halo and with you being a former bungie dev we are egar to set out and create this template for you and allow you to teach the future generation of the game industry.

Follow The design plan that has been formulated will help our team manage our time and scope to hopefully create the simple FPS template that was requested. there may still be conflicts or bugs that arise but we will comment our work to help clarify what each section does for the template. 

