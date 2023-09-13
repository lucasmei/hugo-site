---
title: "The Importance of LaTeX"
date: 2023-09-13T10:12:17-04:00
draft: true
---

# Introduction
For as long as I can remember, I have been writing documents in Google Docs. Then, I attended Ethan Stollar's mini-lecture on using LaTeX to write up documents, and from there I was hooked. LaTeX is the future, and the goal of this post is to give awareness to those interested in technical writing, pursuing their post-grad, and so on. The benefits it provides for formatting outweighs all the mini struggles you'll have in the beginning.

## Clarification 
Before going any farther, I want to make my intentions completely transparent, as I know my writing can sometimes seem too strongly opinionated. I am not a fan of tradition text-editing software like Microsoft Word and Google Docs. Now to be clear, I couldn't call Word or Docs "Text Editors" exactly since they're so much more than that. They're "word-processors"; programs with the sole intention of being used to write documents, show spelling mistakes, give suggestions on language, etc. 

With that being said, I am not trying to push the usage of niche text-editors like vim or emacs, nor am I saying to rule out word processors entirely. Every program has their space, but I think in the scientific academic world those traditional processors have some catching up to do. I am speaking only in this specific environment. I am not here to shame anyone for using Google Docs to write their thesis. The point is to show alternatives to those who are interested in finding alternatives, like me when I was thinking about how to write up glosses for my final 3M03 Paper. If you are comfortable with your workflow in Word, by all means. If you like using Overleaf, that's also great since you're familiarizing yourself with LaTeX

## Experience 
I have used LaTeX for two final papers: LINGUIST 3M03 (Morphology) and 4LC3 (Advanced Syntax and its Interfaces). Before Ethan's talk, I had made example documents for myself in the past, but never worked anything with them since I found LaTeX to be too daunting. I write all of my LaTeX in a terminal-based text-editor called "neovim", a fork of the popular text-editor "vim". For the remainder of this, I'll refer to both neovim and vim as just "vim", since they are functionally the same thing (this isn't a neovim vs vim post). 

# Reasons for using LaTeX
## 1. You want to try something new!
If you aren't someone who likes to break out of their comfort zone and try different methods of performing tasks you already know how to do, this isn't for you. I made the switch to LaTeX because I not only wanted to try a different workflow, I also wanted to see how well I could work within my minimal text-editor in the context of academic writing. The result: pretty efficient. I always love seeing other ways people do the same things I know how to do. It's seeing a different perspective from what you think you already know. Sometimes the payoff is worth it, while in others it isn't. Whether or not that's the case for you is for you to decide. Using LaTeX offers a different perspective on how it feels to write documents, which sounds very nerdy and cliche, but is perfect for me.
## 2. Glossing made easy
I think this is the main reason why I even touched LaTeX. When learning glossing, we do most of it by hand or quickly write it down in a document. Glossing in LaTeX couldn't be easier, and makes the whole process seamless. Here's an example of a gloss I wrote in 3M03:
```LaTeX
\begin{exe}
    \ex
    \gll~Vesa on ulkon-a\\
    Vesa.NOM is outside-LOC\\
    \trans`Vesa is outside'
\end{exe}
```
Let me explain this line by line quickly:
- Begin the example container 
- Start first example
- \gll indicates that what comes after will be the piece of text to be glossed. The \\ indicates a new line is coming
- The text above in its glossed form with the \\ at the end for formatting
- \trans indicates that whatever comes after it will be the translation of the first line

Using this in a document will output a glossed piece of text, without ever having to hit space a bunch of times to try and get the right spacing! 
## 3. Trees made easy
## 4. IPA support
