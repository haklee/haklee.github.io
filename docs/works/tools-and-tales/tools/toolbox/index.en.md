---
title: "Toolbox"
---

*(last modified: 2025. 04. 04.)*

## Intro

Lately, I've started thinking that tools can be changed or learned anew at any time depending on the project. However, life is finite and the time available to use tools is limited, so unfortunately it will be impossible for me to master all the tools. But even so, with the mindset of trying my best to use the tools I want to try out, I keep learning new tools. Here, I will list the tools I have used so far.

| Proficiency  | Description |
| :-----: | :--- |
|    1    | Slightly attempted. Used the tool for 0-1 projects. |
|    2    | Have used it but not so familiar. Worked on 1-2 projects with it. |
|    3    | At a level where I roughly understand what can be done with the tool, and what skills need to be further studied. Worked on 2-3 projects with it. |
|    4    | Skilled enough to choose it as a primary tool for projects. Clearly know what I don't know about it. |
|    5    | Use the tool's language as a part of my body/being. |

## Language

| Tool       | Proficiency | Description |
| :--------- | :----: | :--- |
| python3    | 4      | I used it as the main language for developing simple servers, task queues, packages for geometric operations, or solving various algorithmic problems.|
| javascript | 3      | I have mainly dealt with JavaScript for server development purposes, and have worked with it a bit for front-end development as well. |
| typescript | 2      | Although I developed the server based on TypeScript, I rated my proficiency level lower because I felt that my understanding of the type system itself was not sufficient. |
| C#         | 3      | I mainly used C# for projects dealing with RhinoCommon and the AutoCAD .NET API. |
| C++        | 2      | I first used it while maintaining games in Ngine Studios, and afterwards, I used it a bit for implementing algorithms to solve geometric problems where performance was important, as well as for WebAssembly (wasm). |
| Kotlin     | 2      | I have briefly used it while studying application development. |
| Dart       | 2      | I have briefly used it while studying application development. |
| R          | 1      | I briefly worked with it while participating in a study group invited within SNU Urban Form and Conservation Lab. |

## Web Service - related

### Framework

| Tool    | Proficiency | Description |
| :------ | :----: | :--- |
| NestJS  | 4      | I started with server development using Express, but later settled on NestJS. I have utilized features such as socket communication, logging, guards, type checking, simple testing, Swagger integration, and various ORM integrations. Additionally, I have implemented functionalities like login, cloud storage integration, and task queue integration. |
| Next.js | 2      | I briefly worked with it for creating toy projects that integrated the front-end and server. |
| Flask   | 2      | I briefly used Flask when I needed to add server functionality to projects based on Python. |
| Django  | 2      | I briefly worked with it creating an API server that integrates with Celery. After examining DRF and Django Ninja, I chose to use Django Ninja for the following reasons: DRF seemed too tightly coupled with ORM, and Django Ninja was much easier to use initially. |

### library

| 도구    | 숙련도 | 설명 |
| :------ | :----: | :--- |
| Zustand  | 2      | I started using it while looking for a good library to use instead of the complex Redux for state management in React. After comparing it with Jotai, it seemed to have a structure more suitable for larger projects, and looking at the number of downloads on npm, it seemed like more people were using it, so I chose it. My understanding of Zustand is limited to knowing that when trying to use it with Next.js, there's a conflict between the server needing to be stateless and Zustand managing state globally, so this needs to be taken into consideration. |
| R3F | 1 (AI)      | I started exploring its use for implementing processing-like screens on web pages. Initially, I was looking at Three.js, but then I saw that R3F (React Three Fiber) seemed to be easier to use with React, so I began creating various things with Cursor AI. |

### Query Builder / ORM

| Tool    | Proficiency | Description |
| :------ | :----: | :--- |
| TypeORM | 2      | I worked with TypeORM while maintaining a project that was implemented with it. However, the ORM's entity-based perspective of viewing the database didn't suit my preference, so I later transitioned to the query builder. |
| Kysely  | 3      | Being familiar with writing queries, I was drawn to Kysely for its TypeScript-friendly nature and settled on using it as my query builder. |
| Prisma  | 1      | While looking for a query builder/ORM to replace TypeORM, I briefly tried Prisma. However, at the time, it did not yet support various geometric data types in MySQL, so I moved on. |

### MQ

