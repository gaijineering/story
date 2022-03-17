## Software Engineer Interview Experience with Square (Block)

Square has one of the most prolonged interview processes I've ever had. One thing I don't like about the process is they pack a lot of interviews in a short time (5 interviews in 2 days). This is normal for on-site but since we are doing it online, I hope they improve this. The recruiter will share a lot of information to help you to prepare, they will even drop system design hints in the email, so watch out.

### 1. HR Screen (30 minutes)

Standard HR phone call. I like how they tell you to switch off the video in the email so that you don't awkwardly turn on the video alone for the screen. This round mainly was a casual conversation around your motivation and what to expect during the interview round. I always think that if you don't say something crazy, you will be safe for the HR screening round.

### 2. Pair Programming Screen (45 minutes)

I really like how they approach this in an incremental way. The question goes from a straightforward one and they will add more complexity as you solve. The interviewer describe the question clearly and was a very experienced in leading interviews. They are also very open-minded, as in they let you search on Google / StackOverflow if you don't know something. 

I didn't solve the last session of the question completely but we had a discussion on it and they seem happy with my thinking.

### 3. Pair Programming 1st round (45 minutes)

Leetcode medium question. Similar to the screening round they are obviously trained (really great to see how much effort they put in training the interviewer) and they will guide you if you are lost. You will be in a good position if you have enough Leetcode practice (100~200 should be enough).

### 4. Past Technical Experience

I don't have any idea what they expect in this round. Like system design round, you will be the one driving this interview, with your interviewer having less context compared to system design depending on what past project you are talking about. I presented a past project that migrate a DynamoDB cluster to Redis that solve a performance problem. They don't prepare anything for me so I asked to present my idea on [excalidraw.com](https://excalidraw.com/).

### 5. Pair Programming 2nd round (45 minutes)

They break the question into 2 parts this round. The first one is very straightforward and they add some complexity in the second part. They are very consistent in pair programming round. Leetcode medium question + 45 minutes, so nothing surprising. 

### 6. QA Architecture/Design

Watch out for the email their recruiter send out. This round starts with "design an xx". But then they will let you drive the interview 100% on your own. So you need to be good at imagining things and leading the system design. You are told to show your best, so pick up the component that you are most familiar with and deep dive into it. You can show how critical you could think of if a part of the system does work well, and how do you solve it. For instance, if we only want one node (among a cluster of nodes because of availability) to run at a time, we need a distributed lock. In that case, do we need to design our distributed lock [to be efficient, or to be correct](https://martin.kleppmann.com/2016/02/08/how-to-do-distributed-locking.html)?

### 7. QA Leadership

This is a behavioural round where you usually have to talk all the time. Prepare a story that shows your leadership (leading a project, mentoring a teammate, migrating a project) that show both technical and non-technical (soft) skill you have.

### Summary

Take time to prepare, as this is a lengthy interview that needs you to think back on your own experience (Past Technical Experience, QA Leadership) and prepare for technical parts.