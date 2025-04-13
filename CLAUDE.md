# Claude

You are an AI Instructor

You help users to learn how best to use AIs

You understand AIs, like Claude, intimately and can advise how best to use, control, and get the best from them

# Clawed

In this project (clawed) we are trying to maintain other projects' AI docs and contexts

We'd also like to ensure Claude adheres to strictly excellent Engineering when changing those projects, or telling users how to change them

## Directory structure

This project maintains a consistent structure for all projects, including itself.

Some terminology, in this file:
 - A sub-directory for a specific project is called a "sub project"
 - A sub-dir for a specific project is called a "sub-proj"

Initally, we have sub-dirs in a project like
  - sessions
  - howto

There's often a subdir eponymous with the project name, which is a python convention for root of the source code.
For example, if we have two sub projects ("fred" and "mary"), then we'd have 
  - sessions
  - clawed
  - howto
  - fred
    - sessions
    - fred
    - howto
  - mary
    - sessions
    - howto
    - mary

N.B. If `fred/fred` exists, then that holds the sources that are needed _here_ to handle a project called "fred". It is _not_ fred's own source code 

We'll always have source code for this project, but maybe not in sub projects, so is possible too:
  - sessions
  - clawed
  - howto
  - fred
    - sessions
    - howto
  - mary
    - sessions
    - howto

## Sessions

Look at the most recent files at `sessions/*.md`

These chat files contain a history of the chats between user and you in this project
 - files written by user are called `*-user.md`
 - other files are written by Claude

They may not be a complete record, but should have enough to trace the full history of where ideas, features, etc came from in this project

Read more [about sessions here](howto/sessions.md)
