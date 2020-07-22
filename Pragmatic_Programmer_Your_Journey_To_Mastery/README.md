# Notes about the 20th edition


## 1. It’s Your Life

### You Have Agency
Does your work environment suck? Is your job boring? Try to fix it. But don’t try forever. As Martin Fowler says, “you can change your organization or change your organization.”

## 2. The Cat Ate My Source Code

We can be proud of our abilities, but we must own up to our shortcomings—our ignorance and our mistakes.

### Team Trust

Above all, your team needs to be able to trust and rely on you



### Take Responsibility

If there was a risk that the vendor wouldn’t come through for you, then you should have had a contingency plan. If your mass storage melts—taking all of your source code with it—and you don’t have a backup, it’s your fault. Telling your boss “the cat ate my source code’’ just won’t cut it


### Provide Options, Don’t Make Lame Excuses

Think through all of your options before telling someone no. Have options ready and try what you think they will suggest.


## 3. Software Entropy

### Don’t Live with Broken Windows

Don’t leave "broken windows" (bad designs, wrong decisions, or poor code) unrepaired.
Neglect accelerates the rot faster than any other factor.

### First, Do No Harm

One broken window - a badly designed piece of code, a poor management decision that the team must live with for the duration of the project — is all it takes to start the decline. If you find yourself working on a project with quite a few broken windows, it’s all too easy to slip into the mindset of "All the rest of this code is crap, I’ll just follow suit."

### Challenges

- Help strengthen your team by surveying your project neighborhood. Choose two or three broken windows and discuss with your colleagues what the problems are and what could be done to fix them.

- Can you tell when a window first gets broken? What is your reaction? If it was the result of someone else’s decision, or a management edict, what can you do about it?

It can be hard to notice at first but keeping an eye on the code and thinking ahead makes planning for broken windows easier.
My first reaction is to fix it. I have put other things on hold in order to fix bugs that we have.
You should always fix the windows since it affects everyone in the project. Not only the one who caused it.



## 4. Stone Soup and Boiled Frogs


It’s time to bring out the stones. Work out what you can reasonably ask for. Develop it well. Once you’ve got it, show people, and let them marvel. Then say "of course, it would be better if we added..." Pretend it’s not important. Sit back and wait for them to start asking you to add the functionality you originally wanted. People find it easier to join an ongoing success. Show them a glimpse of the future and you’ll get them to rally around.

### Be a Catalyst for Change


### Remember the Big Picture

Don’t be like the fabled frog. Keep an eye on the big picture. Constantly review what’s happening around you, not just what you personally are doing.

### Challenges

- While reviewing a draft of the first edition, John Lakos raised the following issue: The soldiers progressively deceive the villagers, but the change they catalyze does them all good. However, by progressively deceiving the frog, you’re doing it harm. Can you determine whether you’re making stone soup or frog soup when you try to catalyze change? Is the decision sub- jective or objective?

By having the bigger picture in mind we will eliminate most errors of stearing in the wrong direction. It's definitely objective. It all depends on what is the end result of the bigger picture.

- Quick, without looking, how many lights are in the ceiling above you? How many exits in the room? How many people? Is there anything out of context, anything that looks like it doesn’t belong? This is an exercise in situational awareness, a technique practiced by folks ranging from Boy and Girl Scouts to Navy SEALs. Get in the habit of really looking and noticing your surroundings. Then do the same for your project.

## 5. Good-Enough Software

The phrase "good enough" does not imply sloppy or poorly produced code. All systems must meet their users' requirements to be successful, and meet basic performance, privacy, and security standards. We are simply advocating that users be given an opportunity to participate in the process of deciding when what you’ve produced is good enough for their needs.

### Involve Your Users in the Trade-Off



### Make Quality a Requirements Issue

Great software today is often preferable to the fantasy of perfect software tomorrow. If you give your users something to play with early, their feedback will often lead you to a better eventual solution.

Don’t spoil a perfectly good program by overembellishment and overrefinement. Move on, and let your code stand in its own right for a while. It may not be perfect. Don’t worry: it could never be perfect.

### Challenges

- Look at the software tools and operating systems that you use regularly. Can you find any evidence that these organizations and/or developers are comfortable shipping software they know is not perfect? As a user, would you rather (1) wait for them to get all the bugs out, (2) have complex software and accept some bugs, or (3) opt for simpler software with fewer defects?

