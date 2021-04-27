# Teaching-HEIGVD-RES-2021 (PT)
This is the main repo for the course RES, taught at HEIG-VD in 2021. 

This is where you will find lecture notes, slides and some of the examples presented in the class. We will also keep links to the different repos used throughout the semester (for assignments).

## Upcoming deadlines

* Sunday, **May 2nd** (23 PM): submit the SMTP lab results
  * You work in pairs
  * You have 3 lab sessions to do the job, BUT we strongly advise you to give it a push and to do (most of) it this week
  * Starting next week, we continue with HTTP and Docker, so it will be more comfortable if you put it behind you.
* **Thursday, April 22nd and Thursday, April 29th**, I will not give a live lecture. A lot of video content was produced last year to introduce 2 key topics: HTTP and Docker. You will consume this content during these sessions and make sure that you.
* Pay **very close attention** to these videos. Make sure that you run the experiments and practical steps yourself. Take notes. In the **next written test**, you will very likely have to solve challenges with Docker (on your machine). You must be able to read and write complete HTTP requests on paper and in a program.

## Tentative schedule

| Week              | Course                                         | Lab                                         |
| ----------------- | ---------------------------------------------- | ------------------------------------------- |
| 1                 | Introduction, process & tools                  | Chill Protocol (no grade)                   |
| 2                 | Java IO - part 1                               | Java IO                                     |
| 3                 | Java IO - part 2                               | **Java IO (grade, weight 1)**               |
| 4                 | TCP programming                                | Protocol design exercise (no grade)         |
| 5                 | TCP programming                                | Protocol implementation exercise (no grade) |
| 6                 | **Test 1**                                     | SMTP lab                                    |
| **Eastern break** |                                                |                                             |
| 7                 | SMTP                                           | SMTP lab                                    |
| 8                 | **Web casts**: HTTP Protocol + intro to Docker | SMTP lab                                    |
| 9 (29/04)         | **Web casts**: HTTP Protocol + intro to Docker | **SMTP lab (grade, weight 1)**              |
| 10 (06/05)        | **Live**: HTTP infrastructure                  | HTTP infra lab                              |
| 11 (13/05)        | Ascencion                                      | HTTP infra lab                              |
| 12 (20/05)        | **Test 2**                                     | HTTP infra lab                              |
| 13 (27/05)        | HTTP infra lab (grade)                         | **HTTP infra lab (grade, weight 3)**        |
| 14 (03/06)        | **Live**: UDP programming                      | UDP Lab (orchestra)                         |
| 15 (10/06)        | UDP Lab (orchestra)                            | UDP Lab (orchestra)                         |
| 16 (17/06)        | Semester review & exam prep                    | **UDP Lab (orchestra) (grade, weight 1)**   |

## Repo for the labs