| Tool   | Proficiency | Description |
| :----- | :----: | :--- |
| Celery | 3      | I started using Celery to integrate task queues with functionalities implemented in Python |
| ZeroMQ | 2      | I first encountered ZeroMQ when creating internal tools at Ngine Studios, and later briefly used it to implement a task queue for a server built with Node.js. |

### Monitoring

| Tool       | Proficiency | Description |
| :--------- | :----: | :--- |
| Prometheus | 2      | I have used it for service monitoring. |
| Grafana    | 2      | I have used it for service monitoring. |

### Testing

| Tool     | Proficiency | Description |
| :------- | :----: | :--- |
| Swagger  | 2      | I have mainly used Swagger in conjunction with NestJS for manually testing various API functionalities. |
| Postman  | 3      | I have used Postman for manually testing API functionalities or when I needed to perform a series of consecutive API calls. |
| Insomnia | 1      | I have used Insomnia before using Postman for manually testing API functionalities. |

## Version Control

| Tool | Proficiency | Description |
| :--- | :----: | :--- |
| git  | 4      | Through various trials and errors, I learned how to use Git. I have acquired an understanding to a degree where I can create and establish a modified gitflow strategy tailored to the development team's situation. |

## Project Management

| Tool       | Proficiency | Description |
| :--------- | :----: | :--- |
| Jira       | 3      | I first utilized it during the game maintenance process at Ngine Studios, and I have an understanding level where I can create and experimentally use a ticket management strategy tailored to the development team's situation. |
| Confluence | 3      | I first utilized it during the documentation process for code maintenance at Ngine Studios. |
| Trello     | 2      | I once used it to manage personal schedules and task lists for planning and implementing small toy projects, but I am not using it currently. |
| Notion     | 2      | I once used Notion for organizing personal materials and creating landing pages for small toy projects, but I am not using it currently. |
| Slack      | 3      | In the various teams I have been a part of so far, I have commonly used it. I have an understanding level where I can create a Slack bot to log necessary content and implement simple voting functions. |

## Database

| Tool       | Proficiency | Description |
| :--------- | :----: | :--- |
| MySQL      | 4      | I have performed tasks ranging from basic database design for service operations to setting spatial indexes, optimizing slow queries, writing recursive queries using CTEs, creating triggers and procedures, as well as database dumps and migrations. |
| PostgreSQL | 3      | In situations where I need to create a service from scratch, I mainly choose MySQL, but I have also worked on several toy projects utilizing PostgreSQL. |
| SQLite     | 2      | There have been a few instances where I used SQLite when developing apps that required a local database. |
| Redis      | 2      | I have utilized Redis when dealing with task queues, and there have been a few instances where I used Redis in situations where data did not necessarily need to be managed with a relational database. |

## Deployment

| Tool           | Proficiency | Description |
| :------------- | :----: | :--- |
| pm2            | 3      | I frequently utilized it for zero-downtime server deployment and log inspection. |
| docker         | 3      | I have utilized it in various deployment scenarios. Since I have only used it focusing on the features needed for each situation, I think that my overall understanding may not be very high. |
| docker compose | 3      | I have utilized it in various deployment scenarios. Since I have only used it focusing on the features needed for each situation, I think that my overall understanding may not be very high. |
| github action  | 2      | The current site is managed by using Github Actions to automate deployment. |

## 3D/CAD

