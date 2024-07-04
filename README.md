# FateSRDObsidian

This is a repository where I collect the contents of the Fate SRD and transform it to work well as an [[Obsidian]] "vault" for use as an RPG tool.

## Disclaimer the First

To be as clear as possible, ***I do not own the content of this repository***.  It is repurposed from existing available sources.  You probably _also_ do not own this content, so publishing it might get you into trouble.  Talk to the owners of things before you make a huge mistake.

## Disclaimer the Second

This is a git repo of an [[Obsidian]] vault. 

I do not care if you're "not good with git".  I do not care if you don't understand [[Obsidian]].  

There are sufficient tutorials available on the interwebs such a person of even less-than-average mental acuity can figure it out.  However, if you take the effort it _might_ be worth it to you.  

That said, if you find that these instructions specify something that is false, then reporting it as an issue is the right answer.  Don't have (or want to have) a GitHub account?  No problem.  You can fix your copy locally and the rest of us will just go along being wrong.

## Obsidian Vault

A "vault" is [[Obsidian]]-speak for "folder with markdown and config files".  If you don't know what [[Obsidian]] is, then the linked word `[[Obsidian]]` probably isn't working for you.  So go to https://obsidian.md to learn about it.  

Some things you should know about this vault:
- Effectively all content here is scraped from the web and/or cloned from the Fate SRD GitHub repo.
- I have done a substantial amount of [hopefully merely cosmetic] modification to that content.
	- As I am just a flawed human, I cannot factually represent that the content in this vault matches the intent of the various people who created that content.  But I'm willing to talk about that.
- Any errors are almost certainly mine.  Please enter a GitHub issue for that.
- It is my intention to keep everything here as up-to-date as possible with regard to the Fate SRD site (which is no longer going to be updated).
	- But again, I'm not perfect, so I will accept pull-requests against this repo for actual errors.
- If there is any additional content ***that you have the right to publish*** and would like it to be included in this vault, I will also accept pull-requests for that (within reason).
- If you own content that is in this repo inappropriately (because I failed to vet it like an idiot or because you just don't want it there), I deeply apologize and will do whatever I can do alleviate your concern.  Note that for CC-licensed material, you have effectively no recourse as long as the CC licensing elements are met.  They are. I checked.  But I'll probably pull it out of the vault anyway because there's no reason to be an asshole about it.
- See [[VERSIONS]] to note releases of this document.

## Why Did You Do This?

Because I started running a [[Fate Core|Fate]] game.  My handwriting is ***notoriously*** poor, so I tend to use [[Obsidian]] for all of my note-taking and self-referential data collection.  As a means for that, [[Obsidian]] is excellent. I can source-code control the contents of a vault.  I can install plugins that do a lot of really cool things.  I can start writing and just start by typing `[[` and any topic I want and Obsidian will make a placeholder reference for me inside a note.  Furthermore, it'll tell me that I need to fill that in later.   

 I wanted to link to specific things in the SRD, _et al_ and doing that required writing my documents with active links to the specific pages in the SRD using anchor tags.   I tried that for about 2 days and stopped because it totally sucked.  This is WAY better.  I can build pages from templates and the generated page will have active links to anything that connect it to within the vault.  It's all technically offline so I can work on it anywhere.

So when I enter a player's character named `[[Rosemary]]` and make a note on `Rosemary.md` that she is friends with `[[Bradley]]`,  that link is active.  I can then sync that repo down to the tablet I use to run my game and I have an internally hyperlinked knowledgebase of players, NPCs, zones, and games.  This network is additionally hyperlinked _to the relevant rules_.  Rosemary has `[[Contacts]] +4`?  There's a live link on her page to the [[Contacts]] skill.  As many of the [[fate-srd.com/fate-srd.com/fate-accelerated/Stunts|stunts]] and [[Aspects (FST)|aspects]] as possible have their own links.  Any [[Extras]] are linked.  When I create a new [[Conspiracies|conspiracy]], the note  for that conspiracy has an active link to the [[Conspiracies]] note.  And any specific rules or rulings that get made for a given game world also get their own writeups to ensure that I don't repeat myself.  I can tag elements of my games with various values to make sure I don't forget things.

## How's It Going So Far?

So far, it has worked very well.  I can use some of the existing TTRPG plugins for [[Obsidian]] to further help manage my games and updates are automatically synced to my desktop systems (I use Dropbox and DropSync, but any sync service such as the for-pay Obsidian sync would likely work; Google Drive doesn't work well for a few reasons).  I manage to carry _far less_ stuff to the location where we play, since most of what I need is on a single Android tablet.  I carry a speaker for occasional music and can cast o the TV in the gaming area to show people data (almost always from this vault).

I will attempt to record some footage of me using this tool, both in planning and in-game.

## Using This Thing

There are multiple ways to use this repo.  

### The Easy Way
The easy way, if you're just going to use it as a reference or don't care about updates, is to download the latest version from the "Releases" page of this repository.  Unzip the archive and use your installed version of [[Obsidian]] to open the vault.  You will likely have quite a bit of trouble acquiring updates to the vault's data, but that's just part of the cost of doing things the easy way. 

### The Slightly Harder Way
The next level of difficulty involves cloning the repository directly using [[git]].  This will allow you to do several things:
1. You can pull updates directly from the `main` branch of this repository and as long as you haven't done anything too weird the updates should be mergeable.
2. Since you'll be working off a cloned [[git]] repo, you can branch and make modifications with the knowledge that you can roll back (usually).
3. You can also make a new upstream and push to that, if you understand how to work git.

For both the Easy and Slightly Harder ways, it is ***strongly*** suggested that you not modify any of the existing files.  A better idea would be to create a new folder called "Changes" or "My game" and put all your changes and new content in there. 

### The Actually Hard Way
The most correct way of using this repo (and really any [[Obsidian]] vault backed by [[git]]) is to fork this repository into your own GitHub account, clone your fork, and set this repository as an `upstream` remote.  That would allow you to:
1. Modify your fork of the repo at your discretion.
2. Push your changes back to your repository.
3. Merge changes from this repo (your `upstream`) into your repo while preserving your local changes.  It's not perfect, but we live in an imperfect world where [[git]] is the most popular source code management tool.

## Updates
I will make nominal "improvements" to the repo, and make new releases, as appropriate.  You can obtain those updates per the way you're [[#Using This Thing]].