There's plenty of examples. When MacOS updates it could have added a full option to allow a user to foresee what apps on the computer would not be working on the new 64-bit only version. But they ship it without it since that takes time.
(3) Having simple software makes it easy to predict and depend on it.


- Consider the effect of modularization on the delivery of software. Will it take more or less time to get a tightly coupled monolithic block of software to the required quality compared with a system designed as very loosely coupled modules or microservices? What are the advantages or disadvan- tages of each approach?

I think in regards of speed a monolithic block of software is definetly faster to develop since you don't need to scructure your code in different places, make functions general etc. Very loosely coupled modules takes longer but it's much easier to debug, fix and update this software.
If you get handed a project with separate modules it is much easier to understand how it works.

- Can you think of popular software that suffers from feature bloat? That is, software containing far more features than you would ever use, each feature introducing more opportunity for bugs and security vulnerabilities, and making the features you do use harder to find and manage. Are you in danger of falling into this trap yourself?

When I used AWS I found that they definetly had that issue. 99\% of their features I would never use but this is from the interface perspective. How they do their software I don't know. I tend to work from the user journey and derive what things would be amazing to see from them and then scale off the most far off ideas. Then again, quick testing with users tells a clearer picture.


## 6. Your Knowledge Portfolio

1. Serious investors invest regularly—as a habit.
2. Diversification is the key to long-term success.
3. Smart investors balance their portfolios between conservative and high-
risk, high-reward investments.
4. Investors try to buy low and sell high for maximum return.
5. Portfolios should be reviewed and rebalanced periodically.
To be successful in your career, you must invest in your knowledge portfolio using these same guidelines.



### Invest regularly

Find a habit of learning, the habit is as important as the sums, so plan to use a consistent time and place away from interruptions.


### Diversify

The more different things you know, the more valuable you are.
The more technologies you are comfortable with, the better you will be able to adjust to change.



### Manage risk

Have a portfolio with tested and safe bets with a few bets and "hot" technology.
Consider databases, they were really hot and then come out of fasion only to come back stronger.
Blockchain is a hot and more risky investment that can pay off, try to spread your risk.

### Buy low, sell high

Learning an emerging technology before it is popular can be hard but can really pay off.

### Review and rebalance

This is a very dynamic industry. That hot technology you started investigating last month might be stone cold by now.


### Most important is to - Invest Regularly in Your Knowledge Portfolio


## Goals



### Learn at least one new language every year

Different languages solve the same problem in different ways. To know several languages, you can avoid being stuck in a rut.

### Read a technical book each month

Read books about topics related to your current project until you have mastered them, then read books outside your stack.


### Read nontechnical books, too

Since we work with humans, don't forget nontechnical books to get the human side of the equation.


### Take classes

Look for classes that appeal to your interest.

### Participate in local user groups and meetups

Isolation can be deadly to your career; find out what people are working on outside of your company.

### Experiment with different environments

If you have worked with makefiles, try an IDE. If you worked mostly on windows, try linux.

### Stay current

Read news and posts online on technology different from your current project to get variety.

  
## Opportunities for Learning

Always have something to read when you have the time.

## Critical thinking

The last important point is to think critically about what you read and hear. You need to ensure that the knowledge in your portfolio is accurate and unswayed by either vendor or media hype.

###  Ask the "Five Whys"

Ask a question, and get an answer. Dig deeper by asking “why?” Repeat as if you were a petulant four-year old (but a polite one). You might be able to get closer to a root cause this way.

### Who does this benefit?

The benefits to someone else or another organization may be aligned with your own, or not.

### What’s the context?

Consider an article or book touting a “best practice.” Good questions to consider are "best for who?"" What are the prerequisites, what are the consequences, short and long term?

### When or Where would this work?

Under what circumstances? Is it too late? Too early? Don’t stop with first-order thinking (what will happen next), but use second-order thinking: what will happen after that?

### Why is this a problem?

Is there an underlying model? How does the underlying model work?

### Challenges

- Start learning a new language this week. Always programmed in the same old language? Try Clojure, Elixir, Elm, F#, Go, Haskell, Python, R, ReasonML, Ruby, Rust, Scala, Swift, TypeScript, or anything else that appeals and/or looks as if you might like it.

I choose to try Haskell because I'm intrigued by the functional aspect of it.

- Start reading a new book (but finish this one first!). If you are doing very detailed implementation and coding, read a book on design and architecture. If you are doing high-level design, read a book on coding techniques.

I'm going back and forth between the two. I choose to start with a book about design and architecture: - Software Architecture in practice


