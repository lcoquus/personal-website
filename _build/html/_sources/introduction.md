# Introduction: What is Electricity?

Saturday morning. I'm sitting opposite a friend at a trendy inner city cafe. A napkin littered with esoteric diagrams and equations lies in front of me. He's almost finished his pancakes, but I've barely touched my hot breakfast. Is this the start of a revolutionary business enterpise? No. It's my futile attempt to answer the question, *what is electricity?*. The issue is by no means my friend. He's an intelligent university student majoring in biology. I'm in my final year of an electrical engineering degree, so in theory I understand what's going on. In theory. The issue lies with electricity.

## The Problem with Definitions

*Electricity* is one of those generic words which is so vaguely and inconsistently defined as to be unhelpful in any discussions of the thing itself. Is it the movement of electrons through a conductor? Well, yes, but there's more to it than that. Is it the same as lightning? Kind of, but not necessarily. What about electromagnetic radiation? Or static electricity? What are those, and how are they connected? These, and many more questions, quickly confuse and obfuscate any attempt to produce a concise definition. Therefore, my aim in this book is not so much to define what electricity is as *what it does*. What are the fundamental properties of electricity? How does it behave in different conditions? How can we use it effectively? By answering these queries, I hope that you will come to understand and appreciate electricity even more.

## Four Keys to Understanding Electricity

I believe that there are four essential concepts which need to hover in the back of your mind as we begin to investigate electricity:

### 1. Mathematics

Electricity is a physical phenomenon. But like most physical phenomena, the language of mathematics often provides the most accurate translation of its behaviour. I'm aware that many people have mixed feelings about mathematics. This is why popular explanations of electricity tend to shy away from the robust descriptions which it offers. However, they suffer from a lack of depth which can be frustrating for those who wish to dig deeper. The only alternative appears to be undergraduate textbooks, an expensive and unengaging solution. This book aims to straddle a *via media*, a middle way. Since I do not think electricity can be explained sufficiently without the use of mathematics, I will include equations in every chapter. But I will try not to leave you scratching your head too much (a little head scratching is good for you though). Therefore, I will assume roughly a high school level of mathematics education. This includes trigonometry, basic algebra, and the fundamentals of calculus. For example, the following equations will hopefully look familiar:

$$ \sin^2{x}+\cos^2{x}=1 $$

$$ x=\frac{-b\pm\sqrt{b^2-4ac}}{2a} $$

$$ \int \frac{1}{x} \ dx = \ln{|x|}+C $$

If they don't, I would recommend brushing up on your knowledge of these topics before proceeding. They represent the foundation upon which our exploration will rest.

### 2. Abstraction

Electricity is difficult to explain succinctly. One of the reasons for this is that electricity has many properties, which manifest themselves very differently in different situations. The way we understand electricity in an electric circuit, at face value, bears little resemblance to lightning. It's impossible for the human mind to retain a conscious awareness of every aspect of electricity at once. So we employ the principle of abstraction. Abstraction allows us to focus on the specific aspect of electricity which is relevant to our problem. We know that electricity is more than this, but we don't need to think about anything else.

Let me illustrate with the example of a banquet. If you were to host a banquet, you would have a lot to think about. However, the principle of abstraction might make your life a little easier. One issue to address is ingredients. You need to write a very long shopping list and send somebody to buy all these ingredients. But did you notice that you've already applied abstraction? You didn't consider how to farm the ingredients or transport them to the supermarket. Instead, you treated them as items which existed in the supermarket for you to purchase. Let's continue planning the banquet. Now you need to decide what to serve for each course. You look through a recipe book and choose the meals which suit the occasion. You've applied abstraction for a second time. You treat each meal as an item to be arranged in the banquet. You know that meals are made up of ingredients, but when you're planning each course of the banquet you don't need to be conscious of this. Finally, you need to figure out when each course will be served. You write a schedule to ensure that the guests will be well fed for the entire evening. Once again, abstraction comes to your aid. You can temporarily forget that courses are made up of meals and meals are made up of ingredients and ingredients need to be farmed. Each course is a black box to be placed somewhere on your schedule.

This culinary thought experiment demonstrates how we should approach electricity. Understanding electricity involves electrons and fields and waves and strange pictures. But we cannot comprehend all these things simultaneously. Nor do we need to. We can use abstraction to concentrate our efforts on one idea at a time.

### 3. Modelling

You are familiar with the concept of modelling, even if you don't realise it. A diorama of a new skyscraper and the stage of a theatre production are both models. But a set of mathematical equations can also be a model. What these three things have in common is that *they accurately describe one aspect of something and disregard other aspects*. The diorama shows what the building will look like, but not how big it is, or what is inside it. The stage shows what a location looks like, but not what materials are used in its construction, or what it smells like to be there. In the same way, a set of equations can describe one aspect of electricity and disregard others. For example, Ohm's law, which we will learn about in Chapter 1, accurately describes the relationship between voltage, current, and resistance in an electric circuit. It tells you nothing about electromagnetic radiation or the signal to noise ratio. But that does not diminish its usefulness. We will encounter many equations and other models in our study of electricity. None of them will be perfect because each of them will neglect something about electricity. But that does not make them any less useful.

### 4. Analogy

The final concept to keep in mind throughout this book is analogy. An analogy seeks to explain something by comparing it to something else. This is especially helpful in studying electricity because electricity is usually invisible, and invisible things are difficult to visualise. Like models, analogies are imperfect representations of their subject. However, they differ from models in that they emphasise concepts, rather than properties.

A common analogy used in explanations about electric circuits is known as the water analogy. I will outline it more thoroughly in the next chapter, but in brief, it compares electricity in a circuit to the flow of water through pipes, connecting voltage, current, and resistance to the behaviour of the water and the characteristics of the pipes. There are no scale models or lengthy equations in the analogy, simply a picture to imagine which assists in understanding the reality. Analogies on their own are insufficient, since they lack the rigour of a good mathematical model. Nevertheless, at times when our minds struggle to comprehend, a good analogy can save us.

## How to Read This Book

I have structured this book to approximate the progression of a typical electrical engineering degree. We will begin with simple electric circuits, since they are both the easiest to understand and the most fundamental in understanding electricity as a whole. From there, we will delve into some of the underlying physics which enables electric circuits to function, culminating in Maxwell's equations of electromagnetism. Having considered the theory behind electricity, we will then turn to some typical applications, in two broad categories: using electricity to carry energy, and using electricity to transmit information.

There are two particular features of each chapter which I will point out before we begin. The first is the *In Real Life* section. One frustration of learning about electricity in depth is that it can feel far removed from the ways in which we experience elecricity on a daily basis. This section will consider a real-world example relevant to the content of the chapter. I want you to feel the satisfaction of realising that you now know a bit more about how things work.

The second feature is the *Mathematics Corner*. While I provided the mathematical assumed knowledge earlier in this introduction, I also want to cater to those who have a more thorough mathematical background. I find the mathematics involved in electrical engineering to be clever and beautiful, albeit unfamiliar and challenging when you first encounter it. So, if you are comfortable with university-level mathematics, particularly linear algebra, complex analysis, and vector calculus, please enjoy these additions for enhancing your understanding. If you have no knowledge of these topics, you are also more than welcome, but do not fear, I have designed the *Mathematics Corner* to be skippable without any serious loss to the flow of the book.

With the preliminaries now out of the way, let us dive in to the essentials of an electric circuit.