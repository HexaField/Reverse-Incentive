# Reverse Incentive

*Systemic change requires systems thinking*

*(Disclaimer: This project is in it's early stages, and thus all containing materials must be taken with a grain of salt. All collaborators are not liable for erroneous information contained therein. All project methodologies are subject to change. View [the contributing document](./contributing.md)) if you would like to get involved.*

## The Project

The universe we find ourselves in is rather [complex](https://en.wikipedia.org/wiki/Cynefin_framework). Navigating the structures and systems that dictate how we operate as a civilisation is becoming [increasingly difficult](https://www.youtube.com/watch?v=7LqaotiGWjQ). Reverse Incentive is a project designed to disambiguate and map [hyperobjects](https://www.hcn.org/issues/47.1/introducing-the-idea-of-hyperobjects), allowing us to have a better grasp of the [territory](https://fs.blog/2015/11/map-and-territory/).

## The architecture - open source data

Github acts as an asynchronous collaboration tool, as well as a database / repository. Running a website off this repository that allows users to explore the data contained in this project. This is the broader intention - to make the data as user friendly, therefor as comprehendable, as possible.

The planned methodology is for the project maintainers to be the maintainers of the 'live' version (on the website). This repository can then be forked, and changes made into PRs as per the usual github workflow.

The data itself will be contained in JSON documents. There will need to be a large degree of experimentation and iteration to converge on an adequate data structure, though it should be largely as simple as adding arbitrary data and references to other documents. This can be thought of similar to wikipedia.

## The client - distributed collaboration 

The client is a peer to peer solution for instant collaboration. Basically p2p google docs for JSON. Idk, it might be unnecessary, or something might already exist. The current idea is that this can run as a standalone client, or connected from the main webpage via github login portal. Users can then create and join sessions, which allows instant 

(see [client.md](./client.md) for implementation details - todo)

## The endpoint - data as a resource

Hosting an endpoint allows external tools to provider richer visaulisations. Something something anti-rivalry...

## The result - a meta ecosystem of systems thinking

Yup. Says it all.