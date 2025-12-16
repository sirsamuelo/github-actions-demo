# github-actions-demo

## Hello wrold
File - `helloWorld.yaml`
What we will learn ? 
- event on push
- `jobs`, `steps`, `run`


---

## 2️⃣ Run only on a specific branch
### Goal
- Run the workflow only when pushing to main
- Add another job that runs only on develop

### You’ll learn
- `on.push.branches`
- Branch-based conditions
- file `specificBranch.yaml`


## 3️⃣ Multiple jobs
### Goal
- Create 2 jobs
    - `build`
    - `test` 
- `test` should run only after build

### You’ll learn
- `needs`
- Job dependencies
