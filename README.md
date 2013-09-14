tenos
=====

Tenos is the codenamed project for an AR Meeting Room application. As a log line it effectively acts as a UI and immersive based experience for interacting with conference room and meeting data for an office.

# Roadmap
The roadmap lies here to help guide the high level direction of the development.

## Introduction
The project has 3 pillars, a data source, geographcial and orientational tracking, and then rendering and displaying the former two.

The prioritized focus will be on the latter, and using dummy sources if needed for the former two.

## Test Cases
Write even the most simple of test cases that can be automated, and require
essentially no maintenance, as they will help with make sure new stuff does not break the old stuff.

# Git Branching
Serves as basic guidelines and tips for using the nvie.com Git workflow model.

## Introduction and Justification
This workflow model serves as a way to insulate the master which is 
automatically built via scripts and the free Adobe Cloud builder we get.

Insulating the master from changes coming upstream also allows the maintainers
to organize features against the backlog, and incoming assets. This should 
decrease time for acceptance/rejection of pull requests.

## The Main Branches
This is desribed extraordinarly better in the main article and is the source of the inclusive picture. master is built from automatically, and should ALWAYS be green. Lemme stress this: master is what would roll out to production so make
sure it is fucking green before we build it.
