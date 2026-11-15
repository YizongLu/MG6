# MG6

1. I think the entire for loop will complete before the Update method finished. Therefore, if the for loop takes a really long time to finish, the game will lag until the for loop finished.
2. I think the issue is you can go through the left side or the right side of platforms or even go through the vertical border with tag "Platform" when player is moving upward. I think it is because we don't check whether the cat collides with the platform bottom. We only disable the collider when the cat is moving upward.