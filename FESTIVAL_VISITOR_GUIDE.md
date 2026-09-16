# Festival Visitor Guide

## Student Information

- Name: Alvin Ramcharran
- Course and section: CSC350 25081-LEC
- Date: 9/15/2026

## Repository Evidence

- Current branch:  main
- Personal Homework 2 GitHub URL:(https://github.com/alvinramcharran279-ops/CSC350-HW2-alvinramcharran279-ops)
- Starting `git status`: On branch main, nothing to commit, working tree clean
- Starting preparation commit ID: bd125dd

## Festival Identity

- Festival name: NY Beer Festival
- Location: Meadowbrook Commons, Kingston, NY
- Intended audience: Adults 21 and over
- Theme:  A place to taste beers from all around the world.

## Prediction Before the First Commit

1. Where does the saved change currently live?

   The saved change lives only in my working directory on my computer.

2. Has it been staged or committed?

   No, it has not been staged or committed yet. it is only an unstaged change.

## Arrival Information

- Transit or parking: Park in the Meadowbrook Commons paid lot. visitors pay for their own parking.
- Entrance or meeting location: Front Entrance of meadowbrook commons

## Accessibility Information

1. A wheelchair entrance is located on the west side of the venue.
2. Service and guide dogs are welcome throughout the festival grounds.

## Visitor Reminder

Do not leave your bags unattended and remember that tickets are non-refundable.

## GitHub Verification

   Verified on GitHub by Alvin Ramcharran.

## Commit Evidence

| Checkpoint | Short commit ID | Required message |
|---|---|---|
| Personalized guide | [7accf7b] | `docs: personalize festival visitor guide` |
| Visitor access information | [f439ad7] | `docs: add visitor access information` |
| GitHub verification | [2e2cb41] | `docs: verify independent homework on GitHub` |
| Final reflection | [ID] | `docs: complete independent Git reflection` |

## Individual Reflection

1. What is the difference between saving a file and committing it?

   Saving a file only updates it in my working directory, while committing records a permanent snapshot of the staged changes in my local repository's history.

2. What is the difference between `git diff` and `git diff --staged`?

   git diff shows changes that are not staged yet, while git diff --staged shows the staged changes that will be included in the next commit.

3. Why did the GitHub verification sentence not appear locally before `git pull`?

   The sentence was committed on GitHub, so my local repository was one commit behind until git pull downloaded that commit and updated my local file.

4. What did `-u` accomplish in `git push -u origin main`?

   the -u enabeled branch tracking so i didn't have to specify origin main every time.

5. What evidence proves that the local and GitHub repositories are synchronized at the end?

   git status tells me that i'm up to date with main and shows a clean working tree, and the newest commit in git log matches the one on github.

