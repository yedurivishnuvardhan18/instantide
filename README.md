
# InstantIDE

InstantIDE is a browser-based development environment that allows users to instantly preview, run, and interact with projects directly from GitHub repositories — without complex local setup.

InstantIDE provides an instant coding playground where users can paste a GitHub repository link and immediately preview the project in the browser. It supports frontend, backend, and full-stack projects with intelligent handling of assets, Docker-based execution, and automatic environment setup.

The goal of InstantIDE is to remove setup friction and make learning, sharing, and showcasing projects effortless.

## Used By

This project is used by:

- Students learning web development  
- Educators & mentors  
- Hackathon participants  
- Open-source contributors 

## Features

- Instant GitHub repository preview  
- Supports HTML, CSS, JavaScript projects  
- Node.js & backend project execution  
- Automatic Dockerfile detection & generation  
- Raw GitHub asset handling (images, files)  
- Live preview inside the browser  
- No local setup required 


## Tech Stack

- Frontend: HTML, CSS, JavaScript, React  
- Backend: Node.js, Express  
- Containers: Docker  
- APIs: GitHub REST API  
- Dev Tools: Vite, NPM


## Screenshots

<img width="1894" height="826" alt="image" src="https://github.com/user-attachments/assets/a91710a7-6c21-4135-9a29-40a99fd4768a" />
<img width="1894" height="895" alt="image" src="https://github.com/user-attachments/assets/492a3296-30a5-46a2-8035-5ef92d073c0f" />
<img width="1897" height="903" alt="image" src="https://github.com/user-attachments/assets/68ed193c-bf8f-44f8-bde9-ef1890d550bc" />
<img width="1888" height="897" alt="image" src="https://github.com/user-attachments/assets/4f41a8a2-a13e-4f70-b7d9-5463f104caa0" />
<img width="1893" height="909" alt="image" src="https://github.com/user-attachments/assets/fd7703c0-977d-40f2-bb37-2d6cb71eb5b3" />
<img width="1902" height="907" alt="image" src="https://github.com/user-attachments/assets/bf7e878c-7156-4c9a-893b-251c94153740" />









## Run Locally

Clone the project

```bash
  git clone https://github.com/your-username/instantide.git
```

Go to the project directory

```bash
  cd instantide
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```


## Installation

Install my-project with npm

```bash
  npm install  
  cd instantide
```
    
## Usage/Examples

```javascript
1. Open InstantIDE  
2. Paste a public GitHub repository link  
3. InstantIDE detects project type  
4. Environment is prepared automatically  
5. Project preview is shown in the browser 
```


## Running Tests

To run tests, run the following command

```bash
  npm run test
```


## Deployment

To deploy this project run

```bash
  npm run build    
```
```bash
  npm run start      
```


## Optimizations

- Asset URL rewriting for raw GitHub content  
- Intelligent project-type detection  
- Docker-based isolation for backend projects  
- Reduced container startup time  
- Improved preview rendering performance  


## Roadmap

- Support for Python projects  
- Multi-container project support  
- Authenticated private repo previews  
- Live terminal access  
- Project sharing links


## Lessons Learned

- Handling diverse GitHub project structures is complex  
- Docker automation improves reliability significantly  
- Asset path issues require intelligent URL rewriting  
- Developer experience matters as much as functionality  


## FAQ

#### Question 1

Q: Does InstantIDE support backend projects?  
A: Yes, Node.js projects are supported using Docker.

#### Question 2

Q: Do I need Docker installed locally?  
A: No, Docker runs on the server side.


## Related

Here are some related projects

- CodeSandbox  https://codesandbox.io/
- StackBlitz   https://stackblitz.com/
- Gitpod       https://ona.com/


## Authors

- [Yeduri Vishnuvardhan](https://www.github.com/yedurivishnuvardhan18)

