# fdx-MYiR-debugging
This repository will be used as common ground for source file sharing, error logs, etc ; in order to facilitate debugging

## AP issue
- We can get the AP running and working, we've been using it for testing and it works just fine at first.
- At some point, some driver related errors appear in the kernel log (The ones that are in the .txt file).
- After that the AP falls, and the only way we could get it working again is by removing and inserting the driver from the kernel itself.

### Suggestions ordered by priority: 
- **Updated driver**: If the error isn't that complex and it can be fixed with a newer driver version, it would be ideal.
- **Mitigating the error**: If the previous isn't possible, then it would be good to have some guidelines on how to mitigate it, how to detect when the error happens and what actions could be taken in order for the AP to not be in an unoperable state with the system unnoticed.
