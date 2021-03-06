Title: Computational Investing, Part I (Coursera) Review
Date: 2013-12-02
Tags: MOOCs, Investing, Python

* [About The Course](#about-the-course)
* [My Background](#my-background)
* [Signature Track](#signature-track)
* [Course Overview](#course-overview)
* [What I Loved](#what-i-loved)
* [What Could Be Improved](#what-i-would-improve)
* [Summary](#summary)

<a name="about-the-course"></a>

## [About The Course](#about-the-course)

Computational Investing, Part I was instructed by Tucker Balch, a professor at Georgia Institute of Technology. Tucker is an ex-fighter pilot (according to his opening video), the founder of [Lucena Research](https://lucenaresearch.com/) and has a PhD in Robotics and Machine Learning.

The course page notes that it is "intended for folks who have a strong programming background, but who are new to finance and investing"; a close enough description to me.

<a name="my-background"></a>

## [My Background](#my-background)

I came across the course through someone's comment on Hacker News and signed up immediately.  I have been running a site for a couple of years called [MagicRanker](http://en.wikipedia.org/wiki/Efficient-market_hypothesis), a simple implementation of a thing called the Magic Formula from [The Little Book That Beats The Market](http://www.amazon.com/Little-Still-Market-Books-Profits/dp/0470624159). My money is invested following this approach, so I guess you could say I have experience with "computational investing", but generally I have no idea what I'm doing.

I have, however, spent the last couple of years coding mostly in Python and I'm pretty comfortable with it; so I was lucky that the course's projects were all Python based. Though at the time though I hadn't played with the cornerstone data science libraries like NumPy and Pandas.

<a name="signature-track"></a>

## [Signature Track](#signature-track)

Tucker's class was one of the first to utilise Coursera's [Signature Track](http://blog.coursera.org/post/40080531667/signaturetrack). Which, for a $50 (AUS) fee, provides identity verification through ID scans and "keystroke biometric" profiling (apparently a [thing](http://en.wikipedia.org/wiki/Keystroke_dynamics))</a> and is therefore able to give you a credible certificate. I decided to sign up for it and I'm glad I did. My problem with MOOCs is that I often find myself distracted with life halfway through, and emptily promise that I'll "finish it one day". <span class="pull_quote right">But by being slightly out of pocket though Signature Track, I felt a sense of commitment that helped me prioritise the course.</span> Though I didn't like the idea initially, I think Coursera's hard course start and end dates help with this too.

Interestingly, according to [Tucker's blog](http://augmentedtrader.wordpress.com/2013/11/20/a-comparison-of-online-mooc-versus-on-campus-course-delivery/), the "completion rate for MOOC students who invested ... at the beginning of the course for a validated certificate was 99.0%." A good sign for MOOCs, who journalists love to bemoan for their apparently [low completion rates](http://www.timeshighereducation.co.uk/news/mooc-completion-rates-below-7/2003710.article).

<div class="img-annotated">
    <img src="/images/comp_investing_verified.jpg" alt="Signature track">
</div>

<a name="course-overview"></a>

## [Course Overview](#course-overview)

Week 1 begun with an overview of the course. It was mentioned in one of the first slides that "students will grade each other". I'd heard about this before and was interested to see if it would work. Turned out, however, that all assignments were server graded. Given my busy circumstances, I was thankful. The next modules covered the basics of hedge fund management, including how managers are paid and how they attract investors. Then a look at what to expect from the rest of the course.

Week 2 opened with a series on estimating company value using balance sheet metrics, news and other information. Event studies were also discussed, followed by a lecture on [Capital Asset Pricing Model (CAPM)](http://en.wikipedia.org/wiki/Capital_asset_pricing_model). If I'm honest, I found the presentation of this topic a little dry and hard to follow. For me, [MBA Bullshit](http://www.mbabullshit.com) had a far simpler [CAPM Introductory Series](http://www.youtube.com/watch?v=LWsEJYPSw0k).

Week 3 was a joy. [NumPy](http://www.numpy.org) was introduced, as was [pandas](http://pandas.pydata.org), through a series of video tutorials that accompanied a [text-only series](http://wiki.quantsoftware.org/index.php?title=Numpy_Tutorial_1). The video tutorials were paced a little slow and I preferred the text version. Later we were acquainted with a quant library built for the course called [QuantSoftware ToolKit](http://wiki.quantsoftware.org/index.php?title=QuantSoftware_ToolKit), highlighting the richness of resources provided by the team.

The very first homework was assigned, creating a "brute force" portfolio optimiser. I found the assignment to be easier than understanding the lectures, at least the parts of the assignment required to pass.

Week 4 delved into market arbitrage: the various ways investors exploit market inefficiencies. A theory called [The Effective-market Hypothesis](http://en.wikipedia.org/wiki/Efficient-market_hypothesis) was covered. The video sound quality this week was particularly poor. I think the team was experimenting with different recording techniques, as it improved the week after. 

<div class="img-annotated">
    <img src="/images/comp_investing_efficient_markets.jpg" alt="Definitely coffee in the cup">
    <p>Definitely coffee in the cup</p>
</div>

Lastly, there was a lengthy discussion around portfolio optimisation and the second homework was assigned: performing an Event Study. Most of the code was already provided and only minor tweaks were required to pass the exam.

Week 5 was another extremely useful week for me. Bollinger Bands were introduced, followed by a discussion around the difference between *closing* price and *actual closing* price (actual close factors in things like stock splits and dividends). Additionally, there were modules covering practical techniques for dealing with bad market data from providers. 

The homework here was harder than last week's. The assignment was to create a straight forward Market Simulator. With a bit of effort, though, I was able to piece something together that passed the quiz. I do question how well I would have done had a human graded my code - it was often not pretty.

Week 6 furthered the discussion around assessing event studies. Then, different investing strategies were compared using [Warren Buffett](http://en.wikipedia.org/wiki/Warren_Buffett) and [Jim Simons](http://en.wikipedia.org/wiki/James_Harris_Simons) as opposing case studies. An in-depth discussion about CAPM followed. As before, I had trouble groking this. Partly, I'm sure, due to a lack of interest.

The week's homework pieced together two of the earlier assignments, creating an event study and then running it through a simulator. Since the hard work was already done, the task was trivial.

Week 7 was, from a financial perspective, probably the most practical week. Videos covered the different information feeds available for hedge fund managers then a discussion around Technical Analysis.

The majority of the latter half of the week was set aside to talk about the homework assignment, an implementation of Bollinger Bands.

<div class="img-annotated">
    <img src="/images/comp_investing_question.jpg" alt="An example of the quiz from Week 7">
    <p>An example of the quiz from Week 7</p>
</div>

Week 8, the final module, was centred around two homework assignments building from previous week's work. In the first, we were to perform an event study based on Bollinger Bands and, in the second, feed that data into a market simulator.

I wish I had had more time to spend on them. I ended up knocking together a half baked solution that narrowly passed the exam, moments before I left for a week long holiday. I also needed help from the forum here. I'm not proud of the code, and I doubt I would have done very well if an instructor graded it.

***

<a name="what-i-loved"></a>

## [What I Loved](#what-i-loved)

Firstly, Tucker and the team put a lot of work into the course and it shows. The course was filled with supplimentary material like professional interviews, book recommendations, the QSTK libary, programming tutorials and a wiki rich with content.

I really got a kick out of the programming side too. Just being introduced to NumPy and Pandas made the course worth my time. With the little bit of knowledge I got from this course and [this book](http://shop.oreilly.com/product/0636920023784.do), I was able to rewrite the internals of MagicRanker and make it a shit load faster and more extensible.

I was also quite thankful that the homework was relatively easy. Hard enough to keep me thinking but, for a person with a decent amount of programming experience, definitely passable. Perhaps a little too easy at times.

<a name="what-i-would-improve"></a>

## [What Could Be Improved](#what-i-would-improve)

The course lectures were sometimes a little dry and a bit long for my Gen Y attention span. Udacity's model of providing question-based "checkpoints" along the way, really helped to keep me engaged and break up the videos. This course could consider something similar. Come to think of it, there were actually a couple of them in earlier videos but they seemed to disappear by Week 2.

There was also a number of problems with the video quality, including low audio, distorted audio, bloopers and so forth. Sometimes I wondered why they hadn't rerecorded the videos where there were clearly major defects.

I think Coursera has some work to do with the interface too. I found it slightly annoying that the video couldn't be made full screen via the UI. Not sure why they would prevent that, since they have the videos available for download. Lastly, I found the forums a little disorientating. Especially coming from Udacity's forum system where posts are linked to lessons and assignments making it clear what they're about. Though, in fairness, I didn't spend much time getting used to the forum.

Completely unrelated to the course quality, but I also had a bit of trouble with a lot of the "maths" that goes into finance. Often there are *theoretical world* values plugged into formulas that involve *real world* implications. The idea of the "risk premium" in CAPM is a good example of this - can the standard deviation of an investment's historic performance really be enough to say if it is safe or not?

<a name="summary"></a>

## [Summary](#summary)

Minor flaws aside, if you've got an interest in the quant world and a reasonable programming background, you will almost certainly find this course worthwhile. If you haven't programmed before, then I would consider taking an introductory course first.

Despite the persistent criticisms, the MOOC phenomena over the last couple of years has improved my life considerably and I'm in debt to people, like Tucker and his team, who are willing to upload high-quality courses like this for *free*. We are living in a magical time.
