## Subtree

```bash 

# 1. Add remote

$ git remote add scheduler git@github.com:mvaliolahi/scheduler.git


# 2. Add subtree (--squash prevent to store subproject history)

$ git subtree add -P src/scheduler scheduler master --squash


# 3. Pull subtree
	
$ git subtree pull -P src/scheduler scheduler master


# 4. Push

$ git subtree push -P src/scheduler scheduler master

```

Note: before adding the subtree, the scheduler directory must not exist.