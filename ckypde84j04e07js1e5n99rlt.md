## Software Engineer Interview Experience with PayPay Japan

### Why PayPay ?
- Exciting scale: 1000 Transaction/s on 2021 ([source](https://codezine.jp/article/detail/13703))
- [Work From Anywhere at Anytime (WFA)](https://about.paypay.ne.jp/pr/20200805/02/)
- [Competitive salary](https://opensalary.jp/companies/paypay)


It took me 3 weeks to finish the process. While I am not allowed to tell you everything especially PayPay interview question, I will try my best to describe the experience.

1. Codevue online coding test
2. Phone Interview
3. Loop Interviews (x4)
4. Talent Acquisition round


### Codevue online coding test
Time is valuable. Do things fast. To be fast, you have to get used to common operations.
Like [hackerrank](https://www.hackerrank.com/) etc, codevue coding test starts by reading input from `os.Stdin` and writing output to os.Stdout. So you have to get used to parse a string into a data structure in your programming language and vice versa fast. For instance `19.24,20.00` to `[19.24, 20.00]: Array[Float]`
Practice how to use the standard lib of your programming language to do this. (If you use Go then strong, strings are your friends. Or better go practice in hackerrank)

Finally, if you are stuck, you are allowed to `fmt.Printf` or `console.log`. I was stuck during my second question for a few minutes and having my coding recorded I was hesitant to debug it the hard way. I debugged it by using “fmt.Println”, solved the problem immediately and passed!
The best way to prepare this is no other than leetcode.


### Phone Interview
It is said 45 minutes but actually, it was 30 minutes + time for me to ask questions. The interviewer seems busy because he tries to end the interview at the 30th minute.
This round mainly goes through your resume to make sure you know things. I heard that there are some candidates who have coding tests in this round (on Google Docs ?!?) but I didn’t.


### Loop Interview x 4
While they might suggest you finish the loop interview in a day, I would suggest you avoid it. Because it’s draining. Give yourself some break between the interviews.

#### Loop Interview 1 (Programming knowledge)
I was interviewed by one of the team lead. Young, passionate and very friendly. This round starts with testing your most familiar programming language. Garbage collector, data races topics etc for around 30 minutes. Another 15 minutes was used to solve a leetcode question.

#### Loop Interview 2 (Data structure and algorithm)
Worst round because I don’t actually know what they want. They describe a case and ask what’s the best data structure for that. Then Big O topic. The interview then continued with a leetcode question.

#### Loop Interview 3 (Backend knowledge)
This is the only round without any coding. But it asks everything a software engineer should know. From networking to Linux to Database to container to a distributed system.
Expect questions like “what happens when you open an URL from browser” and “explain ACID”
A few good resources that I find really helpful are
- [Systems Performance: Enterprise and the Cloud, 2nd Edition (2020)](https://www.brendangregg.com/systems-performance-2nd-edition-book.html): Models, Concepts, Architecture of every chapter are your alliance
- [High Performance Browser Networking](https://hpbn.co/): Chapter 2 ~ 4 are your friends
- [Designing Data-Intensive Applications](https://dataintensive.net/): Chapters 2, 3, 5 ~ 9 is for you
You are not expected to answer everything perfectly, so feel free to let them know you don’t know so that they can move to next. Luckily for me, my interviewer was very knowledgeable and willing to teach, so while I might not answer everything, I learned a lot.

#### Loop Interview 4 (System Design)
Interview with one of their senior manager. In this round, they will revisit your resume, have a coding session and finally ask you to design a small system. That’s a lot.
I told the interviewer I have seen the coding question on leetcode so they pulled out another one which I also have seen on leetcode too but I decided to move forward because it was an easier one.

### Summary
You can see that most of the interviews are general knowledge + one leetcode. So, to prepare well:
1. Read a lot especially the book I introduces
1. [leetcode](https://leetcode.com/)
1. For system design please check out http://systemdesign.gaijineer.co/

If you want to catch up on more interview process stories, you can find me on [Twitter](https://twitter.com/yangwei21).