---
layout: essay
type: essay
title: "The Art of Asking Smart Questions in Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Software Engineering
  - Learning
  - Stack Overflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart.png">

Communication is one of the most critical skills in software engineering, In Eric Raymond’s article “How to ask questions the smart way”, he provides guidelines for effective interaction with the open source community, and asks questions effectively.
Learning programming language is never an easy thing, often need to spend a lot of time to learn and practice, during this period you may encounter a lot of problems you do not understand or can not solve, and ask others for help to find a solution is inevitably one of the smart choices, but there are many ways to ask questions, and how to ask questions correctly and smartly is the key.

By asking smart questions will greatly help efficiency, learning and community help. 
A smart question is more likely to get quicker and more accurate answers, the replier can more easily understand what question you are asking for and provide the best match answer.
And the process of asking a smart question also leads to a deeper understanding of the problem.
It also Helps build a culture of mutual respect and collaborative problem solving.
And there are some articles like “How do I ask a good question?” in the Stack Overflow help center that will guide you how to ask a good question.

## What is a Smart Question?

Almost 90 percent of all programming questions can be answered on Stack Overflow, but you need to know how to pinpoint the problem, and you need to provide at least the following information such as what programming language you are using, what framework you are using, what problems you are running into such as installation failures, crashes, etc. what did you try and etc.

According to Eric Raymond’s article, he said a smart question should:
-on-topic and have a title that sums up the problem
-Be specific and clear in its wording.
-Provide all necessary context, including code snippets, logs, and error messages.
-Show what the asker has already tried to solve the problem.
-Be polite and respectful to the community.
And more.
These will increase your chances of getting an effective and responsible answer to your question.

## Smart and Not Smart Question

Lets look at the example of ask question in an “smart way” and “not smart way”.

SMART:
<a href="https://stackoverflow.com/questions/237104/how-do-i-check-if-an-array-includes-a-value-in-javascript">How do I check if an array includes a value in JavaScript? - Stack Overflow</a>

In a question “How do I check if an array includes a value in JavaScript?” written by brad, she asked the community: What is the most concise and efficient way to find out if a JavaScript array contains a value?

And she provides a code, and try to find is there any more efficient way than this method.

This is the only way I know to do it:

<pre> 
function contains (a, obj) {
    for (var i = 0; i < a.length; i++) {
        if (a[i] === obj) {
            return true;
        }
    }
    return false;   
}
</pre>

She clearly conveyed what he was trying to figure out, what she had tried and worked on, and her tittle was very close to what she wanted to ask.
The questioner received 62 possible answers, and each repiler actively discussed and gave their most satisfactory answers and suggestions.

NOT SMART ：
<a href="https://stackoverflow.com/questions/59102067/why-im-getting-this-error-in-rust-while-running-cargo-in-terminal">why i'm getting this error in rust? while running cargo in terminal - Stack Overflow</a>

In a question “why i'm getting this error in rust? while running cargo in terminal” written by Abhi Singh, he posted a question with only a title and error message report, and without any description,
His question did not follow the guide on how to ask good question, there was a lack of required details and the question could be searched up online, did not show any effort.
The questioner did not receive any possible answer from replier and was recommended to follow the guide on how to ask good question to edit the details of the question, and do some research first, which was clearly a not smart question.


## In Conclusion

Smart questions can improve the efficiency of problem-solving and enrich the community through high-quality discussion, benefiting not only ourselves, but also those we ask and others who may have similar questions in the future.
repiler can quickly and simply understand the questions we ask and let us get a satisfactory answer, while people with similar problems can quickly find a satisfactory solution through the answers to our questions, saving everyone's time.

