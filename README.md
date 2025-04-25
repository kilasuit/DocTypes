---
title: DocTypes Readme
date: 2025-Apr-22
author: kilasuit
initalAuthor: kilasuit
docOwner: kilasuit
#updatedDate:
#updatedBy:
#updateReason:
---
<!-- markdownlint-disable MD025 MD033-->
# DocTypes

Note - This project & many linked projects uses British English for spelling, be mindful of this when reading though this and other repos.

## TLDR (Too long Didn't Read)

We use lots of different files or documents in our life, and this repo should help anyone coming into tech understand different types of documents that maybe in use already, as well as bringing some new ones that we sorta use, or may use but call them something else.

As such I recommend learning about and using as many of these types of document as as part by your own life & across the teams you work with in your current/future projects.

## The Longer Version

We likely all know of [The Pains of Poor/Missing Documentation](https://blog.kilasuit.org/2016/04/15/the-pains-of-poormissing-documentation/) and whilst many of us `detest` documentation, whether writing it or reading it, it's one of the things that we can & should commit and push ourselves to do better as we continue to evolve in our lives.

Whilst AI tools & others may help out with authoring and maintaining, for teams that can't or won't use them, this repository and linked ones, should enable us when usign the docTypes here to be better "Documentarians" (not my term & is usually used for those that produce tother media types, like audio/visual documentaries) or more aptly `Document Historians` which may be referred to as a [documentalist](https://wikidiff.com/documentarist/documentalist) (not that I like that term much) helping ensure that any information that helps ensure that `important contexts` are not lost & can be shared, importantly back with ourselves, let alone the sharing that we are doing with others too.

This repo & others that that are linked to, should be seen as a Work In Progress from `Apr 2025` onwards until either a [FIN](#final-interaction-notes-fins) has been published & the repo has been archived or gets moved to another organisation.

It will contain many `teachable moments` and will showcase the power of using software development practices to track, manage and publish all kinds of docs.

### Research Areas

This repo and it's contents & linked repos (particularly those I am authoring and maintaining) are a part of research that I am doing into the following areas

- Business Management (following on from my Level 3 NVQ in Business & Administration)
- The Tech Industry in General
  - Software Development Processes
    - ALM
    - DevOps
    - Platform & Systems Engineering
    - Secure Software Development
- [Psychology](https://en.wikipedia.org/wiki/Psychology)
  - Psychology in Business / [Industrial & Organisational Psychology](https://en.wikipedia.org/wiki/Industrial_and_organizational_psychology)
  - [Sociology](https://en.wikipedia.org/wiki/Sociology)

Research here will be linked to and posted on [my blog](https://blog.kilasuit.org) or where relevant the [Mental Health Affects Someone Like Me Site](https://mhasl.me) as well as being linked to in [my OrcID profile.](https://orcid.org/0009-0009-6030-3517)

All Research will also form the basis for Discussions or Presentations at User Groups, Conferences and other events, if you are interested in me speaking about all of this then please fill [in this Issue](addlateer)

This as research covers many areas, it will be used as evidence for any courses that I may apply to, as well as future ones that I may build & teach across [the different levels of education we use in the United Kingdom,](https://www.gov.uk/what-different-qualification-levels-mean/list-of-qualification-levels) all the way up to PhD / Level 8 qualification.

I hope that during the life of this project that I will be able to make use of the fantastic book [Managing your Mental Health during your PhD: A Survival Guide](https://link.springer.com/book/10.1007/978-3-031-14194-2) by Zoë J. Ayres

### Project Goals

These are detailed in this project's [Initial ADR](docs/ADRs/ADR001-2025-Apr-17-Initial.md/#) with main key deliverable of sharing knowledge, starting discussions, and having teachable moments.

In time this repository will be published to it's own site, with that to be something done as part of a build & release process.

This will contain links to other repositories or suitable material where those processes are already in place and ones that I recommend using.

We will add many others that can be used in the setup of your project to enable you to better document your project along with it's processes and who may in a project need to follow these processes.

This is entirely provided to enable discussion and debate around the Human element of as well as a number of different areas of Software Development, and where possible is meant to enable discussions with others with similar processes to utilise them as they are or adapt them and provide feedback.

As such this project will introduce you to a number of, what we believe to be core documents as well as any processes that are required to get the most out of those documents. These should enable you and others to engage with this and other projects in future in as transparent as possible.

## Typical Documents

### Contracts

There are lots of different types of documents that we refer to as contracts
These are vast enough that this could & should be it's own repository or link to another source.
As such at this time, I am pondering about how these are to feature in this project.

### Design Documents

We use design documents, often called Architecture Design Docs, to show the vast amount of items we require to combine together to get the end product.

In some areas you may hear, High Level & Low Level Design be used, you may even hear Recipe being used.

These documents can regularly be entirely held in peoples heads or have been put together on a whiteboard and live in someones photo album.

These documents are **cruical** for onboarding new team members and for ensuring that products are built to the intended specifications & is why sometimes you may hear  people speak of recipes, that and it reminds us subconciously to make sure we actually do eat.

### Configuration Documents

That said, we often find we skip building a Design Document, as we build a solution on the go and do so using some form of configuration document. You likely will have heard of the term Infrastructure as Code (IaC) & you may also have heard of the term Configuration as Code (CaC) and whilst they are similar, they often form part of an overall Application as Code (AaC) definition, which allows developers and adminstrators to work together in maintaining these definitions.

Both of these work together, with IaC, and are a repeatable, easily sharable mechanism for your future projects.

They also are important for sharing a machine config when diagnosing issues with software & may be requested to help determine if issues are caused by other software,

These and sample configurations will be hosted in the [ConfigDocs repository](https://github.com/kilasuit/ConfigDocs) when I get around to it.

### Repo Config

This is an immense area, and due to this is to be detailed in the [RepoConfig repository](https://github.com/kilasuit/RepoConfig) when I get around to it.

### Architecture/Any Decision Record (ADR) / MADR

These documents help with determining a point in time of why certain things around the structure/architecture of the project were chosen as well as why they changed in a way that pulls that information out from peoples heads.

This helps massively in determining project health, onboarding new people and much more & as such are highly recommended for you to use in your projects.

I have some ADR's in my [PSProfile repo](https://github.com/kilasuit/PSProfile) which is a living repo for changes to my PowerShell Profile as I start making use more of alternative Operating Systems to the Windows set of Operating systems, like Ubuntu and other Linux variations, not for the first time in life either. I am working on adding them to other repos of mine too.

People with the following Job Titles are common examples of individuals who may be tasked with writing these particular docs

- Project Architect (which may be know as Project/Programme Manager)
- Software Architect/Developer
- Consultant
- IT Practitioner
- DevOps/Platform Engineer
- Site Reliability Engineer
- Systems Administrator
- Trainer

ADR's may be contained as either their own docs or contained as part of Meeting Notes, though it is preferential to make seperate docs as you can provide a fuid (fully Unique Identifier) that enables .

For more info on these please read up on

<https://github.com/adr/madr>
<https://adr.github.io/madr/>

### IINs, DINs & FINs....?

The process of using IINs -> DINs -> FINs is useful for you taking 1/more ideas -> starting projects -> working PoC -> working developed project -> retiring a project.

It is also useful from a psychological perspective in giving you and/or others a more useful form of closure on all manner of things & as such whether you document these via electronic methods or not, or even just verbalise them, can be a help of relief for you and others.

This is especially true as often we are taught to `ask why` and is why many of us instinctively use the `5 whys` technique in our day to day lives.

#### Initial Interaction Notes (IINs)

The Initial Interaction Notes or known as IINs are documented in their [own repository](https://github.com/kilasuit/InitialInteractionNotes) and you can see some sample IIN's as I start authoring them in [this repository](https://github.com/kilasuit/IINs), like the partial IIN for the [Scott and Mark Learn To series](https://github.com/kilasuit/IINs/blob/main/docs/IINs/mine/TechStuff/Scott_and_Mark/Partial/IIN-P01-2025-04-017-Series.md) with plenty more of these to come in the coming weeks & months ahead, including a number of different IINs around bits of technology like PowerShell, PowerShell DSC (PSDSC) & it's evolution to DSC, Windows (Client/Mobile/Server), Ubuntu, VSCode, Docker/devContainers/Kubernettes and countless others.

These are of great use for sharing a quick `This is what I thought` of new things.

I don't expect that all potential IIN's will get documented but it would be nice to see more people using them

#### Developing Interaction Notes (DINs)

The Developing Interaction Notes or known as DINs are documented in their [own repository](https://github.com/kilasuit/DevelopingInteractionNotes) and you can see some sample DIN's in [this repository](https://github.com/kilasuit/DINs), like the DIN's I'm intending authoring around my ongoing & somewhat developing experience with the GitHub Platform.

It also will be used for ongoing developing experiences that I am in process of working on, like how you can use automation tooling for taking private work & moving and publishing it to the public.

#### Final Interaction Notes (FINs)

The Final Interaction Notes or known as FINs are documented in their [own repository](https://github.com/kilasuit/FinalInteractionNotes) and you can see some sample FIN's in [this repository](https://github.com/kilasuit/FINs), like the FINs I'm intending authoring around my experiences with things like the SurfaceBook 2, Windows Mobile, other devices & much more in future.

Whilst these notes are called Final, they may be `Temporary` or a `Final for now` type, which is of use when you are between projects but likely to come back to them, but they may very likely also be `Permanent` because you've decided it's time to move on to something different, or had been forced to (RIP Windows Mobile)

An area these are useful for, is providing feedback to Landlords when you move properties, and also as part of your handover notes when leaving an organisation.

### Adopters

This DocType is a file that is often used in OpenSource projects to show who has adopted a project, whether it be all of the project, or parts from the project.

For Example, I @kilasuit, am an Adopter of many of these DocTypes, particularly those that are in other repoistories of mine.

### InspiredBy

As projects start they either have one or many things that have given the project the inital inspiration required for the project to start.

Sometimes this comes from other projects or in a number of cases, may have been **InspiredBy** a thought in the shower, bath or doing other tasks, like mindless browsing, scrolling & generally being content sponge as part of our ways that help us relax and destress.

They could have been sparked ✨ by a converstation you've had with others, and

The `InspiredBy.md` file should be linked to in a Project ReadMe whether contained in the repository or pointing to another living document, like an existing document or an authored book or other articles, including any links to published research or projects and providing that important citation, whilst mentioning and and respecting any licenses

When located in the repository it should be located in the `docs` folder contained in the repository root.

An example of this file is located in [PSProfile InspiredBy](https://github.com/kilasuit/PSProfile)

However, it is also fine for a projects Readme to include a section detailing what inspired the project. The recommendation to have it as a seperate document is to maintain seperate file histories, especially as multiple projects may want to share a starter InspiredBy document where the history can be tracked and traced back as time & the projects evolves

The decison to use TitleCase for this file is to allow future localisation as well as easier searchability using hashtag based searching across social media & whilst I'd like to say it **must** be used as a name for this file or readme section, it is of course your choice, however you will be limiting tracability as well as my planned reporting for this project.

### Mental Notes

Mental Notes are a doc type that we all use on a daily basis, and whilst they aren't typically something many share very well if they intend to share them.

They also often get forgotton or overwritten, perhaps by something more pressing and important, or more often than not, just because we have moved on to something else.

To get around this issue, Mental Notes something that I found best to record using very quick TODO software like Microsoft ToDo, or audio recordings or dictations into note software like OneNote.

It's only recently that I have been on/off once again making more use of dictation to help me as with keeping track of these mental notes & speech driven development (SDD) will be a big area in latter half of 2025 & beyond.

### Meeting Notes

Taking notes from meetings, is a fine art, many of us are great at taking and committing our mental notes, or taking physical notes, whilst others prefer a meeting summary or rely on meeting transcripts (when they are hosted using remote technologies) or a mix of all of these together.

Notes may be offline only using non-digital means like real pens and paper.

Though more often than not there are some notes taken & for many in the Tech space they may take offline as well as digital notes via writing/typing, dictation, video recordings or even by use of Assistive Intelligent Agents, whether they be of the human kind, our pets, or technology like AI tooling like the many different Co-pilot or agent technologies that are out there.

When writing this may be by using touch screen friendly tablets in apps like OneNote or Evernote, Word, PowerPoint, Visio, or Paint. You may even write physical notes that use special papers and pens that digitise the notes at the time of writing them, giving both an online and offline set of notes.
You may use exosketches or similar, or physical whiteboards or digital whiteboarding apps that allow multi-editin whether in-person or via remote sharing.
You may even make use of this in collaboration apps like the Office set of applications, which is something that is very well used today.
You may also use remote co-authoring technologies of Meeting Notes, including via the Co-Authoring experinces that Microsoft 365 & Google Docs provide, or in files like via markdown files, using technologies like [Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/) & similar tech (happy for a PR here with other similar services) to share live access to a file or project that you are working on.

Notes are so so important, that we have discussions and <u><b>meetings</b></u> about notes, like `How to take them, when to take them, who to take them` and much more. We also, as *you* may have **noted** here, may have *notes* that are about **notes** which are linked to more `notes` about other NOTES that we have perhaps mentally nOtEd that we need to make a N0t3 of in more detail than just in our heads and to tell others about them.

I don't now about you, but that's a lot of areas where our notes are interlinked, which makes it incredibly easy to be forget about a task around either a single note or set of notes.

It's also beneficial for most if not all types of meetings, including ones where IINs, DINs & FINs may be of use, to have notes openly (perhaps though for some they should not be publicly accessible) published somewhere, as this enables those that missed the meeting to review discussion points & play catchup. That said with AI we may see less of this, however, having Meeting Notes captured is imporrant, so important, I feel that extra r is required there 😉 🏴‍☠️

### Privacy Polices

As AI is used more this will be something that many projects should have and for it to detail when & why AI Tools are used, as well as which tools are used.

The use of AI Tools is covered in this project's [Initial ADR](docs/ADRs/ADR001-2025-Apr-17-Initial.md/#used-technologies) & if this changes in a future ADR, this link shall be be updated.

### Donation Polices

As more and more of us are facing periods of unemployment, whether attached to a formal course of study, or like I am, `doing my own tings` we should all be using a Donation Policy of some sorts

I do have the Sponsorship and Funding options that GitHub provides as part of GitHub Sponsorships, as well as others that are listed in my [Donation Policy Page on my blog,](https://blog.kilasuit.org) which details bits around donations, whether they be financial or

## Science behind taking Notes

It is important to Note (forgive the pun😛) that the art of note taking is beneficial for our memory, however we take those notes, as well as for our general mental health, and is why many who engage with Mental Health Services, whether that be via counselling or via a number of differing therapies. Therefore it's good for individuals to not just take mental notes, but then spend the time to convert them into physical ones to.

I have written a little about the importance of note taking as part of [It's #TimeToTalk, But it's also #TimeToWrite](https://mhasl.me/2019/02/07/its-timetotalk-but-its-also-timetowrite/) which was a post tied in with the #TimeToTalkDay which occurs on the 7th February.

It is also similarly important for mental cleansing, if you work in Software Development, and also elsewhere in life, to regularly spend time doing document related tasks, whether that be responing to or shredding documents, much like it is important in dealing with Emails & your ongoing Tasks list.
