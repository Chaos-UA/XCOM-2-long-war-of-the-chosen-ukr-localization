You created an XCOM 2 Mod Project!

This is an optional add-on mod for Peek From Concealment.

This mod fixes the movement preview UI to account for Peek's modified concealment rules. This means you should only see a warning flag if you're actually going to break concealment.

This mod requires Gotcha Again.
In the future it is completely possible that Gotcha may update and break this mod, but in that case it won't do any harm to remove it (besides getting the false warnings again).

No guarantees are provided that the preview will be perfectly trustworthy. I am not liable for soldier deaths caused by the UI being a dirty liar. That said, I tried to make it as accurate as possible.

Note: The mod launcher may specify that this mod conflicts with Gotcha Again, ignore it, it should work anyway.

ps. Based on reading the Gotcha code I believe that everyone who worked on the project should be eligible for sainthood.

Troubleshooting
If the mod doesn't work for you there is one thing you can do to fix it. Go to Gotcha Again's XComEngine.ini and find the line
+ModClassOverrides=(BaseGameClass="XComPathingPawn", ModClass="XComPathingPawn_GA")
and delete it or prepend a semicolon (;) to comment it out.
This will also remove the conflict warning from the mod launcher. You'll have to re-add this line if you remove this mod, or Gotcha won't work.

UPDATED 12/26 - Came back and fixed the civilian bug after approximately 3 billion years. (Hopefully)