| Title                    | Repo (new repos need to be created for 2021)                 | Webcasts                                                     | Graded |
| ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| Chill Protocol           | https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2021-Chill | [RES 2021 Playlist](https://www.youtube.com/playlist?list=PLfKkysTy70QY_C0t9avTuEsLVVObxOtTM) (12 webcasts, ~2 hours). *We need to update this, in order to use GitHub Actions instead of TravisCI.* Also see [this article](https://medium.com/software-engineering-heig-vd/network-programming-res-prelude-eab67078955a) on Medium. | no     |
| Labo Java IO             | https://github.com/SoftEng-HEIGVD/https-github.com-SoftEng-HEIGVD-Teaching-HEIGVD-RES-2021-Labo-Java-IO | 3 webcasts have been added to the RES 2021 playlist          | yes    |
| Protocol design exercise | https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2021-Exercise-Protocol-Design | 1 webcast has been added to the RES 2021 playlist.           | no     |
| SMTP                     | https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2021-Labo-SMTP | 4 webcasts have been added to the RES 2021 playlist.         | yes    |
|                          |                                                              |                                                              |        |
|                          |                                                              |                                                              |        |
|                          |                                                              |                                                              |        |
|                          |                                                              |                                                              |        |

## Resources

- YouTube [playlist](https://www.youtube.com/playlist?list=PLfKkysTy70QY_C0t9avTuEsLVVObxOtTM)

## 

## Week 1

* Course introduction: objectives, semester planning, intro to first lab
* The "Chill Protocol" lab
  * Get familiar with the GitHub workflow
  * Get familiar with toolset and practices that will be used during the semester (maven, lombok, JUnit)
  * See a first example of a "communication" protocol 
* [Slides](./slides/00-Introduction.pdf)

## Week 2

* Java IO, part 1
* The Java IO Lab (file operations)
* [Slides](./slides/01-JavaIOs.pdf)

## Week 3

* Java IO, part 2
* The Java IO Lab (file operations)
* [Slides](./slides/01-JavaIOs.pdf)

## Week 4

* Webcast for the lab: https://www.youtube.com/watch?v=95GwsyiSMXI (added to the RES 2021 playlist)
* TCP programming, part 1
* [Slides](./slides/02-TcpProgramming.pdf) and [extra slides](./slides/02-TcpProgramming.pdf).
* Recommended activities for the lab:
  * Start by reading the guidelines in the lab repo (https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2021-Exercise-Protocol-Design)
  * Do the exercise in a pair
  * Watch my solution
  * Redo the exercise (make sure that you are able to reapply the process for another protocol)
  * Read and run the TCP examples

## Week 5

* TCP programming, part 2
* [Slides](./slides/02-TcpProgramming.pdf) and [extra slides](./slides/02-TcpProgramming-example.pdf).
* Recommended activities for the lab:
  * Work in pairs
  * One student implements the client
  * One student implement the server
  * Try to make the client and the server work together, troubleshoot and review each other code
* This is the [URL](https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-RES-2018-Labo-02) for an old lab (Roulette Protocol) that I talked about during the lecture. Once again, you do not have to do this lab, but it is interesting for you to read the code to understand the structure of a multi-threaded TCP server implementing a custom application-level protocol.

## Week 6

* Written test



## Easter Break



## Week 7

* The Simple Mail Transfer Protocol (SMTP)
* Theory and demos on Thursday, lab on Friday
* [Slides](./slides/03-SMTP.pdf)

## Week 8

* HTTP Protocol and Docker
* [Lecture notes](./lectures/04-Lecture4-HTTP.md) 
* [Slides](./slides/04-HTTPProtocol.pdf) 
* The Docker Playlist: https://www.youtube.com/playlist?list=PLfKkysTy70QbseGZcVbpTXhas2xrXKk61
* The HTTP Playlist: https://www.youtube.com/playlist?list=PLfKkysTy70QZG5eUH6nyLrUZLn8Hnlf86

## Week 9

* HTTP Protocol and Docker
* [Lecture notes](./lectures/04-Lecture4-HTTP.md) 
* [Slides](./slides/04-HTTPProtocol.pdf) 
* The Docker Playlist: https://www.youtube.com/playlist?list=PLfKkysTy70QbseGZcVbpTXhas2xrXKk61
* The HTTP Playlist: https://www.youtube.com/playlist?list=PLfKkysTy70QZG5eUH6nyLrUZLn8Hnlf86

## Week 10

* HTTP infrastructure
* [Lecture notes](./lectures/05-Lecture5-WebInfrastructure.md) 
* [Slides](./slides/05-WebInfrastructures.pdf) 

## Week 11

* No lecture this week, because of the Ascencion break
* However, you are encouraged to continue working on the HTTP Infrastructure lab. It is time consuming, but it is not hard. It is well guided (the webcasts guide you through the process). But, as always, be careful: everyone in the group actually does the work and understand the procedures. Otherwise, you will have a hard time at the exam.

## Week 12

* Test 2
* This test will focus on the SMTP and HTTP protocols, as well as on Docker.
* We will keep the content of the "HTTP infrastructure" lecture for the exam.
* There will very probably be a practical part, like for the first test. So make sure that you have a running Docker installation on your machine, that you have the toolset presented in the videos (e.g. curl, postman) ready to be used. 

## Week 13

## Week 14

## Week 15

## Week 16













