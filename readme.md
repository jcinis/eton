# eton

Simple git-based note management built to be compatable with [GitJournal](https://gitjournal.io/).  Notes are saved in markdown but include an additional YAML header to track created and modified dates, title, tags and additional metadata.


## Installation

```eton``` expects ```~/notes``` to contain a git repository

```
cp eton ~/bin/
mkdir ~/notes
cd ~/notes
git init
```

## Usage
```
eton
eton --title "Brain Dance - Day 13708"
eton --title "Brain Dance - Day 13708" -t idea -t "brain dump"
```

## Format Example
```
---
created: 2019-12-04 23:48:44+00:00
modified: 2018-10-28 01:04:02+00:00
title: Brain Dance - Day 13708
tags: idea, brain dump
---

# Brain Dance - Day 13708

- Authenticity is time-bound.  Authenticity is always a slippery term, because on multiple dimensions it has loose boundaries.  One can only know authenticity in one’s own actions, within one’s own culture, and in one’s time.
- Individuals often have unconscious, but incredibly well-formed and tribal views of what “fun” should look like.  Unless we are exposed and open to deeply learning about how and why others are having “fun”, we will live less dynamic and “fun” lives as experiences become routine and the ladder we are climbing begins to look like the only one.
- The desire to quickly signal connection or status is the primary driver of behavior and conversation and most social situations.  Taking a moment to disassociate and to be silent together is often far more powerful connector due to its honesty and vulnerability.
```

