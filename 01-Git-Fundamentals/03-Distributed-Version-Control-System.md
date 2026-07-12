# Distributed Version Control System (DVCS)

## What is a Version Control System?

A Version Control System (VCS) is a software that tracks changes made to a project over time. It helps developers maintain different versions of a project, restore previous versions, and manage project history efficiently.

---

# Types of Version Control System

There are three types of Version Control Systems:

1. Local Version Control System (LVCS)
2. Centralized Version Control System (CVCS)
3. Distributed Version Control System (DVCS)

---

# Local Version Control System (LVCS)

A Local Version Control System stores all project versions only on the local computer.

### Advantages

- Simple to use.
- No internet connection is required.

### Disadvantages

- No collaboration.
- If the local system fails, project history may be lost.

---

# Centralized Version Control System (CVCS)

A Centralized Version Control System stores the entire project in a central server. Developers connect to the server to access and update the project.

### Advantages

- Easy collaboration.
- Centralized project management.

### Disadvantages

- Internet connection is usually required.
- If the central server fails, development is affected.

### Example

- Apache Subversion (SVN)

---

# Distributed Version Control System (DVCS)

A Distributed Version Control System allows every developer to have a complete copy of the repository along with its history on their local machine.

Git is a Distributed Version Control System.

### Advantages

- Works offline.
- Every developer has a complete backup.
- Faster operations.
- Easy collaboration among multiple developers.
- Better reliability than a centralized system.

### Example

- Git

---

# Comparison

| Feature | Local VCS | Centralized VCS | Distributed VCS |
|----------|-----------|-----------------|-----------------|
| Project History | Local Computer | Central Server | Every Developer |
| Internet Required | No | Usually Yes | No (for most operations) |
| Collaboration | No | Yes | Yes |
| Backup | Limited | Server | Every Local Repository |

---

# Summary

A Version Control System helps developers manage different versions of a project.

- Local VCS stores versions only on the local computer.
- Centralized VCS stores the project on a central server.
- Distributed VCS gives every developer a complete copy of the repository.

Git is a Distributed Version Control System because every developer has a complete copy of the repository and its history.