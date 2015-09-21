# Introduction

> *"If you have an apple and I have an apple and we exchange apples, then you and I will still each have one apple. But if you have an idea and I have an idea and we exchange these ideas, then each of us will have two ideas."*

> Attributed to Bernard Shaw

What is free software? What is it and what are the implications of
a free program licence? How is free software developed? How are free software projects funded and what are the business models associated to them that we are experiencing? What motivates developers, especially volunteers, to become involved in free software projects? What are these developers like? How are their projects coordinated, and what is the software that they produce like? In short, what is the overall panorama of free software?

These are the sort of questions that we will try to answer in this document. Because although free software is increasing its presence in the media and in debates between IT professionals, and although even citizens in general are starting to talk about it, it is still for the most part an unknown quantity. And even those who are familiar with it are often aware of just some of its features, and mostly ignorant about others.

To begin with, in this chapter we will present the specific aspects of free software, focusing mainly on explaining its background for
those approaching the subject for the first time, and underlining its importance. As part of this background, we will reflect on the
definition of the term (to know what we're talking about) and on the main consequences of using (and the mere existence of) free
software.

##  The concept of software freedom

Since the early seventies we have become used to the fact that anyone marketing a program can impose (and does impose) the conditions under which the program can be used. Lending to a third party may be prohibited for example. Despite the fact that software is the most flexible and adaptable item of technology that we have, it is possible to impose the prohibition (and it frequently is imposed) to adapt it to particular needs, or to correct its errors, without the explicit agreement of the manufacturer, who normally reserves the exclusive right to these possibilities. But this is just one of the possibilities that current legislation offers: *free software*, on the other hand, offers freedoms that *proprietary software* denies.

> #### Note: Proprietary Software

> In this text we will use the term *proprietary software* to refer to any program that cannot be considered free software in accordance with the definition we provide later.

## Definition

So, the term "free software", as conceived by Richard Stallman in his definition (Free Software Foundation, ["Free software definition"](http://www.gnu.org/philosophy/free-sw.html) [120]), refers to the freedoms granted to its receiver, which are namely four:

* Freedom to run the program in any place, for any purpose and
forever.
* Freedom to study how it works and to adapt it to our needs. This requires access to the source code.
* Freedom to redistribute copies, so that we can help our friends
and neighbours.
* Freedom to improve the program and to release improvements to the public. This implies the availability of the source code as well.

The mechanism that guarantees these freedoms, in accordance with current legislation, is distribution under a specific licence as we will see later on (chapter 3). Through the licence, the author gives permission for the receiver of the program to exercise these freedoms, adding also any restrictions that the author may wish to apply (such as to credit the original authors in the case of a redistribution). In order for the licence to be considered free, these restrictions must not counteract the abovementioned freedoms.

> #### Note: The ambiguity of the word free

> The English term 'free software' includes the word 'free', standing for 'freedom'. But the term can mean also 'free of charge' or 'gratis', which causes a great deal of confusion. This is the reason why in some cases the English borrow Spanish/French words and refer to 'libre software', as opposed to 'gratis software'.

Therefore, the definitions of free software make no reference to the fact that it may be obtained free of charge: free software and gratis software are two very different things. However, having said this, we should also explain that due to the third freedom, anyone can redistribute a program without asking for a financial reward or
permission, which makes it practically impossible to obtain big
profits just by distributing free software: anyone who has obtained
free software may redistribute it in turn at a lower price, or even
for free.

> #### Note: Selling free software

> Despite the fact that anyone can market a given program at any price, and that this theoretically means that the redistribution price tends towards the marginal cost of copying the program, there are business models based precisely on selling free software, because there are many circumstances in which the consumer will be prepared to pay in exchange for certain other benefits, such as for example a guarantee, albeit a subjective one, for the software acquired or an added value in the choice, updating and organization of a set of programs.

From a practical point of view, several texts define more precisely what conditions a licence must fulfil in order to be considered a free software license. Among these, we highlight for their historical importance the [Free Software Definition of the Free Software Foundation](http://www.gnu.org/philosophy/free-sw.html) [120], the [Debian Free Software Guidelines](http://www.debian.org/social_contract.html") [104], used by the Debian project to decide whether a program is free software, and the [Open Source Definition](http://www.opensource.org/docs/definition_plain.html) [215], definition of the term "open source software", by the Open Source Initiative, which is very similar to the former two.

> #### Note: 

> For example, the Debian Free Software Guidelines go into the detail of allowing the author to demand that distributed source codes not be modified directly, but rather that the original is accompanied by separate patches and that binary programs be generated with different names to the original. They also demand that the licenses do not affect other independent programs distributed by the same means.

## Related terms

The term 'open source software', promoted originally by Eric Raymond and the Open Source Initiative is equivalent to the term 'free software'. Philosophically speaking, the term is very different since it emphasizes the availability of the source code and not its freedom, but the definition is practically the same as
Debian Free Software Guidelines, which was designed as a set of rules to determine if a piece of software was compliant with the Free Software Definition by the FSF.

'Open source' is perhaps more 'aseptic'than 'free software', and emphasizes the technical side, which can provide technical benefits, such as improved development and business models, better security, etc. Strongly criticised by Richard Stallman (see "Why 'free software' is better than 'open source<'" [204]) and the Free Software Foundation, it has resonated far better with the commercial literature and with the company strategies that one way or another support the model.

Other terms associated in some way to free software are as follows:

| Term | Definition |
| -- | -- |
| Freeware| These are gratis programs. They are normally only distributed in binary form, and can be obtained free of charge. Sometimes it is possible to obtain permission to redistribute, and others not, meaning that then it can only be obtained from the 'official' site maintained for that purpose. It is frequently used to promote other programs (normally with more complete functionality) or services. Examples of this type of programs include Skype, Google Earth or Microsoft Messenger. |
| Freeware | These are gratis programs. They are normally only distributed in binary form, and can be obtained free of charge. Sometimes it is possible to obtain permission to redistribute, and others not, meaning that then it can only be obtained from the 'official' site maintained for that purpose. It is frequently used to promote other programs (normally with more complete functionality) or services. Examples of this type of programs include Skype, Google Earth or Microsoft Messenger |
| Shareware | This is not even gratis software, but rather a distribution method since usually the programs can be copied freely, generally without source code, but not used continuously without paying for them. The requirement to pay may be motivated by a limited functionality, being sent annoying messages or the mere appeal to the user's ethic. Also, the license's legal terms may be used against the transgressor. |
| Charityware, careware | This is normally shareware that requires payment to be directed towards a sponsored charity. In many cases, instead of demanding payment, a voluntary contribution may be requested. Some free software, such as Vim, asks for voluntary contributions of this nature (Brian Molenaar, "What is the context of charityware?" [173]).|
| Public domain | Here, the author totally renounces all his rights in favour of the public domain, and this needs to be explicitly stated in the program since otherwise, the program will be deemed proprietary and nothing can be done with it. In this case, if additionally the source code is provided, the program is free. |
| Copyleft | This is a particular case of free software where the license requires any distributed modifications to be free as well. 
| Proprietary, locked-in, non-free | These are terms used to refer to software that is neither free nor open source. |

## Motivations

As we have seen, there are two large families of motivations for free software development, which likewise give rise to the two names by which it is known:

* The ethical motivation, championed by the Free Software Foundation, which has inherited the hacker culture and supports the use of the term 'free', arguing that software is knowledge that should be shared unimpeded, that hiding it is antisocial and additionally claims that the ability to modify programs is a form of freedom of expression. You can study this in more depth by reading "Free software, free society. Selected essays of Richard M. Stallman" [211] or the analysis of Pekka Himanen "The hacker ethic and the spirit of the information age" [144].

* The pragmatic motivation, championed by the Open Source Initiative [54] which supports the use of the term 'open source', and argues the case of the technical and financial advantages that we will discuss in the next section.

Aside from these two main motivations, people working on free
software can do so for many other reasons, including for fun [217] or for money, potentially with sustainable business models. Chapter 4 studies these motivations in detail on the basis of objective analyses.