-  Get out and talk technology with people who aren’t involved in your current project, or who don’t work for the same company. Network in your company cafeteria, or maybe seek out fellow enthusiasts at a local meetup.

I have a network with more experienced people where I can ask about advanced stuff. Also I will try to be more active on reddit and stack overflow.

## 7. Communicate

We spend a lot of time communication in verbal languages and we should treat it with the same respect and practice like we would a computer language.
English is Just Another Programming Language.

### Know Your Audience

You need to understand the needs, interests, and capabilities of your audience. 
One of the Neuro Linguistic Programming presuppositions is "The meaning of your communication is the response you get." Continuously improve your knowledge of your audience as you communicate.


### Know What You Want to Say

Plan what you want to say. Write an outline. Then ask yourself, "Does this communicate what I want to express to my audience in a way that works for them?" Refine it until it does.



## 8. The Essence of Good Design



### Challenges

- Think about a design principle you use regularly. Is it intended to make things easy-to-change?

Modularity and simplicity with scalability. By making things modular, it's easy to know that changing one part only affects that part.
By keeping things simple, we ignore having overly complex code that can written more simply and thus easier to understand and changed for future developers.
Scalability sets some complexity but when done right, it actually makes it easier to change since we will see the cause and effect more clearly.

- Also think about languages and programming paradigms (OO, FP, Reactive, and so on). Do any have either big positives or big negatives when it comes to helping you write ETC code? Do any have both? When coding, what can you do to eliminate the negatives and accentuate the positives?


Object oriented code tends to be longer and a bit more complex than functional programming. 
Big positives can come from being easy to handle objects rather than functions.
Functional programming can really make it easy to build a modular and easy to change system.
Try to look at what each part you are coding will be used for and leverage the best approach for your specific problem.

- Many editors have support (either built-in or via extensions) to run commands when you save a file. Get your editor to popup an ETC? message every time you save and use it as a cue to think about the code you just wrote. Is it easy to change?

I would save this for each code review. So let's say when we are pushing code and want to create a pull request in order to merge into the master branch, we have to think of how easy it is to maintain and change in the future.




## 9. DRY—The Evils of Duplication (Don't repeat yourself)
Don't repeat yourself and strive for having the same knowledge not duplicated.




## 10. Orthogonality


### Challenges

- Consider the difference between tools which have a graphical user interface and small but combinable command-line utilities used at shell prompts. Which set is more orthogonal, and why? Which is easier to use for exactly the purpose for which it was intended? Which set is easier to combine with other tools to meet new challenges? Which set is easier to learn?

Since the graphical interface tool only needs to have one thing to crash in order for the tool to be unusable I would say that it's less orthogonal.
In regards to easier to use for exactly the purpose it was intended and easier to learn I would have to say the graphical interface tool.
The set that is easier to combine with other tools is the command-line utilities.


- C++ supports multiple inheritance, and Java allows a class to implement multiple interfaces. Ruby has mixins. What impact does using these facilities have on orthogonality? Is there a difference in impact between using multiple inheritance and multiple interfaces? Is there a difference between using delegation and using inheritance?

It seems on further digging that in C++ we have multiple inheritance which can be an issue for orthogonality since an object can have several classes and thus information misrepresented. But C++ demands that we explicitly express which parent class has the feature to be invoked to avoid issues and orthogonality is maintained.

In Java with multiple interfaces we inherit from one class but the interface also demands that we specify what class is doing the implementation and therefore orthogonality is maintained.

From my understanding, Java and C++ both uphold orthogonality but from different approaches.



### Exercises

- Exercise 1: You’re asked to read a file a line at a time. For each line, you have to split it into fields. Which of the following sets of pseudo class definitions is likely to be more orthogonal? 
class Split1 {
  constructor(fileName)
  def readNextLine()
  def getField(n)
}
or
class Split2 {
  constructor(line)
  def getField(n)
}

I would say Split2 since we haven't sent the fileName as an explicit parameter to Split1. Otherwise both would be orthogonal.

- Exercise 2: What are the differences in orthogonality between object-oriented and functional languages? Are these differences inherent in the languages themselves, or just in the way people use them?


In object-oriented languages we have orthogonality when we specify clearly what a objects attributes are and solve inheritance by following DRY.
In functional languages we have orthogonality by our way of building our functions. They don't use global variables and we send data explicitly.

I would say it's both. In functional languages it is easier to follow a orthogonal approach but we still need to make sure we send data explicitly and steer clear of global data.