| Tool                      | Proficiency | Description |
| :------------------------ | :----: | :--- |
| Rhino3D                   | 2      | I have briefly used it while taking architecture major courses. |
| Grasshopper               | 4      | I utilized it in architectural major courses and various external projects. Even when I couldn't create the desired form using Rhino3D, there were many cases where the work was possible with Grasshopper. |
| RhinoCommon               | 4      | I utilized it in various external projects. Before RhinoCompute came out, I judged that it would be difficult to rely on Rhino for commercial projects, so I barely used it. However, since 2024, I have been trying to use it again. |
| AutoCAD                   | 2      | I have briefly used it while taking architecture major courses. |
| AutoCAD .NET API          | 3      | In 2024, while exploring the features utilizing various Autodesk product lines, I used it for the first time. |
| AutoLISP                  | 1      | While looking for ways to incorporate programming into AutoCAD, I briefly studied it. However, as my interest shifted towards utilizing the .NET API, I did not explore it in more depth. |
| Dynamic Block(AutoCAD)    | 2      | While exploring AutoCAD's features, I discovered some functions that could be easily implemented through dynamic blocks, so I tried working with them a little bit. |
| Revit                     | 2      | I have briefly used it to use Dynamo. |
| Dynamo(Revit)             | 2      | I heard an explanation that it provides features corresponding to Grasshopper in Rhino3D, so I briefly tried using it. However, since I was not familiar with Revit, I only followed some basic tutorials and did not use it extensively after that. |
| Autodesk Platform Service | 2      | I followed some basic tutorials after seeing through some examples that it can be utilized to automate functions that can be performed within Revit and AutoCAD |
| Blender                   | 2      | I have briefly used it for personal projects. I used it and then forgot it several times, so I took Blender Guru's donut tutorial about three times. But it's been a long time since I last used it so I've almost forgotten it now. |
| Cinema4D                  | 2      | I have briefly used it for personal projects. I used it and then forgot it several times, so I took Greyscalegorilla's basic tutorial about two times. But it's been a long time since I last used it so I've almost forgotten it now. |
| 3ds Max                   | 1      | I have briefly used it while taking media art major courses. |
| SketchUp                  | 1      | I have briefly used it while taking architecture major courses. |
| SolidWorks                | 1      | I have briefly used it while taking mechanical engineering major courses. |
| QGIS                      | 2      | In the first semester of 2017, I first used QGIS to utilize geographic information provided by the public data portal for a design project. In the second semester, I used QGIS integrated with Python to analyze pedestrian data in Undergraduate Independent Study course. After that, I conducted a workshop over several weeks to explain how to use QGIS to undergraduate and graduate students in the Department of Architecture & Architectural Engineering. But it's been a long time since I last used it so I've almost forgotten it now. |

## 2D

| Tool              | Proficiency | Description |
| :---------------- | :----: | :--- |
| Adobe Photoshop   | 3      | I have briefly used it while taking architecture major courses. |
| Adobe Illustrator | 2      | I have briefly used it while taking architecture major courses. |
| Adobe InDesign    | 2      | I have briefly used it while taking architecture major courses. |

## Video

| Tool                | Proficiency | Description |
| :------------------ | :----: | :--- |
| Adobe Premiere Pro  | 3      | I have briefly used it while taking media art major courses. |
| Adobe After Effects | 1      | I have briefly used it while taking media art major courses. |

## Sound

| Tool          | Proficiency | Description |
| :------------ | :----: | :--- |
| SuperCollider | 1      | I have briefly used it while taking media art major courses. I used it and then forgot it several times, so I took Eli Fieldsteel's basic tutorial about three times. But it's been a long time since I last used it so I've almost forgotten it now. |
| Pure Data     | 1      | I have briefly used it while taking media art major courses. |
| Max/MSP       | 1      | I have briefly used it while taking media art major courses. |
| FL Studio     | 1      | I have briefly used it for personal projects. |
| Cubase        | 1      | I have briefly used it for personal projects. |
| Ableton Live  | 1      | I have briefly used it for personal projects. |
| GoldWave      | 1      | I have briefly used it for personal projects. |

## Graphics & Other

| Tool           | Proficiency | Description |
| :------------- | :----: | :--- |
| Processing     | 1      | I have briefly used it while taking media art major courses. |
| vvvv           | 1      | I have briefly used it while taking media art major courses. |
| Resolume Arena | 1      | I have briefly used it for personal projects. |
| TouchDesigner  | 1      | It was not covered in class, but I briefly used it to test what kind of features it has. |
| OpenGL         | 1      | I used it to verify the results of geometrical algorithms implemented in C++. |
| Vulkan         | 1      | While searching for graphics-related materials, I discovered it and became interested, so I briefly tried it out. After writing a 900-line "hello triangle" code, I lost interest. |

## Electronics

| Tool         | Proficiency | Description |
| :----------- | :----: | :--- |
| Arduino      | 3      | I have briefly used it while taking media art major courses. |
| Raspberry Pi | 2      | For the second version of the homepage, I implemented it by installing a WorkPress site on a home server set with r-pi. |
| Synology NAS | 2      | For the first version of the homepage, I implemented it by uploading a site made with Indexhibit on a Nas. |
