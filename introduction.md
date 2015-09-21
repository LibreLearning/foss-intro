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

## The consequences of software freedom

Free software offers many advantages and, of the few disadvantages, many have been exaggerated (or invented) by proprietary competitors. The most well-founded disadvantage is the financial one, since as we have seen it is not possible to make much money from its distribution, which can and tends to be made by someone other than the author. This is why other business models and financing mechanisms are needed, which we look into in chapter 5. Other disadvantages, such as the lack of support or poor quality, are related to financing but also in many cases are false, since even software with no form of financing tends to offer good support levels thanks to user and developer forums, and often the quality is very high.

Bearing in mind the financial considerations, we should note that the free software cost model is very different to the proprietary software cost model, since a large amount of it develops outside of the formal monetary economy, and frequently using exchange/barter mechanisms: "I give you a program that you are interested in, and you adapt it to your architecture and make the improvements that you need." Chapter 7 discusses the right software engineering mechanisms to make the most of these unpaid for human resources with their own particular features, while Chapter 8 studies the tools used to make this collaboration effective. Also, a large share of the costs is reduced by the fact that it is free, since
new programs do not need to start from scratch, because they can reuse already made software. The distribution also has a much lower cost, since it is distributed via the Internet and with free advertising through public forums designed for this purpose.

Another outcome of the freedoms is the quality resulting from the voluntary collaboration of people who contribute or discover and notify bugs in environments or situations that are unimaginable for the original developer. Plus, if a program does not offer sufficient quality, the competition may take it and improve on it on the basis of what there is. This is how collaboration and competition, two powerful mechanisms, combine in order to produce better quality.

Now let's examine the beneficial consequences for the receiver.

### For the end user

The end user, whether an individual or a company, can find real competition in a market with a monopoly trend. To be precise, it does not necessarily depend on the software manufacturer's support, since there may be several companies, even small ones with the source code and the knowledge that allows them to do business while keeping certain programs free.

Trying to find out the quality of a product no longer relies so much on the manufacturer's trustworthiness as on the guide given by the community's acceptance and the availability of the source code. Also, we can forget the 'black boxes', that must be trusted 'because we say so', and the strategies of manufacturers that can unilaterally decide whether to abandon or maintain a particular product.

Evaluating products before they are adopted has been made much easier now, since all we have to do is to install the alternative products in our real environment and test them, whereas for proprietary software we must rely on external reports or negotiate tests with suppliers, which are not always possible.

Because of the freedom to modify the program for own use, users are able to customize it or adapt it to own requirements correcting any errors if there are any. The process of debugging errors found by proprietary software users is normally extremely laborious, if not impossible, since if we manage to get the errors debugged, the correction will often be incorporated in the following version, which may take years to be released, and which moreover we will have to buy again. With free software, on the other hand, we can make corrections or fixes ourselves, if we are qualified, or otherwise outsource the service. We can also, directly or by contracting external services, integrate the program with another one or audit its quality (for example in terms of security). To a great extent control is passed on from the supplier to the user.

### For public administrations

Public administrations are large users with special characteristics, as it has a special obligation towards its citizens, whether to provide accessible services, neutral in relation to manufacturers, or to guarantee the integrity, utility, privacy and security of their data in the long term. All of the above makes it obligatory for public administration to be more respectful towards standards than private companies and to maintain data in open formats and to process data with software that is independent of maybe foreign companies' strategies, certified as secure by an internal audit. Adaptation to standards is a notable feature of free software that proprietary software does not respect to the same extent, because it is generally eager to create captive
markets.

Also, the Administration serves as a sort of showcase and guide for industry, meaning that it has a great impact, which ought to be directed at weaving a technological fabric that generates national wealth. This wealth may be created by promoting the development of companies dedicated to developing new free software for the Administration, or maintaining, adapting or auditing existing software. In chapter 6, we will look at this issue in more depth.

### For the developer

For the software developer and producer, freedom significantly changes the rules of the game. It makes it easier to continue to compete while being small and to acquire cutting edge technology. It allows us to take advantage of others' work, competing even with another product by modifying its own code, although the copied competitor can then also take advantage of our code (if it is copylefted. If the project is well-managed, it is possible to obtain the free collaboration of a large number of people and, also, to obtain access to a virtually free and global distribution
system. Nonetheless, the issue of how to obtain financial resources remains, if the software is not the product of a paid-for commission. Chapter 5 deals with this aspect.

### For the integrator

For integrators, free software is paradise. It means that there are no longer black boxes that need to be fitted together, often using reverse engineering. Rough edges can be smoothed out and parts of programs can be integrated in order to obtain the required integrated product, because there is a huge share pool of free software from which the parts can be extracted.

### For providers of maintenance services

Having the source code changes everything and puts us in the same position as the producer. If the position is not the same, it is because we are lacking an in-depth knowledge of the program that only the developer has, which means that it is advisable for maintenance providers to participate in the projects that they are required to maintain. The added value of services is much more appreciated because the cost of the program is low. It is currently the clearest business with free software and the one where the most competition is possible.

## Summary

This first chapter has served as a preliminary encounter with the world of free software. The concept defined by Richard Stallman is based on four freedoms (freedom to execute, freedom to study, freedom to redistribute and freedom to improve), two of which require access to the source code. This accessibility and its advantages have motivated another less ethical and more pragmatic point of view, defended by the Open Source Initiative, which has given rise to another term: 'open source software'. We have also mentioned other related similar or opposite terms, which serve to clarify various concepts. Finally, we have discussed the consequences of free software for the main parties involved. 
