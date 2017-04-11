# Debugging your CV / Résumé

This guide (http://git.io/mycv) is written to help you debug your CV, based on common bugs we've seen in students CVs (aka Résumés) submitted to the [School of Computer Science CV Bank](https://studentnet.cs.manchester.ac.uk/employment/industryclub/cvbank) at the University of Manchester. Wherever criticism of your CV comes from, don't take it personally -  it is probably one of the first you have written. Think of your current CV as version 0.1, alpha or perhaps beta release. There are many chances to debug and improve it - find out more at http://man.ac.uk/U1q7VI and http://man.ac.uk/6Ef90a

> DISCLAIMER: If you ask three people what they think of your CV, you will get three different and probably contradictory opinions. CV's are a very subjective thing. The advice below is based on common sense, experience and ongoing conversations with members of our [industry club](http://www.cs.manchester.ac.uk/industry/club/). What makes a good CV will depend on the personal preferences and prejudices of the reader. There are some general rules, which are described below.

While referring to this guide, remember that
* the **main purpose of your CV is to get an interview, not a job**. Your CV should catch attention and provide talking points for an interview but not give your whole life story
* the chances are, your CV will be [assessed in seconds](http://www.huffingtonpost.com/2012/03/23/resume-tips-for-post-50s_n_1372705.html), rather than minutes so brevity really is key

**Table of Contents**

- [Education] (http://git.io/mycved)
- [Experience & Projects](http://git.io/mycvex)
- [Skills](http://git.io/mycvsk)
- [Formatting](#formatting-fm)
- [Structure](#structure-st)
- [General](#general-gen)
- [Hobbies & interests](#hobbies-and-interests-hob)
- [Personal details & References (REF)](#references-ref)
- [Next steps](#next-steps)

## Formatting

It is really important to get the formatting of your CV right so that it looks professional. It can take a long time to get the look right, because every pixel matters and you are highly constrained by space (one or two pages). Don't under estimate the importance (and time needed) to get the style looking clean and professional:

  1. **WASTE OF SPACE** Space is very valuable, you should use every pixel, millimetre and word to maximum effect. If there are big blank spaces this can look bad - fill space by providing more detail, increasing the font size, line spacing (e.g. try 1.5 line spacing) or reducing page margins & etc. Make sure you use all the vertical and horizontal space available without filling the page completely.
  2. **CRAMPING YOUR STYLE** It can be tempting to cram things on - but this makes it hard to read if the text is too small. Rather than list EVERYTHING you've done EVER, show the most important or relevant aspects. The final document should be easy on the eye to get you an interview. If you get the chance, you can fill in details at the interview.
  3. **BLANK SPACE** Make sure you use all the space available, both vertical and horizontal. Two pages is the norm for a CV, though some employers ask for a one pager. You shouldn't have too much blank space on either type.
  4. **PDF** The Portable Document Format is a more idiot-proof way to distribute documents than Word files, and PDF works on more platforms and devices. Beware of converting Word to PDF, it can be an unpredictable and lossy conversion which messes up fonts, page breaks and other important formatting. Some employers will use software that won't accept PDFs, and will insist on Word. Thankfully they are not too common.
  5. **MICROSOFT / GOOGLE** Word, Google Docs and other word processors are OK, if that is what you are most comfortable with. However, using LaTeX can make your CV stand out because the typography is usually much better. If you did COMP101, remember [Why LaTeX?](http://studentnet.cs.manchester.ac.uk/ugt/COMP10120/labscripts/101lab3.pdf) Despite the limitations of LaTeX, it is a very good tool for making professionally typeset PDFs (exactly what your CV should be). There are some good CV templates available from [overleaf.com/gallery/tagged/cv](https://www.overleaf.com/gallery/tagged/cv) and [sharelatex.com/templates/cv-or-resume](https://www.sharelatex.com/templates/cv-or-resume). Plenty of good generic templates are available elsewhere  [google.com/search?q=cv+template](https://www.google.com/search?q=cv+template).
  6. **STYLE** Don't underestimate the importance of style, formatting and typography. Badly formatted CVs will end up in the bin. Formatting can be tedious, labour intensive and time consuming, but it is worth spending the time to get it right. Use a template if it helps, see for example Bryn's CV http://bryn.co.uk/CV.pdf. Bryn is a final year student in Computer Science, who did a placement at Google during 2015/6.
  7. **AVOID UNDERLINE** Underline was <span style="text-decoration: underline">designed for typewriters</span> and should usually be avoided. Sometimes it is OK to use underline for hyperlinks, as it helps to show that they are clickable URLs. `Fixed width fonts` look pretty horrible too (for example default URLs in LaTeX). Look at any professional document, it is very unlikely that you will find underline. `Fixed width fonts` are usually reserved for code, not something you are likely to have on your CV
  8. **PRINT IT** Print out your CV to check what it actually looks like with different printers. Can you read it? Odd things can happen that make your CV look rubbish, so it is worth trying out a few different printers. Does it fit nicely on two pages? Are there any nasty page and line breaks that create ugly [widowed & orphaned text](https://en.wikipedia.org/wiki/Widows_and_orphans)? If you're using a fancy looking font, bear in mind that they may not be available on every device and printer. You might need to investigate [embedding the fonts in the pdf](https://en.wikipedia.org/wiki/Font_embedding) to prevent any unpredictable [font substitutions](https://en.wikipedia.org/wiki/Font_substitution) spoiling your hard work.
  9. **BAD PAGE BREAKS** splitting sections across pages is usually a bad idea and can waste space. If you have to split a section, make sure the title follows it. e.g. “EXPERIENCE (continued)”
  10. **BAD LINE BREAKS** take care that the line breaks occur in sensible places, if necessary, adjust the text so it fits better into the space available. Bad line breaks waste valuable

  space and make it harder to read the document - they distract the reader from what you are saying.
  11. **TABULATE** Tables can be a good way to arrange information, but they usually look better, cleaner and easier to read WITHOUT a border
  12. **ONE PAGE OR TWO?** Depending on where you send your CV, it can handy to have both a one page and a two page version. You could have a trunk version with two branches. It is usually much easier to write a two pager than a one pager, but some employers demand a one page.

## Structure (ST)

The order and structure of your CV is as important as the content

  1. **FIRST THINGS FIRST** The first page should usually be Education and Experience (usually in that order), second page page all the other stuff. Order with the most important (or recent) things first. It is debateable if your personal details should go front and top. Is your postal address *REALLY* the most important thing about you? Does it deserve prime space at the top of your CV? Many people put personal details at the end  - often just email and telephone no. for first contact. If a company really needs to post you something, they can contact you by phone or email to get your snail mail address.
  2. **REVERSE** Reverse chronological order is normal, (most recent first) and it is often the easiest way to structure your CV. Within each section, order likewise, most important (or relevant) work experience goes at the top of that section and so on

## General (GEN)

Some general points that apply to all sections of your CV

  1. **HYPER LINKING** It is good to have *some* links in your CV that also work on paper (you won't know if the person reading it will be reading the PDF on-screen or a printed version). Spell out the URL (so it works in print) and also make the link in the PDF clickable to cover both scenarios. Link to anything you have that adds context to what you're saying e.g. company websites, your personal website, LinkedIn, GitHub, BitBucket, HackerRank, DevPost, Stackoverflow profile, any project URLs, hackathon / competition URLs  (without overlinking). If you have a LinkedIn profile, make sure you [customise and shorten your LinkedIn url] (https://www.google.co.uk/search?q=custom+linkedin+url) it will look much better than the default alphanumeric string used to identify you. If you've not used LinkedIn before, it's a business-oriented social networking service (see Figure. 1 for details). Think of it like Facebook or Twitter for grown ups, where people talk about employment and business. See Figure 1. for details. Joking aside, recruiters and Human Resource departments do use LinkedIn to fill job vacancies.
  2. **KNOW WHAT I MEAN?** Don't assume the reader of your CV knows what you're talking about. It's a classic mistake to make when writing.
  3. **UNDERSELL** a CV is no place for modesty - it is a professional advert for you to secure an interview with a prospective employer. Don't hide your light under a bushel!
  4. **VERBS FIRST** Starting sentences with VERBS can often help to emphasize what you have done rather than what you know. See http://git.io/verbsfirst Don't make the reader trawl through long pieces of prose to find out more, bullets are usually easier to scan and digest. Your CV will be assessed in seconds or minutes, the reader won't have time to read your life story - they are just trying to decide if they should interview your or not. You will be able to fill in the details at interview.
  5. **OVERSELL** but don't oversell by exaggerating or being deceptive about your achievements - it is easy to spot and check up on. Some employers have very rigorous background checks, so honesty is the best policy. If one inconsistency is found in your CV, however trivial, you could be rejected in the “subject to satisfactory references phase” of your job application.
  6. **QUANTIFY** improve any claims you make by adding numbers. For example, instead of saying “won prize for best student in year” you could say “won prize for best student in year (out of 200 in total)”
  7. **EXPAND** Expand abbreviations where you have space. For example, not every reader of your CV will know what PASS stands for
  8. **ME ME ME ME ME ME ME** Your CV is all about you, but you should be careful to avoid using first person personal pronouns “*I, me, my*” too much as it gets repetitive and can make you sound like a self-centered egomaniac. One way of avoiding this is to put the verb first, so instead of saying “*I developed a system for improving logistics*” you can say “*developed a system for improving logistics*”. It is OK to have a few “I's” in there,  and it is difficult to avoid in a personal statement, but too many personal pronouns can give the wrong impression.
  9. **SPILLING and GRAMMAR** Bad spelling and dodgy grammar look awful. Use a spell checker, but don't rely on it completely. Proof read the document manually. Proof read it again. Then proof read it again.
  10. **PROVE IT** It is very easy to make statements without backing them up with evidence or context. Wherever you can, try to avoid making unsupported claims e.g. “I am an excellent team worker” or “I am a Java expert”. Anyone can SAY this, how can you PROVE it? Don't tell people, show them. When did you work in a team? What did you use Java for? What was the result?
  11. **RESULTS** As well as describing what you did using active language, it can be good to describe results of your actions. So instead of saying “*developed a system for improving logistics*” you could say “*developed a system for improving logistics which reduced company overheads by 20%*”. This is what the CV and LinkedIn guide at http://man.ac.uk/6Ef90a calls the “CAR Model: Context, Action, Result”.
  12. **PERSONAL STATEMENT** If you are going to write a personal statement keep it brief, one or two sentences should do. Don't write your life story and a great big long essay, no-one will read it. E.g. “*I am a second year student studying Computer Science at the University of Manchester looking for an opportunity to apply my skills in algorithms and Java in the financial services industry*” not [“*A long time ago in a galaxy far, far away...*”](https://en.wikipedia.org/wiki/Star_Wars_opening_crawl)
  13. **LinkedIn** It can often be beneficial to have a [LinkedIn](http://www.linkedin.com) profile, See Figure 1 below. Your digital social media profile doesn't need to be as detailed as your CV, and you might not want to put all that personal information online. However, recruiters often use LinkedIn when they have vacancies to fill. Having a profile can also be a useful way to manage your professional network. If you'd like to connect on LinkedIn, I'm happy to connect with students at [https://www.linkedin.com/in/duncanhull](https://www.linkedin.com/in/duncanhull).

![social media explained in donuts](http://www.geek.com/wp-content/uploads/2012/02/social_media_donut-590x590.jpg "Social media explained in doughnuts")

**Figure 1: Social Media explained (in doughnuts)**

## Hobbies and interests (HOB)

Hobbies reveal some of your personality, which is what employers really care about

  1. **ANYONE FOR QUIDDITCH?** Hobbies aren't just an afterthought - it is an opportunity to stamp your personality on your CV and add a bit of colour to what can be a dry and factual document. Hobbies can be talking points for the interview, or make you stand out. They can also break the ice if you are fortunate enough to share interests with your interview panel. You might not have lots of spare time outside of study, but there is much more to university that just getting a degree. For example, there are ~500 different societies you could get involved in at [Manchester Student's Union](http://manchesterstudentsunion.com) alone (including [quidditch](https://en.wikipedia.org/wiki/Quidditch) in the [quidditch club](http://manchesterstudentsunion.com/groups/quidditch-club))
  2. **MEMBER?** If you are involved in activities or societies you should explain your role in the group. By itself, “member” is very vague, you can be a member of a society without doing anything. Were you a treasurer? Partipant? Organiser? Leader? Publicist? Secretary? Hacker? Hanger-on? Beer-drinker? Rabble rouser? Advocate? Trouble-maker? See ACTIVE LANGUAGE.
  3. **COMPUTING?** Is computing also your hobby? Don't be ashamed if it is. While it is important to have a work-life balance, if computing is your hobby (as well as your degree and day job) it shows commitment and enthusiasm to the subject beyond education. This is a good thing. In Computer Science, everyday is [geek pride day](https://en.wikipedia.org/wiki/Geek_Pride_Day)!

## Personal Details (PD) and REFERENCES

How to get in touch, much of this information can go at the end of your CV.

  1. **ADDRESS** PushedForSpace? Consider leaving out your postal address as an email address and phone number are usually sufficient, first contact from a prospective employer is unlikely to be by post. Some people put personal details last (with references), as they aren't the most important thing about you. Another option is to have them in the header or footer, if you have space, so that they are on every page of your CV.
  2. **THIS IS A CV (WELL DUH!)** Don't include the title RESUME or CURRICULUM VITAE. It will be obvious to the reader that the document is a CV/Resume, saying so is usually a waste of valuable space. The title of the document should be YOUR NAME big, bold and simple. E.g. just “ALAN TURING” not “CURRICULUM VITAE ALAN TURING”.
  3. **DATE OF BIRTH** You don't need to include your date of birth on your CV - your age should not a factor in your job applications. Also, publishing your birth date *could* make you more vulnerable to identity theft, see the [dangers of revealing your date of birth](http://security.stackexchange.com/questions/95029/how-dangerous-is-it-to-reveal-your-date-of-birth-and-why) for example.
  4. **MUGSHOT?** It is unusual to put a photo of yourself on your CV. What you look like should not be a factor in your job application (though some recruiters find it helps them to remember your face, especially if they have to deal with a high volume of CVs)
  5. **MARRIAGE & GENDER** Your marital status & gender should not be relevant to your job application either
  6. **MYDOMAIN.COM** The email address me@mydomain.com says more than just how to contact you, it shows that you know how to setup an email server and a web server. Make sure you mention your personal domain and email if you have one. It can give a better impression than a generic me@hotmail.com or me@gmail.com.
  7. **ON REQUEST** Usually you can just say “references available on request” rather than listing all your referees. If you have space, listing your referees will make it easier for the employer as they won't need to contact you again to get them, but most people won't have space to include them. Also by saying “on request” you know when the references will be taken up (because you'll be notified) so you have more control over the process.
  8. **ASK YOUR REFEREES** Make sure you check with your referees before references are taken up (often after your interview), its good to have a mixture of referees from different places if you can (e.g. Employers, University tutors etc) and you obviously need to be confident that they will write you a good reference.

## Next steps

What to do next:

* **RELEASE OFTEN** Having [released your CV early, keep releasing it often](https://en.wikipedia.org/wiki/Release_early,_release_often). According to [Linus's (Torvald's) Law](https://en.wikipedia.org/wiki/Linus%27s_Law) ''*given enough eyeballs, all bugs are shallow*''. So the more people who see your CV, the more bugs you can squash. Do a CV swap and peer-review with a fellow student (if you haven't already). Show it to your friends, colleagues, family, personal tutor, pet dog etc. The more people who see it, the better it will get. You can apply many of the the principles of [agile software development](https://en.wikipedia.org/wiki/Agile_software_development) to your CV.
* **IMPROVING** See five steps to take next: 1) Explore, 2) Connect, 3) Communicate, 4) Reflect and 5) Apply http://www.careers.manchester.ac.uk/myfuture/ and if you are in:
  * First year of your degree, see http://www.careers.manchester.ac.uk/first/
  * Middle years of your degree, see  http://www.careers.manchester.ac.uk/middegree/
  * Final years of your degree, see http://www.careers.manchester.ac.uk/final/
* **RE-CHECK** Have another look at the CV and LinkedIn guide from the careers service http://man.ac.uk/6Ef90a there is good advice mentioned there that is not in this guide
* **UPLOAD** Upload an updated version to the CV bank once you've changed it https://studentnet.cs.manchester.ac.uk/employment/industryclub/cvbank
* **REJECTION** It is hard work finding a job, most people will make several unsuccessful job applications and have multiple interviews before receiving a job offer from an employer they are interested in. Coping with rejection is routine part of applying for jobs. Keep trying and aim to get better each time, learning from your mistakes rather than repeating them.
* **SUGGESTIONS?** If you have any comments or suggestions on how to improve this guide, [raise an issue](https://github.com/dullhunk/book/issues) or [submit a pull request](https://github.com/dullhunk/book/compare). The source is written in [markdown](https://en.wikipedia.org/wiki/Markdown), and we welcome constructive feedback

Good luck with your applications and interviews. If you need any help speak to [Mabel Yau](https://www.linkedin.com/pub/mabel-yau/26/152/a5), the [careers service](http://www.careers.manchester.ac.uk/services/guidance/) or myself. I'm happy to give more feedback on improved versions of your CV in the future, while you are at University.

--[Duncan Hull](http://www.cs.man.ac.uk/~hulld), September 2016
