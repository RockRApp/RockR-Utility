# RockR-Utility

This repository will contain any files we need to share that don't have anything to do directly with either the frontend or backend exclusively. For instance, we can keep track of any diagrams we make, project plans to keep development on schedule, roles without our dev teams, etc. 

Regarding the use of the other repos:
Code can be a fragile thing, so we need to take precautions to avoid breaking something that someone else has written. I don't know everyone's backgrounds in group development positions, so I'll elaborate quickly on how to use the repos in an efficient and safe manner.

The root of issues in any Version Control System (VCS) is that if a line of code is modified by 2 developers, the system can't predict which modification is "more" correct, or how to merge the two modifications safely. To combat this, we should use our own branches for unstable work - things that could possibly cause a conflict with other users. Just to be safe, its best to use our own branches for everything, then merge everything back to master when the feature is complete.

So, everyone should create a branch that unique to their name so they can modify code and feel safe committing and pushing code to it. When someone completes a feature, merge it back to master. In a business setting this means submitting a pull request to the repository manager, but in our startup we can just make sure everone is aware of a merge to master.

Another helpful tip is to COMMIT OFTEN. This is often given as advice, but rarely adequately carried out in practice. VCS allows us to make frequent "backups" of our work, so we should use that to our advantage whenever possible. If you're starting on something new, commit what you previously were working on. If you have a working portion of something you're working on, commit it. It's ok to say things like "Added structure for such-and-such", even if that structure isn't actually used anywhere in the code.