## Conflicts (as well as Contests and Challenges) as campaign/scenario-level pacing structures.

Okay, so one of the things I've been brewing in the back of my head is some way to put some kind of larger structure into a Fate campaign -the idea is pretty much directly stolen from Burning Empires (and, to a lesser degree, Mouse Guard). There's something just kind of satisfying to me about the idea. It also fits in with my idea of fractal challenges (see: <https://plus.google.com/108546067488075210468/posts/87wrm6yrdWx>). I've just finally got enough of my head wrapped around it to share it a bit more.

Just to note: I don't know that this is a good idea. It could be a terrible idea. This is just my initial thought on how to implement it.

The basic idea is that, ultimately, the entire plot of a game (at a given level) can be viewed as a single Overcome roll. But that's not particularly narratively interesting, so we employ a pacing mechanism to drive more detail into the game and make it last longer. Each "turn" in the pacing mechanism employed (be it Challenge, Conflict, or Contest) can in turn be turned into another Challenge/Conflict/Contest, and so on and so forth.

For an initial pass, and because I like the symmetry, I'm going to presume that the pacing mechanisms work the same on all levels. I don't know if that's the right solution, but I think it's a good starting place, and as I said the symmetry pleases me.

To generate one of these pacing mechanisms, we create appropriate "side" characters representing the factions involved. We give them skills appropriate to the side and representing their ability to influence the world. We also give the whole situation appropriate aspects.

Note that the skills probably do not match in any way to the character skill list!

Let's assume a Conflict. Now, on each "turn", each side gets to make a move, just like a "normal" Conflict. If the move is made in such a way that it can't be framed as a scene involving the PCs, it's just rolled.

However, if it can be framed as a scene involving the PCs (and the effort should be made to do so!), we "drill down" into the fractal by designing the scene.

We come up with goals for each side of the scene, and an idea of what pacing mechanism the scene uses. If the scene is an Overcome or a Create Advantage, we define what "success with style" means. If it's an Attack, we define what can be done in the scene, and how much stress it's worth.

Then, the scene is played out. The results translate up to the "higher level" Conflict just like if it were a single roll -if an Overcome is successful, it removes an Aspect. If a [[Create Advantage]] move is successful, a new aspect is generated. An Attack deals stress and (possibly) Consequences.

Then, we move to the next side's turn, until the higher-level conflict is finalized in some way.

So, the basic flowchart would look something like this:

1. Set up the Conflict
	- Make sides, with appropriate skills and aspects and stress tracks
	- Create situational aspects describing the scene
	- Make zones, if necessary?
2. Decide who goes first by some manner
3. The side whose turn it is gets to declare a normal Conflict action. This should still be narrative rather than simply "I attack"
4. If this cannot be framed as a scene involving the PCs, simply roll as normal.
5. If this can be framed as a scene, create the scene:
	- Give appropriate NPCs/resistance per the relative skills of the sides
	- If aspects are invoked, modify appropriately
	- Define success criteria, and stress values if this is an Attack
6. Play the scene out
7. Using the criteria set in step 5, transfer stress/aspect creation/destruction/consequences to the "upper" conflict.
8. Move to the next side and go to Step 4.

So, I absolutely hate mechanics without examples, so here's the example. This is pretty much the same example as the last time I mentioned this in a comment.

The Rebel Coalition is fighting off the Imperions! To destroy the Doom Base, they first need to deactivate its shield generator on the forest moon of Rodne.

The rebels just have a few units in comparison to the Imperions. The Imperions have a lot more hardware and men (though it's a relatively small base), but they have the disadvantage of being in a known location and pretty much unaware of the rebel presence. So we'll model that out:

>___ Rebels___:
> - Raid: 2
> - Recon: 3
> - Sneak: 4

> ___Imperions___:
> - Detect: 1
> - Assault: 4
> - Search: 2

We'll say that the Imperions are [Blissfully Unaware], as well as being in a [Fixed Position], but that they have [Heavy Support] and are [In a Secure Bunker].

The Rebels are [Small and Mobile] and have the advantage of [No Fixed Location].

There's also some [Hostile Natives] in the area, because hey, why not? And the whole thing is in a [Thick Forest].

So, we decide the Imperions go first. Not because of any game reason, but because I want the sample to more closely match the movie. Deal with it.

The Imperions are heavily limited by the aspects in play -they can't really attack the Rebels while they're Blissfully Unaware. So the GM decides that he wants to become aware of the Rebel presence. That sounds like Detect vs. Sneak.

Okay, we could roll here, but could we turn this into a scene? Obviously, we can! So we decide an interesting scene would be for a light Imperion patrol to find the Rebels, and then have a chase scene as the Rebels try to catch the Imperions and prevent them from reporting back to base! That sounds like a Contest, so we set that up appropriately. The Imperions only have a 1 Detect, which isn't going to work well for them, so they really only get a couple of mooks involved, and the main PCs manage to chase them off in short order. (There's a question here on whether the Imperions invoked their Heavy Support aspect to bring the speeders into play or not.)

Well, the PCs won that round, so the Blissfully Unaware aspect stays. The PCs realize that a direct assault will be pretty pointless, so they decide to get some help from the Hostile Natives. We decide that this is likely a Challenge, and that SWS will require that the natives end up believing that we are gods.

Fortunately, the player of the translator bot ends up pulling this off, giving the Rebels two free invokes on the Hostile Natives aspect! Go, team!

(My memory on the order of events in the movie gets a bit fuzzy here, so forgive me if I gloss over a bit).

So the Rebels decide that with their newfound friends, they have a chance to attack the Imperions and take out the shield generator. However, the Imperions have invoked their Heavy Support, making the resistance pretty tough. The Rebels decide that their Hostile Natives have come along for the ride, evening out the fight a bit. Appropriate stress values are decided on for taking out various numbers of enemies, and the Conflict is on! Some stress is done, but not enough for a Consequence -boo, hiss, the Rebels have gained some ground but haven't radically altered the course of battle -yet.

The Imperions mount a counter-attack, which ends up being fended off by the Rebels.

The bunker is getting annoying! The Rebels decide it's time to neutralize that, and spend their turn Overcoming that particular obstacle. This is done as a Challenge, representing the difficulty of gaining entry to the bunker, while fighting off the attacking Thundertroopers. Again, the PCs succeed, meaning they get access to the bunker! The fight moves inside!

And so on, until the Imperions concede or are Taken Out.

There's still some open questions I have like dealing with Fate Points since a Fate Point expenditure at the "upper level" has so much more impact, how do I deal with them? Do I just say that expending a "upper" Fate Point requires one FP per PC? Or do I give them a separate pool? These are all good questions.

I also don't really know how I feel about the inherent one-sidedness of the Attack option. In a "normal" attack, only the attacker can deal stress. I don't know how that fits in this case, but I guess you could make the argument that a "success with style" boost could model a scattered retreat, and in most cases, the attackers will simply retreat rather than take any kind of significant casualties or loss of position.

Anyway, thoughts? Comments? Suggestions? Is this just a terrible idea within the general Fate framework?

---