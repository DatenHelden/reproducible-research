###The Idea
Wrapping up [useR2015](http://user2015.math.aau.dk) in a few words: it was a fantastic conference. We met a lot of wonderful open minded people, who enlarged our water research driven universe. 

All R users are taking advantage of the nearly infinite problems that can be solved 
with it in a systematic, transparent and automatised way. Both, automatisation and 
transparency are a prerequisite for achieving the "gold standard": [reproducible research](http://reproducible-science-curriculum.github.io/duke-techexpo2015/#/4) 


###The Challenge

**Creating a centralized R knowledge hub for reproducible research** by wrapping the state of the art 
tools & packages available for R.


###What to do?

1. Screen the R world for already available tools which you are using because of their excellant functionality. 

2. Add them 

3. Explain from a functional point of view why your proposed tool is so great

4. Community should evaluate the usefulness!

####Which components? 

What are the best tools/packages for:

**1. Data**
- Import: getting different file formats, data bases & Web data (e.g. Twitter, Facebook) 
into the R universe
- Preparation: cleaning, aggregatiion
- Analysis: graphical visualisation

**Something missing? Please add it in the markdown document "index.md" on** [Github](https://github.com/DatenHelden/reproducible-research.org)

**2. Modelling**

**Proposed methodology:** "Wrap your model" (conference paper by [Hauke Sonnenberg et al. 2014](http://dx.doi.org/10.13140/RG.2.1.2140.3683))

**Examples:**
- Machine learning: [mlr package](http://mlr-org.github.io/mlr-tutorial/tutorial/release/html/) 
- Environmental: e.g. [openmodelling](http://kwb-r.github.io/openmodelling/) by [Kompetenzzentrum Wasser Berlin gGmbH](https://github.com/KWB-R)

**Something missing? Please add it on** [Github](https://github.com/DatenHelden/reproducible-research.org)

**Usual workflow:**
1. Parameterise
2. Run,
3. Analyse,
4. Calibrate,
5. Validate,
6. Predict and .....

**3. Document**

your results (automatically, e.g. by using R package [rmarkdown](http://rmarkdown.rstudio.com) by [RStudio](http://rstudio.com)). 

**4. Deployment**: 
-  Web-based or stand-alone?, 
-  Development or production?, 
-  In case of production: does your used tool scale without being too expensive (i.e. price is independent to the number of connected users?)

**Tools:** 
- [Shiny](http://shiny.rstudio.com),
- [R API "OpenCpu Project](http://opencpu.org), ... 

**5. Additional topics**: 
- Crowdsourcing: e.g. [Ohmage](http://www.ohmage.org/) as open-source framework for data collection, analysis (using R) and ready-to-use apps (for iPhone, Android) based on user defined surveys ([Slides](http://www.stat.ucla.edu/~jeroen/med2/#/step-1) & interactive examples [Snack](http://jeroenooms.github.io/dashboard/snack/), [Advertisement](http://jeroenooms.github.io/dashboard/media/) by [Jeroeen Ooms](https://jeroenooms.github.io/)

- Learning:
  + OpenBooks: e.g. statistics by [OpenIntro](http://www.openintro.org); R: [Advanced R](http://adv-r.had.co.nz/) & [R packages](http://r-pkgs.had.co.nz/) by [Hadley Wickham](http://had.co.nz/), ....
  
  + Training: [DataCamp](http://www.datacamp.com)
   
###Who?
Something is missing? Please help us in improving the concept by contributing to the project by adding the missing things them in the markdown document "index.md" on [Github](https://github.com/DatenHelden/reproducible-research.org).

###When?
There is no clear deadline for the tasks listed in the proposed project roadmap listed below. However, the idea is to complete the "design phase" until end of December 2015.

**Proposed Roadmap:**
1) Concept phase
1 A) Structure the R knowledge according to topics and subtopics (e.g. modelling, data input, ...)

1 B) Identifying the best tools for each topic by using a community driven evaluation (e.g. standardised questionaire to each package developer based on topics e.g. "visualisation" -> results could be send to offer package developers on same topic for cross-evaluation -> best on received feedback a TOP list could be generated helping new user to immediately use the best available packages)

2) Design phase 

After completing the concept phase the design phase should start making the website look as professional as e.g. [Rstudio](http://www.rstudio.com) but so flexible so that the community can add topics easily (i.e. by modifying markdown files) for each webpage on [GitHub](https://github.com/DatenHelden/reproducible-research.org)

Want do you think about it? I would really love to receive your comments & feedback on [GitHub](https://github.com/DatenHelden/reproducible-research.org).


###FAQ
### How do I know that an R tool/package is of high "functional" quality?

**How can a separate "functional" well designed tools from "conventional" tools?**. 
We define "conventional tools" in this context as tools that are well-kown (often because they is a company behind it with big money and a marketing strategy behind). An example of such an tools is for example [shiny](http://shiny.rstudio.com), which is used for interactive web applications in R. Such tools are sometimes useful e.g. for rapid protypeing. However, such tools should always critically reviewed concerning their efficiency to be used in a production based context (e.g. scalable web-based software-as-a-service products) in terms of: 
- Money: does your used tool scale without being too expensive (i.e. price is independent to the number of connected users?)
- Time: are there additional skills required by the R user? Or would it be possible to outsource the graphical user interface (GUI) development to a professional web developer?
- Useability: how complex can the web interface be considering time & money constraints?

In a production based context, which requires scalable solutions the [R API OpenCpu Project](http://opencpu.org) by [Jeroeem Ooms](https://jeroenooms.github.io/)
is "functionally" superior to the "conventional" [shiny](http://shiny.rstudio.com) approach because its: 
- Free-of-charge for infinite number of users while [shiny costs 9995$ for 20 concurrent users per year](http://www.rstudio.com/pricing/)
- No need to learn the "reactive" shiny programming language on top of R  
- Enables the separation of web based GUI development from R package development 

**Questions to be answered by yourself:**
- Do you want to be completely responsible for the GUI development? Or wouldn`t it be better (in terms of money, time & useability) to outsource this task (e.g. by contracting a professional web designer) and using the [R API](http://opencpu.org) by [Jeroeen Ooms](https://jeroenooms.github.io/)?
- Is the level of website complexity you could do with [shiny](http://shiny.rstudio.com) sufficient for your problem at hand? And if yes: are you sure that your web tool will be used **forever** (!) only by a small amount of people concurrently? If you answered both questions before with "yes" then **shiny** might be an option for you! **If not: use the [R API](http://opencpu.org) for your web app!**

### Add your questions here! 

For adding your FAQ-questions add them in the markdown document "index.md" on [Github](https://github.com/DatenHelden/reproducible-research.org)

