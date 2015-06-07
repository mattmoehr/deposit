%Using Social Media to Define Neighborhoods
%Matthew J Moehr

# Introduction to Neighborhood Effects

Sociologists have long struggled to find a method for drawing boundaries around neighborhoods [@Sampson2002, 445; @Matthews2011, 39-41; @Burton2000a]; however, this doesn't stop us from publishing thousands of research papers detailing the neighborhood effect on various aspects of health, education, employment, and voting. The overarching goal of this project is to introduce a new way of defining neighborhoods based on social media. Along the way I will demonstrate why the definition of neighborhoods is fundamental, not only to the conceptualization of spatial demography, but also to the ongoing debates about the measurement and modeling of neighborhood effects. 

At first it may seem curious that an entire dissertation could be devoted to "mere" methodological concerns about defining neighborhoods. I argue that this is a worthy endeavor for two reasons. First, neighborhoods are weird things -- sociologically speaking. They have strong effects on people's lives, and yet, when compared to other institutions like schools, states, religions, or the labor market, neighborhoods have very little formal power. To understand this paradox, we must first come up with good definitions of sociologically meaningful neighborhoods. The second reason that neighborhoods can fill up an entire dissertation can be seen in the proliferation of methodological appendices I have included here. Each appendix in this dissertation represents one particular situation where my research questions bumped up against the accepted methods of social science research. Since this happened quite frequently in this project, I must surmise that social science, and sociology in particular, has not developed enough of the basic tools for dealing with spatial data, photographs, and non-random samples. Fifteen years ago, Gieryn [-@Gieryn2000, 484] called for a deeper and broader engagement with place-based sociology, but apparently, not enough of us have met his challenge:

> "I am a victim, perhaps of trained incompetence in a discipline that cultivates statistics and words as means to grasp the social. Sociologists could become more adept with maps, floor plans, photographic images, bricks and mortar, landscapes and cityscapes, so that interpreting a street or forest becomes as routine and as informative as computing a chi-square. That visualizing (I think) is the next step." 

To take a step in Gieryn's direction, I have made use of publicly-available data from photographs shared on Flickr ([https://www.flickr.com/]()). Specifically, I use information about the geographic location and the placenames, which are added to the photographs by their creators and other Flickr users. By aggregating together millions of these photographs, social science researchers can begin to glean useful information about neighborhoods (or other geographic entities like cities, regions, or points of interest). I will further detail the background of Flickr, geotagged photographs, and the methods I used for defining neighborhoods; but for now, the important point is that this novel approach stands opposed to the de facto standard of using administrative boundaries like census tracts to define neighborhoods [@Krieger2006]. Administrative boundaries have been created to serve a myriad of bureaucratic goals [@Harvey2006], but to my knowledge, there is no nation-wide set of boundaries that were designed to capture sociologically meaningful neighborhoods. Below I will further describe the history and methods behind census tracts because they are the most commonly used definition for neighborhoods in social science research.

Neighborhoods and their effects is a large literature itself, but it belongs to the even larger field of spatial social science [@Goodchild2004] and spatial demography [@Entwisle2007]. Within these broader fields there are a number of ongoing debates, but, in order to limit the scope of my dissertation, I have chosen to bracket off some of these problems. In no way does this mean I think these are trivial issues or not important for spatial social sciences. I hope that some of my work might help bring up interesting new ideas or questions regarding these debates. For example, I have explicitly chosen to avoid:

- Theoretical works on the distinction between space and place.
- The potential problems created by the ecological inference fallacy.
- All of the additional complications introduced by space-time methods.
- Debates about the role of scale in social theory or related problems of regionalization.
- The emerging research on spatialized social networks and social capital.
- The statistical literature developing new spatial econometric models.

The rest of this chapter is organized as follows. First, I will review the background literature on neighborhood effects. In this section I will be paying special attention to the research of Robert Sampson, Patrick Sharkey, Kyle Crowder, Scott South, and their co-authors. The first background section also includes the summary of census tracts and a description of the implicit assumptions made by researchers who use census tracts. Second, I describe social media and Flickr in particular. The second background section describes geotagged photographs and where they fit into the current area of research known as volunteered geographic information (VGI). Third, I take a detour into the philosophy of science so that I can clearly state how this dissertation contributes to the field of neighborhood effects research. Fourth, and finally, I will give a brief summary of each of the three empirical chapters, which flesh out the overarching goal of providing a new method to define neighborhoods. 

## Background on neighborhood effects

In the past twenty years, the concept of "space" has seen a growing popularity in sociological research. In general this literature argues against methodological individualism and tries to emphasize the direct, indirect, and interactional effects that the local environment may have on behaviors and life outcomes [@Gieryn2000]. Neighborhood effects is the most common type of spatial research. See @Sampson2002 for a review of neighborhood effects research. Specifically, for a history of the development of neighborhood effects in different literatures I recommend @Entwisle2007 [687-94] in demography, @DiezRoux2010 [126-32] in public health, @Durlauf2004 [2211-24] in economics, or chapter 2 of @Sampson2012 in sociology. These reviews often cite the same theoretical works including the Chicago School of sociology; Marxist perspectives offered by David Harvey; William J. Wilson's _Truly Disadvantaged_; social capital theories like those from Robert Putnam; and social network research on information flows like @Coleman1988 and @Granovetter1973. In terms of empirical touchstones, the most oft mentioned study is the Moving to Opportunity experiment (summarized well in @Ludwig2012); the debate begun by Jencks and Mayer criticizing the size and identification of neighborhood effects (see e.g. @Jencks1990 and @BrooksGunn1993); and the massive surge in publications as GIS and census data become more usable on personal computers in the 1990s (e.g. @Sampson2002 [444] and @Entwisle2007 [690] both show graphs of the trend).

The neighborhood effects literature has come a long way, intersects with many fields of study (e.g. criminology, public health, education), and can now be thought of as its own paradigm. However, the neighborhood effects paradigm has a number of problems. One of the most onerous problems noted by writers such as @Manski1993 and @Oakes2004a is the "selection effect." According to the neighborhood literature, a selection effect is the generally higher probability for people to move among similar neighborhoods. When they move, disadvantaged people tend to move to disadvantaged neighborhoods and conversely more advantaged people tend to move to more advantaged neighborhoods. Thus, it is methodologically challenging to parcel out the unique contributions of the individuals' and the neighborhood's effects. However, in the last few years, more research is being published that specifically models [@Wodtke2011; @Blume2010] or theorizes [@Sampson2012 chapter 12; @Sharkey2014 chapters 4 and 5] the selection effects as not just a "problem," but an integral part of understanding the neighborhood dynamics in modern U.S. urban settings. Thus, Oakes's critique does not seem to be as lethal 10 years on, however, selection effects are still present in most neighborhood effects research -- including my own. We are starting to think of the selection process as one of the key mechanisms of how neighborhoods work, in other words selection effects are one type of broader area of contextual effects, which we turn to now.

As Oakes argued, "Social scientists have long suffered an interest in neighborhood effects, which they view as a special case of context effects -- the raison d’etre of social science [-@Oakes2004a, 1930]." Other types of contexts include schools, churches, clubs, social movements, and sometimes even "culture." Thus, to argue for the importance of neighborhoods is to argue for the importance of a special type of context. And while neighborhoods are unique in some aspects -- they're spatial, they arise from and influence economic activity, they don't have clear boundaries -- they are susceptible to some of the same problems of all contextual models. @Hauser1970 was an early critic of contextual modeling with individual-level regressions, saying "...their [contextual effects] magnitude will be inversely proportional to the adequacy and completeness of the underlying model of relationships among individual attributes [662]." In other words, Hauser claims that contextual effects will increase as individual-level errors increase. Advances in multilevel modeling developed by Raudenbush and colleagues [e.g. @Raudenbush2002] in the 1990s and 2000s have solved some of the problems. However, very specific types of pre- and post-treatment data collection along with clustered samples are required to produce well-identified estimates of the contextual effects even with hierarchical models (or the more general class of linear mixed models).

If individuals can change group memberships, e.g. between schools, neighborhoods, or clubs, then contextual models will have to deal with the selection effects problem as described above. Additionally, if the contexts and individuals mutually influence one another, the models may be threatened by problems of endogeneity. Manski's paper [-@Manski1993] on the "reflection" problem is an early demonstration of the problem with estimating the effect of the neighborhood independently of the attribute of the people, when most people's attributes are also strongly related to neighborhood selection (either through choice or constraint). Additionally, there may be endogenous effects that arise because, a) residents' beliefs about their neighbors may change their own behavior, or b) each resident's behavior may change the neighborhood, which then in turn influences that resident. Note that the problem of endogeneity would still exist in the absence of selection effects. For example if we prevented everyone from moving, there could still be endogenous neighborhood effects. The current method for solving these two closely related problems entails modeling them directly by using longitudinal data [@Wodtke2011] or social interaction models [@Blume2010].

Most contextual effects do not have a problem with lack of support, but because America is severely segregated along income and racial lines, there is a dearth of observations with white, rich people living in disadvantaged neighborhoods and virtually no observations of black, poor people living in well-off neighborhoods [e.g. @Sampson2012, chapter 5]. This means that the "effect" of certain demographic characteristics (income, race, and to a lesser extent, eduction), are conditioned on the person's neighborhood. E.g. we can't estimate separate effects of being in a majority black neighborhood and being in the black racial category, because there aren't enough observations of non-black people living in majority black neighborhoods to give consistent standard errors on the estimates. It is likely that persistent residential segregation [@Quillian2002] makes the lack of support problem worse for neighborhood effects  than for other contextual models based on contexts like schools. Social scientists are accustomed to dealing with problems like measurement error, missing data imputation, heteroskedasticity, and omitted variable bias; however, neighborhood effects models are plagued by additional methodological problems that afflict all types of contextual models.  

Each of these problems -- selection effects, endogeneity, and lack of support -- is exacerbated by the fact that researchers implicitly assume that neighborhoods are extensive and mutually exclusive. Social science researchers often use the census tract (or an agglomeration of multiple tracts) to define the neighborhood for each individual, and tracts cover the entire U.S. and never overlap. This posits a situation where a person is "all in" or "all out" of a neighborhood, and every single person is in one and only one neighborhood [for similar critiques see @Matthews2011, 38; @Blume2010]. We can easily imagine that a person might live in a gray area between two neighborhoods and thus might be partially in each neighborhood. Alternatively, we can imagine people that live (or work, or shop, or socialize) in areas that are either too sparsely populated to function like most neighborhoods, or are controlled through private gated communities, or are designed to accommodate constant residential turnover like dorms or military bases. The work in Chapter 4 also brings into focus less densely populated areas in rural, suburban, and exurban communities. Many of these areas are not defined as neighborhoods based on Flickr data, and this means that individuals located in "non-neighborhoods" are modeled separately. The background literature on neighborhood effects shows us that we are still searching for improved methods for handling contextual effects and endogeneity.

Another recurring problem in the literature is the modifiable areal unit problem (MAUP). The MAUP has dogged spatial social science for at least 60 years [@Gehlke1934; @Robinson1950; @Openshaw1984; @Jelinski1996].  Briefly, the problem can be described as the undecidability of the "correct" spatial units to use for statistical analyses.  It should be intuitive that the conclusions of a statistical model depend on both the substantive relationships in the data and the way that the data are aggregated.  Thus, it would be desirable to know how to divide up the study area so as to render the substantive conclusions valid. However, most research uses census tracts  because they are readily available, and researchers claim that census tracts are not blatantly wrong. For example this is an early example of a phrase often seen in the literature:

> "Census tracts contain 4,200 people, on average, and are formed by local committees appointed by the Census Bureau to approximate locally perceived 'real' neighborhood boundaries. Thus, there is considerable appeal to the use of census tracts to approximate most conceptions of neighborhoods. There is little we can do about concerns that tracts are larger than true neighborhoods, since the tract is the smallest geographic unit for which we were able to gather neighborhood-level data [@BrooksGunn1993, 378]."

The two best formalizations of the MAUP can be found in @Openshaw1984 and @Fotheringham1991. These works are important to me as they introduce two tools for thinking clearly about the MAUP. First, @Fotheringham1991 [1025] divide the MAUP into two separate problems: scale and zoning. Scale problems have to do with finding the best spatial scale at which to model the phenomenon of interest. Hipp and colleagues [@Hipp2007; @Hipp2012a; @Wooldredge2002] have been testing models using different levels of census geographies (blocks, block groups, tracts), which demonstrated that scale problems are not as dramatic as originally thought. However, @Fotheringham1991's conclusions about zoning effects seem to hold up. For example, they showed that census blocks could be aggregated into any number of configurations -- of which, the official census tract boundaries is just one possible realization -- and found "it was possible to report from one zoning system that there was a significant positive relationship, from another that there was no significant relationship, and from yet another that there was a significant negative relationship [1041]!"

In my thinking, @Openshaw1984 and @Fotheringham1991 play a second role. Namely, they turn the usual modeling approach on its head. Most quantitative sociological research focuses on two problems: what observations should be included in the model? and, what variables should be included in the model? However, these two papers -- and my dissertation chapters -- attempt to move these questions to the background. Their approach is to use the same model over and over again, with different operationalizations of areal units. In this approach, the researcher looks for differences between models, which presumably arise from the different configuration of neighborhoods, rather than concentrating on model specification and model selection. I like this approach as my conclusions do not rely on finding the "correct" model. Instead my empirics are geared toward showing that the model parameters change with different operationalizations of neighborhoods. Thus, potential criticisms of Openshaw, Fotheringham, or my work are diffused with this counter-argument: it is highly probable that the models used here are misspecified or biased, however, it is highly improbable that specification and bias problems differentially afflict models with different neighborhood configurations. I.e. sure the models are wrong, but they're probably wrong in consistent ways.

Some researchers, including @Sampson2012 [258], think that the MAUP is ignorable when using spatial lag or error models because the parameters of the model can estimate the spillover effects coming from nearby places. These authors would suggest that spatial models can "control" for the MAUP by allowing spillover effects. @Anselin2002 proves this is wrong [262-3; see also @Wall2004], and concludes:

"Given these problems [the MAUP], one might be tempted to dismiss spatial lag models estimated for aggregate units [i.e. neighborhoods]. Clearly, a naive interpretation of the parameters of such a model is misguided when they are considered as proxies for individual-level parameters that reflect substantive spatial dependence, e.g. as implied by a spatial reaction function [i.e. spillover effects]. However, there remain many contexts where the interest is in the aggregate object considered in its own merit, and not as an aggregation of lower level units [i.e. people]."

To understand why census geographies may aggravate the MAUP, we need to review the Census's building blocks, methods, and purposes for creating geographical units. The fundamental building block of all census geography is the... well, block. In 2010 blocks were defined as "statistical areas bounded by visible features, such as streets, roads, streams, and railroad tracks, and by non-visible boundaries, such as selected property lines and city, township, school district, and county limits and short line-of-sight extensions of streets and roads." Blocks are created by Census Bureau staff using GIS. One or more blocks are combined into block groups, which may contain between 600 and 3,000 people. One or more block groups are combined into tracts, which "generally have a population size between 1,200 and 8,000 people, with an optimum size of 4,000 people." 

The block groups and tracts are created with local input through the Census Bureau's Participant Statistical Areas Program[^partstat]. According to it's own documents the Census Bureau will only step in to delineate block groups and tracts when there is no participation from local stakeholders.

[^partstat]:
    [https://www.census.gov/geo/partnerships/psap_overview.html]()

"The primary purpose of census tracts is to provide a stable set of geographic units for the presentation of statistical data." This means that stable boundaries are favored. Local participants are instructed to split or merge census tracts to conform with the target population limits, and warned against re-arranging boundaries that would result in non-nested boundaries. The Census Bureau's preference for stability -- combined with the little known fact that it wasn't until the 1970s that census tracts first covered all metropolitan areas and wasn't until 2000 that they covered all of the U.S. [@Krieger2006] -- means that the 2010 census tracts will be biased toward the legacy of the built environment for urban areas from the 1960s and the built environment for rural areas from the 1990s.

The Census Bureau's documentation for the 1990 geography process contains this instruction: "When first established, census tracts are to be as homogeneous as possible with respect to population characteristics, economic status, and living conditions." As far as I can tell, this specific instruction has been removed from the Bureau's instructions for census tracts, but again, combined with the preference for stability, we should assume that census tracts are biased toward homogeneity with regards to the listed characteristics.

All five of these aspects of census geographies -- visible features, hierarchical arrangement, optimal population of 4,000 people, preference for stability, preference for homogeneity -- may make census tracts into poor operationalization of neighborhoods. For example, Matthews, Kwan, and Sampson agree that census tracts are almost certainly too small to be good definitions of activity spaces. And multiple researchers have noted that as we move up the hierarchy (block... block group... tract), the amount of variance will decrease. This pattern in results is certainly attributable to the "real" spatial segregation in our world, but we can not tell how much the pattern is de/emphasized by the preference for homogeneous areal units. Thus we might want a type of neighborhood areal unit that was bigger, and yet allowed for heterogeneity "with respect to population characteristics, economic status, and living conditions."

Finally, there is one overarching reason that census geography is probably making the MAUP worse for neighborhood effects. To wit: the entire process is a black box. To my knowledge no social scientist (or historian) has analyzed the black box [see @Krieger2006 for an overview]. The only notable exception is the methodological appendix contained in @White1987, but it applies to the 1980 census, and it only analyzes the output of the local participant committees -- not their makeup or functioning. There may be biases in who participates, how different local participant committees function, the fidelity of the committees to the bureau's instructions, the tendencies to include or exclude information from the real estate industry, or the amount of people and places under the purview of each committee. The make up of the local participant committee may lead to some tracts, e.g. in downtown areas, being more intricately defined and smaller in size, simply because the members live in the area and have the type of knowledge that locals have of neighborhoods. And the opposite may be true in that some areas are generalized and bigger because no members have local knowledge of the area. We simply have no way of knowing how much, or if, this occurs because census tracts are the product of a black box.

Unlike geographic units like counties or cities, neighborhoods have a strong subjective component where residents define their own boundaries. The Census Bureau's methods for defining census tracts give no regard to the subjective nature of neighborhoods. It is possible that some individuals on the locals committees offer input on the subjective definitions of neighborhoods, but again, give the black-box nature of the process, we have no way of knowing. Therefore in the case of neighborhoods, it may be especially desirable to find a method using bottom-up definitions rather than top-down definitions. There are two extant methods for defining neighborhoods with bottom-up methods. Both have significant challenges for practical implementation, and have had very little impact on research in spatial social science.

First, an obvious way of making bottom-up definitions is to directly ask residents to draw maps of their neighborhoods. There is a long history of research on mental maps, but mostly in behavioral geography [@Lynch1960; @Gould1974; @Golledge1981, 1337-8], with only a few exceptions in psychology or sociology (see @Coulton2001 and the citations on page 372 therein). All of the existing research with mental maps is limited to a small number of neighborhoods within a small number of cities and has never been generalized to a nation-wide setting. Even so, they tend to show rather large divergence from census geography. For example @Coulton2001 concluded "...census tracts may be reasonably sized units for representing neighborhoods, but there is no evidence that residents see their neighborhoods according to census geography [381]."

Second, there is a growing body of literature suggesting that activity spaces and travel patterns may be one way of representing of neighborhoods that are more like day-to-day life for most people. @Matthews2013a is the foremost champion of this approach at the moment, but it has its roots in the GIS, feminist, and multi-method research pioneered by Mei-Po Kwan and colleagues [@Kwan2002; @Kwan2009; @Kwan2008]. The basic idea is that if we understand people's daily movement then we can define their neighborhood as the area where they usually work, play, shop, learn, and live. Again, these methods have, to my knowledge, only been applied in small samples in a few urban settings. However, with increases in GPS enabled mobile phone use and improvements in wearable activity tracking technology, it may become more practical to implement these methods with large, random, and nation-wide samples.

Interestingly, both strains of research usually focus on the neighborhood -- no one bothers to make bottom-up definitions of a state or a nation. I point out this obvious point just remind readers that neighborhoods are "weird" when compared to other levels of geography. Neighborhoods may need bottom-up definitions more than other geographies, but the methods for making bottom-up definitions are also more prohibitive for small, localized geographies like neighborhoods. The neighborhood effects literature has long been stuck in this bind: we think we want bottom-up definitions but they are impossible to implement in nation-wide samples. Data from social media may now allow us to find a middle way.

Before finishing this section, I would like to quickly list the aspects of the current definition of neighborhoods and contrast it with Flickr neighborhoods. These points have been sprinkled throughout the preceding section on the neighborhood effects literature, but it will be useful to put them in one place. @Spielman2013 [73] is one notable exception, but generally, authors do not explicate their definitions of neighborhoods. This has contributed to the current situation in the literature where "neighborhoods are whatever is measured by neighborhood effects[^attitudes]." To avoid this, first, I list the five implicit assumptions of the current definitions of neighborhoods:

1. Extensive: census geographies usually cover the entire country and they do not leave any gaps between polygons. Are neighborhoods extensive? It is easy to imagine lightly populated areas that are not inside "neighborhoods" at all. Likewise, it seems possible that some places might have so much turnover (college towns) or lack almost all social connections (high crime areas) that they do not function like a "neighborhood." I argue that a definition of all the neighborhoods within a city does not necessarily have to cover all the territory of the city; or they might. Regardless, it is a question to be answered empirically, not circumvented by definition.
2. Non-overlapping: the practice of using census geography to define neighborhoods has put in our minds that it is definitionally impossible for them to overlap. But is this true? Could it be useful for some modeling approaches to operationalize neighborhoods that can overlap, thus showing space that may be affected by more than one neighborhood?
3. Mutually exclusive: the next logical step is to interrogate the dichotomous nature of neighborhood variables. Can a person (household, school, shooting event, etc.) be only partially in a neighborhood? Can a person be in multiple neighborhoods? Are points near the edge of a neighborhood affected by it the same way that points in the middle would be affected? (There could be some interesting work done by combining number two and three: what would partial *and* overlapping neighborhoods do to our models?)
4. Size: I am not aware of any research that posits a fundamental size of a neighborhood. Some researchers try to rationalize the use of census tracts because they are about the right size to contain daily activities like work, school, shopping, and socializing, but that is both a dubious empirical claim and irrelevant for the purposes of defining neighborhoods. People move and communicate, so I think it would be a hopeless task of trying to figure out how big (in terms of space, population, or whatever metric you want) a neighborhood should be. Furthermore, I see no reason to conceive of all neighborhoods as being, even roughly, the same size. There is no theoretical problem with having enormous and tiny neighborhoods in the same research. 
5. Homogeneity: the Census Bureau has sought census tracts with homogeneous social and demographic characteristics since at least 1930 [@Krieger2006; @Census1947, 10]. This line of thinking is then adopted by other researchers when making definitions of neighborhoods such that we sometimes mislead ourselves into thinking that neighborhoods should maximize within-neighborhood homogeneity and between-neighborhood heterogeneity. But what about a particular neighborhood that is known for its diversity and heterogeneity? Is it defined out of existence? Another problem with constructing neighborhoods by maximizing internal homogeneity is that we run the risk of confounding our other predictor variables. If we define neighborhoods as contiguous areas with similar racial and income characteristics, and we estimate the effects of race, income, and neighborhood on a child's chances of high school graduation, then we've essentially entered the race and income variables into our model twice (albeit the neighborhood variable might have some more noise in it than the two separate variables).

Relaxing some or all of these assumptions for neighborhood definitions can help us improve our measurement of neighborhood effects. However, we do need some assumptions about what a neighborhood is. I think neighborhoods must satisfy these three, much less restrictive requirements:

1. A neighborhood could potentially exist anywhere -- rural, urban, suburban, industrial, commercial, residential, land, water, etc. To a passer-by it might seem as if an abandoned strip mall is not part of any particular neighborhood, but some kids might use its parking lot for a regular pickup soccer game on their way home from school. To them it is certainly part of, not just any, but their neighborhood. As researchers we can not say *a priori* that some areas are off limits to neighborhood definitions.
2. Neighborhoods must have some sort of geographical presence. Sociologists study many different types of communities, organizations and institutions. It is only when these entities are stuck to the earth, it is only when they have a spatial component, that we might rightly consider them neighborhoods.
3. Neighborhoods have to have a name, and people have to use the name for communication.

That last one is probably the most controversial, so additional explanation is warranted. I think neighborhoods (or the names thereof) must be used by people to communicate and signify meaning. One simple case is the situation where one person asks another person for directions to a certain neighborhood. If no one has ever heard of the neighborhood, it does not exist. Note that I am not arguing that this sort of communication must be unproblematic for the neighborhood to exist -- just that it must be possible; people can and do disagree about where neighborhoods are located. And remember that certain social actors like real estate agents may have strategic goals in mind when trying to communicate neighborhood names, so I am also not arguing that this criteria is free of power dynamics. I am arguing this: since census tracts do not have recognizable placenames they do not qualify as definitions of neighborhoods (more on this in Chapters 2).

That is a short list of the required features for a neighborhood. Obviously, research projects might need to include other aspects in a definition of a neighborhood. If a paper is about the effect of bike paths on obesity, then the distance traveled by an average bicyclist in an hour might be a useful upper bound on the size of neighborhoods for that particular project. However, these additional requirements can not be determined without specific knowledge of the social phenomenon, and thus can not be part of *a priori* definitions of neighborhoods. Now that we have summarized the literature on neighborhood effects, explored some of its current methodological challenges, and listed the assumptions behind its definition of neighborhoods; we will turn to Flickr as a potential source for new defintions.

[^attitudes]:
    A book by @Danziger1997 brought this phrase to my mind, but he was in the process of critiquing the concept of attitudes within psychology. There is probably much to be learned from that debate, as "attitudes" became a hot topic that was linked to many substantive areas: voting, health, household economics, family demography. Many aspects of this pattern -- a concept getting more popular , using it to explain outcomes in multiple domains, *then* trying to figure out how to define it -- may also be going on with neighborhood effects research. For an early summary of attitude research in multiple domains see @Ajzen1977, which is structurally equivalent to @Jencks1990 in the neighborhood effects literature. The exact quote from @Danziger1997 [152] reads, "Attitudes were whatever it was that attitude scales measured, just as intelligence was whatever intelligence tests measured. The question of the meaning of such measures was not often addressed."

## Background on Flickr

At this point, I will briefly introduce Flickr and the process for geotagging photographs, but each subsequent chapter includes more detailed information on how I turn the photographs into neighborhood boundaries. Flickr was founded in Canada in 2005 and was subsequently bought by Yahoo. It allows users to upload photographs and share them with the world, with a select list of followers, or keep it private to themselves. During the upload process, users can apply titles, descriptions or geotags. Geotags are defined as a combination of latitude and longitude plus a geographic placename. In Flickr, placenames are drawn from the Where On Earth (WOE) gazetteer, which was created and maintained by Yahoo. In addition to the user specified meta-data, each photograph usually contains a number of meta-data attributes such as the date and time the photo was taken, type of camera, aperture settings, and whether or not the camera's flash fired. All of the meta-data for publicly viewable photographs in Flickr can be queried by the public. Throughout my dissertation I made use of the query features to gather geotagged photographs in specific cities, which were geotagged with neighborhood-level placenames. Since 2010, Flickr's share of internet traffic for photo sharing has been declining as Facebook and Instagram have become more popular. However, I choose to use Flickr because its geotagging data is the most robust, and compared to upstarts like Facebook, Instagram, and Twitter, it has a relatively steady level of user engagement dating back over a decade.

In contrast to the basic building blocks in census geographies, neighborhoods based on Flickr photographs do not necessarily have to follow visible boundaries, but they can be defined to follow street patterns if that is what the researcher wants. (See Chapter 2, Appendix 1 for some further description of the non-trivial challenge of turning points into polygons.) The geographic hierarchy is also open to specification by the researcher. In all of my work I concentrate on just the neighborhood level, but the raw data in Flickr also contains tags for cities, states, nations, continents, and individual points of interest. 

When it comes to methods & purposes, neighborhoods based on Flickr should be seen as a representation of meta-behavior. In other words, millions of users are going about their normal lives and sharing photographs. Some of the users add geographic information to photographs (possibly to increase communication with other people, possibly to help themselves remember and catalog their images, possibly for some other reason). Then I come along and harvest parts of the Flickr database to define neighborhoods. The Flickr users themselves are (almost certainly) not trying to map or diagram a neighborhood. Thus, I  argue that neighborhoods based on Flickr data reflect the neighborhood as it is being used in one slice of daily life -- the internet -- as compared to census tracts which are defined with a set of instructions and input from stakeholders who are beseeched to map and diagram places. To borrow a phrase from @Matthews2013b [1065], I'm confident that the Flickr photographs represent a meaningful slice from at least one of the user's "domain[s] of life (work, school, health, and family)." I think this shows that Flickr data is less susceptible to criticisms of the MAUP (once a researcher figures out how they want to transform points into polygons) because they are not just one possible way to partition space into areal units, they are representations of shared understandings, aggregated communications, and daily activity. Flickr neighborhoods might be accurate or inaccurate, biased or valid, precise or imprecise; but they are not the result of an artificial, black-box process and therefore they are less open to modification (more on this in chapter 3).

Flickr neighborhoods can be based on large, nation-wide samples of photographs and users. In 2012, Flickr estimated that their worldwide databases contained over 900,000,000 geotagged photographs. The alpha shapes used in Chapter 4 are based on nationwide data; however, the neighborhood definitions in chapters 2 and 3 are based on much smaller sub-samples. Even so, the smaller samples still have more users than the samples cited in mental mapping studies, and the number of photographs used in chapters 2 and 3 is higher than the total number of nodes in all of the activity space studies summarized by @Matthews2013b. Unlike the previous methods for creating bottom-up definitions of neighborhoods, Flickr data already comes to us at the nation- and world-wide scale.

Flickr users are applying placenames and geographic coordinates to their images during their normal activity of saving or sharing photographs. When users geotag photographs, they are not drawing their entire mental map of a place, but they are using their embedded geographic knowledge to apply the geotags.  Users can use placenames and coordinates (along with other tagging and textual descriptions) to enhance a photograph's meaning for themselves, allow them to remember important information in the future, and help communicate with other Flickr users. I do not know if users are strategically employing geotagging -- e.g. is a photo viewed more if it is tagged with Williamsburg or Brooklyn or both? -- however, I am confident that geotags are based on users' understanding of where they are and how a user thinks other people understand places. Flickr doesn't elicit a mental map, but the geotag data arises from the latent mental maps of users. These three facts -- 1) Flickr is a large sample, 2) taking and uploading photographs is a slice of a user's activity space, and 3) tags and coordinates are drawn from embedded geographic knowledge -- mean Flickr photographs can be a compromise between top-down and bottom-up methods for defining neighborhoods. 

To conclude this section I will preview the longer treatment in chapter 2 dealing with potential biases in the Flickr data. Research using Flickr is part of a wider topic known as volunteered geographic information (VGI). VGI is the type of data that is produced by willing or unwitting users of modern communication technologies like GPS-enabled phones and social media platforms like Foursquare and Flickr.[^osm]  Many researchers have already noted that VGI is biased in terms of who has access to the technology and who is likely to use geographically-enabled services [@Elwood2012]. Potentially even more problematic for my project is that not only are biases about "who" does VGI, but the "where" may be biased as well. It is probable that more disadvantaged places will be less represented in VGI in general [@Haklay2010], and less represented in Flickr in particular. These are known limitations of my proposed method for defining neighborhoods, and they are addressed further, especially in chapter 2. For now, I will leave the reader with this question: are you sure that census tracts are not also biased in terms of who makes them and where they are more or less accurate?

[^osm]:
    The OpenStreetMap project ([www.openstreetmap.org]()) asks volunteers to contribute geographic information so it can make an free, open-source alternative to the geographic databases owned by Google or Microsoft. For my research, though, I concentrate on the VGI that is collected almost as an afterthought through Flickr, not the type of explicit VGI collection going on with OpenStreetMap.

## Theoretical contributions

To clearly state the contributions and conceptualizations that my dissertation makes to the field of spatial demography, but first I need to take a detour through a bit of the philosophy of science. I apologize ahead of time if this seems pretentious, but I promise there are concrete statements at the end of the section. First, I will explain 3 perspectives on the philosophy of (social) science, and why they are a poor fit for my empirical work. Then I will explain the perspective I most often use in my own thinking about neighborhood effects, social media, and spatial demography.

The first perspective is "critical realism" based on work from Sayer [-@Sayer1984] and summarized in the field of sociology by @Gorski2013. Arguably, critical realism forms the backbone of most sociological research and publication today and is a central part in graduate pedagogy. This perspective uses a common rhetorical technique summarized well in this boilerplate example of how to write a journal abstract:

> The question of xxx has been widely debated in xxx field, with scholars such as xxx and xx arguing xxx. However, these works/articles/arguments/perspectives have not adequately addressed the issue of xxxx. My paper addresses the issue of xx with special attention to xxx. I argue that ... [one main point]. In conclusion, this project, by closely examining xxxxx, sheds new light on the neglected/little recognized/rarely acknowledged issue of xxxxx. [@Kelsky2011]

There are two reasons critical realism does not work for neighborhood effects research. First, we do not have a well-defined dialectic between two or three scholars within this field. @Sampson2012 is one clear voice, but even though there are some critics,[^critics] there is not an alternative approach that directly and consistently puts forth an alternative to Sampson's work. Additionally, my empirical work does not fill a single lacuna within the field. Instead, my empirical work addresses a small part of multiple strains of research in neighborhood effects, but it does not try to settle any of the particular substantive debates (schools, health, crime, etc.). The purpose of my research is instead to ask questions about the definition of neighborhoods themselves. Due to these two reasons, I chose to look beyond critical realism for a philosophy of science for my work. 

[^critics]:
    @Oakes2004a argues against Sampson's approach from the methodological side by claiming that neighborhood effect modeling is hopelessly afflicted by endogeneity and omitted variable biases. Harvey [-@Harvey1973, chp 4] argues against Sampson (and all human ecology research based on the Chicago School) from a Marxist point of view. While both are useful critiques, neither present a competing framework. Instead, they both prescribe the wholesale abandonment of research like Sampson's.

The second perspectivie is due to Howard Becker [-@Becker1963; -@Becker1998]. Becker represents what Gorski would call the "soft constructivist" epistemology within the social science. According to Becker, there are real things, real events, and real cause and effect; however, humans are constantly labeling and making meaning out of their daily lives. The labels and meanings are at least as important as the real stuff -- according to constructivists like Becker, anyway. So the Howie perspective suggests that we make theory when we explain what we found, but without using any identifying characteristics of the case. Becker [-@Becker1998, 126-7] gives us an example of how he turned the findings of his dissertation ...

> These teachers make their careers by moving from school to school within Chicago... rather than trying to rise higher... their moves between positions in the school system can be understood as trying to find a school in which the people they interacted with -- students, parents principals, other teachers -- would act more or less the way the teachers expected them to.

...into this theoretical contribution...

> ...my study showed how people in bureaucratic systems choose between potential positions by assessing the way all the other participants will treat them and choosing places where the balance will be best, given whatever they are trying to maximize.

Labeling theory and soft constructivism work for many fields of sociology, but I don't think it works as well for neighborhoods. My concrete finding might be...

> Neighborhoods have effects on crime patterns and residential segregation, but if we do not define the neighborhoods in ways that correspond to the locally understood boundaries, then we are probably coming up with an incorrect estimate of the effect of the neighborhood.

... and that could be turned into the theoretical claim ...

> Social groups have effects on behavior and patterns of material culture, but if we do not accurately operationalize the groups (families, religions, clubs, gangs, schools, etc.) then we will not be able to distinguish group effects from other individual or cultural effects.

... which seems like a justifiable theoretical claim, but I think it's just a restatement of sociology's founding tenant: no person is an island. Soft constructivism fails in this situation because neighborhoods are not a subtype of social groups in the same way that schools are a subtype of "bureaucratic systems." Neighborhoods are not just another type of institution; they're different from other social groups because of a) their geographic existence, b) their importance for multi-generational processes, and, c) their centrality in the power dynamic of governments, real estate developers, and local residents. Neighborhoods are also different from institutions like schools, state governments, and employers, because they  do not have any mechanisms with which to directly control people. As an institution, neighborhoods are both weaker and stronger[^stronger] than other social groups.

[^stronger]:
    I think neighborhoods are stronger than religious or school institutions for example because they structure the physical environment of people and have intergenerational effects. On the other hand, I think neighborhoods are weaker than most other institutions because they (usually) don't have their own policing force, their own taxing powers, or mechanisms for expelling members. Although, we know that many neighborhoods exerted these powers through unofficial means to create racial segregation.

The last perspective, which I rejected, is reflexive Marxism (my term, which the writers may not ascribe to themselves). This perspective includes 
C. Wright Mills [@Mills1959] and Pierre Bourdieu [@Bourdieu1992, 218-24]. These authors again use "soft constructivism" to argue that humans give meaning to their worlds; but they maintain a strain of Marxism that focuses on differential power and the constraints of materialism and money. For example, Bourdieu's [@Bourdieu1984, chp 7] explanation of food preferences among the French working classes in the 1970s shows how people exhibit agency through the "choice of the necessary." Reflexive Marxism is different from critical realism and labeling theory because it says that the source of good theory comes from breaking down the barrier between the realms of social analysis and everyday life. Bourdieu has fancy sounding words like "habitus" and "praxis" to explain this part, but Mills's [-@Mills1959, 196] folksy advice resonates more with me:

> What this means is that you must learn to use your life experience in your intellectual work: continually to examine and interpret it. In this sense craftsmanship is the center of yourself and you are personally involved in every intellectual product upon which you work.

On most levels, reflexive Marxism works for neighborhood effects research. However, there it increases the risk of overemphasizing a particular point of view in our research. Sampson [-@Sampson2012, 406] , the entire Chicago school, David Harvey, and even going back to Frederick Engels [@Engels1844, 46-7], all like to include a few pages that describe how they stroll through the city observing neighborhood things like the physical appearance of buildings, the behavior of people on the sidewalks, and the sound of cars or trains. This type of "strolling" behavior is usually taken-for-granted and the privilege of the stroller is left unexamined. It is probable that white, affluent researchers experience and write about a city from their own praxis. Feminist scholars have argued that strolling through a city is a privileged point of view [@Massey1994, especially 234; @Kwan2002], therefore, we should be more suspicious of sociological work that actively deploys the vantage of the flâneur as part of its theoretical grounding. 

Finally, we come to the perspective I like (unfortunately it does not have a widely accepted name). Kuhn's [-@Kuhn1962] approach to paradigms of social science research has served as the most useful tool for understanding the theoretical contributions of my dissertation project. Most importantly, @Kuhn1962 [44] says that paradigms do not have strict rules or fundamental laws, but are instead made up of a set of shared research questions and methodological practices. This is exactly the situation we find in the current neighborhood effects literature. For Kuhn, there are two types of research: normal science and anomalies. Normal science is the attempt to solve the puzzles defined by the paradigm with the tools known within the paradigm. For example, @Wodtke2011 time-series data and novel weighting method deal with the known endogeneity problems. When anomalous results arise during the course of doing normal science, a paradigm is not abandoned -- instead, additional "normal science" is conducted to try to resolve the anomaly, and it is only after many rounds of anomalies and resolutions that a new paradigm might arise. One of the problems in the neighborhood effects paradigm is that we don't know how to define neighborhoods, and this problem has been so resistant to normal science that it is almost ignored at this point. This sounds similar to Kuhn's description:

> The early attacks upon the resistant problem will have followed the paradigm rules quite closely. But with continuing resistance, more and more of the attacks upon it will have involved some minor or not so minor articulation of the paradigm, no two of them quite alike, each partially successful, but none sufficiently so to be accepted as paradigm by the group. Through this proliferation of divergent articulations ... the rules of normal science become increasingly blurred. (83)

Using geotagged photographs to define neighborhoods is a (not so minor) articulation of the current neighborhood effects paradigm. My research is part of the "debate over fundamentals" that Kuhn notes as a sure sign of a paradigm in crisis [-@Kuhn1962, 91]. The theoretical contribution of my work lies in the fact that it uses a different approach to defining neighborhoods. It shows that different conclusions arise from Flickr-defined neighborhoods compared to the paradigm's accepted method of using administrative boundaries, e.g. census tracts. Note that I am not claiming to offer a new paradigm, because, as many people have noted [@Kuhn1962, 148; see the summary of the Duhem-Quine Thesis in @Gillies1993, chp 5], scientific progress does not happen by testing two competing paradigms against one another (as critical realism might suggest). Instead, anomalies and *ad hoc* explanations accumulate in until the paradigm's practitioners are too embarrassed to support it any longer, and then they (perhaps begrudgingly) switch their research questions and methodological tools.

I will now briefly summarize this detour through the philosophy of science. I don't want to use critical realism because the neighborhood effects literature does not fit into its boilerplate framework. I don't want to use Becker's style of soft constructivism because I think there is something unique about neighborhoods that can not be abstracted away as "social groups." I do not want to use reflexive Marxism because I don't want to contribute more flâunerism to the field of urban sociology. Therefore, my theoretical contributions come in through the use of the historical philosophy of science as developed by Thomas Kuhn. In Kuhn's terms, I will contribute another "divergent articulation" to the field of neighborhood effects research by spurring on a debate on its fundamental concept, the neighborhood.

## Summary of empirical chapters

The empirical chapters are meant to demonstrate three crucial elements that all new methods must provide. First, I will show that Flickr data -- even though it does not look anything like other sociological data -- can be coaxed into a form that makes it usable for common questions asked by researchers. Second, I show that neighborhoods based on Flickr have face validity and that they are robust to the types of bias that I can measure. Third, and most importantly, I show that census-tract-based neighborhoods and Flickr-based neighborhoods will produce different conclusions.

In chapter 2, I use a case study of photographs from Phoenix, AZ and analyze a sample of images in order to measure potential bias. I look for the bias that might arise if a user or place was a particular outlier that had "too much" influence on the boundaries of the neighborhoods. I look for this type of bias because we would like the new neighborhood definitions to represent shared understandings of the place, and this would not be the case if my new method is prone to drawing boundaries around the photographs of an anomoulous user or around photographs that are markedly different from all the other images in the neighborhood. To do this, I invented three scoring criteria for images to rate the content of the image, rate whether the image was taken by a local or a tourist, and quantify the amount of engagement that Flickr users have with an image. Then I take each of these three scores and use a method of spatial outlier detection (which I also invented), so see if any of the boundaries are significantly altered by outliers. In order to gage what would be a legitimate cutoff for "significantly altered" I pull in external information from the Phoenix planning department's definition of urban village areas. By using this external information, I can say if the amount of bias is more or less than the difference between Flickr and the official boundaries. Since the measured bias is relatively lower and the Flickr neighborhoods are in the correct parts of the city, I conclude that Flickr neighborhoods are likely to be robust to outlier photographs.

In chapter 3, I concentrate on the MAUP by comparing Flickr boundaries in Chicago with 3 alternatives: census tracts, a raster, and neighborhoods defined by the Project for Human Development in Chicago Neighborhoods (PHDCN) [@Sampson2012, chp 4]. To compare the alternative neighborhood definitions in a real-world example, I use data on homicide locations. Through univariate analysis and spatial models, I argue that the Flickr neighborhoods are preferred over census tracts and rasters, and at least as good as the PHDCN definitions. Since the PHDCN project invested a substantial amount of time and money into constructing their neighborhoods, it is quite significant that I, as a non-expert on Chicago, can use Flickr to make definitions just as good as the PHDCN. Even setting aside benefits in models and operationalizations, the cost savings in my new method is an important contribution in itself. Additionally, I show that the Flickr neighborhoods will produce a dramatically higher variance in the counts of homicides than the PHDCN neighborhoods. This is a surprising finding because Flickr has fewer neighborhoods than PHDCN, and therefore, we would expect it to have lower variance. The results of the models gives us good evidence for a way to solve the MAUP. The surprising finding about the variance points out the need for future research on the connection between neighborhood definitions, measurements of variance, and known sociological research on residential segregation.

In chapter 4, I propose a new theory called "segmented neighborhood attainment," which is a combination of neighborhood attainment theory [@South2011b] and segmented assimilation theory [@Alba1997]. The basic idea of neighborhood attainment theory is that households with more resources (wealth, education, social captial) will attain housing in more advantaged neighborhoods. I think this theory has a problem because some people may aspire to neighborhoods which correspond to the "white picket fence in the suburbs" stereotype and others might aspire to "warehouses turned into loft apartments." Thus, there are different segments of the population on different attainment trajectories. By combining Flickr neighborhoods and census data, I show a) there are different segments of the neighborhood attainment system, b) these segments are not evenly distributed among people in different race and ethnicity categories, and c) attributes like education and home ownership which used to appear to be directly related to more attainment actually have different effects in different segments.

In the concluding chapter I don't spend very time recapitulating my findings. Instead, I take license to look ahead at two topics. First, I try to integrate my work with some of the other think pieces that have been written about neighborhoods and spatial social science. By integrating my findings, I hope to point out future research that can and should be done within neighborhood effects research. Perhaps Flickr is not the absolute and final answer for defining neighborhoods, but researchers can no longer keep a straight face when they say that they have to use census tracts because there are no other viable options. Second, I take a step back and look at research using data from social media. I draw parallels to the state of sociology just after World War II as our field leaped ahead with the use of survey methods and left behind the founding work of Marx, Weber, Durkheim, Park, and DuBois (which was almost entirely void of surveys). I think we now sit at another inflection point -- to embrace ICT and social media data or not? -- and sociology would need to once again jump into new modes of funding, pedagogy, and publication if we want to say meaningful things about the new data sources.  

# Testing Flickr Neighborhoods for Bias

## Introduction

The neighborhood has been implicated in a variety of research as affecting education, crime, obesity, and poverty among other things [@Sampson2002]. The neighborhood in these studies is almost always defined as a census tract.[^7] Sometimes researchers justify their use of census tracts based on arguments about the geographic extent of socio-economic behavior. Some authors say there is no choice but to use the census tract, but there is a growing critique of the de facto use of census tracts to define neighborhoods [see @Matthews2011, 39-41]. 

[^7]: Different authors may conceptualize neighborhoods differently. For example, @Galster2001 thinks of them as a "bundle of spatially based attributes," many authors think of them as spatially-embedded social networks [@Liu2010, 1388], Burton has proposed overlapping layers of family, neighborhoods, and culture around each individual [@Burton1997; @Burton2000a], @Suttles1972 elaborated an oft neglected notion of "contested community," @Harvey1973 and @Castells1983 built Marxist interpretations of neighborhoods, and of course there is the tradition of the Chicago School of sociology that gave us "natural areas" [@Park1925]. The conceptualization of neighborhoods might seem diverse. However, many of these different writers are quoted in papers that all end up operationalizing the neighborhood as a census tract. 

Krieger's [-@Krieger2006] succinct summary of the history of the census tract notes how they were originally developed with administrative goals in mind. In 1906, Walter Laidlaw of the Population Research Bureau of the New York Federation of Churches convinced the Census Bureau that congregations needed a more stable way of tracking and predicting population in the New York area. Voting wards changed too often and were at the whims of local party machines. The 1910 census included census tracts for New York and seven other cities. The number of cities covered was expanded in each year, but it wasn't until 2000 that the entire nation -- urban and rural -- was delineated into tracts.

The Census Bureau has created a loose network of volunteer committees, state agencies, and tribal governments to create and maintain boundaries for tracts and other small area statistical units. Creating homogeneous tracts with boundaries following identifiable features is a difficult task for a national agency, and since its beginnings in 1910, the backbone of tract definitions has been local committees -- originally called local census tract committees and now known as Census Statistical Areas Committees (CSACs, @CensusBureau1994). The Census Bureau encourages these local committees to make membership open to anyone, but in reality they are almost always composed of people with specialized knowledge of geographic and demographic data: planning departments, health agencies, school administrators, transportation authorities, chambers of commerce, real estate developers, marketing agencies, religious organizations, and less frequently, neighborhood associations and political parties [@CensusBureau1994]. To my knowledge the only research done on the composition and conduct of the local committees is contained in a methodological appendix by @White1987. He noted that often the work of the committee is done by a single person or a very small group within a single agency. In larger, older cities there doesn't tend to be much controversy, but in faster growing areas he found that there can be a tendency for committees to want to define tracts along boundaries relevant to the local governance bodies (e.g. school boards and fire districts). This leads to small tracts subject to frequent expansion and creates tension with the Census Bureau's desire for all tracts have at least 2,500 residents and remain stable between decennial censuses [@White1987, 296-8]. The important thing to understand is that census tracts are not "real" things; census tracts are defined by a small, non-representative group of people.

The census tract is not the only small area statistical definition maintained by the Census Bureau. For example, the census currently aggregates blocks into units known as Urbanized Areas and Urban Clusters. Along with ZIP Code Tabulation Areas, these alternative small area statistical units are not necessarily coterminous with tracts. In the 1980 census, the Bureau also tabulated statistics for neighborhood areas. These neighborhood areas were defined by local municipalities to correspond with the boundaries relevant for local community development and governance. Since 1980, the neighborhood definitions have been gradually phased out and replaced with census tracts [@White1987, 291]. Other government bodies may generate neighborhood definitions too. The most common example is school boards, but other examples are the U.S. Housing and Urban Development's Empowerment Zones[^empzone] and tax increment financing (TIF) districts run by state and local governments.[^tif] Additionally, many cities maintain definitions of neighborhoods that are used in various functions like economic boosterism, transit planning, and building codes.[^cityhoods] 

[^empzone]:
    ([http://portal.hud.gov/hudportal/HUD?src=/hudprograms/empowerment_zones]())

[^tif]:
    For example, see Chicago's website about TIF districts at [http://www.cityofchicago.org/city/en/depts/dcd/provdrs/tif.html](). Interestingly, Arizona is the only state in the U.S. which does not have state-level legislation to enable TIF financing. Recent coverage suggests that Phoenix in particular wants to enable TIFs ([http://www.bizjournals.com/phoenix/news/2015/02/04/the-tif-over-the-missing-public-dollars-for.html]()).

[^cityhoods]:
    In Phoenix, the Village Planning committees do not directly control building codes, however, village planners have special privileges on the city's design committee and village planning committees have direct input to the city's General Plan [https://www.phoenix.gov/pdd/pz/general-plan-update]().

Given the limitations of census and administrative geographies, social scientists need to find an alternative method to define neighborhoods. Immediately, then, we are faced with the question as to what a "better" definition of a neighborhood might entail. There are many examples of social science research which propose new and better ways to measure our concepts. For example, @Thomson1935 proposed a new way of measuring intelligence; @Swidler1986 changed the concept of culture; and Becker's [-@Becker1962] human capital was a departure from the contemporaneous neoclassical and Marxian concepts of capital. Each of these examples share a rhetorical approach: first they attempt to show that the new measure is different from the existing methods, and second, they argue that the new measure is robust within the context of the respective fields of psychology, sociology, and economics. (Hopefully, the new measure is different *and* better than the existing one, but from a rhetorical point of view, simply showing a significant difference is sufficient for motivating the need for a new measure. Proving it is better can be left to follow-up studies.) 

I want to take up the task of finding a new way to measure neighborhoods. My method is to aggregate geotagged photographs from Flickr into neighborhood definitions. I will show that my definitions are different from the existing neighborhood boundaries maintained by the City of Phoenix. In the data and methods section, I further describe my motivation for using Phoenix's official village planning areas instead of census tracts. I will show that the Flickr neighborhoods are robust to three specific sources of bias. At the outset, I will note that I take as given the user-base of Flickr is not representative of the nation. However, neither were the groups responsible for creating census tracts or Phoenix's village planners. Both Flickr and administrative definitions are biased because they privilege the viewpoints of certain people (most likely rich, white, college-educated, male people). That form of bias will be set aside because it effects both the existing and new definition of neighborhoods. In this paper I will argue that Flickr neighborhood definitions are robust to undue influence from a subset of photographs or users. Specifically, I will be looking for photographs that show a low amount of place-referential content, photographs that generate little interest from the Flickr online community, and users that are likely tourists in the area. These types of photographs/users may skew the Flickr neighborhoods away from the inter-subjective understanding of neighborhoods shared by local Phoenix residents. Thus, to claim that Flickr neighborhoods are robust I will show that the neighborhood boundaries remain relatively stable even when the subset of outlier photographs are removed from the sample.

The current paper uses a form of volunteered geographic information (VGI), found within Flickr, which is a social media platform [@Goodchild2007a; @Elwood2012]. At this point I offer a brief nod to the growing field of study dedicated to social media and VGI. @Ruths2014 argues that social media provides vast new opportunities to studying human behavior. For my purposes, it is even more useful for extracting neighborhood data because the information attached to videos, photos, blogs, and posts is not restricted to the traditional hierarchy of state-county-city-ZIP-street that defines much of the geographic data found in the US. Thus, social media users are more free to use neighborhoods, points of interest, regions, colloquialisms, and other geographic entities to annotate and share their content. Social media has another advantage over the standard social science methods: it already comes in machine-readable formats. Well-known research methods such as mental maps [@Lynch1960], interviews [@Coulton2010], space-time paths [@Kwan2002 654], and community studies [@Lynd1956; @Drake1945] would require extensive abstracting and digitizing to turn the information into the type of geographical data that can be used to define neighborhood boundaries. These projects would be practically impossible to implement on a nation-wide scale, but social media is by default global.

VGI sits at the crossroads of two technological trends of the last decade: Web 2.0 and neocartography. Web 2.0 is a term that applies to various social media platforms and practices where users can upload their content, which is then consumed by other people. Neocartography describes the practice of creating maps with Web 2.0 technologies and is often mentioned as an example democratization of a technology (making maps) that existed for centuries as the exclusive domain of government and corporate powers [@Crampton2009]. VGI, Web 2.0, and neocartography have their problems though (@Wilson2013 write a useful introduction for the special issue of _Environment and Planning A_ on the topic of "neogeography"). Obviously, there are issues with differential access to computers, the internet, and time to learn the technology; however, critical geographers are beginning to argue that the "digital divide" is only one of many problems with these trends [@Elwood2012]. Even within the population that has access to Web 2.0 technology, sharing geographic information is rare -- therefore neocartography is often based on the outliers of the world [@Haklay2013]. In no way would I argue that Flickr neighborhoods, as a specific case of VGI, are a perfect solution for spatial social science. However, there is general agreement that census geographies are poor measurements of neighborhoods; if Flickr definitions are different from existing measures, they are worth exploring even with known drawbacks.

The rest of the paper is organized as follows. First, I delve into the scant  literature on Flickr in social science research. Second, the data and methods section covers my particular case example of Phoenix and outlines new analytical techniques for detecting spatial bias. Third is the results section. For the impatient: Table 1 and Figure 1 show that Flickr is different from administrative boundaries; Tables and Figures 3 through 5 show that Flickr definitions are robust to the specific forms of bias I outline below. Finally, in the discussion I elaborate on the few neighborhoods that fail my tests for bias, and describe how my new definitions should be used in future research.

## Flickr

Flickr began in 2004 in Toronto, and was purchased by Yahoo! in 2005. It quickly grew into the largest photo sharing web service. All along, the user base of Flickr tended to be somewhat older and more educated than internet users in general. It seems likely that Flickr users are more likely to be hobbyist photographers as well, and as @Li2013 hypothesize, the entry cost for digital cameras and paraphernalia causes a selection effect for Flickr users. Today, most of the world's digital photo sharing occurs in other platforms like Instagram, Facebook, or Wiebo; however, the Flickr database passed 100 million geotagged photographs back in 2009, which is more than enough to extract accurate geographic footprints [@Hollenstein2010; @Catt2009].

Flickr photographs contain geographic meta-data in a number of forms. First, users can simply write in placenames in the photo's titles or description. Much like writing a note on the back of a physical photograph, the site visitors will see the title and description when they view the photograph. Second, a photo could be tagged with a placename. Tags can be anything, and a photo can have as many tags as the user wants. Titles, descriptions, and tags are text entered by users -- they do not necessarily contain geographic information and what geographic data they do contain may be ambiguous (see @Ireson2010 for creative disambiguation methods). Photos with the word "Lincoln" in the title include, among other things, the city in Nebraska, the President, the car, and countless high schools. This type of meta-data is necessary, but not sufficient for my purposes in constructing neighborhoods.

A second way that photos can contain geographic information is by addition to galleries or sets. Galleries are curated by Flickr users and they can add other users' photos to their own galleries. Sets are groups of photos that all belong to one user. These grouping devices are often focused on a place like Brooklyn, but might also be thematic like "black and white portraits." Galleries was the main vehicle for sharing photos in the early years of Flickr, and there are some very dedicated curators and contributors. In future research it might be fruitful to explore how the organization of photos into galleries as opposed to sharing photos through connections on social network sites like Facebook and Twitter might influence the geographic data available in different platforms. For example, many Flickr galleries spawned meet-up groups in cities across the world.

Finally, photographs can be tagged with placenames from a finite set of geographic places, and they can be given latitude and longitude coordinates. This is what is properly termed a geotagged photo. In most of what follows, I am analyzing geotagged photos because they can be turned into neighborhoods the easiest. In 2009, Flickr claimed that they had over 100 million geotagged photos. While coverage is uneven, with whiter, wealthier, more urban areas having more, there are geotagged photos from every corner of the earth (see @Haklay2010, 698 for an analysis of coverage in OpenStreetMap by income). To construct a boundary for a particular neighborhood a researcher would only need to query the Flickr database for all geotagged photos from, for example, Haight-Ashbury, San Francisco, California, and draw a polygon around the points. It would look something like [http://www.flickr.com/places/info/2416070](http://www.flickr.com/places/info/2416070).[^1]

[^1]: As it turns out, the "draw a polygon around the points" part is non-trivial, but for the remainder of this paper I will be using a convex hull of the points to define the neighborhood. See Appendix A for alternative methods of drawing polygons around points and notes comparing each method's relative strengths and weaknesses when used in neighborhood effects research.

Even though it has been around for about a decade, there is very little social science research that makes use of Flickr's -- or with any photo-sharing platform's -- geotagged data. One exception is @Wall2011, whom analyzed (mostly Westerners') photographs in Thailand: "Muslims live throughout Thailand; nevertheless, Muslims tended to be geotagged as mainly occupying rural areas or villages." More similar to the research question at hand, @Hollenstein2010 researched the use of generic geotags like "downtown" and "city center" in six cities worldwide. They concluded that users can accurately locate and define points of interests along with multiple levels of their surrounding environment. While the city was the most commonly used toponym, Flicker data could be reliably used to make footprints for neighborhoods. 

Neighborhoods defined by geotagged photos from Flickr meet all of the requirements I outlined in chapter 1. The data and methods for constructing them are available for every place on earth and it requires no local knowledge of the place. Their presence in the Flickr database shows they represent socially meaningful geographic units because there would not be any photos geotagged with placenames that people do not find meaningful. And third, my method of bounding the points creates neighborhoods with insides and outsides.[^2] As I suggested above, I also find it desirable to have neighborhood definitions based on how people "use" the neighborhoods in normal life rather than in a setting such as drawing their mental map. Flickr is a part of normal life because the users are adding geographic information to their photos to organize, enrich, and share their images of the world.

[^2]: Note that it would be possible to take the collection of individual geotagged photos and use distance decay formulas to construct a sort of neighborhood "surface", and future research might fruitfully compare the results of convex hulls with distance decay definitions of neighborhoods.

## Potential criticism of geotagged Flickr photos

Along with common criticisms of social media data -- such as representativeness, platform constraints, and large samples [@Li2013; @Ruths2014] -- there are three potential criticisms that pertain specifically to geotagged photographs.

It could be argued that the photos themselves aren't necessarily about the places that are indicated in the geotag. Indeed, they might not be about places at all. People certainly use Flickr to share silly photographs of cats or to capture specific events like rock concerts. As @Rose2003 found in studying the rituals around sharing and describing family snaps, which, "are also taken, displayed and circulated in awareness of the pervasiveness of absence and distance. Hence the spatial stretching of domestic space beyond the home. Photos bring near those far away (p. 12)." Thus Flickr photographs might be more about the people, cats, or concerts referenced in the image, and not have anything to do with a neighborhood.

When leveling this criticism at the Flickr-defined neighborhoods, the critic is suggesting that content like families, cats, and rock concerts are somehow less valid representations of neighborhoods than images of buildings, streets, or local points of interest. Remember, though, that I am arguing that neighborhood definitions are best found in the way people use the placename, so if people use a neighborhood to tag and categorize pictures of mundane events that have little direct reference to geographic locations, then I think sociologists should attempt to include this lay usage in their analyses. But to placate the critic, it is easy enough to look at a subset of photos and code them for elements that show aspects of a place. I coded photos with a series of six dichotomous indicators for buildings, people, camera flash, indoors versus outdoors, proper names, and a wide angle zoom.[^rose]

[^rose]: My approach was to use a type of image content analysis [@Rose2007, 59-73]. Originally, I had hoped to use the content analysis as a training set for computer vision image analysis, however, that proved to be an unfruitful line of inquiry. The choice of coding individual features within the image creates data that is easier to use for a computer, but admittedly, leaves a lot to be desired in terms of making holistic claims as to what the image is "about." For example, @Hollenstein2010 looked at pictures tagged with certain public parks in London, and relied on their own expert knowledge to determine if the image was accurate. Future research might find more traction by gathering opinions from many different coders and use a measure of inter-rater reliability as a proxy for determining if the photograph is about a place.

A second common critique is that tourists might just be infiltrating and skewing the definition of the neighborhoods. Neighborhoods are often imagined to be representations of the local knowledge about places within an urban environment. Thus, critics want to be able to weed out the images from tourists and other outsiders [@Li2013, 63]. I think it is arguable the extent to which neighborhoods should be defined by the insiders' points of view because I have defined neighborhoods based on their use. Outsiders could use neighborhoods in many ways similar to locals, and even more so, the fidelity between outsiders' definitions of a neighborhood and its role in the urban structure may be quite high, for example, Bourbon Street, Hollywood Boulevard, or one of the many Little Italys, Chinatowns, or Gayborhoods [@Orne2013] may be mostly defined by interactions with the non-residents that visit the neighborhood. Thus it is not a clear cut case that we would improve the definition of a neighborhood by filtering out the outsiders' photos. However, I do think there is a compelling argument to be made for comparing the potential geographical differences between locals and tourists [@Fischer2010].[^4]

[^4]: The data in my current project doesn't allow me to fully test the idea, but I find Lynch's [-@Lynch1960] idea of "imagability" to be especially well suited for explaining why the insider-outsider distinction may not carry much weight. Highly recognizable tourist landmarks might skew the definition of the neighborhood within the Flickr database, but just as likely, the iconic places, buildings, and streets change the mental maps of the locals. In the end, the locals *use* the neighborhoods in ways that are consistent with the image of the place as seen by outsiders.

The Flickr database is not ideal for determining the hometown of users. Individuals may choose to supply their home cities, but many leave out this information and some may not accurately reflect where users live. Furthermore, the user-supplied location information can change at any time and is not tied to the date of the photograph. And as a final complication, the level of geography usually doesn't match as users mostly list their hometowns but rarely supply neighborhoods of residence. I imputed the "home" of each user in my sample by gathering each user's 100 most interesting geotagged photos (more on the concept of "interesting photos" below) and computed the geographic centroid of the photos. Users with home centroids located further from Phoenix indicate one of two possibilities: a) the user travels a lot and uploads most of their photos from traveling, or b) the user has lived or currently lives in another location. This is not a perfect operationalization of tourists, but it should allow us to notice any patterns where tourists and locals are defining two competing definitions of a neighborhood.

Finally, some critics accurately point out that small sample problems  can creep up when looking at obscure or rarely used neighborhoods [@Hollenstein2010, 43; @Delta2003 for a different context]. It might be easy for a single user or a small group of users to bias the neighborhood definition-- there's very little to be gained by hijacking a neighborhood definition, so I'm not arguing that there are Flickr users with nefarious motives, but the biasing could still happen with small samples.[^6] There are two simple checks against this issue: 1) determining the number of unique users contributing to each neighborhood definition, and 2) test if any neighborhoods are defined by uninteresting photos near the edges of the neighborhood.

[^6]: Admittedly, some users will  actively seek out ways of creatively subverting the limitations of a given social media platform. For example, tagging things like houseboats or logging a Foursquare check-in at a private residence. But this isn't too surprising if we consider location data within social media to be a method for performing identity construction [@Schwartz2014].

Early in the history of the company, Flickr patented an algorithm for rating every photograph's "interestingness" [@Butterfield2012]. The algorithm takes into account the number of times an image is viewed and the amount of engagement that users have with it through comments, tags, and adding it to groups. The exact formula behind the interestingness score is a secret, so I recreated a similar measurement based on the same components. Interestingness is a proxy for the amount of interaction with the photograph, so if critics are to believe the claims of small sample problems, they would have to demonstrate that the neighborhood is based on photos from just a few users, and that these photos are not interesting to other Flickr users. Remember, I am arguing that neighborhoods are made -- and should thus be defined -- by the way they are used in an everyday setting like communicating from one person to another the location. Taking an image and geotagging it is one way to use the neighborhood, but another equally valid use would be to search out, view, favorite, and group images from other users. Thus, the small sample criticism can only hold up when there are very few users contributing images and very little interest in the images.

## Data and Methods

### Sampling

I picked Phoenix because I've never been there, therefore I can not use my expert knowledge to influence the results. It is also a rapidly growing city in a rapidly growing region of the country. Phoenix is not a "classic" in the neighborhood literature (like Chicago, New York, Boston and Los Angeles), so if we can find evidence that this method for defining neighborhoods is valid in even this car-based, suburban, Sun-Belt city, we might have reason to believe the method will be valid in places that have been regularly identified as having more salient neighborhood identities.

Phoenix has 14 village planning areas that are officially recognized by the city. I used these 14 areas as the standard way to measure neighborhoods. They represent an improvement over census tracts for operationalizing neighborhoods because they were constructed to help local village planning boards enact laws pertaining to the built environment. (They are also assigned recognizable names, which is important for comparing them with Flickr.) On visual inspection, the official village planning areas are about the same size as Flickr neighborhoods, which is important given that I use the percent of overlap as in my analytical approach. If I were to do the comparison between Flickr neighborhoods and census tracts, I would most certainly find evidence to support my argument. However, it would be weak data because the Flickr neighborhoods are much larger than census tracts, so I would essentially be fixing the game in my favor. I use the village planners instead because they represent a tougher case -- if I can show that Flickr neighborhoods are different from village planners, then I will have stronger evidence that my new method is different *in important ways* from the standard measures of neighborhoods.

The Flickr database has 254 neighborhoods within Phoenix, and from this list I selected the 14 neighborhoods that matched to the official village planners. I originally drew a random sample of 2371 geotagged photographs from within Phoenix to use in developing my coding scheme for the image content analysis. To ensure that each of the 14 village planning areas was covered in my sample, I drew a secondary sample stratified by neighborhood and randomly sampled at least 50 images from each. As a comparison group, I also drew a random sample of 214 photos that were not geotagged in any way. The images lacking geotags were used to ensure the validity of my coding scheme across different types of photos.

In the analyses of neighborhood boundary biases, I limit the sample to just 846 images that belong to the village planner neighborhoods. This is for two reasons. First, as I argue against the criticisms outlined above, I will often need to resort to a baseline in order to answer the question, "Does this source of bias *significantly* change the boundaries?" One way to measure the level of significance is to compare the difference between the neighborhoods as defined by Flickr and those defined by Phoenix; and then see how much of that difference can be attributed to the bias introduced by one of the criticisms. Second, as a practical matter, it was time prohibitive to code photographs from all 254 neighborhoods.

The latitude and longitude coordinates for all of the photographs within a neighborhood are used as the basis for calculating a convex hull. Convex hulls are the smallest convex polygons that can be drawn around a set of points. These shapes then are used as the definition of the neighborhood for testing the potential measures of bias.

### Creating variables to measure bias

I calculated a variable to operationalize each of the three sources of potential bias. Each variable was calculated for each photograph in the analytical sample (except in the case of tourist-influence where some values could not be calculated).

First, I scored all photographs on a scale of how much the image referenced a place. In German, "platz" is a word that can be loosely translated as place or space, and "bilder" means images, so I will use the term "platzbilder" to mean "place-referential content in images." The platzbilder score is based on a factor scale method. I develop the factor loadings by using a split sample testing procedure, the details of which can be found in Appendix B. The final factor loadings and the cross-correlations that were used in creating the factor scores are displayed in Table B2. The important thing to remember is that platzbilder is a combination of six separate dichotomous indicators that I coded myself, and shouldn't be thought of as subjective judgment of what the photo is about. Perhaps I should have used the terminology "relative count of place-referential elements within a photo", but platzbilder is shorter and hopefully easier to remember.

Second, the measure of tourist-influence is the distance between the photograph and the centroid of the users 100 most interesting photos. I created the users' "home" centroid by querying Flickr for the 100 most interesting photos for each user in my analytical sample. From this set of additional photos, I dropped any photos that were already in the analytical sample to calculate the users' home centroid. Distance between users' home and their photographs was calculated in kilometers on a sphere based on latitude and longitude coordinates. Other methods for determining locals and tourists exist [for example, @Fischer2010], however, my method creates a continuous variable for each photo, thus avoiding some problems with non-normality arising from categorical variables in the second step used for identifying outliers (described below).

Third, I downloaded data on the number of times the photograph was viewed, added to groups, added to sets, commented on by other users, and favorited by other users.[^9] These attributes were combined according to this formula in order to calculate my version of Flickr's interestingness score:

$I = ln(V) + G + S^2 + f(C) + f(F)$

Where 

$V =$ number of times the photograph is viewed;

$G =$ number of groups that include the photograph;

$S =$ number of sets that include the photograph;

$C =$ number of comments on the photograph;

$F =$ number of times the photograph was favorited; and

$f(x) =$ function to right-censor $x$ at a maximum of 35.

I admit the transformations on each variable look arbitrary. They were chosen to make each variable's contribution to the overall interestingness score more equitable.[^10] 

[^9]: It is possible to imagine a situation where users engage with a photograph to criticize it, point out that the owner has mis-labeled or mis-tagged the image, demand that it be removed from sets or groups, or removed from Flickr entirely. This sort of "negative" interest would also increase my measure of interestingness, but I did not see any instances of it in my analytical sample so I am confident in using interestingness as a unidimensional measure of "positive" interest.

[^10]: Note that all of the attributes that went into calculating the interestingness score are time sensitive. All of the photos in my analytical sample were uploaded between 2005 and 2009; and I gathered the attributes for the calculation of interestingness in late 2012 and early 2013, so the photos had between 3 and 8 years to accrue interest from users. Future research may want to look into the relationship between time and the amount of interest in a photograph, but I would suspect that it follows the power law distribution seen in many ICT studies such that we would expect a vast majority of the interest to be expressed in a relative short time right after the photo is uploaded [@Li2013].

### Analytical Approach

In the results section I will proceed through each of the potential sources of bias in turn. There is no generally accepted test statistic for the amount of bias in a geographic boundary, so I invented by own. 

First, I calculate "spatialized hat values" for each photo. (See Appendix C for a detailed discussion.) The hat value should be familiar to most students of linear regression:

$\hat{y} = \mathsf{H}y$

where

$\mathsf{H} = \mathsf{X} ( \mathsf{X^\intercal} \mathsf{X} )^{-1} \mathsf{X^\intercal}$

In lay terms, the hat matrix "puts a hat on y" by translating the $n \times p$ matrix of observed x-values into a vector of length $n$, which can be multiplied by the observed y-values to create predicted y-values -- i.e., y-hat. The hat matrix is also useful in regression diagnostics because the diagonal elements of the matrix tell us how much each observation is contributing to the predicted y-values. Observations that are outliers among the x variables tend to have high influence on the predicted y-values [@Cook1977]. I want to leverage this feature of the hat matrix to find out if any of my photos are outliers -- more specifically, if any of my photos are simultaneously spatial outliers and outliers in the distribution of platzbilder, tourist-influence, or interestingness. Thus, I use the spatial coordinates of each photograph and the measure of bias to form a $n \times 3$ matrix of observed x-values; calculate the diagonal elements of the hat matrix; and use Monte Carlo methods to figure out which, if any, of the observations are outliers given what would be expected in a random spatial distribution.[^11] The spatialized hat values are calculated on the photos within each neighborhood, so they can be interpreted as an indicator of the photo's simultaneous deviation from the _neighborhood's_ spatial center and the _neighborhood's_ mean value of the variable under consideration (platzbilder, tourism, or interestingness).

[^11]: Again the reader could Appendix C for a full demonstration, but I wanted to point out that my Monte Carlo methods are not exactly the same as seen in most spatial analyses (e.g., as described in @Besag1989). GeoDa, ESRI, and (the R package) spatstat all implement MC methods for rejecting a null hypothesis of "complete spatial randomness," which to me, is too low of a standard (see @Goovaerts2004 for an improved method that compensates for regional background and heterogeneous population sizes). I developed a method to first construct a non-parametric, moving average density based on the observed values for the variable under consideration. Then I drew values from this synthetic distribution for each point in the neighborhood, and a new hat matrix was constructed based on the new randomized data. By creating 1000 MC runs, I was able to examine the diagonal elements of 1000 hat matrices, and from this was able to ascertain good estimates of the 95% confidence interval for cell values along the diagonal. The MC draws can be interpreted as the distribution of hat values from the given spatial points with attribute values drawn from an approximation of the observed distribution.

In most sociological modeling, the proper thing to do with outliers is to exclude them from analysis; or at the very least, to quantify how sensitive the final conclusions are the inclusion or exclusion of the outliers. In this case, we are interested in the size and shape of the convex hulls based on the data points -- we are not interested in the data points themselves. I chose to remove outliers when their value was below the neighborhood mean, but when the outlier was greater than the mean, I added territory to the neighborhood. The additional space was a circle with radius equal to one half the median intra-neighborhood photo-to-photo distance. In other words, outliers that are  more likely to be good at defining neighborhoods -- high platzbilder, locals, and high interest -- added area to a neighborhood equal to the overall median "size" of photos in all neighborhoods.

After adding or removing territory around photos, the resulting convex hulls represent what the neighborhood would look like if we corrected for a source of bias. In other words, the new neighborhood boundaries have removed some sources of bias from the extreme levels of place-referential, touristy, and interesting photos. To quantify the amount of bias I calculate the overlap between the analytical sample and the "corrected" sample. I use this ratio to represent the amount of bias in the neighborhood boundaries.

The conclusions hinge on the amount of bias versus the amount of substantive differences between Flickr and the village planners. Thus, the hypothesis that Flickr neighborhoods are robust measurements of neighborhoods boils down to a test if $(1 - A) < (1 - B)$, where $A$ is the overlap between the analytical sample and the sample adjusted for outliers, and B is the overlap between Flickr neighborhoods and Phoenix village planners. Rewritten as a formula:

$A_{b} = \frac{S_{b}^{*} \cap S_{b}}{S_{b}^{*} \cup S_{b} }$

$B_{b} = \frac{F_{b} \cap V_{b}}{F_{b} \cup V_{b}}$

Where...

$S_{b} =$ convex hull around the analytical sample;

$S_{b}^{*} =$ convex hull around the analytical sample, corrected for outliers;

$F_{b} =$ convex hull around all Flickr photographs;

$V_{b} =$ Phoenix village planners;

...and $b$ is an index for the neighborhood. I calculate separate values of $A_{b}$ for platzbilder, tourism, and interestingness, and organize the results accordingly. First, though, I will describe the results of calculating $(1 - B_{b})$ -- the difference between Flickr and Phoenix village planners.

??? signposting: a) looking for quantification of how much the polygons might change due to anomolous photos/users; b) baseline to tell if the change is "enough" will be the amount of change between Phoenix and flickr; c) to find supporting evidence for Flickr, we need to find small amounts of change due to anomolies.

## Results

\begin{figure}[htbp]
    \centering
    \caption{Map of official Phoenix village planners and Flickr neighborhoods}
    \subbottom[]{
        \includegraphics[width=\linewidth, keepaspectratio=true]{phoenix_village_planners_map_20150315.pdf}
    }
    \subbottom[]{
        \includegraphics[width=4cm, keepaspectratio=true]{phoenix_legend_20150315.png}
    }
\end{figure}

The Flickr neighborhoods overlap to a large degree with Phoenix village planners, but tend to be smaller and pulled back from the borders of the neighborhoods. An exception to the pattern is the overlap between Camelback East and Paradise Valley on the eastern edge of Phoenix. But otherwise, visual inspection of Figure 1 would suggest that we can expect $B_{b}$ to be relatively high. However, Table 1 shows that the rate of overlap varies between .21 and .75, which means that the difference between Flickr and official boundaries ranges between 25% and 79%. When trying to compare two distributions or sub-groups, social scientists often like to use methods based on standard deviations. If we treat the area of the village planners as a sample (n = 14), we see that the mean is 94 km$^2$ with a standard deviation of 38 km$^2$. Then, treating the area of difference as a second sample, we see that the area of difference between Flickr and village planners ranges between .2 and 2.7 standard deviations of the village planners' area. In the education context, a .5 to 1 standard deviation difference is usually considered substantial and important [e.g. @Cheadle2008a, 11], so we have evidence that Flickr neighborhoods are importantly different from the official Phoenix neighborhoods.

\begin{sidewaystable}[pht!]
    \small
    \caption{Overlap between Flickr neighborhoods and Phoenix village planners.}
    \begin{tabularx}{0.9\textheight}{lcd{-1}d{-1}d{-1}}
        \toprule
        & \multicolumn{1}{c}{Photos in Flickr (n)} & \multicolumn{1}{c}{\shortstack{Area of Flickr \\ (sq. km)}} & \multicolumn{1}{c}{\shortstack{Area of village \\ planners(sq. km)}} & \multicolumn{1}{c}{\shortstack{Overlap ratio}} \\
        \cmidrule{2-5}
        Ahwatukee Foothills & 2889 & 98.45 & 91.48 & 0.64 \\ 
        Alhambra & 847 & 30.34 & 49.61 & 0.51 \\ 
        Camelback East & 996 & 58.97 & 93.87 & 0.29 \\ 
        Central City & 5021 & 41.68 & 54.76 & 0.50 \\ 
        Deer Valley & 1598 & 89.73 & 146.00 & 0.53 \\ 
        Desert View & 687 & 150.87 & 175.85 & 0.41 \\ 
        Encanto & 5883 & 26.16 & 26.97 & 0.75 \\ 
        Estrella & 1696 & 102.79 & 107.14 & 0.61 \\ 
        Laveen & 2712 & 80.96 & 79.21 & 0.71 \\ 
        Maryvale & 882 & 41.67 & 83.47 & 0.33 \\ 
        North Gateway & 674 & 141.60 & 115.02 & 0.57 \\ 
        North Mountain & 691 & 18.95 & 89.67 & 0.21 \\ 
        Paradise Valley & 2753 & 165.54 & 110.92 & 0.49 \\ 
        South Mountain & 459 & 48.84 & 103.02 & 0.47 \\
        \bottomrule
    \end{tabularx}
\end{sidewaystable}

I present the descriptive statistics for my analytical sample of geotagged photographs in Table 2. The three variables of interest take on quite different distributions. Platzbilder, by virtue of being a factor score, is a continuous variable that approaches a normal distribution (see Appendix B for details). The distance between each photograph and the owner's imputed "home" location is highly left skewed due to visitors from the population centers of the eastern U.S. and world travelers. Figure 2 displays the histogram for the tourist-influence variable for the entire sample -- notice the bump around 4200 km, which is the distance from Phoenix to the New York-Boston population center. I did some additional exploratory analysis of the distributions of tourist-influence in each of the neighborhoods, and often saw some dramatic departures from the overall distribution depicted in Figure 2; some neighborhoods have more photographs from tourists, but that is the point of the corrections for outliers. Interestingness shows the most well-behaved distribution among all of my variables, and this makes sense because the variable is calculated as a weighted average of simple count variables (views, comments, groups, etc.). Perhaps the most important numbers in Table 1 are the low number of users contributing photographs to Deer Valley (10), Estrella (9), and Laveen (6)  in my analytical sample. The Encanto neighborhood also had a low number of users (11) but as it represents one of the densest urban areas of Phoenix, the user density is much higher. These four neighborhoods account for all of the instances where bias trumps substantive difference, and are described in more detail within the description of each variable. 

\begin{sidewaystable}[pht!]
    \tiny
    \caption{Descriptive statistics for analytical sample of Flickr photographs.}
    \begin{tabularx}{.8\textheight}{lrr*{9}{d{-1}}}
        \toprule
        \parnoteclear
         & & & \multicolumn{3}{c}{Platzbilder} & \multicolumn{3}{c}{Touristyness\parnote{based on a sample of 715 photos because some users did not have enought data to determine home locations.} (km)} & \multicolumn{3}{c}{Interestingness} \\ 
         & Photos & Users & \multicolumn{1}{c}{mean} & \multicolumn{1}{c}{min} & \multicolumn{1}{c}{max} & \multicolumn{1}{c}{mean} & \multicolumn{1}{c}{min} & \multicolumn{1}{c}{max} & \multicolumn{1}{c}{mean} & \multicolumn{1}{c}{min} & \multicolumn{1}{c}{max} \\ 
        \cmidrule{2-12}
        Ahwatukee Fthl. & 118 & 20 & -0.25 & -1.59 & 1.50 & 1833.61 & 51.78 & 7904.39 & 11.57 & 0.00 & 57.81 \\ 
        Alhambra & 50 & 27 & -0.07 & -1.74 & 1.76 & 1517.17 & 6.37 & 10715.73 & 9.32 & 0.00 & 81.42 \\ 
        Camelback E. & 50 & 20 & -0.34 & -1.74 & 1.76 & 1488.38 & 18.73 & 4184.49 & 9.25 & 0.00 & 31.84 \\ 
        Central City & 50 & 31 & 0.02 & -1.74 & 1.90 & 1689.04 & 0.00 & 14438.48 & 13.92 & 0.69 & 106.64 \\ 
        Deer Valley & 50 & 10 & -0.58 & -1.74 & 1.25 & 442.63 & 26.08 & 4540.27 & 3.72 & 0.00 & 11.48 \\ 
        Desert View & 52 & 17 & -0.81 & -1.74 & 1.76 & 593.02 & 0.00 & 2230.48 & 4.10 & 0.00 & 11.82 \\ 
        Encanto & 120 & 11 & 0.09 & -1.74 & 1.90 & 212.27 & 13.04 & 4458.93 & 4.61 & 1.39 & 54.54 \\ 
        Estrella & 51 & 9 & -0.08 & -1.51 & 1.76 & 415.26 & 27.04 & 4196.21 & 6.30 & 1.61 & 39.04 \\ 
        Laveen & 50 & 6 & -0.69 & -1.74 & 1.53 & 3856.80 & 54.76 & 4199.32 & 19.11 & 0.00 & 43.82 \\ 
        Maryvale & 50 & 18 & -0.44 & -1.59 & 1.76 & 955.04 & 4.83 & 4204.42 & 6.38 & 0.69 & 20.85 \\ 
        N. Gateway & 50 & 15 & -0.51 & -1.74 & 1.53 & 865.92 & 3.19 & 3911.25 & 3.52 & 0.00 & 11.55 \\ 
        N. Mountain & 55 & 25 & -0.69 & -1.74 & 1.76 & 838.14 & 0.00 & 5352.24 & 6.16 & 0.00 & 78.73 \\ 
        Paradise Valley & 50 & 16 & -0.74 & -1.74 & 1.53 & 1599.34 & 0.00 & 9334.63 & 5.00 & 1.00 & 42.36 \\ 
        S. Mountain & 50 & 15 & -0.32 & -1.74 & 1.76 & 1885.66 & 5.91 & 10798.95 & 10.14 & 0.00 & 34.62 \\ 
        &  &  &  &  &  &  &  &  &  &  &  \\ 
        & 846.00 & 192\parnote{192 is less than the sume of the column because some users contribute photos to multiple neighborhoods.} & -0.34 & -1.74 & 1.90 & 1184.67 & 0.00 & 14438.48 & 8.05 & 0.00 & 106.64 \\  
        \bottomrule
    \end{tabularx}
    \parnotes
\end{sidewaystable}

\begin{figure}[htbp]
    \centering
    \caption{Histogram of distance from photos to imputed home locations for the photographs owner (n = 697). Binning size is 100 kilometers. This figure omits 18 photos with distances greater than 5,000 kilometers.}
    \includegraphics[height=4in, keepaspectratio=true]{phoenix_touristy_histogram_20150315.pdf}
\end{figure}

The results in Table 1 show that the new measure of neighborhoods, Flickr, is different from the existing measure, so the next task is to determine if the new measure is also robust to potential forms of bias. I treat each of the three potential sources in turn. First for platzbilder, Figure 3 displays the outline of neighborhoods based on the full analytical samples, the grey shaded polygons are corrected for outliers. Each diamond marker indicates an outlier. Remember, the identification of outliers is based on the hat matrix (see Appendix B), which combines the value of the attribute and its spatial location. The take home message from Figure 3 is that Estrella and Laveen shrink very dramatically. Additionally, Paradise Valley and Camelback East shrink just enough so that they are no longer overlapping neighborhoods. 

\begin{figure}[htbp]
    \centering
    \caption{Map of Flickr neighborhoods with corrections for platzbilder outliers in gray. Neighborhoods are based on the analytical sample of photographs (n = 846).}
    \subbottom[]{
        \includegraphics[width=\linewidth, keepaspectratio=true]{phoenix_placey_map_20150315.pdf}
    }
    \subbottom[]{
        \includegraphics[width=7cm, keepaspectratio=true]{phoenix_outlier_legend_20150315.png}
    }    
\end{figure}

The visual trends in the map in Figure 3 are confirmed in Table 3. We see Estrella with the lowest amount of overlap. One should note that we have removed only 5 photos from Estrella, but there are three fewer users in the corrected sample, which suggests that users either contribute a very small number or a very high number of photos to the analytical sample for this neighborhood. The next lowest rate of overlap is .68 in Encanto, but in this case the lower overlap seems to be due to photographs with high levels of place-referential content on the northeast edge of the neighborhood. Adding a small amount of territory around the high outliers has a large effect on the measure of overlap because Encanto is a relatively small neighborhood.

\begin{sidewaystable}[pht!]
    \small
    \caption{Platzbilder outliers}
    \begin{tabularx}{0.9\textheight}{lccd{1}ccd{1}d{1}}
        \toprule
         & \multicolumn{3}{c}{Full analytical sample} & &  \multicolumn{2}{c}{Corrected for outliers} &  \\ 
         \cmidrule{2-4} 
         \cmidrule{6-7}
         & \multicolumn{1}{c}{Photos (n)} & \multicolumn{1}{c}{Users (n)} & \multicolumn{1}{r}{Area} & \shortstack{Outlier \\ Photos (n)} & \multicolumn{1}{c}{Users (n)} & \multicolumn{1}{r}{Area} & \multicolumn{1}{r}{Overlap Rate} \\ 
        \cmidrule{2-8}
        Ahwatukee Foothills & 118 & 20 & 33.58 & 7 & 19 & 37.41 & 0.81 \\ 
        Alhambra & 50 & 27 & 18.12 & 4 & 26 & 15.80 & 0.87 \\ 
        Camelback East & 50 & 20 & 25.17 & 4 & 20 & 33.05 & 0.76 \\ 
        Central City & 50 & 31 & 13.97 & 6 & 31 & 18.89 & 0.74 \\ 
        Deer Valley & 50 & 10 & 61.81 & 2 & 10 & 67.33 & 0.92 \\ 
        Desert View & 52 & 17 & 101.43 & 2 & 17 & 105.74 & 0.96 \\ 
        Encanto & 120 & 11 & 6.22 & 7 & 10 & 9.33 & 0.65 \\ 
        Estrella & 51 & 9 & 86.90 & 5 & 7 & 14.85 & 0.13 \\ 
        Laveen & 50 & 6 & 45.85 & 4 & 5 & 54.25 & 0.85 \\ 
        Maryvale & 50 & 18 & 13.97 & 4 & 18 & 21.69 & 0.64 \\ 
        North Gateway & 50 & 15 & 73.85 & 4 & 15 & 80.96 & 0.91 \\ 
        North Mountain & 55 & 25 & 15.51 & 5 & 25 & 20.69 & 0.75 \\ 
        Paradise Valley & 50 & 16 & 114.60 & 4 & 16 & 121.98 & 0.94 \\ 
        South Mountain & 50 & 15 & 43.09 & 4 & 14 & 31.45 & 0.72 \\ 
        \bottomrule
    \end{tabularx}
\end{sidewaystable}

Turning now to the variable of tourist-influence, the first thing to note is that the full sample is actually slightly reduced for this variable because about 130 photos were taken by users that did not have enough other geotagged photos to create an estimate of their "home" locations. Thus the solid outlines in Figure 4 are slightly contracted from Figure 3. We can see in Figure 4 that many additional neighborhoods are potentially biased from touristy content. Maryvale, South Mountain, Ahwatukee Foothills and Deer Valley have visible changes when we remove the high touristy photos. A bit of googling and browsing back through my sample leads me to believe that there is actually a mountain near the South Mountain and Ahwatukee Foothills neighborhoods, which is surrounded by a natural area that attracts many visitors. Presumably, some of these visitors are from out of town, so finding high amounts of bias from tourists in likely tourist areas is a good sign that my method for detecting bias is working as expected. The changes in Deer Valley and Maryvale are probably not due to any obvious tourist attractions in the area. However, when we look at Table 4, we see that the amount of bias for Maryvale (.67), while high relative to other neighborhoods, is exactly tied with the amount of substantive change for this neighborhood (see Table 1). And in Deer Valley the bias (.50) is only slightly higher than its substantive change (.47), and this is probably attributable to the fact that removing 3 touristy photographs resulted in dropping 2 users.

\begin{figure}[htbp]
    \centering
    \caption{Map of Flickr neighborhoods with corrections for touristy outliers in gray. Neighborhoods are based on the analytical sample of photographs which had valid home locations (n = 716).}
    \subbottom[]{
        \includegraphics[width=\linewidth, keepaspectratio=true]{phoenix_touristy_map_20150315.pdf}
    }
    \subbottom[]{
        \includegraphics[width=7cm, keepaspectratio=true]{phoenix_outlier_legend_20150315.png}
    }
\end{figure}

\begin{sidewaystable}[pht!]
    \small
    \caption{Tourist-influenced outliers}
    \begin{tabularx}{0.9\textheight}{lccd{1}ccd{1}d{1}}
         \toprule
         & \multicolumn{3}{c}{Full analytical sample} & &  \multicolumn{2}{c}{Corrected for outliers} &  \\ 
         \cmidrule{2-4} 
         \cmidrule{6-7}
         & \multicolumn{1}{c}{Photos (n)} & \multicolumn{1}{c}{Users (n)} & \multicolumn{1}{r}{Area} & \shortstack{Outlier \\ Photos (n)} & \multicolumn{1}{c}{Users (n)} & \multicolumn{1}{r}{Area} & \multicolumn{1}{r}{Overlap Rate} \\ 
        \cmidrule{2-8}
        Ahwatukee Foothills & 52 & 12 & 6.31 & 5 & 11 & 10.50 & 0.59 \\ 
        Alhambra & 42 & 22 & 17.62 & 4 & 20 & 19.88 & 0.89 \\ 
        Camelback East & 43 & 18 & 25.17 & 1 & 17 & 17.23 & 0.50 \\ 
        Central City & 46 & 29 & 13.03 & 1 & 28 & 14.22 & 0.92 \\ 
        Deer Valley & 50 & 10 & 61.81 & 3 & 8 & 35.53 & 0.50 \\ 
        Desert View & 47 & 13 & 91.47 & 3 & 10 & 95.52 & 0.96 \\ 
        Encanto & 120 & 11 & 6.22 & 7 & 9 & 11.51 & 0.46 \\ 
        Estrella & 49 & 8 & 86.90 & 5 & 5 & 15.22 & 0.07 \\ 
        Laveen & 47 & 4 & 41.35 & 3 & 4 & 41.35 & 1.00 \\ 
        Maryvale & 46 & 15 & 13.97 & 1 & 14 & 9.06 & 0.33 \\ 
        North Gateway & 48 & 13 & 66.33 & 3 & 11 & 61.64 & 0.84 \\ 
        North Mountain & 39 & 22 & 15.51 & 2 & 20 & 17.53 & 0.89 \\ 
        Paradise Valley & 39 & 14 & 114.60 & 3 & 13 & 116.12 & 0.99 \\ 
        South Mountain & 47 & 13 & 24.56 & 2 & 11 & 21.22 & 0.52 \\ 
    \end{tabularx}
\end{sidewaystable}

The interesting thing about the map based on the interestingness variable is that there is much less shrinkage in the neighborhoods. Like the other two variables, Estrella and Encanto show the most bias when it comes to interestingness. However, unlike the other two variables, the photos identified as outliers with less interest did not tend to be located near the edge of neighborhoods. It is an open question as to whether this means anything about boundary making or the propensity for landmarks to exist on the edge of neighborhoods. Lynch's [-@Lynch1960] concept of "imageability" rested on the hypothesis that neighborhoods had identifiable landmarks located on the edge of neighborhoods. The pattern in the current study shows that $B_{b}$ is higher for interestingness than the other two variables for every neighborhood (see Table 5). Also note that this is not merely an artifact of finding fewer outliers for the interestingness variable -- as the raw count of outliers across variables seems to be within a consistent range of about 3 to 8 outliers per neighborhood. Photographs identified as outliers for this source of bias tend to be located closer to the center of their respective neighborhoods, thus bias from interestingness is overall lower for all neighborhoods. 

\begin{figure}[htbp]
    \centering
    \caption{Map of Flickr neighborhoods with corrections for interestingness outliers in gray. Neighborhoods are based on the analytical sample of photographs (n = 846).}
    \subbottom[]{
        \includegraphics[width=\linewidth, keepaspectratio=true]{phoenix_interest_map_20150315.pdf}
    }
    \subbottom[]{
        \includegraphics[width=7cm, keepaspectratio=true]{phoenix_outlier_legend_20150315.png}
    }
\end{figure}

\begin{sidewaystable}[pht!]
    \small
    \caption{Interestingness outliers}
    \begin{tabularx}{0.9\textheight}{lccd{1}ccd{1}d{1}}
        \toprule
         & \multicolumn{3}{c}{Full analytical sample} & &  \multicolumn{2}{c}{Corrected for outliers} &  \\ 
         \cmidrule{2-4} 
         \cmidrule{6-7}
         & \multicolumn{1}{c}{Photos (n)} & \multicolumn{1}{c}{Users (n)} & \multicolumn{1}{r}{Area} & \shortstack{Outlier \\ Photos (n)} & \multicolumn{1}{c}{Users (n)} & \multicolumn{1}{r}{Area} & \multicolumn{1}{r}{Overlap Rate} \\ 
        \cmidrule{2-8}
        Ahwatukee Foothills & 118 & 20 & 33.58 & 6 & 20 & 34.82 & 0.96 \\ 
        Alhambra & 50 & 27 & 18.12 & 2 & 27 & 22.47 & 0.81 \\ 
        Camelback East & 50 & 20 & 25.17 & 3 & 19 & 18.58 & 0.56 \\ 
        Central City & 50 & 31 & 13.97 & 3 & 31 & 18.11 & 0.77 \\ 
        Deer Valley & 50 & 10 & 61.81 & 4 & 9 & 60.50 & 0.84 \\ 
        Desert View & 52 & 17 & 101.43 & 5 & 16 & 102.79 & 0.90 \\ 
        Encanto & 120 & 11 & 6.22 & 8 & 11 & 8.66 & 0.50 \\ 
        Estrella & 51 & 9 & 86.90 & 5 & 8 & 54.53 & 0.57 \\ 
        Laveen & 50 & 6 & 45.85 & 4 & 5 & 42.36 & 0.77 \\ 
        Maryvale & 50 & 18 & 13.97 & 5 & 18 & 18.53 & 0.75 \\ 
        North Gateway & 50 & 15 & 73.85 & 2 & 15 & 77.12 & 0.96 \\ 
        North Mountain & 55 & 25 & 15.51 & 2 & 25 & 17.98 & 0.86 \\ 
        Paradise Valley & 50 & 16 & 114.60 & 5 & 16 & 123.95 & 0.92 \\ 
        South Mountain & 50 & 15 & 43.09 & 4 & 15 & 46.26 & 0.93 \\ 
    \end{tabularx}
\end{sidewaystable}

See Table 6 for a summation of my critical test for bias: $(1 - A_{b}) < (1 - B_{b})$ across the fourteen neighborhoods ($b$). In the summary table, we see that Encanto and Estrella fail the test for bias for all three potential sources. Deer Valley and Ahwatukee Foothills also fail the test for bias coming from tourist influence. In general, Table 6 has many more "Yes" than "No" values. In the discussion section I elaborate on why I think this meets the criteria for showing that Flickr, as a new measure of neighborhoods, is different and robust.

\begin{table}[htp!]
\caption{Summary of test for bias.}
    \begin{tabularx}{\textwidth}{lccc}
        \toprule
         & \multicolumn{3}{c}{Bias less than difference?} \\
         & Platzbilder & Tourist Influence & Interestingness \\
        \cmidrule{2-4} 
        Ahwatukee Foothills & Yes & No & Yes \\ 
        Alhambra & Yes & Yes & Yes \\ 
        Camelback East & Yes & Yes & Yes \\ 
        Central City & Yes & Yes & Yes \\ 
        Deer Valley & Yes & No & Yes \\ 
        Desert View & Yes & Yes & Yes \\ 
        Encanto & No & No & No \\ 
        Estrella & No & No & No \\ 
        Laveen & Yes & Yes & Yes \\ 
        Maryvale & Yes & Yes & Yes \\ 
        North Gateway & Yes & Yes & Yes \\ 
        North Mountain & Yes & Yes & Yes \\ 
        Paradise Valley & Yes & Yes & Yes \\ 
        South Mountain & Yes & Yes & Yes \\
        \bottomrule
    \end{tabularx}
\end{table} 

## Discussion

Overall, Flickr neighborhoods are different from Phoenix's official village planners (see Table 1). My findings agree with @Hollenstein2010 in showing that Flickr neighborhoods are not obviously wrong, and in most cases are robust against the influence of a few wayward users or photographs. Of course there are exceptions to this as we see in the Encanto and Estrella neighborhoods. These two neighborhoods exemplify two different reasons for their apparent lack of robustness. First, Encanto is small and dense, therefore the procedure I created for adding territory around high outliers had dramatic effects on its overlap measures (remember, the amount of territory added for high values was based on median distances among all neighborhoods). Second, Estrella was less dense and had some photos along its northern side that were outliers in all measures of bias. Estrella shrank significantly, and in a consistent pattern when removing photos: it contracted to the south and east. A third caveat to the overall conclusion is that tourist locations -- in the case of Phoenix it was a natural park area -- may have strong influences on the boundaries of Flickr neighborhoods, for example, in South Mountain and Ahwatukee Foothills.

Without looking for additional data, we can yet see a few ways forward in addressing the caveats. In the case of Encanto, Table 1, shows that it by far has the highest ratio of photographs per square kilometer. Therefore, we might be justified in thinking that the boundaries of Encanto are the least likely of any neighborhoods in this study to be biased. Future research should refine this simple measure of photo density to identify the places where bias would be most likely to exceed substantive differences. In Estrella, Tables 3 through 5 show that this neighborhood always loses the most users (calculated as percentage change between the analytical sample and the corrected neighborhoods). By removing just a handful of outlying photographs I have removed 10-44% of the users contributing photos to Estrella, which in turn, cuts into the robustness  of its boundaries. And turning back to Figure 1 confirms that the northern edge of the neighborhood is Interstate 10, which means the pattern in Figures 3, 4, and 5 -- wherein Estrella contracts toward the south and east -- could mean that the area along the northern side of the polygon is only tangentially in the neighborhood. Authors such as Jane Jacobs  have noted that road construction projects in the 1960s and 70s were often deleterious on neighborhood-level communities [cf. @Klemek2008, 320 for the retelling of Jacobs's fight against expressway construction in Toronto]. Therefore, we might suspect that the results seen in Estrella reflect the tendency for neighborhoods to be set off from interstate highways. The inclusion of the photographs along Estrella's northern edge is probably a form of bias. Turning to the area around the South Mountain natural area, we can return to Tables 1 and 4 and compute weighted means of overlap for the combination of Ahwatukee Foothills, Laveen, and South Mountain -- the three neighborhoods that are next to the natural area. Using the formulas from page 12, we see that the average amount of substantive difference (.41) is greater than the amount of bias (.20) for the set of neighborhoods collectively. This would probably be one area where larger samples of photographs could be used to hone in on the estimate of bias from tourists in and around the natural area.

Estrella shows signs of bias; Encanto, South Mountain, and Ahwatukee Foothills may, but probably do not show signs of bias; and the other neighborhoods are robust. Moreover, there are consistent and large differences between Flickr and official neighborhoods (Table 1), even though I specifically chose Phoenix village planners because they are a more direct comparison to Flickr than census geographies. There are other important differences between Flickr and official boundaries. Flickr leaves gaps between neighborhoods and allows them to overlap. They are almost always larger than census tracts, however, in Phoenix at least, there are many more Flickr neighborhoods than there are official village planners. The inter-subjective neighborhood definitions expressed through VGI is different from official boundaries, and this paper has shown the VGI-based definitions to be acceptably robust; therefore, Flickr is one option for a new operationalization of neighborhoods.

The definition of neighborhoods is at least as important as the other thorny problems of neighborhood effects that are being addressed through fixed effects models [@Oakes2004a], selection effects [@Blume2013], and social network analysis [@Sampson2012, chp. 13]. Neighborhood effects research is badly in need of a viable alternative to census geographies and official boundaries for defining neighborhoods. Even though Flickr neighborhoods may be interesting alternatives, it is not a foregone conclusion that researchers should use them. Indeed, given the persistent and pervasive racial and socio-economic segregation of people in the U.S. [@Molotch1969; @Massey1993; @Quillian2002; @Logan2013], we might suspect that re-jiggering neighborhood boundaries will have little or no influence on the substantive conclusions of research. The next step, then, is to look for substantive differences by substituting Flickr neighborhoods for existing boundaries in well-known models of crime and neighborhood attainment.

# Using Flickr neighborhoods to address the MAUP: Data from homicide patterns in Chicago

## Introduction

Sociologists know that neighborhoods influence individual outcomes, but they have long struggled to define socially meaningful neighborhoods in their studies [@Sampson2002]. The neighborhood is often operationalized as the census tract [@Krieger2006], but we know that this has some problems. One of the biggest problems with administrative geographies like census tracts is known as the modifiable areal unit problem (MAUP), which was first described in the early 20th century [@Gehlke1934] and continues to haunt spatially inclined social science to this day [@Matthews2013b]. Briefly, the MAUP arises because continuous space can be divided up into discrete units, but there are an infinite number of possible configuration of these discrete units. Conclusions from spatial models depend on the substantive relationships in the data, e.g. health, education, or crime, and the way space is divided into discrete units. Or as @Sampson2012 [259], put it, "One criticism of neighborhood-level research concerns the artificiality of boundaries; for example, two families living across the street from one another may be arbitrarily assigned to live in different neighborhoods even though they share social ties." 

As researchers, it is difficult or impossible to know, *a priori*, how to divvy up space into units, so we often fall back on well-known boundaries. For example, researchers might use political boundaries like nations, states, or cities; they might use shared languages as a way to make boundaries around regions; or they may use physical features like roads and rivers to bound spatial units that fit their analysis. The "neighborhood" does not have any of the well-known boundaries that are available at other scales, and therefore, neighborhood effects research is especially prone to the MAUP. The purpose of this paper is to demonstrate the use of geotagged photographs in the Flickr photo sharing platform as one way to define socially relevant neighborhoods and deal with the MAUP. As an empirical case, I will use homicide data from Chicago to show how Flickr-defined neighborhoods can outperform other neighborhood definitions currently used in the literature. In the remainder of the background section, I review the history of the MAUP, then describe the geotagged data in Flicker, and briefly review the literature on spatial models of criminology.

### Background on the history of the MAUP

The MAUP was problematic for the emerging field of quantitative geography back in the 1960s and 1970s. The conclusion of most papers in this era was that the MAUP was impossible to solve [@Berry1964; @Harvey1973; @Openshaw1984; @Robinson1950]. An important paper in sociology was @Fotheringham1991, because they explored the problem in multivariate models. The authors attempted to disentangle what they saw as the two sides of the MAUP: a) the "aggregation" problem which focuses on the scale of the spatial units, and b) the "zonal" problem which suggests that even if the correct scale is chosen there are many possible configurations of spatial units at that particular scale. They concluded dourly,

> "It is clearly possible to find almost any desired result by aggregating the data in different ways. The reliance on the results from one particular zoning system, be they census tracts, block groups, or some other similar aggregation of individual-level data, must be highly suspect [@Fotheringham1991, 1042]."

During the 1990s and 2000s a lot of authors acknowledged these problems while continuing to produce neighborhood effects models [for reviews see @Jelinski1996; @Sampson2002; @Entwisle2007; @Ioannides2010]. In the last ten years, three strains of research have developed to address the MAUP. First, Hipp and colleagues have attempted to directly measure it by testing a large number of models at many different levels of spatial aggregation [@Hipp2007; @Hipp2012; @Ouimet2000]. Second, researchers have begun to combine principles of social network analysis with spatial statistics to more concretely operationalize connections, spillovers, and proximity effects [@Tita2009; @Papachristos2013; @Sampson2012 chapters 13 and 14; @Gould1991; @Liu2010, 1413; @Hipp2012a]. Third, @Fotheringham1998 invented geographically weighted regression (GWR), which allows for different effects in different places. None of these innovations solve the MAUP per se, but they allow researchers to be more confident that their results are robust to alternative spatial aggregations. To try to solve the MAUP a researcher must answer the 80-year old challenge from Gehlke and Biehl [-@Gehlke1934, 170] :

> "The ultimate question is whether a geographical area is an entity possessing traits, or merely one characteristic of a trait itself."

I tend to answer that neighborhoods, as one example of a "geographical area," are indeed entities.[^some] We should therefore try to address the MAUP by finding boundaries for neighborhoods that a) are sociologically meaningful, b) make our statistical findings robust, and c) can be created for any dataset without the need for expert/local knowledge on the part of the researchers. 

[^some]: 
    More precisely, I think that some space can be said to be enclosed by entity-like neighborhoods. I suspect that not all space is in a neighborhood, though, and one area of future research might look at delineating space that is in a neighborhood from space that does not belong to any neighborhoods.

The Project for Human Development in Chicago Neighborhoods (PHDCN) was specifically created to understand the ecological role of neighborhood contexts for the people living in Chicago [@Sampson2012, see especially chapter 4]. The PHDCN was carefully constructed to deepen and broaden our understanding of neighborhoods and their effects on social phenomenon, so it is fitting to use this as a touchstone for looking at how we can improve the definition of neighborhoods. To my knowledge, the PHDCN's definitions of neighborhoods are the most in-depth attempt at defining geographic entities as they are in the world. The PHDCN defined neighborhoods within the boundaries of the city of Chicago by combining two, three, or four census tracts. They combined the tracts with guidance from factor analyses and expert knowledge from social scientists living and working in the city. As compared to most research that just uses census tracts, the PHDCN neighborhoods are superior operationalizations of real-world neighborhoods; however, there are still two problems with the PHDCN definitions. First, they are beholden to the underlying arrangement of census tracts and this might increase the influence of the MAUP. For example, both the census tract methodology and Sampson's work strove to make all spatial units have about the same number of people and cover about the same amount of territory. There are no laws governing the size and population of neighborhoods, so we should suspect that these additional criteria for Sampson's neighborhoods might distort their boundaries. Second, the PHDCN used expert, local knowledge of Chicago to fine tune their neighborhood boundaries, but for many applications in spatial demography [e.g. @South2011b], it would be impossible for researchers to access this type of knowledge across the entire nation.

### Background on Flickr geotagged photographs

I will introduce an alternative set of neighborhood boundaries based on geotagged photographs from the Flickr photo sharing service, and test if the collective wisdom of Flickr users can provide an operationalization comparable to the PHDCN. If Flickr can provide acceptable neighborhoods we could improve many areas of spatial research without launching expensive studies like the PHDCN in every city. And to address the MAUP, it will be useful to compare models that use Sampson's neighborhoods and Flickr neighborhoods in order to quantify how much each of them might fall prey to the old nemesis.

The approach I will suggest in this paper is to extract definitions of areal units from geotagged media available in Web 2.0 platforms.  Let us take that statement one step at a time. *Web 2.0* platforms are the types of web services that allow users to upload content for sharing, viewing, and interacting by other people. This definition includes Facebook, Twitter, Instagram, YouTube, Sina Weibo, and many others. It is important to note that these platforms have many different terms of service, user-bases, and media types (text, video, pictures, music, etc.).[^bias] An increasing number of platforms are including *geotagged* information in the meta-data attached to the media. Each platform uses geographic information differently. For example, Facebook generally collects location information and displays a list of users that are in the same place. While Flickr has a feature to display the most popular photographs as dots on a map. I am proposing to *extract* the geotagged data from these photographs and aggregate it to create *crowdsourced*[^crowdsourced] definitions of neighborhoods, which I argue are more like real world neighborhoods than can be found in census tracts or PHDCN neighborhoods.

[^bias]: 
    I am aware that using social media in social science research opens up many problems of representativeness, socio-economic bias, and positionality [@Rose1997]. However, I think dismissing social media out of hand is problematic in its own right. The survey by @Duggan2013 is a good overview of the representativeness of social media, and see @Crampton2013 for a good summary of where research with geotagged social media is right now and where it may go in the future. Certainly, there is a potential source of bias from the fact that Flickr users will tend to be more white, educated, and affluent than the population in general. However, I would also remind the reader that the committees imbued with the power to define census tracts were not based on random population samples either.

[^crowdsourced]:
    Crowdsourcing is a process where lots of individuals each contribute small amounts of information, and broader conclusions can be drawn from the aggregated data. While crowdsourcing has become a relatively popular principle with the rise of internet communication technology, we should remember that the original Oxford English Dictionary was created through a crowdsourcing process begun in 1857 [@Winchester2004].

I will use the location of geotagged photographs in the Flickr photo-sharing platform to define neighborhoods in Chicago.  Then I will specify models of homicide counts.  The models will be constructed with five alternative neighborhoods - from Flickr, from the PHDCN [@Sampson2012], census tracts, and two scales of regular grid pattens. The models will be estimated with two alternative specifications - simple OLS and spatial autoregressive (SAR) lag models [@Anselin1988, 32-6]. By comparing the model parameters of these ten instances of the same substantive research question, I will demonstrate the promise of using geotagged data from social media to define neighborhoods. The next section reviews the leading theories in spatial criminology and their relationship to the MAUP. In the following section I further detail the sources of data I used for homicide counts and neighborhood definitions (Appendix A explains the code I used in constructing Flickr neighborhoods). In a section on the analytical approach I explain the spatial model further and introduce my technique for measuring spatial autocorrelation via correlograms. Obligatory sections on results and discussion come at the end.

### Background from criminology

The field of criminology uses multiple theories to motivate spatial models of crime patterns. First, routine activities theory [@Cohen1979] posits that criminal activity occurs when motivated offenders are in the presence of suitable targets and there is a lack of social control to prevent it. Variations of this approach can be found in @Sampson1997 and @Papachristos2011. Second, social disorganization theory [@Shaw1942; @Kelling1982] hypothesizes a connection between socio-economic disadvantage and increased crime. See @Sampson2004 for a good critique of the "broken windows" perspective, which is often considered a variant of social disorganization theory. Unlike routine activities, these theories can be directly operationalized by measuring social disorganization (also known as social disadvantage) within a spatial unit. Social disorganization might be measured as vacancy rates in commercial property and foreclosures in residential property. The issue of the MAUP is quite clear in this case: the areal units must be defined in a way to bound space with similar amounts of disadvantage, or else there will be a higher chance of misestimating the effect of disorganization and a higher chance of committing an ecological fallacy[^fallacy]. Collective efficacy is the third criminology theory I will introduce. It is similar to social disorganization theory or the "social control" component of routine activities theory, and I would point readers to @Morenoff2001 [518-21] and @Sampson2012 [168-173] for a more nuanced contrast of the theories. For my current purposes, it is most important to note how the MAUP is problematic for models of collective efficacy. Namely, neighborhoods need to be defined so as to correspond to places that have the shared expectations, communication networks, and cultural norms which give rise to collective efficacy.

[^fallacy]:
    Actually, having the "correct" areal units does not guarantee immunity to the problem of ecological fallacies, but it is a necessary first step. For a good debate on issues of ecological inference see @Subramanian2009a and the critiques by @Firebaugh2009 and @Oakes2009 (with a response from @Subramanian2009b) in a special issue of International Journal of Epidemiology.

What these three theories have in common is the importance of space in criminal behavior, and aspects of the theories are used to motivate spatial models. Researchers commonly observe spill-over or retribution effects [@Messner1999], cultural norms that ebb and flow across multiple neighborhoods [@Sampson1997], a high density of potential (inebriated) theft victims [@Cohen1979; @Pridemore2011], or increased policing [@Short2010]. When interpreting model coefficients from observational studies like these, the effect of the neighborhood variables are mixed together with measurement error that arises from the MAUP. So the researchers are attempting to support or refute one of the theories of criminal behavior, but they are stuck not knowing if their results are indicators of patterns in social world or if they are artifacts of the aggregation that went into the areal units. @Jelinski1996 [136-7] offered five approaches for dealing with the MAUP; I set aside three of the approaches because they are not generally applicable to social science data.[^badfit] Jelinski and Wu argue that dealing with the MAUP can be helped by finding units that are "ecologically meaningful and not modifiable" -- replace ecologically with sociologically and their point applies well to the current study. Second, they advocate a sensitivity analysis -- basically, trying out alternative areal units to try to quantify the amount the conclusions change based on the modifications. I will use these two approaches from Jelinski and Wu to test Flickr against the standard neighborhood definitions.

[^badfit]:
    The three approaches which I have set aside are @Openshaw1984's optimal zoning method, @Tobler1989's frame independent spatial analysis, and @Fotheringham1989's focus on fractal patterns in rates of change over time. All three of these approaches answer Gehlke and Biehl's original challenge in the opposite way that I answer it: they think that neighborhoods are mere characteristics and not entities unto themselves.

## Methods

### Study area

I chose to use Chicago for this analysis because it has a rich tradition neighborhood research dating back to the work of Robert Park and Ernest Burgess and their numerous students[^2] up through the present with the work of Sampson and colleagues on the Project on Human Development in Chicago Neighborhoods[^3]. I will not delve into the issue of whether or not Chicago is a good representation of urban phenomenon in the U.S. [see @Sampson2012, 95-7 for a defense; see @Goering2013 for a critique], because it meets all my needs for the present study: available geo-located crime datasets, already existing definitions of sociological neighborhoods, and a big enough geographical area to avoid the most serious edge effects [@Anselin1988, 174]. Additionally, it is not readily apparent that a critique of Chicago as non-representative for, say, patterns of homicides, would have any bearing on my conclusions about the modifiable areal unit problem[^4]. Unique cases and generalizable cases are both at risk of from the MAUP.

[^2]: 
    Park and Burgess gave rise to the Chicago School's approach to neighborhood studies [cf @Park1921; @Park1925]. Arguably, however, the best urban theory to emerge from the Chicago School came in the form of Wirth's _The Ghetto_  [-@Wirth1956] and Drake and Cayton's _Black Metropolis_ [-@Drake1945], which were broader in scope and more analytical in tone than all the other work associated with Park and Burgess. See @Abbott1997 for a summary of the strands of thought in the Chicago School.
    
[^3]:
    For a list of papers from the PHDCN project see: [http://www.icpsr.umich.edu/icpsrweb/PHDCN/biblio/series/00206/resources](http://www.icpsr.umich.edu/icpsrweb/PHDCN/biblio/series/00206/resources)

[^4]:
    To play the Devil's advocate, it may be plausible that Chicago's long history of neighborhood culture -- network ties, local organizations, architecture, racial segregation, unique city politics, etc. -- may influence the amount or direction of spatial spillover from one areal unit to the neighboring units. It is an intriguing idea, and I am looking forward to replicating these results in Sun Belt cities (Miami, Phoenix, Houston, Las Vegas, etc.), which are usually not described as having strong, long-standing neighborhood traditions.

### Homicide counts from Chicago

Many researchers have noted that murder records tend to be more accurate than other types of crime data. Law enforcement has more of an incentive to properly document location information for homicides, than say, property crimes like vandalism. Previous research shows that homicides contain less bias from underreporting than other types of violent crime [@Sampson1997; @Morenoff2001].

Each incidence report includes the date, location, and categorization of the crime according to standard FBI codes. The location is given as an address and as coordinates in latitude and longitude. There may be inaccuracies in the location attributes of the homicide data because of errors in recording the addresses or errors when the addresses are geocoded to latitude and longitude coordinates. However, I can tolerate inaccuracies in the current paper as long as they can be considered random perturbations that equally effect Sampson's and Flickr's neighborhoods.  Every record also includes an indicator as to whether or not there has been an arrest made in association with the incident. All incidences coded as homicides during 2009, 2010, and 2011 were included in the present study as the outcome variable of interest. It has been shown in many papers [see for example, @Sampson2012; @Papachristos2013; @Flaxman2013] that patterns of crime are strongly linked in time as well as space. So I gathered all of the homicides without arrests during 2005, 2006, and 2007 to use as the primary explanatory variable. The motivation for using incidents with no arrests was originally to operationalize the idea that lack of law enforcement during the first time period, 2005-07, may have given potential perpetrators additional confidence that they could commit murder without getting punished during the second time period, 2009-11. As it turned out, the patterning of "unsolved" homicides very closely mimics the total number of homicide reports, so this choice of variables is less about perceived enforcement, and more likely a control for areas with a recent history of a high number of homicides.

The reader should be aware that all analysis are conducted with homicide *counts* not rates. In order to calculate neighborhood homicide rates, I would need good data on the population of each neighborhood. Population data would be easily available for census tracts PHDCN neighborhoods. However, finding the populations of the regular grid patterns and the Flickr neighborhoods would be more challenging. Future research could use interpolation to estimate their populations based on data from the census or from sources like the Gridded Population of the World[^gridded] project. Often, it is desirable to use rate variables in spatial analysis to "control" for differing population sizes -- for example, an analysis of poverty rates in U.S. counties will probably be superior to models of the counts of households below the poverty line. My analysis does not fall victim to this problem for two reasons. First, I use a time lagged homicide count as an explanatory variable, so any bias introduced by different populations should be controlled with the time lagged parameter. (Except, of course, if there is significant population change between time periods, but that will have to be set aside for future work.) Second, I am less interested in finding the most precise estimates of the model parameters, and I am more interested in showing that the model parameters change across models with different neighborhood definitions. As long as the potential bias from differing populations can be assumed to be roughly equivalent in the different neighborhood formulations, then the central conclusions of my analysis will hold even though I use counts instead of rates. 

[^gridded]:
    [http://sedac.ciesin.columbia.edu/data/collection/gpw-v3]()

### Street intersections

Sociologists seem to have a weird fascination with street corners [@Liebow1967; @Papachristos2013; @Anderson1976] and crime. I used a GIS system to plot every street corner in the study area, and these points are aggregated along with the homicide data to create an additional explanatory variable. I would note that I am not subscribing to a theory that the street corners are causing homicides or  crime, in general. Instead the inclusion of a count of street intersections is meant to serve two purposes in this paper -- one substantive, and one statistical.

First, there is some reason to suspect that the number of street intersections might be associated with behavior, and thus have some association with criminal behavior. Grannis [-@Grannis2009] has written extensively on the small scale changes in built environments that can have an influence on social outcomes, for example arguing for the importance of "tertiary streets" and stop signs in making community boundaries. Scholars in public health have been keen on understanding the interplay of safety and walkability on health and economic outcomes [@Foster2008; see also @Papachristos2011 on gentrification and crime]. Given these hints, I had originally imagined that street intersections might indicate something important about a neighborhood's history and built environment [see also @Raudenbush1999 on ecometrics]. Upon further reflection, I think street intersections are actually a stand-in variable for two other things: population and the presence of super-developments like Chicago's O'Hare airport or the train- and ship-yards on the southern edge of the city. As a (noisy) indicator for population and industrial development, the street intersection variable has some (weak) substantive additions to make to the models.

Second, as a modeling tool, the street intersection variable turned out to be very helpful. As was mentioned above, the rate of homicides is strongly correlated over time, and thus the model coefficients for the lagged homicide variable were relatively large, robust, and consistent. On the other hand, the coefficients for the street intersection variable were usually not found to be statistically different from zero. Having both variables in the models below, allows us to understand how modifications to areal units can influence strong and weak relationships among variables [@Fotheringham1991, 1030]. 

### Neighborhood definitions

My raw data is three sets of point locations: homicides during 2009-11, unsolved homicides during 2005-7, and street locations. I aggregate each of these three variables into neighborhood counts, under five different sets of neighborhood boundaries.

First, I recreated the "neighborhood clusters" used by Sampson and colleagues in the PHDCN. The neighborhood clusters were created by aggregating Census Tracts according to exploratory factor analysis, well-known barriers like roads and rivers, and the author's expert knowledge of the city. Since there were no publicly available files of these neighborhoods, I scanned a copy of the map on page 22 of _Great American City_ [@Sampson2012] and traced the outlines into a GIS.

Second, I downloaded the 2010 census tracts from the U.S. Census Bureau [@Census2012]. The census tracts were used as a point of comparison even though most research suggests that they are too small to accurately capture perceived neighborhoods [@Coulton2001].

Third, I created neighborhoods based on the geotagged photographs uploaded by users of the Flickr photo-sharing platform. See Appendix A for details on the algorithm used in constructing the Flickr neighborhoods. Here in the text I will just stress that the definition of the neighborhoods emerge from a pattern of use among thousands of users and tens of thousands of photographs. The Flickr neighborhoods are an emergent property of social media. Certainly there is socio-economic, racial, linguistic, and age bias in terms of who uses Flickr; however, the neighborhoods I have constructed are a glimpse into one way that many people use and understand neighborhoods. With no perfect definition of neighborhoods on hand, the use of social media and volunteered geographic information (VGI) [@Goodchild2007a; @Elwood2012] offers an alternative to administrative units.

Finally, I created a simple raster of hexagons[^6] across the study area at two different scales. The size of the hexagons were selected so that they served as sample size bookends: one of the hexagon datasets had more areal units (N = 843) than the Census Tracts (N = 801), and the other hexagon dataset had fewer (N = 274) than the Flickr neighborhoods (N = 289). With the Sampson neighborhood clusters coming in right in the middle (N = 343). It is a well-established pattern that larger spatial units will decrease variation, so I use the hexagonal rasters as a check against spurious results that have more to do with the number of units in the dataset rather than with interesting spatial relationships[^drops].

[^6]: 
    Hexagons were chosen over squares because hexagons form a grid where every unit has exactly 6 neighbors that border along edges and zero neighbors that touch only at a corner. The square-based grid gives rise to 4 "edge" neighbors, and 4 "corner" neighbors, thus making a researcher arbitrarily decide between so-called rook- and queen-contiguity matrices [cf @Anselin1988].

[^drops]: 
    Also please note that the hexagonal rasters will leave out some of the homicide data because the hexagons do not completely fill the irregular shape of Chicago. I could have extended the grid to cover all of Chicago, but that creates an inordinate number of "empty" units along the edges, and biased the model results toward the empty units on the edge of the city. In practice, this is one reason why rasters may not be a good solution to the MAUP as advocated by @Tobler1989.

### Analytical approach

#### Univariate measures of spatial association

I take Tukey's suggestion of exploratory data analysis very seriously [@Tukey1977] in this case because there is no clear cut test statistic for choosing among alternative models. Therefore I present univariate analyses to demonstrate that the MAUP is at work within each variable -- not just in the relationships among variables[^7]. The histogram is a useful tool for this part because it shows the similarity in the shape of distributions even when the range of the variables may be vastly different. All of the univariate analyses presented here are based on spatial data, which, just like time series data, needs special attention to patterns of autocorrelation. Autocorrelation is simply the increased similarity in homicide counts when observations are closer together. 

[^7]: 
    A reader will notice throughout my analyses, I shy away from reporting any statistics that include N in their formulas. As I was working on this project, I found myself often asking, "Is that difference because of important substantive changes between the datasets or just because some datasets have fewer observations?" Since I found this to be a bothersome question, I assume other readers will as well. Any analysis that bumps up against questions of splitting or lumping observations into groups will have to decide if the empirical changes are substantively relevant or just an artifact of a smaller/larger sample size. For example, in models of political conservatism, should self-identified independents be kept separate, lumped together with liberals, or excluded from a a model? It is difficult to decide. I tried to minimize this problem as much as possible by using variance instead of standard deviations, medians and quantiles instead of means, and AIC instead of BIC. 

Correlograms serve the purpose of showing us spatial autocorrelation within a variable. These graphs warrant a bit of explanation. In geostatistics, the primary tool for understanding spatial autocorrelation is the variogram [@Cressie1993, 58-70]. One way to explain the variogram is to think about calculating the distance between all pairs of points within a sample. This gives the researcher a long list with three values on each line: the origin point, the destination point, and the distance from the origin to the destination. The list is then sorted from shortest to longest distance. The list is grouped into chunks based on all points that have distances under 1km, 2km, and so on -- these are often called distance classes. The distance classes are nested. The covariance between the origin and destination points within each nested chunk is calculated and plotted against the distance bands. By examining the autocorrelation across different distance bands, geostatisticians can estimate functional forms that allow them to interpolate values between the sample points [@Bivand2008, 195-201].

Of course, my present task is somewhat different -- I do not want to interpolate values -- but the intuition behind the variogram remains useful because the level of spatial autocorrelation will of course change depending on the way we define neighbors. Thus, I have constructed correlograms, which are close cousins to the variogram except they are more appropriate for lattice data. Lattice data is the term for spatial data arranged in closed polygons like neighborhoods; variograms were originally developed for use on discrete point data like ore samples and weather stations. The Moran's I[^12] statistic calculates the autocorrelation between focal and neighboring units. (For the correlogram, all areal units are represented by their centroids to make calculations faster.) The distance classes are defined in such a way that the first point shows the Moran's I when neighbors are defined as all points within 2km; the second point when neighbors are greater than 2 km but less than 4 km; and so on. Note that this is one of the major differences between variograms and correlograms, and is desirable because we usually want to conduct pseudo-significance tests to see if the observed Moran's I is different from zero within each distance band [@Bivand2008, 267]. Conversely, with the nested distance classes used in variograms, significance testing -- pseudo or otherwise -- is inappropriate.

In Figures 3, 4, and 5, points with pseudo p-values < .05 are printed as filled circles. The pseudo p-values are calculated by permuting the observed homicide counts into different locations and then re-calculating the Moran's I. The range of Moran's I values that come from the permutations gives us a good estimate of the distribution of Moran's I under complete spatial randomness (CSR); and if the Moran's I value from our observed data falls outside the range of permutations, we have evidence to reject CSR.[^13] Rejecting CSR simply means that we have found evidence that there is some sort of departure from randomness, or in other words, we have found evidence that there is a pattern we would not expect given an assumption that homicides occur at random throughout the city of Chicago. Figure 3 shows the correlogram for the homicide locations themselves, and I for one, put very little weight in the null hypothesis that homicides are randomly located. Figures 4 and 5 are more important in that they show the correlograms for the model residuals. Here, I am making a less absurd null hypothesis: conditional on control variables and previous patterns of homicides, the location of homicides in Chicago are spatially random. Finding significant autocorrelation in Figures 4 and 5 means rejecting the null hypothesis of conditionally random locations of homicides. Rejecting the null hypothesis means one of three things: 1) we have conditioned on the wrong things, 2) our neighborhood boundaries are wrong, or 3) there are endogenous effects at work that our models can not capture.

[^12]: 
    @Moran1950 introduced the I statistic as a measure of two-dimensional autocorrelation. Like Pearson's correlation coefficient, Moran's I is bounded from -1 to 1. A chess board pattern would result in I = -1, and a spatial pattern where all the high values are clustered next to each other would approach 1. Thus, a value close to zero suggests randomness in the spatial pattern. There are alternative measures of univariate spatial autocorrelation, e.g. Geary's c, but I prefer using Moran's I because of @Anselin1995's further work on local indicators of spatial autocorrelation (LISA), which allows researchers to look for the clusters of values that contribute significantly to the global patterning.

[^13]: 
    I think it is (or should be) debatable how useful it is to compare our observed data to patterns of complete spatial randomness. @Tobler1970 [236] told us a long time ago that near things are more alike, thus arguing that we will almost never observe CSR. More recently, @Kulldorff2006, presents a method for creating random draws that conform with the spatial autocorrelation parameters observed in the sample. The main conclusions of the current paper, though, rest on the correlograms of model residuals. I am more comfortable with using comparisons to CSR in the current context because model residuals should be independently distributed (in the spatial sense as well as in relation to the outcome variable).

And finally, what good is spatial analysis without a few maps? However, the choice of break points between classes proved tricky within this context because quantile maps from each dataset show that the patterns of homicides are very consistent. When I chose to keep the break points the same across all the datasets, the Flickr maps are markedly different from the others. Admittedly, I made the arbitrary choice to emphasize the differences between the datasets by keeping the break points constant across datasets [see @Monmonier1996 for a cheeky introduction on _How to Lie with Maps_]. 

#### Ordinary least squares linear models

In all of the models, I have taken the natural log of the count of homicides for each areal unit as the outcome variable[^9]. Even though it is well known that spatial autocorrelation violates the normality assumptions for $\varepsilon$ in the OLS model given by:

$\log(Y + .8) = \beta X + \varepsilon$

I think it is good to start with this model as it gives us a point of comparison with the work by Fotheringham and Wong [-@Fotheringham1991] on the MAUP in a multivariate regression setting. In addition, we might hope that a perfectly defined neighborhood structure could eliminate all the spurious autocorrelation in our variables[^8]. 

[^8]: 
    Self-organizing maps (SOM) are a subset neural network analysis, which is in turn, a subset of unsupervised machine learning [@Kohonen1990 is a canonical paper]. SOMs attempt to reduce the dimensionality of data by putting similar things closer together in the output space; not different from factor analysis, principal components, and k-means clustering. Do not let the name fool you, SOMs do not necessarily use spatial or geographical data. If they are used in a spatial context, they approach the problem of spatial autocorrelation and the MAUP the other way around: they take the division of the space into units to be a parameter which is to be modeled. Thus the input is a set of, usually marked, points and the output includes both a partitioning of the space and parameter estimates for covariates [for example @Reyjol2005 use species counts across space and time to estimate fish "neighborhoods" in a German lake]. I see the current project as a middle-ground between the usual reification of Census tracts and the newer, spatialized SOM approaches.
    
[^9]:
    It would be preferable to set up a GLM framework [@Nelder1972] for modeling this data because the underlying raw data is indeed a count variable that could be easily assumed to arise from a (possibly over-dispersed) Poisson process. However, the implementation of GLM estimation within spatial regression models [@Bivand2008, 297-305; @Dormann2007; @Diggle2002] is challenging at the present time and are often based on geostatistics, which brings in its own set of assumptions like continuous spatial processes and isotropy. Implementing non-spatial and spatial models with different link functions makes them difficult (impossible?) to compare. Hopefully GLM models will be further developed for spatial econometric models, but for now, I logged the count of homicides and pretended that the resulting variable was continuous and approximately normal.

#### Spatial autoregressive models

Criminology has increasingly come to recognize the underlying spatial nature of criminal behavior, but arguably the attention to spatial distribution has been present since Shaw and McKay's _Juvenile Delinquency and Urban Areas_ [-@Shaw1942]. Thus it makes sense to explicitly model the spatial relationships of crime data, but we should keep in mind that spatial models do not necessarily help us understand the underlying data generating mechanism. For example, significant spatial parameters could be compatible with a mechanism of retaliatory homicides or with a mechanism arising from different levels of policing [@Tita2009]. As a first attempt to measure the spatial relationships in the present data, I estimate a spatial autoregressive model [@Anselin1988 especially chapter 6]. Intuitively, this is easy to understand: crime will be higher (or lower) in a neighborhood that is bordered by high (or low) crime neighborhoods.

The model is given by:

$\log(Y + .8) = \rho W y + \beta X + \varepsilon$

...and is estimated through a pseudo-maximum likelihood procedure where the spatial lag, $\rho W y$, is estimated before the independent variables $\beta X$ [@Land1992; @Bivand2013, 92]. The $W$ is a weighting matrix that contains non-zero elements for all spatial units $i$ and $j$ that share a border[^10].  Additional refinement as to the modeling of the spatial relationships [cf. @Wall2004 on SAR versus CAR assumptions] and to the weight matrix[^matrix] are probably needed, but this first attempt at spatial analysis gives us an important clue about how the MAUP might influence the results of different model specifications.

[^10]: 
    In my analyses I set the non-zero values of $W$ equal to $\frac{1}{N}$ , which is often called "list-wise standardization." Most of the work by Morenoff, Sampson and their colleagues uses "row-wise standardization" where every non-zero element of $W$ is divided by the total number of neighbors for unit i. Implicitly, their approach means that areal units with a large number of neighbors are influenced proportionally less by each one. I see no a priori reason to make this assumption, so I chose the approach that implies: a neighbor is a neighbor is a neighbor. I have no a priori reason for my assumption either, but in the case of Chicago, many of the areas with high homicide counts are on the edge of the study space; thus have only one side on which to have neighbors; thus have fewer neighbors; and thus the row-standardization approach favored by Sampson et al. would tell us that each neighbor is being more influential. 

[^matrix]:  
    Additional research into the type of row standardization is probably not warranted, however, as the field of spatial statistics should move away from making ad hoc decisions about connections and instead focus on operationalizing the embedded social networks. Chapter 14 in @Sampson2012 demonstrates a perfect type of data to perform the socio-spatial weighting found in papers on gang rivalries [@Tita2009]. Ideally, our $W$ matrices would indicate a presence/absence of spatial connections and the value of element $w_{ij}$ would indicate the strength of the tie between $i$ and $j$ along whichever dimension is relevant for the model.

However, I think it is important to note that the inclusion of a spatial parameter does not address the MAUP. @Sampson2012 [258] is flat wrong in this assertion:

> "This ... reflects what is known as the 'modifiable areal unit problem' that arises when artificial boundaries are imposed on more or less continuous spatial phenomena. Spatial models are designed to address this problem by incorporating spatial errors and interdependencies in operationally defined neighborhood units that are contiguous."

Spatial models were not designed to solve the MAUP. Instead the spurious effects of the MAUP are mixed together with the spillover, diffusion, displacement, etc. effects in the spatial parameters, to render those parameters uninterpretable -- mere nuisance parameters [@Anselin2002, 253]. Since the MAUP can cause a mis-estimation of the spatial parameter, there is no gaurantee that the other parameters of the model will be correctly specified either. As such, I pay very little heed to the estimated values of the $\rho$ parameters in comparing different neighborhood definitions. The $\rho$ is not equal to the average amount of association between areal units, and it can tell us very little about the appropriateness of the "operationally defined neighborhood units." For me, the choice among alternative neighborhood definitions should be made on two criteria. First, statistically, neighborhoods should be preferred based on the spatial autocorrelation of the model residuals. And second, ecologically, they should correspond to real-world places as much as possible.

??? Signposting: a) models will tell us how Flickr compares to PHDCN, census tracts and rasters in terms of the aggregation portion of the MAUP; b) 





## Results

Table 1 presents the univariate statistics for the five different datasets. The most important number in the table is the remarkably high variance of homicides in the Flickr neighborhoods showing that some units within this dataset have extremely high counts. The variance for the Flickr neighborhoods is even twice as large as the hexagon raster with 274 units, which demonstrates that the variance in the Flickr neighborhoods is not a mere artifact of having fewer units. The finding that the Flickr neighborhoods have a few extremely high homicide counts may be consistent with what we know about the racial and economic segregation of cities and especially of Chicago [@Wacquant2012]. For example, @Sampson2012 [268] cites @Pattillo-McCoy1999 as evidence that black, middle-class Chicagoans do not benefit from increased wealth like their white counterparts. Remember we do not know that Sampson's neighborhood clusters or the census tracts are in any way "correct" definitions of neighborhoods, so we can not say that the variance of homicide counts as measured by these geographies are the "correct" sample variances. Many scholars have suggested that Chicago is a highly segregated city [@Quillian2002; @Williams2001], so we should tend to prefer neighborhood definitions that show higher variances -- or at least, any researcher that chooses a neighborhoods with lower variances should be forced to justify their choice. The Flickr neighborhoods have dramatically higher variance in homicide counts than Sampson's, census tracts, or either of the raster neighborhood definitions.


\begin{sidewaystable}[pht!]
\small
\begin{tabularx}{0.9\textheight}{rXXXXX}
  \hline
 & Small Hexagon & Census Tracts & PHDCN & Flickr & Large Hexagon \\ 
  \hline
  N & 843 & 801 & 344 & 289 & 274 \\ 
  Homicides, 2009-11 \\
  n, X = 0 & 440 & 359 & 82 & 121 & 75 \\ 
  \%, X = 0 & 0.52 & 0.45 & 0.24 & 0.42 & 0.27 \\ 
  Variance & 5114 & 4278 & 6483 & 24,442 & 10,946 \\ 
  Median & 0 & 1 & 2 & 1 & 2 \\ 
  90th Decile & 5 & 5 & 10.7 & 14 & 14 \\ 
  Unsolved Homicides, 2007-9 \\
  n, X = 0 & 554 & 491 & 138 & 153 & 118 \\ 
  \%, X = 0 & 0.66 & 0.61 & 0.40 & 0.53 & 0.43 \\ 
  Variance & 1635 & 1400 & 2067 & 5232 & 2837 \\ 
  Median & 0 & 0 & 1 & 0 & 1 \\ 
  90th Decile & 2 & 3 & 5 & 7 & 7 \\ 
  Street Intersections \\
  n, X = 0 & 18 & 1 & 1 & 3 & 2 \\ 
  \%, X = 0 & 0.02 & 0 & 0 & 0.01 & 0.01 \\ 
  Variance & 343,495 & 975,070 & 1,643,633 & 3,661,269 & 770,850 \\ 
  Median & 39 & 35 & 84 & 86 & 119 \\ 
  90th Decile & 65 & 87 & 175.7 & 275.2 & 186.8 \\ 
   \hline
\end{tabularx}
\caption{Descriptive statistics under alternative neighborhood definitions.} 
\end{sidewaystable}

\begin{figure}[htbp]
    \centering
    \caption{Histograms of homicide counts in alternative neighborhood definitions.}
    \includegraphics[width=\linewidth, keepaspectratio=true]{maup_figure1_histograms_2015-03-09.pdf}
\end{figure}

Figure 1 displays histograms of the homicide counts for each dataset, and the first thing to notice is the relative similarity in the distributions. The second thing to notice is the differences in the scales along the X-axis, which confirms the results of the table: Flickr neighborhoods have some units with extremely high counts of homicides[^11]. To drive home this point, I made a choropleth maps for each dataset but used the same category break points for homicide counts across all five panels in Figure 2. We can see how the size and shape of the areal units in Sampson's neighborhood clusters work to split up some of the units in the Flickr neighborhoods with the highest homicide counts. After consulting Figure 2, we can see that the apparent patterns of homicides change depending on the areal units used, and perhaps my research could stop and conclude that the MAUP is still at work. However, cartographers and designers have long had an uneasy relationship with this type of choropleth map[^tufte], and we should be cautious when basing judgments on visual inspection of the maps. Instead we should ask how much the alternative definitions of neighborhoods may change the statistics and models we often use to explain crime.

[^tufte]:
    See for example @Cressie1993 [544] and @MacEachren1995's _How Maps Work_. In this case the very dark colors in the map from Flickr neighborhoods suggest a spatial pattern that is absent from all of the other maps except the one from the PHDCN neighborhood clusters. And it is much more stark than the Sampson dataset. However, the high homicide counts in the Flickr dataset are also in relatively larger neighborhoods, thus there is a dramatically larger amount of "data ink" used to depict these neighborhoods, which could lead us to falsely believe the pattern is significant when it is not. Although he doesn't apply the idea to maps, the concept of data ink come from @Tufte1983.

[^11]: 
    When I first saw this outcome, I immediately thought of the paper by Haklay [-@Haklay2013] that describes how none of the participants in OpenStreetMap events want to map council estates -- U.K.'s concentrated public housing developments. I figured that Flickr users simply did not venture into majority-black neighborhoods in Chicago, this caused a dearth of data in my sample, and then those neighborhoods were just assigned all the leftover space in west central Chicago. After further investigation I am confident that there is adequate coverage of photographs from across Chicago, and the dramatic results in Table 1, which will have ripple effects throughout the models, should be given no more than the usual amount of empirical skepticism.

\begin{figure}
    \centering
    \caption{Choropleth maps of homicide counts in alternative neighborhood definitions.}
    \subbottom[Small hexagonal raster.]{
        \includegraphics[width=6cm, keepaspectratio=true]{maup_figure2_small_2015-03-08.pdf}
    }
    \subbottom[Census tracts.]{
        \includegraphics[width=6cm, keepaspectratio=true]{maup_figure2_census_2015-03-09.pdf}
    }
\end{figure}

\begin{figure}
    \contcaption{Homicides, continued.}
    \contsubbottom[Sampson's neighborhoods.]{
        \includegraphics[width=6cm, keepaspectratio=true]{maup_figure2_sampson_2015-03-09.pdf}
    }
    \contsubbottom[Flickr neighborhoods.]{
        \includegraphics[width=6cm, keepaspectratio=true]{maup_figure2_flickr_2015-03-09.pdf}
    }
\end{figure}

\begin{figure}
    \contcaption{Homicides, continued.}
    \contsubbottom[Large hexagonal raster.]{
        \includegraphics[width=6cm, keepaspectratio=true]{maup_figure2_large_2015-03-09.pdf}
    }
    \contsubbottom[Legend for all panels.]{
        \includegraphics[width=6cm, keepaspectratio=true]{maup_figure2_legend_2015-03-09.pdf}
    }
\end{figure}

The final piece of evidence from univariate analysis is displayed in correlograms in Figure 3. All of the datasets show significant, positive spatial autocorrelation in homicide counts at distances below about 30 km. The significant autocorrelation means that neighborhoods with high homicide counts tend to be closer to other neighborhoods with high homicide counts. On the other hand, if we select two neighborhoods that are about 30km apart, on average, they will show no correlation between their homicide counts. This significant autocorrelation will cause violence to the i.i.d. assumptions built into all least squares regression, but it's described briefly to set up the spatial lag model.

\begin{figure}
    \centering
    \includegraphics[width=\linewidth, keepaspectratio=true]{maup_figure3_cgram_homicides_20130712.pdf}
    \caption{Correlograms of homicides under different neighborhood definitions. Filled circles represent significant Moran's I values as determined by exceeding 95\% of datasets with permuted locations and given homicide counts.}
\end{figure}

Table 2 shows the usual results from a series of OLS models estimated within the five datasets. The $\beta$ coefficient for unsolved homicides is lowest for the Flickr neighborhoods. In the Census tracts and Sampson neighborhood clusters, the coefficient for intersections is not significantly different from zero. While in the other three datasets, this coefficient is very small, but significant. The AIC suggests that the large hexagons are the best operationalization of the neighborhoods, but perhaps we should be suspicious that the rank-ordering of the AIC statistics exactly mirrors the order of the dataset by their N. It appears as if all the additional variation we saw in homicide counts in the Flickr  dataset (see Table 1) is easy for the OLS model to explain. Therefore the model on the Flickr dataset has a lower AIC than the Sampson neighborhood clusters. The large hexagonal raster has the lowest AIC, of course, but this is not too surprising given previous research that finds a consistent trend for increasing  $R^{2}$ (i.e. increasing values of the model's likelihood function) as the number of units decreases [@Gehlke1934; @Openshaw1984; @Hipp2007].
 
Instead of reporting the standard errors for the coefficients I have chosen to show 95% confidence intervals because they help demonstrate how much the changes in neighborhood definition can change the model results. All of the coefficients for prior unsolved homicides are significantly different than zero, but more importantly, the coefficients from the small hexagonal raster and the census tracts are significantly different from the point estimates of the same coefficient under the Sampson neighborhood clusters ($\beta_{unsolved}$ = .249), large hexagonal rasters ($\beta_{unsolved}$ = .254), and Flickr neighborhoods ($\beta_{unsolved}$ = .187). Conversely, the confidence intervals demonstrate that the coefficient from the Flickr neighborhoods is significantly lower than the point estimates from all of the other datasets.

\begin{sidewaystable}[pht!]
\small
% latex table generated in R 3.0.1 by xtable 1.7-1 package
% Wed Jul 17 15:49:52 2013
% tweaked by mjm, 2014-01-07
\begin{tabularx}{0.9\textheight}{rXXXXX}
  \hline
 & Small Hexagon & Census Tracts & PHDCN & Flickr & Large Hexagon \\ 
  \hline
  Intercept \\
  $\beta$ & 0.0240 & 0.2911 & 0.6784 & 0.2592 & 0.2941 \\ 
  95\% C.I. & (-.08--.12) & (.21--.37) & (.53--.83) & (.13--.39) & (.08--.51) \\ 
  Unsolved Homicides, 2007-9 \\
  $\beta$ & 0.3397 & 0.3183 & 0.2488 & 0.1869 & 0.2536 \\ 
  95\% C.I. & (.31--.37) & (.28--.35) & (.22--.28) & (.16--.21) & (.23--.28) \\ 
  Street Intersections \\
  $\beta$ & 0.0049 & 0.0002 & -0.0003 & 0.0017 & 0.0022 \\ 
  95\% C.I. & (0--.01) & (-.001--0) & (-.001--0) & (.001--.003) & (.001--.004) \\
  \\ 
  AIC & 1710 & 1681 & 782 & 661 & 603 \\ 
  BIC & 1729 & 1700 & 797 & 676 & 617 \\ 
   \hline
\end{tabularx}
\caption{OLS models of homicide counts 2009-2011, under alternative neighborhood definitions.} 
\end{sidewaystable}

Figure 4 again shows a correlogram for each dataset, but this time the residuals are graphed instead of the homicide counts. The Moran's I values of the residuals are lower than the corresponding values of Moran's I for homicide counts. However, the filled circles show that there is still significant autocorrelation among the residuals, which means we see heteroskedastic errors in the OLS models for all of the datasets. This is not surprising since we already observed that the spatial autocorrelation in homicide counts violates the i.i.d. assumptions of least squares estimation. 

\begin{figure}[htbp]
    \centering
    \includegraphics[width=\linewidth, keepaspectratio=true]{maup_figure4_cgram_ols_20130712.pdf}
    \caption{Correlogram of residuals from an OLS model predicting homicide counts. Filled circles represent significant Moran's I values as determined by exceeding 95\% of datasets with permuted locations and given homicide counts.}
\end{figure}
 
Table 3 shows the results from the spatial lag model and we can easily see that introduction of a spatial parameter has a sizable impact on the coefficients for unsolved homicides and intersections[^voss]. The Flickr neighborhoods and the Sampson neighborhood clusters show the least amount of change in the parameter estimates between the OLS and spatial models, which suggests to me that these two neighborhood definitions are better than rasters and census tracts at approximating the spatial patterns in the data[^catch]. These two datasets also have the lowest values for $\rho$. Again, paying attention to the confidence intervals shows that the coefficient for unsolved homicides estimated from the  Flickr neighborhoods is significantly lower than the point estimates of all four other datasets. When using the 95% confidence intervals to compare between datasets, there are not any interesting patterns in the coefficients for the street intersections or the spatial parameter.
 
[^voss]: 
    We do not, however, see any change in the direction of the coefficients like @Voss2006 found when analyzing childhood poverty rates at the county level.
 
\begin{sidewaystable}[pht!]
\small
% latex table generated in R 3.0.1 by xtable 1.7-1 package
% Wed Jul 17 16:16:32 2013
% tweaked by mjm 2014-01-07
\begin{tabularx}{0.9\textheight}{rXXXXX}
  \hline
 & Small Hexagon & Census Tracts & PHDCN & Flickr & Large Hexagon \\ 
  \hline
  Intercept \\
  $\beta$ & -0.1082 & 0.0681 & 0.3035 & -0.0200 & 0.0481 \\ 
  95\% C.I. & (-.19- -.03) & (-.01--.14) & (.15--.46) & (-.15--.10) & (-.14--.24) \\ 
  Unsolved Homicides, 2007-9\\
  $\beta$ & 0.1840 & 0.1650 & 0.1669 & 0.1218 & 0.1601 \\ 
  95\% C.I. & (.16--.21) & (.13--.20) & (.14--.20) & (.10--.15) & (.13--.19) \\
  Street Intersections \\
  $\beta$ & 0.0039 & 0.0006 & -0.0000 & 0.0015 & 0.0013 \\ 
  95\% C.I. & (.002--.006) & (-.001--.002) & (-.001--.001) & (.001--.002) & (-.00--.002) \\ 
  Spatial Parameter \\
  $\rho$ & 0.5640 & 0.5655 & 0.4327 & 0.4125 & 0.4543 \\ 
  95\% C.I. & (.50--.63) & (.50--.63) & (.34--.52) & (.32--.50) & (.36--.55) \\
  \\
  AIC & 1457 & 1438 & 708 & 600 & 535 \\ 
  BIC & 1480 & 1462 & 727 & 618 & 553 \\ 
   \hline
\end{tabularx}
\caption{Spatial autoregressive (SAR) lag model results under alternative neighborhood definitions.} 
\end{sidewaystable}
 
Looking once again at the correlograms of the residuals, Figure 5 shows us that there is no spatial autocorrelation left in the residuals for the Flickr dataset. Likewise, the large hexagonal rasters are showing no significant autocorrelation in the residuals, and the Sampson neighborhood clusters have significant autocorrelation at just two distance classes around 10 km[^lisa]. The small hexagonal rasters and Census tracts have small, but significant amounts of spatial autocorrelation among their model residuals at distance classes between 6 and 20km.  
 
[^catch]: 
    Some researchers have criticized models like the spatial lag model which I'm using because the spatial coefficient becomes a "catch all" for many things: spatial diffusion processes, omitted variables, misspecified neighborhoods, and (spatial) endogeneity [@Manski1993; @Tita2009, 152-3]. I have no defense against this critique, but it should not matter for comparing neighborhood definitions or testing for the MAUP -- as long as the $\rho$ is acting as a "catch all" in a similar fashion across all five datasets.
 
[^lisa]: 
    I conducted a follow up analysis using local indicators of spatial association [LISA; @Anselin1995] to investigate the Sampson dataset at the 4-6 and 6-8 kilometer distance bands. At the 4-6km distance, there was a noticeable cluster of significant local Moran's I values on the southwest edge of the city near Morgan Park, but other than that there was no discernible pattern in the local Moran's I values. To put it another way, the significant global Moran's I visible in Figure 5 for the Sampson dataset, can not be attributed to clusters of high or low residuals in the areas with relatively high/low homicide counts (refer to Figure 3). Thus I am willing to attribute the significant spatial autocorrelation in the SAR lag model residuals for the Sampson dataset to dumb luck arising from the Monte Carlo methods used for testing significance.  LISA maps available upon request.
 
\begin{figure}[htbp]
    \centering
    \includegraphics[width=\linewidth, keepaspectratio=true]{maup_figure5_cgram_lag_20130712.pdf}
    \caption{Correlogram of residuals from a spatial lag model predicting homicide counts. Filled circles represent significant Moran's I values as determined by exceeding 95\% of datasets with permuted locations and given homicide counts.}
\end{figure}  

## Discussion

Using alternative spatial definitions changes the parameters of the models. This agrees with previous research on the MAUP [@Fotheringham1991; @Openshaw1979].

Flickr offers one solution to the problem because the neighborhoods that emerge from aggregating user behavior creates socially meaningful neighborhoods. In other words, Flickr neighborhoods have names and shapes that most (local) people can recognize -- none of the Flickr neighborhoods in Chicago are on the opposite side of town from where official municipal boundaries would place them. Secondly, the neighborhoods are gleaned from Flickr users during their normal interactions on the website. They are not asked explicitly, for example in a survey, and thus they may be closer to *en vivo*, shared understandings of place[^19].  

[^19]: 
    This paper has tried to tackle a big problem in the MAUP, and has set aside a deeper question about the concepts of "space" and "place" in the area of neighborhood effects research. For a more extensive treatment of this debate see @Tita2010 and especially the cited works on 472-3; @Matthews2011 and works cited on 39-41; @Marston2005 put place-space on top of the list of conflated binaries, and sociologists could do well to consider their perspective; @Gieryn2000 [464-5] offers a good definition of "place" but his dismissal of "space" is too simplistic; and @Lefebvre1991's work is important but I recommend @Harvey1991's _Afterword_ in the book as a gentler introduction. In all the work on place and space, @Suttles1972's theorizing is my personal favorite because of its close relation to empirical projects of urban land development. To oversimplify: Flickr neighborhoods are more like places, and census tracts are more like space. When sociologists theorize the causal mechanisms of neighborhood effects, they tend to use concepts of neighborhoods as places. Whether right or wrong, since we conceive of neighborhoods as places, perhaps we should operationalize our neighborhood boundaries with methods more aligned to our theorizing.

In addition to face validity, Flickr neighborhoods should be preferred because they show the lowest amount of spatial autocorrelation in model residuals for both the OLS and SAR models. Granted the PHDCN neighborhoods also showed similar patterns, but Sampson and his colleagues used factor analyses and expert knowledge in the construction of their definitions. A tie between Flickr and PHDCN on the model residuals should be seen as a win for Flickr because much less information went in to defining the Flickr neighborhoods. The large hexagonal raster also showed no significant spatial autocorrelation among residuals in the SAR model, which indicates that researchers may want to consider turning all of their data into rasters to overcome the MAUP, as originally suggested by @Tobler1989. The small, but significant amount of spatial autocorrelation in the residuals from models based on the smaller hexagonal raster and the census tract indicates that these neighborhood definitions may be too small to capture the socio-economic patterns of Chicago; they are therefore plagued by "excess" spillover between units. To use @Fotheringham1991's terms, the small hexagonal raster and the census tract have aggregation problems. Flickr, PHDCN, and the larger hexagons solve the aggregation portion of the MAUP, but it is unknown if they appropriately address the zonal portion.

A final criteria we should use for determining the best neighborhood definitions comes from research into economic and racial segregation. Chicago like most U.S. cities is highly segregated along racial (and to a lesser extent economic and class) lines [@Massey2009; @Lichter2012; @South2011b; @Massey1993]. Indeed, the original impetus for much of the neighborhood effects literature was the work of William Julius Wilson [e.g. -@Wilson1990] on persistent, geographic, racialized inequalities in urban America. @Sampson2012 [chapter 4] provides a good summary of how Wilson's work inspired the PHDCN[^18]. Therefore, we as researchers should try to use neighborhood definitions that reflect what we know about segregation in urban settings, and the clearest piece of evidence in this paper is the dramatically higher variation in homicides when counted according to Flickr neighborhoods (refer back to Table 1). Think about the math behind calculating the variance of homicides: when lots of observational units have very low values and lots of units have very high values, you get more total variance. Variance is a simplistic definition of segregation, so Flickr neighborhoods are better at operationalizing the segregated geography of Chicago[^careful].

[^18]: 
    And Wilson also wrote the forward for _Great American City_ [@Sampson2012, 8-14]. Wilson and Sampson's perspective on urban segregation is not the totality of theorizing on the subject, however. For example, @Wacquant2012 and the LA School of urbanism critique the Chicago School's approach [see @Dear2008 as an introduction to the L.A. versus Chicago school debate]. I am also interested in how we could use real-time social media data to operationalize some of the theoretical points about the "double-sidedness of the ghetto" [@Wacquant2012, 8], but that is beyond the scope of this paper.
    
[^careful]: 
    Though we must be careful in this regard. If neighborhoods are defined so as to maximize inter-unit racial segregation, and if our models are using control variables like dissimilarity indexes [@Lee2008], we run the risk of modeling a tautology. In my particular case, the Flickr neighborhoods are defined by the service's users, and just happens to display high rates of inter-unit variation in homicide counts.
    
Taken together, the face validity, the decrease in spatial autocorrelation among residuals, and the higher variance in homicide counts demonstrates the Flickr neighborhoods are equivalent or superior to other neighborhood definitions. Returning to Figure 2, we notice that the Flickr neighborhoods are smaller near Chicago's downtown Loop district and larger in predominantly African-American neighborhoods on the South Side. To double check that all of these conclusions hold in the South Side, I conducted a follow-up spatial regime analysis and the results are presented in Appendix B. In short, yes, all conclusions hold in the South Side and in the rest of Chicago.

Unfortunately, Flickr neighborhoods are not available off-the-shelf right now like census tracts, but they can be constructed for any place. Flickr neighborhoods as seen in this paper can be made from publicly available data, open source code, and a little elbow grease[^24]. The next challenge to putting Flickr neighborhoods into practice will be finding ways to use data sources that are collected and aggregated to administrative units like ZIP codes and census tracts. There are a number of existing interpolation methods available for moving data from one set of polygons to another [@Tobler1979; @Goodchild1993; @Holt2004], but, of course, we should test if the inevitable error introduced through interpolation is a major threat to our customary model assumptions. I am moderately optimistic that Flickr neighborhoods will gain in usefulness as additional data sources become available with VGI, remote sensing, ecometrics, and geolocated open data.

[^24]: 
    For researchers short on elbow grease, Foursquare is giving away access to neighborhood definitions for over a thousand cities world wide through the [http://quattroshapes.com/](http://quattroshapes.com/) project. Their version of neighborhoods are based on multiple data sources: Flickr geotagged photographs, Foursquare checkins, and open government data.

Looking ahead, I can see the need for three types of additional research to firm up the conclusions of this paper. First, there is a need to understand how the MAUP might effect the growing number of alternative specifications for spatial models. For example, there have been recent spatial analyses done with random effects models [@Savitz2009a], hierarchical linear models (HLM, aka fixed effects models [@South2011b]), spatio-temporal models [@Kim2003], spatial Bayesian models [@Finley2011], trend surfaces, and geographically weighted regression [GWR; @Graif2009]. Since different modeling frameworks make different assumptions about the data generating processes and use different parameterization of the spatial covariance matrix, some models might be more susceptible to the MAUP than others.

Second, using simplistic notions of contiguity in order to capture complex social interactions seems primitive at best, and very probably causes model misspecification (see ff. 15 for my thoughts on this problem for the current paper).  My favorite chapters of @Sampson2012 deal with the connections among key informants (chapter 14) and inter-neighborhood migration patterns (chapter 13), which show how Chicago neighborhoods are connected through complicated, and not purely spatial, webs of people, knowledge, and resources. Additional examples of this are @Gould1991 on the Paris commune and @Tita2009 on gang turfs in Pittsburgh. Communication networks in social media could be *one part* of a wider research agenda to improve operationalizations of connectivity matrices in spatial models. Instead of thinking of two neighborhoods as connected merely because they share a border, we could use the density of inter-neighborhood communication as a measure of the strength of connectivity among a set of neighborhoods.

Third, this paper is meant to tantalize researchers with the possibility of solving the MAUP by using geotagged data from social media. It is not a validation (in the econometric or psychometric sense of the word) of geotagged social media data. Unfortunately, there is a dearth of research into validating measures of emerging social media data. One promising example is @Cranshaw2012, who used check-in data from Foursquare to construct neighborhoods in Pittsburgh, and then conducted semi-structured interviews with 27 residents about specific areas in the city. Their process is reminiscent of the Census Bureau's original approach for making census tracts [@Krieger2006]. Those of us that believe in the usefulness, appropriateness, and importance of social media data in sociological research must provide further demonstrations of its econometric validity.

# Segmented neighborhood attainment theory: Using Flickr to extend current models.

## Introduction

Neighborhood attainment theory attempts to explain the sorting of households and patterns of neighborhoods within U.S. cities. Attainment of a neighborhood means moving into a more advantaged residential location. As developed by South and Crowder it draws on three theoretical frameworks [-@South1997, 1043-51]. First is the human capital and life-cycle framework which sees household migration as part of a person's goals for families, careers, and age-appropriate amenities. Second, the place stratification model emphasizes the long-standing patterns of residential segregation in the United States over the individual characteristics of any potential moving household [@Logan1987]. Third, the authors add neighborhood- and metropolitan-level contextual effects to the neighborhood attainment model to account for different outcomes. Examples of contextual effects are the quality of the sending neighborhood and the political history of the city or region. Through a series of papers based mainly on the PSID data, South, Crowder, and colleagues have established a strong empirical basis for the neighborhood attainment model [@South1997; @South2011a; @South2011b; @Crowder2003; @Crowder2012; @Crowder2011; @South1999].

Neighborhoods are important for determining the life outcomes of people, and therefore, understanding how people move into and out of differently advantaged neighborhoods is important. They also influence children's life course by constraining educational opportunities, increasing or decreasing exposure to environmental toxins, providing nurturing social interactions, and serving as a repository for social capital formation and networking. Neighborhoods are therefore critical in the process of intergenerational transfers of dis/advantage. Neighborhood attainment is one mechanism of broader theories such as social stratification and US residential segregation [@Massey1993; @Sampson2012, chp 15]. The current neighborhood attainment model is limited, however, because it treats everyone as if they are participating in the same system. In this paper I will propose a "segmented" neighborhood attainment system -- based on concepts borrowed from segmented assimilation theory -- which allows for the possibility that processes such as suburbanization, gentrification, and stratification are not equally felt among households that recently moved. For example work by @Fischer2014 has shown that there is a persistent "dual housing market" across U.S. cities. This research suggests that not everyone is equally free to move to all neighborhoods, thus, we could reasonably expect neighborhood attainment to be quite different for different households.

The hypotheses of this paper are set up to test global versus segmented models of neighborhood attainment to measure which one more accurately predicts the outcome of migration behaviors. The alternative theory is operationalized with neighborhood definitions from Flickr to distinguish segments of the population that may be participating in separate attainment processes. By combining geotagged information from a social media platform with census data, I can conduct the test of global versus segmented models in a nation-wide dataset covering all U.S. cities.

The rest of the paper is organized as follows. First, a section introduces my new theory of segmented neighborhood attainment, and lays out the specific hypotheses that follow from the alternative theory. Second, I describe the data and methods used for creating the new neighborhood definitions based on Flickr. Third, I cover the results of models based on data from the American Community Survey (ACS) paying special attention to the differences among the hypothesized segments. In the concluding section I revisit the theory of neighborhood attainment and draw out the connections between the measurement methods and the new alternative theory. A methodological appendix includes details on the replication studies I used to test for the robustness of the main findings.

## Segmented Assimilation Theory

Segmented assimilation theory comes from the field of demography and is used to explain the experiences of immigrants in the U.S. racial system [@Portes1993; @Zhou1997]. It is a counter-weight to the naive theory of the "melting pot" or to the older theory of "race-relations cycle" from the Chicago School [@Alba1997]. Note that segmented assimilation is still a debated theory in demography, and some researchers try to put a different inflection on the theory by, e.g., emphasizing the unique receiving contexts of certain cities and regions [see @Portes2005, 1001-4 for a summary]. However, for the purposes of this paper the important elements of the theory are useful for drawing analogies to the current neighborhood attainment theory, which often reads as if it were based on the idea of "melting pot" cities.

I am not the first person to read together the ideas of segmented assimilation theory and neighborhood attainment. Many writers have noted that spatial assimilation is a required part of assimilation because ethnic enclaves can prevent socio-economic integration, intermarriage, and English-language proficiency. Therefore, attaining neighborhoods that are made up of mostly majority group residents is a prerequisite for full assimilation [@Alba1997]. @South2005 apply the notions of spatial and segmented assimilation directly to a test of Latino ethnic groups' neighborhood attainment and conclude that there are patterns that can not be explained by classic assimilation models. @Iceland2008 have similar findings in that white Hispanics are more spatially integrated with non-Hispanic whites than are foreign born Hispanics and black Hispanics. While this set of research is aware of both neighborhood attainment theory and segmented assimilation theory, there does not seem to be any work that tries to directly integrate the two. That is my purpose here, and I will proceed by first summarizing five main points of segmented assimilation that are relevant for neighborhoods and residential patterns. Second, I will show how I use these 5 findings to define four segments within the U.S. neighborhood attainment system. Finally, I will propose two hypotheses that test whether the attainment system can be more accurately modeled as composed of four segments or a single system.

First, segmented assimilation shows that it is important when a person arrives in the new country. Some assimilation trajectories open up and others close off because of political changes, economic conditions, or prejudice. In the neighborhood system, this also matters as many researchers have noted that white neighborhoods react differently to the first few non-white residents that move there as they do to additional non-white households. There is still debate exactly when a "tipping point" in racial discrimination may occur [@Hunt2010a, 274], but it is clear that early- and late-movers experience different assimilation contexts.

Second, segmented assimilation theory explayins why ethnic enclave communities might form instead of the hypothetical melting pot. If people (correctly or incorrectly) perceive that certain paths of assimilation and upward mobility are closed off to them, they may prefer to use a different strategy in their life decisions in order to have chances at owning a business, finding credit, getting advice about housing, and protecting their children from potential sources of danger in urban settings. When this idea is applied to the neighborhood attainment model we can see why some people use strategies to find neighborhoods that may not have higher levels of the variables usually considered part of advantaged neighborhoods, but meet their desires based on religions, common languages, having access to foods or services not found in mainstream culture, or a sense of duty to a shared heritage.

Third, segmented assimilation theory allows a way to understand why certain neighborhoods at the turn of the 19th into the 20th century were ethnic enclaves for Eastern and Southern European groups and those same places are now enclaves for Latin American, African, or Southeast Asian ethnicities. In other words, the people change, but the places continue to occupy the same niche within the urban system. Segmented assimilation tells us that urban labor markets have built in demand functions for certain classes of manual labor and locations -- near to the center but not directly in the CBD -- which predict the creation and re-creation of ethnic enclaves in specific patterns [cf. @Spielman2013]. Thus, neighborhood attainment theory is sometimes challenged because ethnic enclaves are very close to, or even intermingled with, some of the most expensive housing in central business districts. 

Fourth, segmented assimilation shows us how the raw material for "cultural omnivores" can be created multiple times in different cities across the U.S. A full discussion of the theory of cultural omnivorousness is beyond the scope of this paper [@Lizardo2012], but there are two important features that merit mentioning. First, cultural omnivores value diversity in art, food, music, political viewpoints. This could take the form of specific economic activity -- avoiding restaurants in a strip mall in favor of a food cart -- and it takes the form of material culture that valorizes diversity. Second, cultural omnivores value authenticity in their cultural diversity. For example, condos in converted in industrial buildings are usually more expensive than similar properties built anew on the edge of cities. Segmented assimilation means that cultural omnivores can consume authentic Latin American food with a ferry ride to Brooklyn instead of a trip to Caracas [@Zukin2010, chp 5]. Additionally, it shows how authenticity (even though it is contested within a social field) can fetch economic premiums -- often in the form of higher rents or housing prices.

Fifth, one of the key ideas of the segmented assimilation theory is the unique place of African Americans within the U.S. racial system. Structural and interpersonal racism are most consistently directed at black Americans, so members of other immigrant groups often need to use strategies to avoid being labeled as African Americans. Research has consistently shown that second-generation black Hispanics from the west Indies fair worse than other people of Hispanic origin [@Waters1994; @Portes2006; @Portes2005]. Given these social dynamics it is not surprising that residential segregation is consistently higher for African Americans than it is for Asian Americans and Latinos. Neighborhood attainment theory could be improved by incorporating these ideas about the unique disadvantage of African Americans within the U.S. racial system and its implications for the spatial arrangement of neighborhoods [@Massey2015].

When we borrow these five findings from segmented assimilation theory and apply them to neighborhood attainment, we can begin to generate more accurate models of residential patterns. By analogy, my aim is to build a model of neighborhood attainment that accounts for suburbanization (white flight), gentrification, ethnic enclaves, and the unique disadvantage faced by black Americans. To do this, I propose a segmented system where each segment is a cluster of choices and constraints that lead to more or less regular patterns of residential sorting. In statistical terms, a segment is its own regression model complete with an independent subset of data and the parameters estimated from that subset. There may be any number of "segments" within the neighborhood attainment system, and future research must continue to refine the operationalization of the segments. However, I think a useful starting point is to posit four main segments. I will now describe the four segments and the method I use for identifying the people and places that are connected with the segments. (In the discussion section I will revisit some alternatives to the plan I have used.)

"White flight" is a term that has been part of urban sociology since the 1960s. @Crowder2000 examines it in reference to the neighborhood attainment theory. @Sampson2012 recently noted that the term could be used for both white and Hispanic populations within Chicago because they both showed migration patterns out of majority African-American neighborhoods. @Pais2009 also found evidence for "minority flight" from predominantly white neighborhoods, so obviously this term can no longer be deployed in a simplistic fashion. Neighborhood attainment theory claims that people in this segment are attaining more advantaged neighborhoods because they move to wealthier places, usually in less dense suburban communities. However, I think the more accurate conceptualization is that white flighters are attaining places that are not part of any neighborhood -- "non-neighborhoods," if you please. Gated communities, private schools, autonomous tax authorities, long commutes, private security forces, etc. are tools used by the segment to partially remove themselves from the concerns of urban neighborhoods. Thus, when sociologists lump together white flighters and everybody else within a single neighborhood attainment model, they probably reach false conclusions. In order to define "white flighters," I overlayed the Flickr neighborhoods (described below) with the census data. Since Flickr neighborhoods are not defined to cover all areas like census tracts, some people can be defined as living outside of neighborhoods -- these people make up the white flight segment in my models. 

Gentrification has been a socio-spatial process in U.S. cities for just slightly less time than white flight. Gentrification is usually described as the movement of rich, well-educated (often white) people into lower-class (often post-industrial) neighborhoods, and the concomitant rise in land value. Gentrifiers have been described as having major influences on the social and built environments of U.S. cities since the 1980s [@Zukin2010; @CDC2009]. The process of gentrification does not fit easily within the theory of neighborhood attainment. Within segmented neighborhood attainment we would look for white, wealthy, and educated individuals that sought out neighborhoods that were demographically diverse, culturally authentic, and having just the right amount post-industrial aesthetic. Census tracts can not tell us how people perceive their environment. Flickr is more capable of defining areas that are likely to be in the process of gentrification. When some places are identified as part of more than one neighborhood, I take it to mean that there is a lot of history, multiple meanings, or cultural interest in the place, thus it may be a gentrified neighborhood. And since gentrifiers are by definition relatively more wealthy, I put in an additional requirement that they had to be above the median income in my dataset ($34,200 in 2005 dollars). Gentrifiers are also required to be native born -- I added this as a way to distinguish between gentrified neighborhoods and ethnic enclaves.

The current neighborhood attainment theory assumes that all individuals are navigating the same system. It assumes that individual attributes (e.g. more education or more wealth) will be translated into "better" neighborhoods, which means that it assumes all people agree on what counts as better neighborhoods. The writers on neighborhood attainment probably do not believe this is how attainment works, however, given the current methods for defining neighborhoods they are stuck with this operationalization. I have already defined two segments of people that use different notions of what counts as a better neighborhood, so I can treat all of the remaining sample as the global neighborhood attainment model would have defined them. The remaining people are either striving toward more advantaged neighborhoods or stuck in place [@Sharkey2014]. It is a difficult task to disentangle these two segments. For the current paper I will use a crude indicator of upward mobility: being employed and having earned a bachelor's degree. Not that these are not the only hallmarks of upward mobility, nor that they guarantee a path through social strata, but these two variables will be a way of operationalizing the difference between stuck-in-placers and strivers; most importantly, this operationalization is possible with available census data.

Everyone not identified yet as white-flighters, gentrifiers, or strivers will by default get defined as stuck-in-placers. Future research could use information about the sending locations of these individuals to see if indeed they are stuck in the same type of neighborhoods across their migrations. The particular segments within the segmented neighborhood attainment system do not have to be operationalized perfectly to test the hypothesis that the segmented model is preferred over a single global model of attainment. At this point, it is also useful to remind the reader that race/ethnic categories have not yet been incorporated into the definitions of the segments. It is possible for a person in any of the 5 race/ethnic categories defined by the census bureau to fall within any of the four segments. I will take advantage of this fact below to run models separately by race/ethnicity and segment to allow for a precise comparison of how the neighborhood attainment systems may operate differently for people of different race/ethnic backgrounds.

### Hypotheses

First, I hypothesize that at least one of the segment-specific models will be more accurate in predicting migration outcomes than the global model. Accuracy will be measured with the use of the root mean square of error (RMSE, details and formulas below). Models are estimated separately for each race/ethnic group, therefore, this hypothesis is tested 5 times. The null hypothesis would be that all of the four segments are less accurate than the global model. In other words, under the null they would have the same or larger RMSE when compared to the global model.

Second, I hypothesize that among the 4 segments there will be at least one individual attribute that has a different pattern of effects (again this is tested separately in 5 race/ethnic categories). Here the accompanying null hypothesis is that the patterns of all individual coefficients are the same in all 4 segments. Model coefficients will be considered different based on the pattern of positive, negative, and non-significant parameters on the individual covariates (e.g. education, income, and home ownership). On one hand this is a relatively weak null hypothesis because I am not specifying which parameter I expect to be different nor how much I expect it to differ. However, it could also be said to be a very severe test. Previous research shows that the U.S. social stratification system is overdetermined with individual attributes like race/ethnicity, education, and income. Furthermore, I have already admitted that the segments are operationalized with some inaccuracies. This "weak" hypothesis also amounts to a proposal that the segmented attainment system -- despite known measurement errors -- will be able to disentangle the overdeterminacy in the U.S. social stratification system. (In at least one instance.)

## Methods

The first subsection describes the census data and the data from the Modeling of Infectious Disease Agents Study (MIDAS) conducted by RTI International [@Wheaton2009]. The second subsection describes the Flickr data I used for defining neighborhoods. The third subsection describes the inclusion criteria I used for selecting ACS data for the analytical datasets, which was then modeled with linear mixed model that is explained in the fourth and final subsection.

### Demographic data

The American Community Survey is a random household survey conducted on a rolling basis by the U.S. Census Bureau. Each year data is collected on approximately 1.2 million households, and the annual samples are combined into 1-, 3-, and 5-year releases that cover different levels of geographic resolution. The ACS covers the household and individual demographic data that had previously been collected on the census "long form" prior to 2000. The survey questions include information about individual attributes like income and education along with questions about how long a household has lived at its current address, thus allowing me to infer recent migration history. All told, the demographic data is comparable to the PSID [@South2011b] and NLSY [@Massoglia2013] often used in neighborhood attainment research. I used the 2005-2009 5-year ACS data because this is the same data used by the MIDAS project.

The MIDAS project was conducted by RTI to develop demographic data with a geographical resolution down to individual addresses [@Wheaton2009]. Obviously, the U.S. Census Bureau does not release the addresses or precise locations of ACS respondents because of confidentiality and privacy concerns. However, the RTI research group wanted to develop models of disease transmission using accurate agent-based models, so they created "synthetic households" based on ACS data, dasymetric mapping, and established methods of iterative proportional fitting [@RTI2013]. The result is a database of 112 million synthetic households, which are replicates of the 6.5 million households found in the 2005-2009 ACS data. Each of the ACS households is repeated between 1 and 100 times in the synthetic data, so to create my data, I randomly selected one of the synthetic replicates for each ACS household and used it as the household location for my models. The use of a random draw from the MIDAS synthetic data could obviously introduce some measurement error into my conclusions. Therefore, I recreated 10 separate datasets (each with 6.5 million records), to test that my conclusions were robust to potential sources of error that could have arisen from the use of the MIDAS data. (Appendix ??? contains further details on ACS geographies like the PUMA and census tract estimates; the MIDAS methods of dasymetric mapping and iterative proportional fitting; and my results from the tests on robustness.)

The result of combining the ACS with the MIDAS synthetic households is that I have both the demographic and geographic resolution necessary for modeling the individual segments of my proposed segmented neighborhood attainment theory. The 2005-2009 ACS data contains information on more than 14 million individuals and 6.5 million households. The full sample is used to calculate the dependent variable of interest, namely, the percentage of the population in the neighborhood that is non-Hispanic white. This calculation is done using the individual sample weights published by the ACS. The MIDAS synthetic households are assigned to a census tract, so it is rather simple to aggregate everyone inside of a tract, and calculate the "percentage white" dependent variable. After calculating the DV, the data was further limited into the final analytical sample. Inclusion criteria are described below.

### Flickr data

The Flickr photo sharing service allows users to upload and tag their photographs. Users can tag their photographs with titles, descriptions, placenames, and geographic coordinates. By collecting all of the photographs tagged with a particular neighborhood and drawing a boundary around the geographic coordinates, we as researchers can see how Flickr users -- in aggregate -- define the neighborhoods where they take photos [@StraupCope2008]. I downloaded the set of the Flickr neighborhoods from [http://www.flickr.com/services/shapefiles/2.0/](). The polygons of Flickr-defined neighborhoods were created by Flickr programmers by applying an algorithm for alpha shapes to the individual latitude-longitude points of the photographs. (For additional details about turning points into polygons see Appendix 1.) Unlike census tracts, which are mutually exclusive, the resulting alpha shapes can overlap and leave gaps between neighborhoods. The gaps between neighborhoods and the overlapping neighborhoods are important methodological improvements  because they allow for more accurate operationalization of the way people understand neighborhoods in the real world.

\begin{figure}[htbp]
    \caption{Example of white flighter and gentrifier definitions based on Flickr neighborhoods.}
        \includegraphics[width=\textwidth, keepaspectratio=true]{flickr_hood_examples_20150503.pdf}
        \subcaption{Circle marked A is part of the white flight segment. Circle marked B is part of the gentrified segment. Solid, dotted, and dashed lines represent the boundaries of three different Flickr neighborhoods. All triangles would be part of either the striver or stuck-in-place segments.}
\end{figure}

In order to define the white flighters segment, I selected all households from the MIDUS data that fell outside all Flickr-defined neighborhoods. This was approximately 65\% of the final analytical sample. Gentrifiers were defined as the individuals that were in 2 or more Flickr neighborhoods. Figure 1 depicts a hypothetical example showing the creation of these two segments. It shows the same set of hypothetical household locations superimposed over census tracts in the left panel and Flickr-defined neighborhoods in the right panel. The household marked "A" is defined in the white flight segment, and the household marked "B" is defined in the gentrification segment. (Remember, gentrifiers must also meet the criteria for native-born and incomes above the sample's median.) Figure 2 depicts a map of Miami-Dade County that demonstrates the households identified as the white flight and gentrification segments. Notice that there is very little intermingling of the two groups, as would be expected. Individuals defined in the white flight segment seem to be located predominantly in the suburban ring, and gentrifiers are mostly in the central city. The departure from the overall trend, could either be errors in my methods of operationalizing the segments or they could be unique local neighborhoods captured by Flickr users. Either way, I suspect that the pattern in Figure 2 is a vast improvement over the global neighborhood attainment model. Households in every MSA have likewise been classified based on the Flickr-defined neighborhoods, although the results are not shown due to space limitations.

\begin{figure}[htbp]
    \caption{Example of individuals defined as white flighters and gentrifiers in Miami-Dade County. (n = 4615)}
    \includegraphics[width=\textwidth, keepaspectratio=true]{miami_segment_map_20150504.pdf}
\end{figure}

### Inclusion in analytical dataset

First, all 6.5 million head of households were selected from the ACS data. Generally speaking, all of the research on neighborhood attainment [e.g. @South1997; @South2011b] uses just the head of households in order to avoid double counting multiple adults from the same home. While the MIDAS data is formulated at the level of households, and ACS contains both household- and individual-level data, my final dataset uses the individual as the unit of analysis.

Second, only those individuals that moved within 12 months prior to the ACS survey were included. This left 781,366 people in the sample.

Third, I removed all individuals that were living in group quarters, which left 754,483 people.

Fourth, I excluded people that moved to rural locations. Limiting the sample to those that had moved into a county within in a census-defined metropolitan area (MSA) left 626,592 people. This exclusion criteria is necessary because the mixed models based on @South2011b use the MSA as a random intercept parameter (people outside of an MSA would be dropped by the model).

Finally, I include only those individuals that lived in a census tract with at least 10 other ACS households. The outcome variable is calculated as weighted percentage of the population in the white alone race/ethnic category. The  cutoff criteria for 10 ACS households is necessary because the ACS weighting data is not perfect, but it improves markedly as it is used in bigger aggregations. My choice of cutoff was based on the need to avoid any bias within the outcome variable, while not excluding all potential white flighters by using a cutoff that was too high. Individuals in the white flight segment tended to live in the most sparsely populated census tracts, so as I increased the cutoff criteria they were the individuals that were most likely to be excluded. The final analytical sample size was 459,602.

The analytical sample was then divided up into four segments per the definitions in the previous section. See Table 1 for a summary of the relative sample sizes of each segment by race/ethnic category.

### Analytical approach

The modeling approach is to use a linear mixed model with a random effect for the metropolitan area (MSA). The outcome variable is the percentage white in the census tract, and it would be ideal to set up a model with a logistic link function. I chose not to use a logistic link function (i.e. not estimate a *generalized* linear mixed model) because the simpler linear-in-percentages model gives us the added "advantage" of allowing for predicted percentages above 100 and below 0. In this context, it is an advantage to make these nonsensical predictions because it makes predicted values at the extremes just as likely to be right or wrong. A GLMM with a logistic link function will always be more accurate near the edges of the 0 to 100 span. All of these modeling decisions mirror the models used by @South2011b, although they chose to call it a hierarchical linear model in keeping with terminology from @Raudenbush2002. 

Also in keeping with @South2011b, I have estimated models separately for each race/ethnic group. This means that all model coefficients are estimated separately for five groups: white, black, Asian, other/multiple race groups, and Hispanic ethnicity of any race. Within the five groups, there are four separate models for each of the neighborhood attainment segments -- and one model for all segments combined. In total there are 25 models. All of the models predict the percentage *white* of each individual's census tract.  Ignoring for now the complication of separate models for race/ethnic groups and segments, the model can be written:

$y_{ij} = \alpha + u_{j} +  \beta x_{ij} + \epsilon_{ij}$

The $i$ is an index for each individual and the $j$ is for the MSA. In this notation, $u_{j}$ is the *random intercept* term for the MSAs and $\beta$ is a vector of *fixed effect coefficients* on the individual-level variables, $x_{ij}$. The $\alpha$, $\epsilon$, and $y$ are, respectively, the global intercept, the individual-level error, and the outcome variable. From a substantive point of view, the random effect of the MSA is a way to control average neighborhood racial composition between, e.g., New Orleans, Seattle and Des Moines. Since the model estimates fixed effects for the individual-level variables, we must assume that the effect of, e.g., having a college degree is the same in Pittsburgh and Miami. Future research could chose to relax this assumption and estimate *random slope* models by making a unique $\beta_{j}$ for each MSA.

I estimated this model in R (3.0.2) with the lme4 package [1.1.7; @Bates2014] and used the default REML criterion instead of the more common maximum likelihood criterion used in most GLM estimation. @Bates2010 [esp. 109] covers the details of REML, but to summarize: it is a two step procedure that estimates the variances of coefficients by first modeling just the random effects; it is unbiased; it does not return a model likelihood, and thus no likelihood ratio tests, AIC, BIC, nor coefficient p-values.[^AIC] To assess model performance I will rely on calculations of the root mean square error (RMSE). In addition the coefficient of variation of the RMSE is obtained by dividing the RMSE by the mean of the outcome variable:

$CV(RMSE) = \frac{RMSE}{\bar{y}}$

...where RMSE is defined as ...

$RMSE = \sqrt{\frac{1}{n}\sum\limits_{i = 1}^{n} (\hat{y_{n}} - y_{n})^2}$

The RMSE is preferred over other model fit statistics like AIC or $R^2$ in this case because it naturally takes on the scale of $y$ and ignores any differences in the total variance of $y$ between the models. By definition we would expect the different segments of the neighborhood attainment system to have different variances in the outcome variable (see Table 4). I have chosen a tool that will help to surface real differences while ignoring the differences that are definitional artifacts. In other words, we can think of CV(RMSE) as a quantification the average error in predicting $y$ divided by the average of $y$. (Where "average error" means the conditional error that results from a model controlling for MSA and individual-level variables.) The RMSE helps us understand if there are holistic differences in model performance between the segments. 

Let us walk through an example. Say 3 individuals moved into a neighborhood with 75% of the population in the white alone category, but based on those observations' MSA and individual covariates the model had predicted them to move into a census tract with a DV of 70, 75, and 80%. Then the errors would be -5, 0, and 5; the squared errors 25, 0, and 25; the mean squared error would be $50/3 = 16.7$; the square root of that is 4.1, so the RMSE is 4.1. If this example is drawn from the stuck in place segment, we could guess that the mean of the DV is around 55, and calculate the CV(RMSE) as $4.1/55 = .075$. These two statistics show us approximately how accurate the model is in predicting the DV. Also remember that the RMSE is in the units of the outcome variable, so it is the error measured in percentage points. The hypothesis tests use the RMSE and CV(RMSE) to determine if the segmented models are more accurate than the global model.

[^AIC]:
    Coming up with good methods for computing these values in (generalized) linear mixed models is a still a field of debate in statistics. At one point in the debate, Doug Bates suggested that he would rather be burned at the stake then implement naive methods for computing p-values (see: [https://stat.ethz.ch/pipermail/r-help/2006-May/094765.html]()). It seems that most statisticians agree that any of the extant methods are at best suspect, and the correct answer will almost certainly require Bayesian methods and MCMC sampling procedures [see @Bolker2009 for practical advice including a flow chart; see @Stroup2014 for simulation results].

To further understand how the different segments work, we have to look at the coefficients. Unfortunately our normal tools, such as Chow tests [@Chow1960] or likelihood ratio test with nested models [@Loehlin2004], are not available for the current task because the models within each segment are estimated on different data. The normal tools are made for testing models that have the same data but different parameters. To my knowledge there are no standard methods for testing for significantly different parameters among the segments, so I chose to use a simple comparison. I classified each parameter as non-significant, positive, and negative; different patterns will lead us to reject the null hypothesis. As you will have noted, I already mentioned that the current state of the field is still up in the air as to the correct way to determine p-values in this modeling context. Therefore I chose an extremely stringent criteria based on t-values, $|t| > 3.34$, which corresponds to a 2-tailed, $\alpha = .001$ in a normal setting.

??? Signposting: a) methods tell us if segmented models are more accurate; b) the null hypothesis is that the models are the same.

## Results

The breakdown of the segments across racial and Hispanic-origin groups is shown in Table 1. Two things are very clear in Table 1. First, as compared to the PSID data used in @South2011b we have many orders of magnitude more individuals in this dataset. Second, the relative distribution of race/ethnic groups across segments is not even. Individuals in the white alone category are least likely to be in the stuck-in-place segment. The people in the Asian alone category are less likely to be in the white flight segment. The black alone, Asian alone, and Hispanic groups are all relatively less likely to be in the gentrification segment.

\begin{table}[ht]
\small
\caption{Sample size by neighborhood attainment segment and race/ethnic category. (Row percentages)}
\centering
\begin{tabularx}{\textwidth}{l*{5}{r}}
  \toprule
& \shortstack{White \\ Flighters} & Gentrifiers & Strivers & \shortstack{Stuck-in-\\placers} & Total \\ 
  \midrule
White alone & 206,060 & 18,968 & 32,783 & 42,263 & 300,074 \\ 
   & (69) & (6) & (11) & (14) &  \\ 
\\
  Black alone & 35,364 & 1,380 & 2,811 & 11,578 & 51,133 \\ 
   & (69) & (3) & (5) & (23) &  \\ 
\\
  Asian alone & 11,571 & 862 & 8,689 & 4,422 & 25,544 \\ 
   & (45) & (3) & (34) & (17) &  \\ 
\\
  Other/multiple race & 6,930 & 648 & 1,107 & 2,529 & 11,214 \\ 
   & (62) & (6) & (10) & (23) &  \\ 
\\
  Hispanic, any race & 38,632 & 1,960 & 4,062 & 19,125 & 63,779 \\ 
   & (61) & (3) & (6) & (30) &  \\ 
   \bottomrule
\end{tabularx}
\end{table}

Tables 2 and 3 display the sample statistics broken down by neighborhood attainment segments and race/ethnic categories. In table 2 we see that gentrifiers tend to be the highest earning segment and those that are stuck in place are the lowest. White flighters are more likely to be married, own their home, and have larger families. 

\begin{table}[htp]
\caption{Summary statistics by neighborhood attainment segments.}
\centering
\begin{tabularx}{\textwidth}{r*{4}{c}}
  \toprule
& \shortstack{White \\ Flighters} & Gentrifiers & Strivers & \shortstack{Stuck-in-\\placers} \\ 
  \midrule
N & 298,557 & 23,818 & 49,452 & 79,917 \\ 
  Census tract \% white alone & 67 & 62 & 60 & 54 \\ 
  Age, 18-29 (\%) & 34 & 38 & 44 & 43 \\ 
  Age, 30-39 & 24 & 31 & 28 & 21 \\ 
  Age, 40-49 & 18 & 14 & 13 & 16 \\ 
  Age, 50-59 & 12 & 10 & 8 & 10 \\ 
  Age, 60+ & 12 & 6 & 7 & 10 \\ 
  Female (\%) & 49 & 46 & 47 & 52 \\ 
  Married (\%) & 43 & 35 & 36 & 29 \\ 
  Number of Children & 0.66 & 0.27 & 0.32 & 0.56 \\ 
  Home Owner (\%) & 37 & 31 & 30 & 18 \\ 
  HH members per bedroom & 0.73 & 0.66 & 0.67 & 0.81 \\ 
  Education (median) & 13 & 16 & 16 & 13 \\ 
  Income (\$) & 53,989 & 99,959 & 69,814 & 33,546 \\ 
  Employed (\%) & 73 & 89 & 81 & 68 \\ 
   \bottomrule
\end{tabularx}
\end{table}

In table 3 we see the results of the U.S. racial system that has been widely reported in the sociological literature. People in the white category live in the whitest census tracts, have the highest home ownership rates, and have the smallest family sizes. It is notable that the black alone category is 62% female, but perhaps this is not as surprising when we consider the epidemic of incarceration among African-American males. People in the Asian alone category are most likely to be married, have the highest incomes, and have the highest level of education attainment.

\begin{table}[htp]
\caption{Summary statistics by race and Hispanic origin.}
\centering
\begin{tabularx}{\textwidth}{r*{5}{c}}
  \toprule
 & \shortstack{White \\ alone} & \shortstack{Black \\ alone} & \shortstack{Asian \\ alone} & \shortstack{Other/\\multiple \\ race} &\shortstack{Hispanic,\\ any race} \\ 
  \midrule
N & 300,074 & 51,133 & 25,544 & 11,214 & 63,779 \\ 
  \shortstack{Census tract \\ \% white alone} & 72 & 43 & 54 & 59 & 46 \\ 
  Age, 18-29 (\%) & 37 & 33 & 35 & 41 & 39 \\ 
  Age, 30-39 & 22 & 27 & 35 & 25 & 30 \\ 
  Age, 40-49 & 16 & 21 & 16 & 16 & 17 \\ 
  Age, 50-59 & 12 & 13 & 8 & 10 & 8 \\ 
  Age, 60+ & 13 & 8 & 6 & 7 & 5 \\ 
  Female (\%) & 48 & 62 & 38 & 54 & 46 \\ 
  Married (\%) & 39 & 25 & 54 & 34 & 45 \\ 
  Number of Children & 0.47 & 0.79 & 0.53 & 0.64 & 0.95 \\ 
  Home Owner (\%) & 37 & 18 & 31 & 23 & 25 \\ 
  \shortstack{HH members \\ per bedroom} & 0.67 & 0.76 & 0.81 & 0.78 & 0.98 \\ 
  Education (median) & 13 & 13 & 16 & 13 & 12 \\ 
  Income (\$) & 59,582 & 37,316 & 66,815 & 44,192 & 41,450 \\ 
  Employed (\%) & 74 & 70 & 76 & 71 & 76 \\ 
   \bottomrule
\end{tabularx}
\end{table}

Table 4 shows the model statistics for the 25 models. Hypothesis 1 is analyzed with the RMSE and its coefficient of variation, but table 4 also contains the mean and variance of the dependent variable for comparisons. We can see that each race/ethnic category has at least one segment-level model that outperforms its respective global model. Remember I am using the criteria that a model has a lower RMSE *and* CV(RMSE) to say that it is more accurate. In support of the first hypothesis, a segment is preferred over the global model (in at least one segment) for all racial and ethnic groups in my dataset. The patterns of the well performing segments are interesting as well. For the white alone category, the white flight segment has the most accurate model. For the black alone category, both the gentrifier and the striver segments outperform the global model. For the Asian alone group, all segments except the stuck-in-place segment have more accurate models than the global model. In the other/multiple race category, the white flight segment is the only one that outperforms the global model. And finally for people of Hispanic origin, the white flight and the gentrifier segments are improvements over the global model. Interestingly, the stuck-in-place segment does not meet my criteria for preferred models in any of the race/ethnic categories. Although, for the black, other/multiple, and Hispanic categories it does at least show a lower RMSE (just not a lower coefficient of variation). This lack of model improvement probably stems from the fact that stuck-in-place individuals were defined as the residual population after having operationalized the other three segments. The operational procedure probably means that there is more multivariate noise (heterogeneity) in this segment than the other three segments, and thus the stuck-in-place segment is less accurate.

\begin{table}[htp]
    \small
    \caption{Model comparisons. Outcome variable is the percentage white in the census tract. All models are estimated with an MSA random intercept and the same 9 individual covariates. (See Table 1 for sample sizes in each model.)}
    \centering
    \begin{tabularx}{\textwidth}{lrrrr}
    \toprule
    Race by segment & RMSE & CV(RMSE) & \shortstack{Mean \\ \% white} & Var(\% white) \\ 
    \midrule
       White alone & & & &  \\
       \quad Global model & 15.29 & 0.21 & 71.87 & 3.88 \\ 
       \quad White Flighters & 14.31 & 0.19 & 74.83 & 3.56 \\ 
       \quad Gentrifiers & 16.47 & 0.25 & 64.89 & 3.58 \\ 
       \quad Strivers & 16.56 & 0.25 & 65.66 & 3.90 \\ 
       \quad Stuck-in-placers & 16.13 & 0.25 & 65.41 & 4.20 \\ 
       \\
       Black alone & & & & \\
       \quad Global model & 22.02 & 0.51 & 42.90 & 6.61 \\ 
       \quad White Flighters & 22.27 & 0.51 & 43.88 & 6.90 \\ 
       \quad Gentrifiers & 19.54 & 0.45 & 43.31 & 4.99 \\ 
       \quad Strivers & 19.84 & 0.44 & 44.93 & 5.66 \\ 
       \quad Stuck-in-placers & 20.25 & 0.51 & 39.37 & 6.00 \\ 
       \\
       Asian alone & & & & \\
       \quad Global model & 17.64 & 0.33 & 53.57 & 5.20 \\ 
       \quad White Flighters & 17.07 & 0.29 & 58.35 & 5.09 \\ 
       \quad Gentrifiers & 17.22 & 0.32 & 53.76 & 4.90 \\ 
       \quad Strivers & 17.42 & 0.34 & 51.18 & 4.70 \\ 
       \quad Stuck-in-placers & 17.65 & 0.39 & 45.72 & 5.23 \\ 
       \\
       Other/multiple alone & & & & \\
       \quad Global model & 17.99 & 0.30 & 59.22 & 5.50 \\ 
       \quad White Flighters & 17.34 & 0.28 & 62.75 & 5.52 \\ 
       \quad Gentrifiers & 17.14 & 0.32 & 53.65 & 4.48 \\ 
       \quad Strivers & 18.29 & 0.33 & 54.91 & 4.66 \\ 
       \quad Stuck-in-placers & 17.52 & 0.33 & 52.88 & 5.18 \\ 
       \\
       Hispanic, any race & & & & \\
       \quad Global model & 18.87 & 0.41 & 45.91 & 6.24 \\ 
       \quad White Flighters & 18.37 & 0.38 & 48.45 & 6.53 \\ 
       \quad Gentrifiers & 18.66 & 0.37 & 50.04 & 4.75 \\ 
       \quad Strivers & 19.07 & 0.39 & 48.72 & 5.49 \\ 
       \quad Stuck-in-placers & 18.51 & 0.47 & 39.76 & 5.41 \\ 
   \bottomrule
\end{tabularx}
\end{table}

Table 5 shows the pattern of coefficients in all of the segment-level models (omitting the global model). Given that the first hypothesis is supported, and we have evidence that segmented attainment leads to some improvements in model prediction, we now want to know what are the important differences between these segments? When scanning across this table we can see that a number of variables have both positive and negative signs: Age 50-59, Age 60+, Married, Number of children, and Education. The income variable is the most consistently positive coefficient, although there are models where it is not significant. Conversely, the dummy variables for gender and employment status are only significant in one model. The two lower age groups are only significant in one model as well. 

When scanning down the columns of Table 5, within a race/ethnic category, we see a few patterns. There are very few significant coefficients in the other/multiple race alone group. For people of Hispanic origin, the number of children and education variables are significant through every segment -- which is not the case for any other race/ethnic category. For people in the white alone category and classified as stuck-in-placers, the home ownership dummy variable significantly predicts living in more white census tracts. Home ownership is not significant for the stuck-in-place segment for any of the other race/ethnic groups. 

\begin{sidewaystable}[htp]
\tiny
\parnoteclear
\caption{Coefficients for models\parnote{Outcome variable is the percentage white of the census tract. Models contain a random intercept for the MSA.} in each segment.}
\centering
    \begin{tabular}{r *{5}{ >{\hspace{.4cm}}cccc<{\hspace{.4cm}} }}
        \toprule
        & \multicolumn{4}{c}{White alone} & \multicolumn{4}{c}{Black alone} & \multicolumn{4}{c}{Asian alone} & \multicolumn{4}{c}{Other/multiple} & \multicolumn{4}{c}{Hispanic} \\ 
        \cmidrule(lr){2-5} \cmidrule(lr){6-9} \cmidrule(lr){10-13} \cmidrule(lr){14-17} \cmidrule(lr){18-21}
        Segments:\parnote{wf = White Flighters; g = Gentrifiers; sv = Strivers; in = Stuck-in-placers} & wf & g & sv & in & wf & g & sv & in & wf & g & sv & in & wf & g & sv & in & wf & g & sv & in \\ 
        \midrule
        Age, 30-39\parnote{Excluded category is Age, 18-29.} & + &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  \\ 
        Age, 40-49 & + &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  \\ 
        Age, 50-59 & + &  &  &  &  &  & - & - &  &  &  & - &  &  &  &  &  &  &  &  \\ 
         Age, 60+ & + &  & + & + &  &  &  &  & + &  &  & - &  &  &  &  & + &  &  &  \\ 
         Female &  &  &  &  & - &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  \\ 
         Married & + & - &  &  & + &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  \\ 
        Number of Children & + &  &  &  &  &  &  & - &  &  &  & - &  &  &  &  & - & - & - & - \\ 
        Home Owner & + &  &  & + & + &  &  &  & + &  &  &  &  &  &  &  & + &  &  &  \\ 
        Per bedroom & - &  &  & - & - &  &  & - & - &  & - &  & - &  &  &  & - &  & - & - \\ 
         Education\parnote{Education is the imputed number of years of formal education. Modeled as a continuous variable.}  & - & + &  & + & + &  &  & + & + &  & + & + &  &  &  &  & + & + & + & + \\ 
        Income\parnote{The greater of the household or personal income. Adjusted for inflation.}  & + & + & + & + & + &  & + & + & + & + & + &  & + &  &  & + & + & + & + & + \\ 
        Employed &  &  &  &  &  &  &  & + &  &  &  &  &  &  &  &  &  &  &  &  \\ 
        \bottomrule
    \end{tabular}
    \parnotes
\end{sidewaystable}

## Discussion

The primary hypothesis is well supported because there is at least one neighborhood attainment segment with lower RMSE-based indicator than the global model. This means that within each race/ethnic category, there is at least one segment that can more accurately predict neighborhood attainment than the global model. If we use the lowest CV(RMSE) to define the "best" model for each race/ethnic category, we see some trends that correspond to previous research. People in the white alone group are most accurately modeled in the white flighter segment. The striver segment is the best model for the black alone category. People in the Asian alone and the other/multiple category are also most accurately modeled within the white flighter segment.[^Asian] And people of Hispanic origin are most accurately modeled in the gentrifier segment. Perhaps the last point is the most intriguing because we usually think of gentrification as a process driven mostly by wealthier, white people. This result probably arises because gentrified neighborhoods and ethnic enclaves are difficult to disentangle in the current data. However, Table 4 also shows us that the gentrifier segment in people of Hispanic origin has the highest mean of the outcome variable and the lowest variance, therefore, the gains in model accuracy are probably not an artifact of accidentally capturing ethnic enclaves. It seems that there is something about my definition of gentrification that is applicable to the neighborhood attainment experience of people of Hispanic origin.

[^Asian]:
    To date, I am not aware of any research that explicitly looks at Asian ethnicities or people of multiple races in terms of their migration patterns relative to predominantly African-American or white neighborhoods. @Pais2009 specifically noted that small samples prevent this analysis in the PSID data. Thus, I can't say for sure if this finding is congruent or incongruent with previous research.

I rejected the first null hypothesis based on direct comparison of the values of RMSE and CV(RMSE), however, we are usually more accustomed to accepting or rejecting hypotheses based on p-values that tell us if the two values are *significantly* different. Unfortunately, this isn't as easy in the mixed modeling framework. I conducted a follow-up analysis by doing naive bootstrap draws from the dataset and calculating RMSE and CV(RMSE), and this procedure suggested that a difference of about .5 (or .012 for the coefficient of variation) would probably be a significant difference in my data.[^exact] But caution is warranted in applying this rule-of-thumb because of the nested and unbalanced nature of my data -- i.e. there are not the same number of individuals in each race/ethnic group, MSA, or census tract. The unbalanced nature of the data means that naive bootstrap samples are not conclusive tests, and the current state of the art in the statistical literature is still debating what to do in this situation.  

[^exact]:
    I did 100 bootstrap draws of size equal to 10% of the total size of the sample within the race/ethnic group. After running a model for each bootstrap draw, I saved the RMSE and CV(RMSE) and calculated the standard deviation of these two distributions. Assuming a normal distribution for the bootstrapped RMSE parameters -- which, by the way, there is no evidence for this assumption -- we can calculate rough estimates for how big a difference would have to be in each of the race/ethnic groups by doubling the standard deviation. First for RMSE: white = .19; black = .40; Asian = .53; other/multiple = .85; Hispanic = .28. Then for CV(RMSE): white = .003; black = .012; Asian = .013; other/multiple = .017; Hispanic = .009. 

The second hypothesis, that the coefficients would show different patterns between the segments, has partial support. Certainly, Table 5 shows us that the patterns of coefficients are not exactly the same across all models. However, it is perhaps too easy to reject the null hypothesis that all coefficients will be the same across models. Indeed, most of the difference in Table 5 are between positive/negative signs and blank spots. Remember that the blank spots exist in the table where the absolute value of the t-value is less than 3.34, and this is my own cutoff criterion. Blank spots in Table 5, therefore, are not enough evidence to reject the null hypothesis with confidence. There is one important example where a coefficient switched from negative to positive: for education in the white alone category. A quick follow-up analysis is called for to understand if the sign-switching on education is a important finding.

In the white flight segment, among people in the white race/ethnic group, the coefficient for education is negative. This is different from most previous research, which shows consistent positive effects between educational attainment and job market and neighborhood outcomes [@South2011b, 1282, Table 4]. When neighborhood attainment is modeled as a single system, this finding is swamped by the overall differences between white and non-white neighborhood attainment. Table 6 shows one reason for this novel finding: while there are  more people in the white flight segment with college degrees (n = 46,220) than there are in the gentrifier segment (n = 8,630), the white flighter is only about half as likely to have a college degree when compared with the gentrifier. White people that move to areas outside of Flickr-defined neighborhoods (i.e. the white flight segment), have lower educational attainment than those that live in areas defined with 2 or more neighborhoods. Usually, more suburban neighborhoods are deemed more advantageous than central city neighborhoods, so in this case we have a paradox that lower educational attainment is associated with the traditional definition of higher neighborhood attainment. This is only a paradox, however, if the model insists on estimating *the* effect of education in the neighborhood attainment system. If we use a segmented attainment model, the paradox goes away as we can see that eduction may have different effects in different segments of the system. Two other variables that may exhibit interesting patterns like this are the marriage variable in the white alone category and the home ownership variable. 

\begin{table}[htb]
\caption{Detail of educational attainment in white alone category and White flight and Gentrification segments.}
    \centering
    \begin{tabularx}{\textwidth}{r*{3}{d{2}}}
    \toprule
        & \multicolumn{1}{c}{White flighters (1)} & \multicolumn{1}{c}{Gentrifiers (2)} & \multicolumn{1}{c}{Ratio 1:2} \\ 
    \midrule
      No HS diploma & 7.71\% & 1.12\% & 6.88 \\ 
      \\
      High school & 23.15 & 6.44 & 3.59 \\ 
      \\
      Some college, no degree & 27.34 & 13.42 & 2.04 \\ 
      \\
      Associate's degree & 8.58 & 5.34 & 1.61 \\ 
      \\
      Bachelor's degree & 22.43 & 45.50 & 0.49 \\ 
      \shortstack{Master's, Professional \\ or PhD degree} & 10.78 & 28.18 & 0.38 \\ 
   \bottomrule
\end{tabularx}
\end{table}

Home ownership shows important differences across race/ethnic groups and segments. The results in Table 5 would suggest that white stuck-in-placers are more likely to live in whiter census tracts if they own their own home. Conversely, home ownership does not seem to have a significant effect on the outcome for the other 4 race/ethnic groups. This conclusion tends to support the findings of @Fischer2014 that "homeownership may not be the ticket to upward mobility that it has traditionally been for other groups, particularly whites [-@Fischer2014, 29]." This finding is only possible when segmenting the neighborhood attainment models because we see that home ownership is positive in the white flight segment but not in the stuck-in-place segment.[^global]

[^global]:
    The t-values for the (unreported) global models for home ownership for white, black, Asian, other/multiple, and Hispanic groups are, respectively: 23.56; 6.06; 6.41; 3.25; 4.28; 5.90. In summary, home ownership is positive and significant in the global models for all race/ethnic groups except Asian alone.

Taken together the support for these two hypotheses suggest that there is a segmented neighborhood attainment system at work in U.S. cities. If we as social scientists, continue to model neighborhood attainment assuming all the individuals in our dataset are moving through the same system, we run a very high risk of having misspecified models and misinterpreting the direction and significance of the estimated coefficients. My ability to distinguish the segments is based on new data available from the ACS, MIDAS, and Flickr neighborhood definitions. My methods for assigning the segments are rudimentary, but this is an area that should be further explored with refinements for identifying the places (exurbs, inner-ring suburbs, gentrified neighborhoods, ethnic enclaves, etc.) and the people (single professionals, retirees, multi-generation families, previously incarcerated, etc.) that are constrained to certain paths of attainment in the segmented neighborhood system. There are also many caveats that I've mentioned throughout this paper that arise from the ambiguity of mixed models. Given the rapid development of mixed models over the last 15 years, though, I am confident that our colleagues in statistics and other quantitative fields will solve the theoretical problems and give us a new crop of useful tools for exploring our nested, grouped, unbalanced, heteroskedastic data with (generalized) linear mixed models. 

Sociologists should concentrate on coming up with the theory and operationalizations of the segments. I think that geotagged social media data (sometimes called volunteered geographic information or VGI [e.g. @Elwood2012]), will allow us to finally define socially meaningful and accurate neighborhoods that can replace census tracts as the default spatial unit in sociology. Many issues still exist, however, in terms of the representativeness of VGI and the challenges of combining census data with it, but these are tractable research problems that can eventually be conquered with methodological improvements like bias correction and data interpolation. In regards to the future research needed for neighborhood attainment segments, I think additional work needs to be done on defining gentrifiers. The work of Richard Florida [-@Florida2002], has a number of problems, but the basic idea of identifying a class of people based on their occupational categories may be useful for this problem. Gentrification also has a cultural and built environment element, and these are what I was trying to capture with my use of overlapping Flickr neighborhoods, but this is a crude measure. Perhaps occupational data could be combined with data from zoning laws (given that residential lofts often replace industrial uses), real estate listings (given that agents may try to capitalize on "hip" neighborhoods), and changes over time in the geotagged social media data (given that gentrification often dies when it has successfully gentrified a neighborhood). Likewise, the concept of stuck-in-placers is based on well-known constraints on people from a web of cultural, economic, intergenerational, and geographic disadvantage [@Wilson1990; @Sampson2012; @Sharkey2014]. However, operationalizing this segment is a challenge. Being stuck in place is something different from being poor because is combines a bundle of negative attributes within a place that has a history of disadvantage. There is often a dearth of individual-level data available that can help us operationalize the experience of being stuck in place beyond the usual demographic variables that we use to measure racism, family structure, and income. In the current paper stuck-in-placers were defined as the residual sample after defining the other three segments, but this also misses Sharkey's  main point that it is not just the people but the disadvantaged places which suggests "the American ghetto appears to be inherited [-@Sharkey2014, 20]." I think future research could combine VGI with census data to help define the socially relevant boundaries of places that have generational histories of disadvantage, and the people that are stuck in these types of places.

The newly proposed segmented neighborhood attainment theory has many inspirations in the literature on assimilation, and the empirical results in this paper show it is an important improvement for our understanding of neighborhoods. Additional research needs to be invested into mixed models and the operationalization of the segments, but there are clear routes forward on both of these paths.

# Conclusions

The purpose of this chapter is to review my findings in light of broader questions about neighborhood effects and the future possibilities of research with social media. Taken together, my three empirical chapters show that social media-based neighborhoods are a robust and substantively important contribution to spatial social science. Many improvements and refinements are still needed, but sociologists should no longer use census tracts to define neighborhoods based on the weak justification that there are no other alternatives. I made this argument by first showing in chapter 2 that the polygons around Flickr neighborhoods are robust to the presence of tourists, images lacking place-referenctial content, and photographs with low engagement 
among Flickr users. In other words, the neighborhood boundaries defined by Flickr are not obviously wrong. In chapter 3, I showed that Flickr neighborhoods had some desirable qualities in a spatial lag model of homicides in Chicago. Compared to PHDCN-defined neighborhoods, Flickr had lower model residuals and more between-neighborhood variance, which showed they changed the results of the model. Finally, in chapter 4, I took advantage of a unique feature of Flickr-defined neighborhoods -- namely, that they can be operationalized in a way that does not require them to be mutually exclusive nor extensive -- to build a new theory of segmented neighborhood attainment. The segments themselves (white flight, gentrification, etc.) need further refinement, but this demonstrates that neighborhoods based on social media can open new avenues for theorizing spatial demography which have been previously closed off because of the implicit assumptions of the census tract.

The neighborhood effects literature has long been looking for a better way to define neighborhoods [@Sampson2002, 445], and social media is one promising avenue forward. Flickr is a good example of social media data because of it's global coverage, it's fine-grained geographic identifiers, and at least some of the images in Flickr are about places. Social media will give social scientists the ability to operationalize neighborhoods more closely aligned to their theories of sociologically meaningful places. The chapters of this dissertation have demonstrated new ways of doing this with publicly available data.



In Chapter 2, I used a random selection of geotagged photographs from the Phoenix area to compare Flickr-defined neighborhoods to the official neighborhood boundaries set by the city planning department. Flickr neighborhoods were shown to be spatially distinct from the official neighborhoods. Moreover, I measured three sources of potential bias and found that in almost all neighborhoods the bias was smaller than the substantive difference between Flickr and administrative boundaries. I grant that Flickr users are not representative of the general population, however, the people responsible for Phoenix's official neighborhood boundaries and the people responsible for defining census tracts are not representative the general population either. Since all available definitions of neighborhoods will probably fail to be representative, we can look at other criterion -- such as the "different" and "robust" standards I wrote about in chapter 2 -- to make useful determinations about the validity of neighborhood definitions.

In Chapter 3, I engaged with the old problem of the modifiable areal unit, which has been around for decades. Flickr-defined neighborhoods exemplify two of the approaches set out by @Jelinski1996 [136] for dealing with the MAUP. First, they are not "modifiable" in the sense that they can be recombined in arbitrary aggregations like census tracts. Flickr-defined neighborhoods are more sociologically meaningful than census tracts. Second, I used an empirical example from homicide data in Chicago to demonstrate that neighborhoods from the Project on Human Development in Chicago Neighborhoods (PHDCN) do not produce lower model residuals than Flickr neighborhoods. In other words, Flickr neighborhoods are no more sensitive to the MAUP than the neighborhood definitions carefully crafted by experts at the PHDCN. These two approaches combine to strongly suggest that Flickr-defined neighborhoods are an important advancement for dealing with the MAUP.

In Chapter 4, I proposed a new theory of *segmented* neighborhood attainment by which I simply mean that not all people experience the same system of attainment when they move among urban neighborhoods. Unlike census tracts, Flickr-defined neighborhoods can overlap and leave gaps in between. I leverage this novel characteristic to operationalize "white flighters" as the people that have moved to areas outside of all (Flickr) neighborhoods; and "gentrifiers" as the people that moved to areas that are contained in 2 or more (Flickr) neighborhoods. With these new operationalizations in hand, I show that models based on segmented neighborhood attainment theory outperform the existing models based on a global attainment theory. My conclusion in chapter 4 re-emphasizes the overarching theme: the methods we use to define neighborhoods has important theoretical and conceptual implications for the way we do neighborhood effects research.

With these points in mind, let me conclude with some broader comments; first on neighborhoods, and then on social media.

## Conclusions about neighborhoods

To reiterate, neighborhoods are both stronger and weaker than other institutions. They are stronger because of multi-generational influences and far-reaching implications for multiple domains of life (e.g. health, education, and employment). They are weaker because there are fewer formal mechanisms for neighborhoods to exert power; neighborhoods don't usually have powers to tax or police, but housing associations and developers can often control many aspects of the built environment. Since neighborhoods occupy this unique position within the array of social entities, we need improved tools and methods for doing neighborhood effects research.

The tools introduced in this dissertation help in three regards. First, we can see that there are indeed alternatives available to census tracts. Past reviews of neighborhood effects [@Durlauf2004; @Dietz2002; @Sampson2002] have all concluded that researchers use census tracts or administrative units out of convenience and give very little conceptual attention to the neighborhood units themselves. This dissertation has proven that there is an alternative, it is based on publicly-available data, it can be manipulated to fit multiple research projects (chapter 3 versus 4), and there is some reason to believe that Flickr neighborhoods are sociologically meaningful. 

Second, the conclusions in chapter 3 suggest that in addition to looking for model fit criteria or the coefficients on the variables of interest, we need to also pay attention to the overall variance of the dependent variable. @Openshaw1984 [34] proposed a truly radical idea: instead of taking spatial units as given and trying to model patterns in the data, we should take the patterns in the data as given (e.g. assume that homicide counts in Chicago arise from an over-dispersed Poisson distribution) and try to model the spatial units. Then instead of accepting/rejecting hypotheses based on t- or p-values, we would determine if our assumptions about the data generating method are accurate based on how closely we can recreate spatial units that match our pre-conceived notions of neighborhoods. I doubt if social scientists will ever take Openshaw's ideas seriously, but as mid-range solution, we can at least estimate how much variance there might be in the dependent variable given alternative (perhaps random) spatial units. In chapter 3, e.g., is the variance of 24,442 based on Flickr neighborhoods more likely to be correct than the variance of 6483 based on Sampson's neighborhoods? What we need to answer this question is a tool (much like Openshaw's AZP [-@Openshaw1984, 21]) to divide Chicago up into spatial units, calculate the variance, and then repeat the procedure to estimate the synthetic distribution of variance. Then we could make an educated guess if 24,000 or 6,000 is more likely to be correct.

Third, neighborhoods are not everywhere. Before quantifying the effect of the neighborhood, social scientists need to put in considerably more work to argue that neighborhoods exist. More precisely, when we use individual level data, we should first try to see if a neighborhood exists around some/all/none of the individuals in the dataset. The results of chapter 4 rest entirely on the novel Flickr definitions which can leave gaps between neighborhoods.[^gaps] The methods used in that chapter could be applied to many projects -- even if they are based on census tracts or existing data sources -- to create a simple dummy variable to control for whether or not people are in sociologically meaningful neighborhoods.

[^gaps]:
    See Appendix 1 for more details about the alternative methods for turning point-data, like photographs, into polygon-data, like neighborhoods. Some of the methods leave gaps between neighborhoods and some do not.

There are at least two major tools that sociologists need, which I have not even begun to explore. First, it is common to note that spatial social science is often hindered by a lack of good theory and methods for defining spatial weight matrices [@Bivand2008, 250]. @Sampson2012 [chp 13] is a great start as is @Gould1991 as they both use human behavior, specifically communication, to operationalize the strength of ties between places. What these works have in common is the use of "auxiliary" information to define the weight matrix. By auxiliary, I mean information that is not included as independent nor dependent variables, and information that is not part of the definition of the geographic units. Using auxiliary information to define connections is superior to using proxies like distance or contiguity for defining connectivity. While I did not use the approach in my dissertation, the Flickr neighborhoods could be seen as one type of "auxiliary" information and used to define a weighting matrix between census tracts. Other social media platforms (RunKeeper,[^runkeeper] and Foursquare, e.g.) may be even more useful for providing auxiliary information because they are designed to track and capture certain behaviors like jogging or dining out. Aggregating this type of tracking data may allow for methods to define spatial weight matrices, which more directly operationalize human behavior [@Matthews2011]. Indeed, this might be the place where Flickr (or other social media data) will become the most widely used within neighborhood effects research -- as cheaply available auxiliary information that can be incorporated into many different types of spatial analysis.

[^runkeeper]:
    Aggregating the traces of multiple people jogging in a city shows interesting patterns about dis/connected places within the city. See http://flowingdata.com/2014/02/05/where-people-run/. Obviously, there are issues with the representativeness of the data based on who uses the RunKeeper service (and who goes running), but it's not clear to me if the lack of representativeness is worse than using simple contiguity to define spatial weight matrices.

The second challenge is to better understand neighborhood change. Granted, one of the aspects that makes neighborhoods unique is their relative stability even in the face of cultural and technological change. However, we do know that temporal processes like gentrification [@Zukin2010], increasing diversity in the suburbs [@Massey2009], and the housing collapse of 2008 [@Fischer2014] can have important influences on the built environment and many of the social aspects of neighborhoods. Understanding temporal dynamics of neighborhoods has begun in the work of Elwert and colleagues [@Sharkey2011; @Wodtke2011]. However, in this research the neighborhood changes only in its relative attributes of socio-economic disadvantage. Existing tools can not measure changes in the cachet or aspirational features of a neighborhood, and these may be particularly important understandings of neighborhood attainment. Perhaps the methods of ecometrics suggested by @Raudenbush1999 would be useful in understanding the changes of neighborhoods, however, this approach will be very labor intensive. I would recommend a combination of ecometrics and data mining from real estate listings, social media, and satellite imagery to come up with a tool for measuring neighborhood changes. The data mining techniques could be validated against ecometric methods and simplified through well-known scale construction techniques [@Dawis1987].

I would have loved to had all or any of these tools on hand while beginning this dissertation. I am sure many other researchers in the field would find them useful as well. They would surely improve the quality of neighborhood effects research by improving both its methods and theory.

## Conclusions about social media

It is easy to critique social media from the point of view that it is a poor substitute for survey data. Social media data may be cheap to acquire, cover parts of daily life that are usually closed off to researchers, and have a much finer time scale than other forms of data colection; surveys surely excel in terms of representativeness, standardized questions, comparability between subjects, and reproducibility. I argue that another, possibly more valid, analogy could be drawn between social media and the long history of content analysis within social sciences. Instead of thinking of tweets, posts, photos, and videos as biased survey samples, we should instead think of them as large and diverse sets of "media." In the sense that a Youtube clip is like a television show (or a TV commercial), we can bring in the methods usually used for content analysis to help us study social media. The rest of this section will develop two arguments. First, I will summarize the history of the development of survey research. Even for social scientists that do not actively use surveys in their research, this history is important because it largely frames the norms and practices of modern social science research. By looking at the history of surveys, I suggest the direction social media reserach could take over the next few decades. The second part of this section, will further develop the analogy between social media and content analysis. While I am not an expert in either survey methodology nor content analysis, my personal experience with social media research gives me a useful point of view to peer into both of these camps.

Turning first to surveys, ...

Now turning to the analogy between content analysis and social media research...

Social media is more closely related to content analysis done on newspapers [@???], personal communications [@??? thomas and zaneicki], or even citation networks among interdisciplinary scholars [@???]. When I say that social media is more analogous to content analysis, what I mean is that the important element is what is in the content, how the nodes of content relate to one another, and what we can learn from the metadata. These three points stand off a bit from the usual elements found in survey research such as representation of a population characteristic, relationships between attitudes, or sub-group differences. 

In the historical treatments of survey research [@Groves2011; @Converse1987] it is common to break up their development into three stages: early pre-World War II efforts that often resembled community studies more than modern surveys, the post-World War II golden age, and the period of decline tied to declining response rates after about 1980. The point of this brief history lesson is only to demonstrate that survey research is the outcome of policies and actions, not an epistemological cornerstone of sociology. Just like survey research was nurtured, funded, and improved through iterations; social media research could take a similar path.

Any analysis that uses social media data does not have any of the standard tools developed for surveys, but that does not mean social media is any less valid in a statistical or sociological sense. First let's think about social media as a data collection system. Here we see that it, rather than serving as a sample from a population, is much more like observational research or historical research with primary sources. There are well-known methods for sampling and guarding against bias, which we can borrow from qualitative research [@Geddes1990; @Lucas2014], so I think some of the criticism of social media is simply a misplaced desire to make every study in sociology into a survey. Furthermore, social media is much more likely to be in situ data than are surveys. One of the long-standing, and never fully answered, questions about survey research has to do with the "survey effect." Do the participants in the surveys have the thoughts, opinions, memories, etc. in their mind during normal life? Or, is it possible that some survey participants have never thought about the topic of the survey for one second, yet, when asked to proofer a response, are willing and able to respond as if the question held real meaning to them [@Schaeffer2005]? 

To continue to build up social media research, so that some day it may be as good as the current survey methods, I think we would need to address three shortcomings in the field of sociology.

#### Pedagogy

In order to prepare a new generation of students to use social media data, we would need to change the curriculum around hypothesis testing and random variable statistics. Not that they should be abandoned, but simply that they should be offered as just one way of doing quantitative sociology. Bayesian methods, semi- and non-parametric modeling, and bootstrapping methods should also be included in basic quantitative training. Most importantly, curriculum should be changed to stress the underlying logic of random variables -- i.e. sociologists are not interested in p-values or t-values per se, but we are interested to know if the observed patterns in the data are likely to be seen "by chance." When we have statistical evidence that the patterns are not from chance, we call them "significant." This same logic can be easily applied to other forms quantitative analysis, but students must know that the definition of "by chance" is not necessarily a p-value greater than .05, and that they may have to work to come up with other reasonable definitions of the null hypothesis.

My experience in working with Flickr data forced me to teach myself many aspects of computer programming that went far beyond the topics usually covered in statistics or methods courses. Indeed, the technological aspects (SAS, STATA, SPSS, R, or whatever) of most sociology curriculum is addressed as an afterthought, and covered only enough to accomplish the work deemed important -- namely the statistics. In the total time spent working on computer programming for my dissertation, only a small fraction was dedicated to doing actual statistics. The vast majority was invested in acquiring, storing, manipulating, and testing my data sources. I am not arguing that every sociologist should learn about relational database management systems or optimizing algorithms, but if the field wants to get to the forefront of social media research, then the technological aspects of data processing have to be given respected places alongside the traditional focus on statistical programs.

#### Follow the money

Possibly the most important, and least understood, difference between social media and survey data is the business environment and intellectual property law that applies to social media data. This problem is not specific to the field of sociology, but has implications for many fields in the physical and social sciences. There is an oft used phrase that applies to free social media platforms:  "If you're not paying for it, you're the product." This phrase suggests that Facebook, Twitter, YouTube, etc. are providing a platform so that they can deliver users to their advertisers. Data collected and disseminated along the way is incidental to their main purpose.

Facebook and Twitter both now enforce restrictive terms of service for collecting and using ostensibly public data that passes through their platforms. Facebook at least has created its own internal research group which famously published an experiment on emotional contagion [@Kramera2014]. And while that paper spurred controversy about the ethics of secretly experimenting on Facebook users, I would instead focus attention on the fact that internal Facebook researchers have the ability to study social media data that is simply not available to the rest of the social science community. In the golden age of survey research, academics could put together funding to "field" a survey on almost any topic and covering any sampling frame that they could afford. With social media platforms this is not necessarily true, although there have been some industry collaborations. There is also reason to believe that many (most?) companies that run social media services will want to use social science research to improve their bottom line. Whether those opportunities will coincide with sociologists interests such as race, class, and gender remains to be seen.

As survey research was just taking off, Gallup put forth the noble call for surveys to serve as a voice of the people; to let bureaucrats and politicians know what the common citizen thought of their world [@Gallup1940]. Of course, in the process Gallup, Inc. has become a highly profitable international company, but still maintains a good deal of data collection in the public interest. Will social media companies like Twitter and Facebook follow suit over the next 25 or 50 years? Unlike the companies that sprung up around the new industry of surveys, the social media companies are not primarily interested in data collection. Facebook, Twitter, and other social media platforms make most of their revenue through advertising, and thus like older forms of media such as newspapers and television, they must engage their user base and keep them interested and happy. To the extent that collecting data relevant to social science questions can happen within their primary goals, social media companies are happy to play along, but this does not guarantee future efforts [@Boyd2012]. The economic and legal frameworks around social media data is troublesome and will potentially scare away researchers, students, or granting agencies.

#### Interdisciplinarity

In learning to understand social media data, sociologists could borrow ideas from other disciplines. This may require some rethinking of our approach to data collection. For example, I have already noted how I think social media is more like observational methods or primary sources in historical research. Unlike survey responses, historical records are almost never anonymous or confidential. Indeed, anonymizing primary sources would in many cases decrease their value as historical data. On one hand this is a debate about research ethics and the role of human subject review boards. But on the other hand this is an issue connected to how sociologists use survey data, and we do that mostly through assumptions of independent observations, or its weaker cousin, the assumption of homoscedastic errors in a regression model. Quantitative sociology is built on these assumptions, not because sociologists think this is how the world operates (I hope), but because surveys are built on these assumptions and surveys have been the main data collection tool for the past fifty years.

Re-orienting sociological research to use social media data gives us a chance to reexamine our assumptions. Should we see connections among our observational units (people, neighborhoods, schools, etc.), as methodological annoyances, which are to be controlled away? Or should we view the lack of independence among observations as a first-class problem -- should we investigate the connectivity as the central question of sociology? Data from social media sources comes to us already embedded in  networks of connectivity -- friends, followers, viewers, commenters, and hypertext links -- and it comes to us sometimes anonymous and sometimes identified (or identifiable). In fields such as history, literary theory, or communication studies, the connections and the identifiable information is treated as the main source for drawing inferences and generating new knowledge. If sociologists want to engage social media as a new data source, we would do well to learn from other disciplines about the methods and ethical practices they have long been using within their fields.


# Appendices

## Methods for turning points into polygons.

### Motivation

Geometry has three basic entities: the point, the line, and the plane (and by extension the closed polygon). With the addition of a few more basic elements like networks, topologies, and projections, the basic geometric entities also form the ontology for all modern geographic information systems (GIS). Unfortunately, the sociological concept of a neighborhood [@Galster2001] does not fit neatly into the GIS ontology. If anything, the neighborhood is most like a polygon, however, the data that I use throughout my research is collected in the form of points -- the latitude and longitude coordinates of individual photographs uploaded to Flickr. Obviously, I need a set of methods for turning points into polygons. This appendix will outline nine methods and discuss their relative strengths and weaknesses.

There is a scant existing literature on the challenge of turning points into polygons and this is probably due to the fact that domain-specific knowledge almost always trumps stale math. For example, a meteorologist can make certain assumptions about wind speed and the location of weather stations -- the wind probably won't make abrupt changes. Conversely, a geologist looking for subterranean ore must use a different set of models and assumptions when analyzing their core samples. Both are specialized subsets of the problem of turning point-data into polygon-based predictions, as is my challenge of turning geotagged photographs into definitions of neighborhoods. Since domain-specific knowledge turns out to be very important in this work there are many different fields that have "solved" this problem for their own purposes, but there is almost no literature on the generalized problem. (And even my focus is a subset of the even more generalized problem faced when we consider 3 or more dimensional space or we allow distance metrics from non-Euclidean geometry like factor scores). The methods used by researchers may alter their substantive conclusions, so this appendix outlines the methods I have found most appropriate for my problem.

In the domain of neighborhood effects research, there are at least seven considerations that we can use to judge the appropriateness of point-to-polygon conversion methods. First, we could decide if we want larger or smaller neighborhoods. Or to put it another way, given a set of points should we prefer a method of drawing a polygon with more or less area inside the neighborhood. Second, do we care about the relative compactness of the neighborhood, where compactness is defined as the ratio of the neighborhood's boundary to area. For example, can neighborhoods be L-shaped or should we force them into more square shapes? Third, a researcher should consider how much they care about islands, archipelagos, pan handles, donut holes, dangling chads, or other "weird" shapes. Fourth, do neighborhood boundaries need to follow visible edges like roads and waterways? Census tracts are defined in a way to follow these edges, but there are not many sociological definitions of neighborhoods that suggest this must be true, therefore, I suggest that this is a decision criteria left open to a researcher. Fifth, there should be an _a priori_ decision to let neighborhoods overlap or not. Again, census tracts never overlap, but that is mere bureaucratic exigency rather than a theoretically grounded operationalization. Some methods for turning points into polygons are capable of producing mutually exclusive neighborhood boundaries, while others allow the polygons to overlap when the points overlap. Sixth, does the researcher want boundaries that are "robust" to a single wayward point laying fair away from the mean of the points? For example, any method could have a preliminary step where the algorithm trims off outlier points, but some methods will naturally deal with outliers without the need for a cobbling together an additional data cleaning step. Seventh, there are a number of practical considerations because the number of points in each neighborhood can be large enough to make $O(n log(n))$ algorithms slightly cumbersome -- and when there are potentially hundreds of thousands of neighborhoods to define in a nation-wide study, a researcher may need to consider the calculation speed.

### Process

Each researcher is free to setup their own well-reasoned decision criteria. Here are mine:

1. Prefer smaller neighborhoods.
2. Do not worry about compactness -- i.e. L-shapes are acceptable.
3. "Weird" shapes are acceptable, although let's not get carried away.
4. Prefer neighborhoods that follow visible boundaries.
5. Neighborhoods can overlap.
6. Prefer methods that deal with outliers as part of the process because outlier trimming introduces another level of arbitrary decision making in the domain of neighborhood boundaries.
7. Prefer faster, easier calculations.

Of course, some of these criteria are in conflict with one another, so picking final methods for turning points into polygons is a balancing act. For example, in choosing small neighborhoods over compact areas, I am trying to err on the side of favoring local knowledge about the shapes of neighborhoods 

Now I will list the potential methods I have explored. It is probably easiest to refer to Figure A1, which shows each method applied to the same set of points. The simplest way to turn points into polygons is to construct **minimum bounding boxes** around the set of points. The result is a rectangle, so it automatically maximizes compactness, but it may create polygons that are too large and contain a lot of empty space relative to other methods. Bounding boxes are the fastest method, so they can be useful as a first pass for spatial analysis. However, there is a loss of face validity in defining neighborhoods as a bunch of overlapping squares and rectangles. Bounding boxes are my least preferred method.

\begin{figure}[htbp]
    \centering
    \caption{Alternative methods for drawing polygons around a set of points.}
    \subbottom[Minimum bounding box.]{
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/a1_panel1_20150114.png}
    }
    \subbottom[Delaunay triangulation.]{
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/a1_panel2_20150114.png}
    }
    \subbottom[Convex hull.]{
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/a1_panel3_20150117.png}
    }
    \subbottom[Minimum spanning tree.]{
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/a1_panel4_20150117.png}
    }
\end{figure}

\begin{figure}
    \contcaption{Alternative methods, continued.}
    \contsubbottom[Alpha shape, $\alpha = 1.505$]{
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/a1_panel5_20150117.png}
    }
    \contsubbottom[Standard deviational ellipsoid]{
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/a1_panel6_20150117.png}
    }
    \contsubbottom[Kernel density estimates]{
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/a1_panel7_20150117.png}
    }
    \contsubbottom[Trend surface]{
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/a1_panel8_20150118.png}
    }
\end{figure}

The next four methods are all special cases of a Delaunay triangulation of points. See panel (b) in Figure A1 for an example of a Delaunay triangulation and see @Okabe1992 [92] for the geometric definition -- I think of it as connecting all the points with the smallest triangles possible. Because all these methods first calculate a Delaunay triangulation they are $O(n log(n))$ in calculation, so they can become cumbersome with very large sets of points or a large number of neighborhoods (>10,000 in my experience). None of the methods in this group follow visible boundaries. A **convex hull** is simply the outside edge of the Delaunay triangulation. Much like the bounding box method, it often contains a lot of empty space, and is always more compact than the other methods in this group. Convex hulls will never have islands or donut holes; however, if the points are in a skinny cluster, a convex hull may appear to have a dangling chad. Another method in this group is the so-called "**nearest neighbor**" algorithm [@Jaromczyk1992], which is a subset of the Gabriel graph (which is a subset of the Delaunay triangulation).  Nearest neighbor graphs are slightly slower than convex hulls as they have to analyze the Delaunay triangulation based on criteria for eliminating some edges. The benefit of this method is that it can trim away some of the empty space we saw in convex hulls. However, this does mean that nearest neighborhood methods are prone to leaving islands and dangling chads. **Minimum spanning trees** are a further subset of nearest neighbor graphs. Strictly speaking MSTs create graphs instead of polygons, however, each point can be classified as either a branching point our a leaf in the MST. Leaves are points connected along one edge, and by connecting the leaves a polygon is formed. It is definitionally impossible to make islands with a polygon made from a MST, but not all MSTs are guaranteed to have three or more leafs. MSTs do not eliminate outliers, but they are often used in identifying outliers, so it would be relatively simple for researchers to apply cutoff criteria to the result of minimum spanning algorithms. Finally, the **alpha shapes** [@Pateiro-Lopez2010] are also based on Delaunay triangulations, but they take an extra parameter that the researcher must specify -- often denoted $\alpha$. Alpha shapes start out as convex hulls and then remove territory depending on $\alpha$. They may end up losing a lot of their compactness and can even start to form archipelagos and donut holes. To me, alpha shapes have the most face validity of any of the available methods, but because they require the specification of an additional parameter, they require more work on the researcher's part to fine tune the balance between neighborhood size and the weirdness of the shapes. Alpha shapes are drawn with arcs for edges, **alpha hulls** use the same set of vertices but connect them with straight edges.

Any set of points in a 2-dimensional space can be turned into a **standard deviational ellipsoid** with a few formulas calculated on the x- and y-coordinates [@Lefever1926]. The result is like a round version of the bounding box, except that some outlier points may lie outside the boundaries of the ellipsoid. Indeed, it is conceivable that every point will end up being outside the ellipse. This method creates compact, non-weird shapes that can overlap. Since the ellipses are calculated without reference to graphs or any need for GIS calculations, it is probably the fastest method available. The size of the ellipse will be proportional to the extent of the points, but in almost all cases a standard deviational ellipsoid will be larger than all methods based on Delaunay triangulation. Much like the bounding box, though, ellipses don't seem to have much face validity for the shape of a neighborhood.

Another set of methods is based on the idea of dividing space into chunks of territory, and then using algorithms to assign each block to one of many possible neighborhoods. There are two main ways of creating the chunks: a) arbitrary units like hexagonal bins or square rasters, or b) based on ancillary data like road networks, census block groups, or ZIP codes. If a researcher uses the first approach they would be **binning** points into polygons. The choice of assignment algorithms could constrain the resulting neighborhood to be one piece or allow for weird shapes like islands and donut holes. Also based on the assignment, there may or may not be empty spaces between neighborhoods. If a researcher chooses, the results could allow overlapping neighborhoods. To put it another way, the researcher has almost limitless possibilities for creating neighborhood boundaries using a block assignment and binning method. Likewise, if a researcher uses some ancillary data like road networks to make the blocks, they will still have many options for controlling the outcome of the neighborhoods. For example the **betashapes** project[^Flickr] divides space based on road networks and waterways, then assigns each chunk to one and only one neighborhood based on which Flickr place has the most photographs in (or near) the chunk. (The betashapes approach also uses some post-processing methods to avoid islands and donut holes, but not necessarily to close all empty space between neighborhoods.) Any methods based on spatial blocks are less compact, more weird, smaller, and much slower to compute than all other methods. Some algorithms will automatically trim outlying photos, which may compensate for some of the draw backs. However, the biggest benefit of binning- or betashape-type methods is that they can be made to follow visible boundaries making them an indispensable part of a researcher's toolbox.

[^Flickr]: The name "betashapes" is attributable to work done by programmers in and around Flickr. I should explain the progression of the *-shapes project that were spawned by Flickr between 2008 and 2011. First, Flickr released a project called [alpha shapes](); second programmers at another company -- SimpleGeo, now defunct -- released [betashapes](), which used a combination of Flickr data and OpenStreetMaps; third Foursquare programmer David Blackman made [zetashapes]() which used Flickr, census blocks, and user-generated edits; and fourth Nathaniel Kelso pitched in at Foursquare to produce the [quattroshapes]() database which made worldwide neighborhood boundaries based on Flickr, open government data, geonames.org, Natural Earth boundaries, and the Yahoo! GeoPlanet gazetteer. The alpha shapes project used an alpha shape method. The beta-, zeta-, and quattro-shape projects used methods based on the idea of dividing space into chunks and then assigning the chunks to neighborhoods.

Finally, I'll just throw in a quick description of **kernel density estimation** and **trend surface** methods. Strictly speaking, these approaches (possibly also methods like splines and kriging) are interested in estimating continuous value functions for sets of points -- they are not meant to be used to turn points into polygons. However, the only thing between a continuous surface and a polygon is a cutoff criteria. Given that alpha shapes, binning, and betashapes all require the specification of arbitrary parameters, setting a cutoff criteria for KDE or trend surfaces does not seem like an insurmountable hurdle. These two methods could be parameterized to make neighborhoods that are less weird than alpha shapes and block methods; they could be more compact than all methods except convex hulls, bounding boxes, and ellipsoids; they could be smaller than all of the methods; and trimming outliers is integrated within their definitions. In terms of of computation these methods are somewhere in the middle. All parameterizations of KDE and trend surface methods would have to allow for the possibility of overlapping neighborhoods. I like the idea of turning points into surfaces and then turning surfaces into polygons, but the main drawback is that it has never been done to my knowledge. For now, I leave this possibility to future research.

Table A1 summarizes the 9 methods cross-classified with 7 decision criteria I listed above. Please keep in mind that the table is meant to be illustrative  not definitive -- 

\begin{sidewaystable}[pht!]
    \tiny
    \caption{Alternative point-to-polygon conversion methods.}
    \begin{tabularx}{\textheight}{l*{9}{c}}
        \toprule
        \parnoteclear
        & \shortstack{Minimum \\ Bounding \\ Boxes} & \shortstack{Convex \\ Hull} & \shortstack{Minimum \\ Spanning \\ Tree} & \shortstack{Alpha \\ Hull} & \shortstack{Standard \\ Deviational \\ Ellipsoid} & \shortstack{Kernel \\ Density \\ Estimation} & \shortstack{Trend \\ Surface} & Binning\parnote{More so than other methods, the binning and block assignment approaches depend on choices made by the researcher, so definitive classifications are more difficult.} & \shortstack{Block \\ Assignment\parnote{ibid.}} \\
        \cmidrule{2-10} 
        Size & Largest & Moderate & Small & Small & Moderate & Moderate & Moderate & \shortstack{Moderate/ \\ small} & \shortstack{Moderate/ \\ small} \\ [3ex]
        Compactness & Highest & High & Low & Low & High & Low & Moderate & Low & Low \\ [3ex]
        Weird shapes & No & No & Yes & Yes & No & Yes & No & Yes & Yes \\ [3ex]
        \shortstack{Visible \\ boundaries} & No & No & No & No & No & No & No & Yes & Yes \\ [3ex]
        \shortstack{Overlapping \\ neighborhoods} & Yes & Yes & Yes & Yes & Yes & Yes & Yes & Yes/no & Yes/no \\ [3ex]
        \shortstack{Removes \\ outliers} & No & No & Moderate & Yes & Yes & Yes & Yes & Yes & Yes \\ [3ex]
        Speed & Fast & Fast & Slow & Moderate & Fastest & Moderate & Fast & Slow & Slowest \\ [3ex]
        \bottomrule
    \end{tabularx}
    \parnotes
\end{sidewaystable}

### Limitations

All methods for turning points into polygons have limitations. There is no perfect way for converting from one to the other while preserving the important information and not sacrificing specificity. Throughout all chapters I followed two overarching principals. First, I always wanted to use the smallest shapes as possible. This means allowing for weird shapes and sacrificing compactness in some chapters. Second, I attempted to keep the Flickr neighborhoods as similar to the existing methods as possible, except for the crucial element under consideration in each chapter. For chapter 2 this is overlapping areas; for chapter 3 it is the alternative ways of aggregating city blocks; and for chapter 4 it is the difference between extensive, mutually exclusive census tracts and potentially overlapping Flickr neighborhoods. I will briefly elaborate the known limitations for the choices made in each chapter.

In Chapter 2 I used convex hulls because it put the focus on the photographs located near to the edge of neighborhoods. Unlike alpha shapes or standard deviational ellipsoids, convex hulls never trim outlier points. Additionally, convex hulls require very few assumptions, the conclusions that I make in chapter 2 are more about the photographs, the meta-data of the photographs, and their locations; the conclusions are less about the assumptions of the method for turning points to polygons. Convex hulls will make the neighborhoods in chapter 2 larger than methods like alpha shapes and betashapes. The methods for finding spatial outliers were designed to see if any individual photographs are causing a bias in the shape of the convex hull by increasing its size, thus I was best served by choosing a method that does not automatically trim outliers. 

In Chapter 3 I used betashapes because I wanted to directly compare Flickr-based neighborhoods with Sampson's [-@Sampson2012] neighborhoods. The method described in the chapter 3 notes that I altered the standard betashapes methods to ensure that all territory within Chicago was assigned to exactly one neighborhood. My version of betashapes are the most like Sampson's neighborhoods: follow visible boundaries, do not overlap, and prefer compactness. The main draw back to this method is the fine tuning of a number of arbitrary parameters: the number of photographs to query for each neighborhood, the scoring algorithm for assignment of city blocks to neighborhoods, the cutoff criteria for making compact neighborhoods, and the street network data used in creating the city blocks. After specifying all of these parameters, the resulting neighborhoods are useful for comparing with Sampson's neighborhoods.

In Chapter 4 I used alpha shapes for two reasons: a) convenience and b) they allowed overlapping neighborhoods and gaps. Convenience was a valid concern in this chapter because it analyzes nation-wide data with about 61,000 neighborhoods. The national dataset of alpha shapes has already been [published by Flickr](http://code.flickr.net/2011/01/08/flickr-shapefiles-public-dataset-2-0/), so it could be downloaded and used without any additional processing. The chapter is directed mostly at the question of how we should conceptualize neigbhorhoods; perhaps as overlapping and non-extensive as opposed to the census tracts definition as non-overlappling and extensive. The major draw back is that alpha shapes make a lot of weird shapes.

It could be argued that my purpose -- showing that Flickr is a new and valid way for neighborhood effects research -- would be better served by picking one method and sticking with it. In using three different methods for turning points into polygons I was trying to present many possible alternatives for future researchers. I am also trying to make each chapter focus on a single way that neighborhood definitions can be shifter from current methods such as census tracts.

## Factor scores for place-referential content in photographs

### Motivation

I want to create a method for quantifying the amount of place-referencing material in a photograph. In other words, I want to measure how much a photograph is about place. This score can then be used in downstream analyses to see if neighborhood boundaries are based on images of places. One way to approach this problem would be to have multiple judges rate the "place-referential" nature of a photograph, and then employ well-known methods for determining inter-rater reliability and scoring validity [@Palmer2001]. However, when we are dealing with something like neighborhoods -- an example where we assume locals know more than outsiders -- this approach scoring content based on outsiders' opinions may be difficult to replicate across multiple cities and/or groups of judges. For example, if one judge happens to know the local hangouts in a neighborhood, they might see "place" whereas a judge with an outsider's perspective would only see a Wal-Mart. Therefore, intersubjective ratings may be a doomed method for quantifying the amount that a photograph references a place.

As an alternative, I offer a method based on content analysis. I looked for clearly identifiable elements in a photograph, assigned a numeric value to these elements and then constructed a composite score about the whole photograph based on its components [@Rose2007]. For the remainder of the appendix I will use the term "platzbilder" to mean the amount of place-referential content in a photograph.

In chapter 2, the platzbilder measure is used to detect potential bias in the shape of the Flickr neighborhoods. Images with high or low values of platzbilder that are also located near the boundary of the neighborhood may have undue influence on the resulting shape. Therefore, I want to identify these images that are simultaneously outliers on the variable and spatial outliers. One could certainly come up with competing hypothesizes about where high platzbilder photos would be likely to occur. On one hand, some streets with high commercial activity might be located on the edge between neighborhoods -- and this street might be photographed more than average places exactly because of its position as a line of demarcation. On the other hand, certain landmarks -- parks, factories, schools, etc. -- might sit at the core of a neighborhood and people may be more likely to photograph these spots in the middle of a neighborhood. If high platzbilder photographs tend to be located in the middle of neighborhoods, they will have less influence on the eventual shape of the neighborhood as defined by Flickr. So in order to explore how much bias photographs may have due to extraordinary amounts of platzbilder, I first need to create a way to consistently and accurately measure how much a photograph is about a place.

### Process

#### Sample

I drew samples of 2371 photographs. All photographs were selected at random using the Flickr API from photographs uploaded between January 1, 2005 and December 31, 2009. First I drew a sample of photographs with textual tags for "Phoenix" or any of the neighborhoods inside Phoenix as listed in the GeoPlanet database. To this I added photographs that were geotagged within a bounding box containing the city boundaries of Phoenix. At this point, the 14 village planners used in the analysis had between 2 and 118 photographs. To make sure that each village planner was represented in the final analytical dataset, I randomly sampled at least 50 photographs geotagged in each of the village planners. Then I added a random sample from within a bounding box surrounding the United States. I used these four groups of samples to ensure representativeness of geotagged photographs of the Phoenix village planners while also avoiding the problem of selecting on the dependent variable [@Geddes1990].

#### Scoring

I looked at each photograph along with its title, description, and meta-data for the camera's flash. I looked for the presence of six elements and scored each one as 0 or 1. 

- *Proper names* like stores, cities, or streets which are legible in the photograph or written into the title or description.
- The picture was taken *outdoors*. When there was some question -- e.g. if the photographer was standing inside a house but shooting a scene located outside -- my final determination was: if it were to rain at the moment the photo was captured, would the photographer get wet? This means that partially enclosed structures like gazebos would not be deemed outdoors.
- The picture contained the exterior face of at least one *building*. Even if the building was very far in the background, if they were clearly identifiable as man-made buildings, it would meet the criteria.
- Using the photograph's metadata, I looked to see if there was *no flash* used. If the flash was used or if I was unable to determine the status of the flash -- often the case for scanned images -- it was scored as 0. 
- *Wide angle* photographs were scored as being about a place. To qualify as a wide angle shot, the photograph had to contain at least one of these standard objects: person, car, or doorway. None of the standard objects could occupy more than 33% of the height of the photograph.
- Having *no people* in the photograph was scored as 1. This may be the most debatable scoring element as some places are known for having crowds of people, and some images of certain stereotypes of people may be salient exactly because they are about a place. However, I feel comfortable that in general photographs without people are going to be more about the place.

#### Factor Analysis

The overall (tetrachoric) correlations in the sample are shown in Table B1. As you can see by the highly significant correlation coefficients, most of the indicators share a lot of variance with the other indicators; the high degree of shared variance means that factor analytic methods are preferred over simple additive scales.

\begin{table}[ht]
  \small
  \caption{Correlations among elements in platzbilder score (n = 2371).}
  \begin{tabularx}{\textwidth}{rlllll}
    \toprule
    & outdoors & no\_flash & no\_people & building & proper\_name \\ 
    \cmidrule{2-6}
    outdoors &  &  &  &  &  \\ 
    no\_flash &  0.41*** &  &  &  &  \\ 
    no\_people &  0.15*** & -0.04*  &  &  &  \\ 
    building &  0.37*** &  0.25*** & -0.07*** &  &  \\ 
    proper\_name &  0.12*** &  0.05**  &  0.15*** &  0.07**  &  \\ 
    wide\_angle &  0.27*** &  0.24*** & -0.31*** &  0.44*** & -0.02  \\ 
    \bottomrule
  \end{tabularx}
\end{table}

After scoring each of the 2371 photographs, I split the sample in half. One half for constructing an exploratory factor analysis and the other half for testing it against alternative parameterizations. The first half was then subdivided into 10 groups with $n =$ 90  photographs. A one-factor solution with no rotation was forced onto each of the 10 sub-groups. This resulted in 10 factor loadings for each element, and I selected the median loading from the 10 as the basis for what I call the "candidate model." This method of running multiple factor analysis in  sub-samples should help to avoid the problem of overfitting the covariance of the scored elements [@Loehlin2004]. With the candidate model in hand, I switched back to the other half of the sample to confirm its ability to explain the covariance structure. In the confirmatory half of the sample I estimated 1-, 2-, and 3-factor solutions for platzbilder. The candidate factor solution was compared against these alternative models using a modified $\chi^{2}$ statistic based on Loehlin [-@Loehlin2004, 155]. As you can see in Table B2, the candidate loadings out performed the 2- and 3-factor models, and while the fit for the 1-factor model was better than the candidate model, it was not significantly improved as judged by the modified $\chi^{2}$. This is quite an accomplishment for the candidate model: even a model estimated on the confirmatory sample was not significantly better at recovering the covariance structure in the confirmatory sample.

\begin{sidewaystable}[pht!]
  \small
  \caption{Model comparison for confirmatory factor analysis in testing half (n = 906)}
  \begin{tabularx}{0.9\textwidth}{l*{7}{d{-1}}}
    \toprule
    \parnoteclear
    & \multicolumn{1}{c}{Candidate Model} & \multicolumn{1}{c}{CFA Model 1} & \multicolumn{2}{c}{CFA Model 2} & \multicolumn{3}{c}{CFA Model 3} \\ 
    \cmidrule(l{2pt}r{2pt}){2-2} 
    \cmidrule(l{2pt}r{2pt}){3-3} 
    \cmidrule(l{2pt}r{2pt}){4-5} 
    \cmidrule(l{2pt}r{2pt}){6-8}
    & \multicolumn{1}{c}{Factor 1} & \multicolumn{1}{c}{Factor 1} & \multicolumn{1}{c}{Factor 1} & \multicolumn{1}{c}{Factor 2} & \multicolumn{1}{c}{Factor 1} & \multicolumn{1}{c}{Factor 2} & \multicolumn{1}{c}{Factor 3} \\ 
    \cmidrule{2-8} 
    Outdoors & 0.842 & 0.489 & 0.540 & 0.821 & 0.901 &  & 0.428 \\ 
    No Flash & 0.607 & 0.516 & 0.537 & 0.305 & 0.516 & -0.389 & 0.187 \\ 
    No People & -0.123 & -0.601 & -0.568 & 0.614 &  & 0.841 & 0.440 \\ 
    Buildings & 0.901 & 0.668 & 0.688 & 0.323 & 0.903 &  & -0.423 \\ 
    Proper Name & 0.201 &  &  & 0.337 & 0.244 & 0.266 &  \\ 
    Wide Angle & 0.724 & 0.998 & 0.996 &  & 0.645 & -0.610 & -0.249 \\ 
    \midrule
    Model df & 13 & 9 & 4 &  & 0 &  &  \\ 
    $\chi^{2}$ &  & 1.418 & 0.192 &  & 0.029 &  &  \\ 
    Modified\parnote{Modified Chi-squared test is due to Loehlin (2004).} $\chi^{2}$ & 7.832 & 8.095 & 0.348 &  & 0.272 &  &  \\ 
    \shortstack{Model compare \\ p-value\parnote{P-value for the null hypothesis that the candidate model is equal to the alternative models. Based on the difference in the modified $\chi^{2}$ and the change in the degrees of freedom.}} &  & 0.99 & 0.71 &  & 0.91 &  &  \\  
    \bottomrule
  \end{tabularx}
  \parnotes
\end{sidewaystable}

In order to turn the factor loadings from the candidate model into a true platzbilder score for each photograph, I applied this formula:

$z = \mathsf{M} \mathsf{R^{-1}} \mathsf{f}$

Where $\mathsf{M}$ is the original data matrix that has been centered and scaled, $\mathsf{R}$ is the observed correlation matrix and $\mathsf{f}$ is a vector of factor loadings. This is the standard method for creating scores based on factor analysis attributed to @Thomson1935, but in the case of more than one factor there is still an open debate on the best approach for creating scores [@Bartholomew2009]. Figure B1 shows boxplots for the distribution of the final platzbilder scores in the different types of geotagged data. Figure B2 shows boxplots within the analytical sample of the 14 Phoenix village planners.

\begin{figure}
    \centering
    \caption{Boxplots showing the platzbilder score in the four different sampling groups.}
    \includegraphics[width=\textwidth, keepaspectratio=true]{appendix_images/b1_geotag_20150119.png}
\end{figure}

\begin{figure}
    \centering
    \caption{Boxplots of platzbilder for each neighborhood in Phoenix.}
    \includegraphics[width=\textwidth, keepaspectratio=true]{appendix_images/b2_hood_20150119.png}
\end{figure}

### Limitations

As anyone who has ever developed a test for the classroom can agree, a single quantitative score, while concise and seductive in its objectivity, is only tenuously connected to the latent construct it is supposed to measure. Whether comprehension of course content or the amount of place-referential content in a photograph, a single score is at best a noisy representation of the underlying phenomenon. And doubly so in this case because it is still not clear to me, what exactly a photograph should contain in order to be "about" a place. Regardless, I am happy with my scoring system because it seems to have some face validity. Figure B3 contains 3 images with high platzbilder and 3 images with low platzbilder (all images were released under a Creative Commons license by their owners). These six photograph clearly demonstrate that some photos contain a good deal more place-referential content than other photos. Additionally, the method for my scoring system is replicable and does not rely on any special insider knowledge of a neighborhood.

\begin{figure}[htbp]
    \centering
    \caption{Example of photographs with extreme values of platzbilder. (a)-(c) have high values; (d)-(f) have low values; all photographs are licensed through Creative Commons as denoted.}
    \subbottom[user: nickbastian, BY-ND 2.0]{ 
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/b3_panel1_20150206.png}
    } 
    \subbottom[user: kingdafy, BY-NC-ND 2.0]{ 
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/b3_panel2_20150206.png}
    } 
    \subbottom[user: mercutiom, BY-NC-SA 2.0]{ 
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/b3_panel3_20150206.png}
    } 
    \subbottom[user: labanex, BY-NC-SA 2.0]{ 
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/b3_panel4_20150206.png}
    } 
    \subbottom[user: AshtangaBoy, All Rights Reserved]{ 
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/b3_panel5_20150206.png}
    } 
    \subbottom[user: labanex, BY-NC-SA 2.0]{ 
        \includegraphics[width=6cm, keepaspectratio=true]{appendix_images/b3_panel6_20150206.png}
    } 
\end{figure}

An additional caveat to my scoring system should be noted. Even though I have used factor analysis to quantify the amount of place-referential content, the final platzbilder variable is still quasi-categorical. Each photo is scored as the combination of six binary variables so the entire sample must take one of $2^{6} =$ 64 values. Thus, the platzbilder variable is a categorical variable with 64 unequally ordered categories. Perhaps the inclusion of a truly continuous variable -- e.g. the percent of green and blue in a photograph or the count of windows -- would help to nudge the final variable into a distribution that could be more honestly called "continuous." The distribution of platzbilder is shown in Figure B4. Figure B5 shows it plotted against the other variables of interest in the study. The combination of content analysis and split-halves factor analysis methods has resulted in a respectably good measure of the photograph, and platzbilder seems to avoid problems of multicollinearity.

Even with these two limitations in mind, the platzbilder score adds important information to chapter 2. Platzbilder is a direct measure of what is in the photograph, while the other two measures -- touristyness and interestingness -- are based on the meta-data of photographs. Meta-data is often easier and cleaner to process in studies of VGI, however, it is important to use a messier concept like platzbilder in this case because good definitions of neighborhoods should be robust to sub-groups of photographs that clearly have nothing to do with the neighborhood. The only way to know if a neighborhood's boundaries are biased by pictures of cats, rock concerts or plates of food is to look at the photographs.

\begin{figure}[p!]
    \caption{Histogram of platzbilder score in the full sample of photographs.}
    \includegraphics[width=\textwidth, keepaspectratio=true]{appendix_images/b4_histogram_20150119.png}
\end{figure}

\begin{figure}[p!]
    \caption{Scatterplots of platzbilder and each of the four variables used in the analysis of outliers (n = 843).}
    \includegraphics[width=\textwidth, keepaspectratio=true]{appendix_images/b5_scatter_20150121.png}
\end{figure}

\newpage

## Development of "Spatialized" Hat Matrices and Test for Outliers

###  Motivation

First a quick definition: a "marked" point is a geographic location combined with the value of one or more attributes [@Diggle2003, 82-5]. For example, when I combine the measure of interestingness with the coordinates of the photographs the result is a set of marked points.

The fundamental question of chapter 2 is whether any photographs can be considered outliers from the other photographs in its neighborhood. In this case, "outlying" is defined as being spatially distant from the centroid of the other points and far from the mean of the variable. There are well defined methods for finding outliers in a set of spatial points [@Besag1989; @Ripley1981; @Cressie1993] or for finding outliers in a multivariate data set [@Cook1977; @Rousseeuw1990]. However, there is not a well established method for determining if a marked point is simultaneously a spatial *and* an attribute outlier. This appendix argues that this can be accomplished by using the methods found in @Cook1977 and considering the latitude and longitude coordinates to be additional attribute variables.

Of course, neither the literature on multivariate outliers nor the spatial point outliers has settled on a method for identifying "significant" outliers. As @Rousseeuw1990 [651] note, the choice of estimators and cutoffs are always somewhat arbitrary.  For the present purposes, significant outliers are identified as those marked points that would be outliers in more than 95% of data sets drawn from a similar data generating mechanism. In other words, if we assume that our observed variable is one draw of a stochastic process, we can make a best guess as to the nature of the stochastic process, make many repeated draws from it, and see where the actual observations fall in relation to the repeated simulated draws. This is a more generalized version of the standard (but flawed) Monte Carlo methods found in many spatial statistics packages [@Bivand2008, 261].

###  Process

Given a set of locations, $S_{i}$, with values $m_{i}$, we end up with a vector of $\{x, y, m\}$ for each of the $i$ observations. For everything that follows I assume that the analysis is done separately for each neighborhood -- which are indexed with $b$. The $n \times 3$ data matrix, $\mathsf{X}$ is transformed according to the formula for the hat matrix:

$\mathsf{H} = \mathsf{X} ( \mathsf{X^\intercal} \mathsf{X} )^{-1} \mathsf{X^\intercal}$

The resulting hat matrix is $n \times n$. For any given element, $h_{ij}$ it gives the amount of influence that observation $j$ has on $\hat{y_{i}}$. The diagonal of the hat matrix, $h_{ii}$, is the amount that observation $i$ leverages the predicted value $\hat{y_{i}}$, while holding everything else constant. In this particular case there are no predicted values -- luckily for me, the diagnol of the hat matrix still tells us how much each observation would leverage the prediction. I take high amounts of leverage to mean that a point is potentially biasing the boundaries of the neighborhood. If the point has high leverage and a high attribute value, it is biasing the shape of the neighborhood toward itself. If it has a high leverage and a low attribute value, the neighborhood boundaries may be ignoring it too much. 

The first step is to calculate the diagnol elements, $h_{ii}$. The second step is to figure out if $h_{ii}$ is *significantly* higher than other elements in the diagonal of the hat matrix. To test for a significant value in the hat matrix, we need to go back and generate a new draw, call it  $\mathsf{X^{*}}$, based on a suite of assumptions about the underlying data generating mechanism. Then we can re-calculate the diagonal elements of the hat matrix -- call them $h^{*}_{ii}$ -- and see where $h_{ii}$ falls within the distribution of all the synthetic $h^{*}_{ii}$ values. Note that standard Monte Carlo methods usually implement a method to randomly assign a value, $m_{i}$, to some point, $S_{j}$. In other words, standard methods make three assumptions:

(a) The data generating process will always produce the exact set of observed values, and 
(b) the data generating process will always produce points in exactly the observed locations, however, 
(c) the value attached to any given position is completely random. 

The standard suite of assumptions is bizarre. In my method I relax the assumption that the data generating process will always create the values just as they are observed. However, I will continue to use assumptions (b) and (c). In order to form a reasonable alternative for the photograph locations, I would need to make strong assumptions about the probability of photographs occurring at a given location. The large corpus of geolocated photographs could be used in coming up with a good guess for this, but it would require specifying a number of parameters like distance decay functions, kriging parameters, or trend surfaces. In essence, coming up wih an alternative to (b) would require creating a defensible method for estimating the probability that a photograph will occur in every single location. I set aside this task for future studies because a lot of alternative models would need to be explored before settling on a preferred method. The final assumption, (c), could also be relaxed by assuming a global level of autocorrelation or other type of spatial heterogeneity [@Goovaerts2004]. I chose to leave this assumption alone because it was not clear to me if the appropriate measure of autocorrelation was intra-neighborhood or across the entire city, and I still do not see a way to make a defensible decision on this point.

I do employ a different approach for part (a). My method takes the observed values, and creates a hypothetical distribution of the attribute. Then it makes draws from this hypothetical distribution to populate $\mathsf{X^{*}}$. When creating a hypothetical distribution for platzbilder, tourist-influence, and interestingness, I chose to forgo parametric distributions like Gaussian and Poison. I have no reason to think that a given neighborhood's attributes should follow a well-known distribution. Therefore, I used non-parametric distributions (inspired by the Kolmogorov-Smirnov method, c.f., @Massey1951) estimated as kernel densities on the observed distributions. Figure C1 shows the observed distribution, the kernel density, and one example of a synthetic distribution for each of the 3 variables. It is important to note two things about Figure C1. First, for demonstration purposes the figures are based on data across all neighborhoods, but in the process for creating significant cutoff values, the kernel density and synthetic distributions are calculated within each neighborhood separately. Second, the synthetic distribution shown in the bottom panel is only one draw from 1000 replicated draws.

\begin{figure}[htbp]
    \caption{Distributions used in formulating cutoff values for significant hat values.}
    \subbottom[Platzbilder (n = 846)]{
        \includegraphics[width=\textwidth, keepaspectratio=true]{appendix_images/c1_placey_20150121.png}
    }
\end{figure}

\begin{figure}
    \contcaption{Distributions, continued.}
    \contsubbottom[Touristyness (n = 715)]{
      \includegraphics[width=\textwidth, keepaspectratio=true]{appendix_images/c1_tourist_20150121.png}
    }
\end{figure}

\begin{figure}
    \contcaption{Distributions, continued.}
    \contsubbottom[Interestingness (n = 846)]{
      \includegraphics[width=\textwidth, keepaspectratio=true]{appendix_images/c1_interest_20150121.png}
    }
\end{figure}

Within each neighborhood, I calculated 1000 versions of the hat matrix, and thus 1000 versions of the diagnol elements, $h^{*}_{ii}$. Keeping in mind that the $h^{*}_{ii}$ vector will be of length $n$ -- the number of photographs within a neighborhood -- we are now in possession of 1000 X $n$ elements of the hypothetical hat matrix diagnols. Call this vector $t^{h}$. I define significant hat values as those that exceed the 95th percentile of values in $t^{h}$. Granted, the choice of the 95th percentile is arbitrary -- with a lower cutoff value, I would potentially flag more points as outliers, and thus Tables 3, 4, and 5 in chapter 2 may be populated with different values. Of course, Table 6 is the most critical table of chapter 2, and it depends, not only on the outlier cutoff, but also on the relative sizes of the polygons, whether points are high- or low-outliers, and what happens to the polygon when an outlier is removed. In other words, Table 6 depends on the decision on the arbitrary cutoff, but also on the observed data.  

Table C1 shows the 1st, 5th, 10th through 90th, 95th, and 99th percentile cutoffs for the hat values of each of the three variables. Table C2 shows the number of photographs identified as outliers within each neighborhood with 80th, 90th, 95th, and 99th percentile cutoffs. Using the 80th percentile would identify too many photographs, and the 99th percentile shows many neighborhoods with now oultiers. The 90th and 95th percentile cutoffs seem to be the best option and I arbitrarily chose to go with 95 because of its common usage in social science research. 

###  Limitations

I have assumed a very simplistic data generating mechanism. It may be an improvement over standard Monte Carlo methods, but just barely. Indeed, it assumes no spatial trends, no edge effects, and that $m_{i}$ and $S_{i}$ are independent. These are strong assumptions given that similar things tend to be nearer to one another than dissimilar things [@Tobler1970; @Tobler2004]. The important point to remember is that this suite of assumptions is meant to form a basis for operationalizing "not outlier" points, i.e. mundane data. It is only when a hat value lies at the very end of the distribution we created with these assumptions, do we start to consider it as a potentially important outlier. I am comfortable with using a simplistic data generating mechanism to form the basis for a distribution of mundane data.

The results in this appendix are not generalizable because the non-parametric distributions from Figure C1 are dependent on the observed data. The method could be replicated, but the results from one neighborhood or variable will not be useful for informing distributions or cutoff values for other locations. In my case the observed variables -- platzbilder, tourist-influence, and interestingness -- are all heavily manipulated in their own rights. I tuned the variables to be sensitive to what I deemed to be potential sources of bias. They were not constructed to have well-behaved distributions,[^1] so the hypothetical distributions within each neighborhood must be permitted to look quite bizarre. I have no way of saying if another researcher will have similar or different results in their data.

[^1]: There were other alternatives that I could have used to make more well-behaved distributions. For example, the platzbilder factor score could have been rotated to take on a $N(0,1)$ distribution. Additionally, the touristy-influence score could have been dichotomized or grouped into rough categories for locals (< 100 km) or tourists (>= 100 km), which would have tamed the apparent Pareto distribution. And while there is significant manipulation for each of the components going into the interestingness measure, no effort was made to standardize or scale the final summed score.  

For me, the most bothersome limitations come from the spatial arrangement of the photographs.  A reliance on Cartesian distance in calculating how far each point lies away from other points is baked into the method. A photograph might be an outlier from the rest of its neighborhood compatriots, if it is separated from them by a river, an interstate, or large open spaces like parks or cemeteries. The methods outlined in this appendix have no notion of "travel distance" between points. This limitation could be fixed with the investment of a lot of time and coding expertise to capture the number of physical barriers that are crossed between the neighborhood's centroid and each photograph. But even with that investment, there is still another limitation: the centroid of a neighborhood might not really be its most prototypical, fundamental, or central place. Therefore, calculating distance from a centroid is not the best way to test if a point is a spatial outlier. The "middle" of a neighborhood could have many different, socially-relevant definitions. This last limitation may be the hardest one to overcome without employing some sort of expert/local knowledge of each neighborhood.

\begin{table}[ht]
\small
\caption{Alternative cutoff points for critcal hat values within each neighborhood.}
\centering
\begin{tabular}{llrrrr}
  \toprule
Variable & Neighborhood & 80\% & 90\% & 95\% & 99\% \\ 
  \midrule
Interestingness & Ahwatukee Foothills & 0.03 & 0.04 & 0.05 & 0.09 \\ 
  Interestingness & Alhambra & 0.09 & 0.12 & 0.14 & 0.29 \\ 
  Interestingness & Camelback East & 0.08 & 0.10 & 0.12 & 0.22 \\ 
  Interestingness & Central City & 0.06 & 0.13 & 0.15 & 0.30 \\ 
  Interestingness & Deer Valley & 0.06 & 0.10 & 0.17 & 0.57 \\ 
  Interestingness & Desert View & 0.08 & 0.10 & 0.13 & 0.21 \\ 
  Interestingness & Encanto & 0.01 & 0.05 & 0.07 & 0.22 \\ 
  Interestingness & Estrella & 0.03 & 0.16 & 0.23 & 0.33 \\ 
  Interestingness & Laveen & 0.07 & 0.10 & 0.12 & 0.30 \\ 
  Interestingness & Maryvale & 0.08 & 0.11 & 0.16 & 0.32 \\ 
  Interestingness & North Gateway & 0.07 & 0.10 & 0.17 & 0.20 \\ 
  Interestingness & North Mountain & 0.07 & 0.11 & 0.13 & 0.21 \\ 
  Interestingness & Paradise Valley & 0.04 & 0.18 & 0.21 & 0.34 \\ 
  Interestingness & South Mountain & 0.08 & 0.10 & 0.13 & 0.23 \\ 
  Platzbilder & Ahwatukee Foothills & 0.03 & 0.04 & 0.05 & 0.06 \\ 
  Platzbilder & Alhambra & 0.09 & 0.12 & 0.14 & 0.16 \\ 
  Platzbilder & Camelback East & 0.08 & 0.10 & 0.11 & 0.22 \\ 
  Platzbilder & Central City & 0.08 & 0.12 & 0.14 & 0.16 \\ 
  Platzbilder & Deer Valley & 0.07 & 0.09 & 0.12 & 0.33 \\ 
  Platzbilder & Desert View & 0.08 & 0.10 & 0.12 & 0.17 \\ 
  Platzbilder & Encanto & 0.03 & 0.04 & 0.07 & 0.09 \\ 
  Platzbilder & Estrella & 0.06 & 0.16 & 0.23 & 0.27 \\ 
  Platzbilder & Laveen & 0.06 & 0.10 & 0.12 & 0.26 \\ 
  Platzbilder & Maryvale & 0.08 & 0.10 & 0.12 & 0.30 \\ 
  Platzbilder & North Gateway & 0.08 & 0.10 & 0.13 & 0.18 \\ 
  Platzbilder & North Mountain & 0.08 & 0.11 & 0.13 & 0.16 \\ 
  Platzbilder & Paradise Valley & 0.07 & 0.16 & 0.20 & 0.23 \\ 
  Platzbilder & South Mountain & 0.08 & 0.10 & 0.12 & 0.23 \\ 
  Touristyness & Ahwatukee Foothills & 0.08 & 0.12 & 0.15 & 0.20 \\ 
  Touristyness & Alhambra & 0.11 & 0.15 & 0.20 & 0.31 \\ 
  Touristyness & Camelback East & 0.09 & 0.11 & 0.14 & 0.25 \\ 
  Touristyness & Central City & 0.08 & 0.13 & 0.15 & 0.25 \\ 
  Touristyness & Deer Valley & 0.08 & 0.11 & 0.14 & 0.34 \\ 
  Touristyness & Desert View & 0.09 & 0.12 & 0.13 & 0.16 \\ 
  Touristyness & Encanto & 0.02 & 0.06 & 0.07 & 0.18 \\ 
  Touristyness & Estrella & 0.10 & 0.15 & 0.22 & 0.24 \\ 
  Touristyness & Laveen & 0.03 & 0.11 & 0.27 & 0.66 \\ 
  Touristyness & Maryvale & 0.09 & 0.12 & 0.17 & 0.36 \\ 
  Touristyness & North Gateway & 0.08 & 0.10 & 0.14 & 0.20 \\ 
  Touristyness & North Mountain & 0.10 & 0.15 & 0.17 & 0.30 \\ 
  Touristyness & Paradise Valley & 0.09 & 0.20 & 0.23 & 0.32 \\ 
  Touristyness & South Mountain & 0.07 & 0.10 & 0.13 & 0.26 \\ 
   \bottomrule
\end{tabular}
\end{table}

\begin{sidewaystable}[pht!]
  \small
   \caption{Number of outlier photographs identified in each neighborhood under alternative choices for critical hat values.}
  \begin{tabular}{lrrrrrrrrrrrrr}
  \toprule
  & & \multicolumn{4}{c}{Platzbilder} & \multicolumn{4}{c}{Touristyness} & \multicolumn{4}{c}{Interestingness} \\
  \cmidrule(l{2pt}r{2pt}){3-6}
  \cmidrule(l{2pt}r{2pt}){7-10}
  \cmidrule(l{2pt}r{2pt}){11-14}
  & n & 80\% & 90\% & 95\% & 99\% & 80\% & 90\% & 95\% & 99\% & 80\% & 90\% & 95\% & 99\% \\ 
  \cmidrule{2-14}
  Ahwatukee Foothills & 118 &  17 &  13 &   7 &   3 &   1 &   0 &   0 &   0 &  21 &  13 &   6 &   0 \\ 
  Alhambra &  50 &   9 &   5 &   4 &   2 &   5 &   2 &   0 &   0 &   9 &   5 &   4 &   0 \\ 
  Camelback East &  50 &   9 &   5 &   4 &   1 &   5 &   4 &   2 &   0 &  10 &   5 &   4 &   1 \\ 
  Central City &  50 &   6 &   6 &   6 &   1 &   6 &   6 &   1 &   0 &  17 &   6 &   1 &   0 \\ 
  Deer Valley &  50 &  12 &   4 &   2 &   1 &   7 &   2 &   2 &   1 &  15 &   2 &   1 &   1 \\ 
  Desert View &  52 &  10 &   5 &   2 &   2 &   9 &   2 &   2 &   2 &  10 &   5 &   2 &   2 \\ 
  Encanto & 120 &  24 &  14 &   6 &   2 &  38 &  12 &   4 &   1 &  86 &  14 &   6 &   1 \\ 
  Estrella &  51 &   8 &   5 &   5 &   3 &   5 &   5 &   5 &   5 &   9 &   5 &   5 &   1 \\ 
  Laveen &  50 &   8 &   5 &   4 &   1 &  29 &   5 &   1 &   0 &   7 &   5 &   4 &   1 \\ 
  Maryvale &  50 &  10 &   7 &   4 &   1 &   7 &   4 &   2 &   1 &  10 &   6 &   2 &   1 \\ 
  North Gateway &  50 &  10 &   6 &   4 &   2 &  11 &   7 &   3 &   2 &  12 &   6 &   2 &   2 \\ 
  North Mountain &  55 &  11 &   6 &   5 &   1 &   7 &   2 &   1 &   0 &  12 &   7 &   5 &   1 \\ 
  Paradise Valley &  50 &   9 &   5 &   4 &   1 &   7 &   2 &   1 &   0 &  28 &   4 &   2 &   0 \\ 
  South Mountain &  50 &   9 &   6 &   4 &   1 &  18 &   6 &   3 &   0 &  16 &   6 &   3 &   1 \\ 
  \bottomrule
  \end{tabular}
\end{sidewaystable}

## Creating neighborhoods with Flickr and OpenStreetMap.

### Motivation

The goal of this procedure is to take the metadata from individual geo-tagged photographs and turn them into neighborhoods. Since this paper is comparing Flickr neighborhoods to Census tracts and PHDCN neighborhoods, I had to construct polygons that were a) non-overlapping, b) contiguous, and c) extended across the entire are of the city of Chicago. Turning a collection of points into a set of polygons is not a straightforward procedure, and I made a number of choices along the way. This appendix spells out my procedure, notes the resources I drew upon, and points out where there could be important alternatives to my approach.

### Process

First let me list the pieces of data I used:

1. Yahoo Geoplanet database.
2. Flickr API.
3. Open Street Maps (from Geofabrik).

Second let me list the software I used:

1. ESRI ArcMap 10.
2. Postgis.
3. ogr2ogr.
4. Python.

If you are familiar with those technologies, this process should seem rather straight forward -- albeit still tedious. I am deeply indebted to the work of Aaron Straup, Schuyler Earl, and much of the rest of the original team of programmers at Flickr. They shared both their creativity through blogs and their source code through github while they were developing Flickr neighborhoods in 2008 and 2009. Many other developers throughout the open source and academic community have built extensions to their ideas. For my part, I tried to follow the instructions on SimpleGeo's betashapes repository[^repo]. Their business was trying to make neighborhoods for most large cities in the world, so they designed more automation into their code than I needed because I was only doing this for one city, but I wanted to make sure I did it really well for that one city.

[^repo]:
    [https://github.com/simplegeo/betashapes](https://github.com/simplegeo/betashapes). 

I first obtained a list of neighborhoods from Yahoo's Geoplanet database. Geoplanet can be extended by users, but it is a proprietary dataset created by Yahoo for use throughout their company. (Twitter, Facebook, Google, and other companies also maintain their own internal geo-databases. Companies like Urban Airship and Factual specialize in providing geo-data to smaller companies. The growth and deployment of geo-data on the web has been an understudied phenomenon [@Crampton2013].) Whereas the betashapes repository gives instructions for downloading all or most of the database, I used the graphical user interface at [http://developer.yahoo.com/yql/console/]() to query all of the "descendants" of Chicago. Descendants can be anything: towns, suburbs, ZIP codes, parks, lakes, etc. So I filtered the descendants to just the suburb place type, which resulted in 327 valid descendants of Chicago.

The betashapes code does the next step automatically (in a Python script called ```geocrawler.py```), but I rearranged the code a bit so it could be done -- and quality checked -- as a separate process. I looped through the list of 327 neighborhoods in Chicago, and queried the Flickr API for photographs uploaded between 2009 and 2011. I limited each neighborhood to a maximum of 1000 photographs, and when there were more than 1000, I chose to keep the most interesting[^interestingness] photographs. I did not download the image itself, and instead just saved the latitude and longitude coordinates of these photographs along with the photo's neighborhood ID. This process created a dataset with 144,903 photos in 309 neighborhoods. This means that 18 neighborhoods were left out due to lack of geotagged photographs.

[^interestingness]:
    Flickr uses a proprietary algorithm to score every image in terms of "interestingness." This score takes into account the number of views, comments, tags, shares, favorites -- basically the amount of engagement that the photograph has with the Flickr user base. By keeping only the 1000 most interesting photographs, the neighborhoods will be based on data that has engagement from the most users.

The second piece of the puzzle for making Flickr neighborhoods is a map of all the blocks in Chicago. I downloaded the Chicago portion of Open Street Maps (OSM) and used "Geoprocessing" tools in ArcMap 10 to create polygons. First I selected all roads, waterways, and railroads from the OSM data, and turned each of these features into simple lines. These lines were then used to break the city into block-like chunks of ground. Of course, there were many slivers of ground, for example in the median of four lane highways; I post-processed the resulting polygons to merge some of the smaller slivers. I then exported the 22,121 blocks from ArcMap in GeoJSON (an open-source format), so it could be used by the scripts from the betashapes repository.

The algorithm developed by Schuyler Earl takes the blocks and assigns each one a neighborhood score. After trimming out all spatial outliers from the Flickr photos, the 20 photographs closest to the blocks centroid are used to construct neighborhood scores for the block. Photographs that are inside the block are scored as 1 and photographs outside the block are scored inversely proportional to their distance from the block. The algorithm does not actually populate a matrix, but for demonstration purposes it might be useful to imagine an 309 X 22,121 matrix where each element is the score between neighborhood $i$ and block $j$. Obviously this will be a large, sparse matrix; and the algorithm simply stores a list of scores. After the scoring is done, the betashapes themselves are constructed by aggregating the blocks into neighborhoods based on each block's top scoring neighborhood. Other considerations like size of the betashape, contiguity, and not making orphan blocks are taken into consideration as the algorithm attempts to assemble the blocks into neighborhoods. The algorithm makes a number of arbitrary choices: 20 photos are scored per block, the formula for inverse distance scoring, a cutoff value for the number of orphans, the maximum allowable size for a betashape, etc. And to my knowledge no one has put in the effort to test out the robustness of the results to using different suites of assumptions. That could be an area of future research as methods for constructing neighborhoods out of point-level social media data become more common.

In my case, the algorithm failed to assign some areas within Chicago to any neighborhoods. I think this occurred because of two different patterns in the photographs. First, some areas had a high number of photographs tagged with two or more neighborhoods. I think the most important example is territory near Hyde Park, Egandale, and South Side. The overlap of the photos causes some non-intuitive results, but I left the polygons alone as much as possible. Second, some territory near the edge of the city was not assigned to any neighborhood. This was probably due to a sparseness of data -- remember I only sampled photographs with tags for neighborhoods within the city, and did not include any of the immediately adjacent suburbs. This problem did not occur in Austin or Moreland, two neighborhoods that show high homicide counts in Figure 2. It was most prevalent in northwest Chicago around Sauganash, and on the southwest side near Morgan Park.

When there are gaps left in the map of neighborhoods, I think a researcher has three options.

1. Exclude that area from analysis. Under the assumption that we are trying to model *the* neighborhood effect, any space that is understood by locals as belonging to multiple neighborhoods will by definition skew model results. This would be akin to removing outliers from regression models.
2. Combine the disputed space with other neighborhoods already on the map. If a researcher can use auxiliary information or expert judgment, unassigned blocks can easily be appended to neighborhoods.
3. Create new neighborhoods to cover all the space within the study area.

I chose option 3 because it did not require any expert knowledge (which I don't have), and because I like the idea that there might be a socially relevant entity that is the Hyde Park-Egandale-South Side neighborhood -- perhaps it's more than the sum of its parts? Again this is something that needs further research because any of the three methods actually make pretty strong assumptions about the casual mechanisms of neighborhood effects because whichever method is chosen determines which neighborhoods can affect which individuals. I did the task of visually adding new neighborhoods to cover all the city along with some additional cleaning up of the topology in ArcMap. The resulting file has 289 polygons, 267 of which were defined by the algorithm, and 22 that I added "by hand."

A reader is justified in their skepticism about how the point patterns of the raw Flickr data relates to the eventual polygon neighborhoods. Especially given the numerous times that I have noted the arbitrary nature of the parameters used in the betashapes procedure. Unfortunately, the limits of printed maps do not give me the ability to display the large number of points (remember it's more than 140,000 photographs) on top of the polygons. The interested reader can explore the data one neighborhood at a time on an interactive map at my website:

[http://mattmoehr.com/genesis/chicago-betashapes.html]()

To summarize, I used Open Street Maps to split Chicago up into little blocks. The blocks were then assigned scores based on how many geotagged photographs from Flickr were in, or near, the block. Blocks that have the same top-scoring neighborhood are aggregated together. A few additional steps are used to deal with orphaned blocks, gaps in the neighborhoods, and wonky topologies. The result is neighborhoods that are based on the street grid of Chicago and that represent the relative density of geotagged photographs uploaded by Flickr users. This procedure results in neighborhood boundaries with names and face validity, the accompanying article shows how the Flickr neighborhoods are also good at capturing socio-spatial behavior (like crime), and I think the future is very bright for neighborhood effects research based on social media data.

## Spatial Regime Models for Chicago Homicides

### Motivation

The spatial lag models used in chapter 3 are designed to parameterize and control for spill-over effects between adjacent neighborhoods. However, if there is a region of neighborhoods where a different set of mechanisms are at work, the parameter estimates of a spatial model may be incorrect. As @Artelaris2014 describes, we can think of all spatial modeling approaches as laying along a continuum from global models (e.g. spatial lag models) and local models (e.g. GWR, @Fotheringham1998). Local models estimate a set of parameters for every location. Global models, as the name implies, estimate one set of parameters for the entire study area. In between these two extremes, spatial regime models estimate separate parameters within pre-specified regions. @Artelaris2014 found that spatial regime models were the best fit for explaining economic integration among sub-national areas in Europe (these regions are analogous to U.S. states and are known as NUTS II). When regime models (or GWR models) out perform global models, the researcher has evidence for a non-stationary process, i.e. there is evidence of different effects in different places.

There is a high degree of residential segregation in Chicago, and going back to the Chicago School era a number of sociologists have posited that there is a different social worlds in the majority African-American area of South Side Chicago. I set up a spatial regime model to test the hypothesis that there is a non-stationary process of homicide patterns within the city. I'm not interested in exploring the stationarity of homicide patterns as a separate substantive question, but will be presenting this analysis as a check for the robustness of the findings in chapter 3. Do the conclusions from chapter 3 hold in the South Side and the rest of Chicago?

### Process

I downloaded a map of the 77 community areas in Chicago from the city's data portal.[^portal] Using information on Wikipedia[^wiki_sside] and the Chicago planning department, I marked 24 community areas as belonging to the "South Side." Then I found the spatial intersection between the South Side and each of the Sampson and Flickr neighborhood definitions. Figure 1 shows each of the neighborhood definitions with the South Side shaded in gray.

\begin{figure}[htbp]
    \centering
    \caption{Maps of Chicago's South Side.}
    \subbottom[Flickr neighborhoods.]{
      \includegraphics[width=5.5cm, keepaspectratio=true]{appendix_images/b2_flickr_2015-03-08.pdf}
    }
    \subbottom[Sampson neighborhoods.]{
      \includegraphics[width=5.5cm, keepaspectratio=true]{appendix_images/b2_sampson_2015-03-08.pdf}
    }
\end{figure}

[^wiki_sside]:
    [http://en.wikipedia.org/wiki/South_Side,_Chicago]()

[^portal]:
    [https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6]()

The spatial regime model is given by

$\log(Y + .8) = \rho W y + \beta_{k} K X + \varepsilon$

where $k$ is an index for each of the regions. The $K$ matrix is $N \times k$ matrix where all cells are valued 0 or 1, and it is constructed in a block pattern so each column is a dummy indicator if the neighborhood is the region -- in my case, the South Side of Chicago and the rest of the city. In essence, the regime model estimates a separate set of parameters for neighborhoods in the South Side of Chicago and the other neighborhoods. Note that the spatial parameter, $\rho$, and the error structure, $\varepsilon$, are still estimated across the entire study area. The hypothesis test is done by the normal likelihood ratio test for comparing nested maximum likelihood models. Most spatial regime analysis is interested in rejecting the null hypothesis that the regime model, call it $M'$, has the same overall likelihood as the global model, call it $M$. When this null is rejected, the researcher can claim that there are different effects of their variables in different sub-regions within their study area. I am less interested in comparing global models to regime models. Instead, let us call the global model estimated on Sampson's neighborhoods, $S$, and the one from Flick neighborhoods, $F$, and then $S'$ and $F'$ represent the respective regime models. Chapter 3 compares $S$ and $F$ and concludes:

1. The different neighborhood definitions cause the models to have different point estimates for the lagged homicide and street intersection parameters.
2. The spatial parameter, $\rho$ is approximately the same.
3. According to the correlograms, $F$ is at least as good as $S$ in reducing the spatial autocorrelation of the model residuals.
3. The variance of homicide counts is much higher when calculated with Flickr neighborhoods.

So my task in this appendix is to compare $S'$ to $F'$ to see if the four findings hold in sub-regions of Chicago like they do at the global level. As the model is set up with two parts, I'm testing that 1-4 hold in both the South Side region and in the rest of Chicago.

Table 1 shows the model results of the spatial regime model for Sampson's neighborhoods ($S'$). Table 2 shows results from Flickr neighborhoods ($F'$). The important comparisons here is between the Flickr and Sampson data sets. We see that the intercepts are significant in the Sampson data but not in Flickr; We see that the street intersections are significant in Flickr dataset but not Sampson; and while the parameters for unsolved homicides are positive and significant in both, the point estimates in the Flickr dataset are much lower. As in the global models, the point estimates from Flickr neighborhoods for unsolved homicides in both regions are lower than the lower-bound of the 95% confidence interval in the Sampson neighborhoods. Again, the spatial parameter is virtually identical in the two data sets.

\begin{figure}[htbp]
    \centering
    \caption{Correlograms of model residuals from spatial regime models.}
    \subbottom[Full study area (n = 345).\newline Sampson neighborhoods.]{
        \includegraphics[width=5.5cm, keepaspectratio=true]{appendix_images/b1_panel_a_2015-03-08.pdf}
    }
    \subbottom[Full study area (n = 289).\newline Flickr neighborhoods.]{
        \includegraphics[width=5.5cm, keepaspectratio=true]{appendix_images/b1_panel_b_2015-03-08.pdf}
    }
    \subbottom[South Side region (n = 94).\newline Sampson neighborhoods.]{
        \includegraphics[width=5.5cm, keepaspectratio=true]{appendix_images/b1_panel_c_2015-03-08.pdf}
    }
    \subbottom[South Side region (n = 91).\newline Flickr neighborhoods.]{
        \includegraphics[width=5.5cm, keepaspectratio=true]{appendix_images/b1_panel_d_2015-03-08.pdf}
    }
    \subbottom[Outside of South Side (n = 251).\newline Sampson neighborhoods.]{
        \includegraphics[width=5.5cm, keepaspectratio=true]{appendix_images/b1_panel_e_2015-03-08.pdf}
    }
    \subbottom[Outside of South Side (n = 198).\newline Flickr neighborhoods.]{
        \includegraphics[width=5.5cm, keepaspectratio=true]{appendix_images/b1_panel_f_2015-03-08.pdf}
    }
\end{figure}

Looking at Figure 2 we do not see as a clear of a case for supporting the 3rd conclusion within the spatial regime models. There is significant autocorrelation among the model residuals in at least one distance band within five of the six panels of Figure 2. This is an odd conclusion given that likelihood ratio tests suggested that, overall, the regime models were more accurately explaining the variation in homicide accounts. To my knowledge, no one has examined if spatial regime models help or hurt in reducing spatial autocorrelation among model residuals, so further research might be needed to understand if this is unique or common in spatial analysis. For this case, conclusion 3 holds in that Flickr neighborhoods are at least as good as Sampson neighborhoods -- even though both may be lacking -- in reducing autocorrelated errors in the two regions of Chicago.

Table 3 reproduces the key descriptive statistics used in chapter 3, which shows that in both the South Side and the remainder of Chicago the Flickr neighborhoods exhibit at least four times as much variation for the homicide variables. This is an important replication of the findings from chapter 3. Researchers often forget that at the bottom of the MAUP is how spatial aggregation affects the variance and covariance among measured variables. Therefore, Table 3 shows that Flickr neighborhoods are importantly different from Sampson's neighborhoods, and this difference is not simply an artifact of Flickr's smaller neighborhoods in The Loop. The conclusion also holds just within the South Side.

\begin{sidewaystable}[pht!]
\small
\centering
\begin{tabularx}{\textwidth}{r*{4}{d{-1}}}
  \toprule
 & \multicolumn{2}{c}{Flickr} & \multicolumn{2}{c}{Sampson} \\
 \cmidrule(l{2pt}r{2pt}){2-3}
 \cmidrule(l{2pt}r{2pt}){4-5}  
 & \multicolumn{1}{c}{South Side} & \multicolumn{1}{c}{Not South Side} & \multicolumn{1}{c}{South Side} & \multicolumn{1}{c}{Not South Side} \\ 
  \midrule
N & 91.00 & 198.00 & 94.00 & 251.00 \\ 
  n\_Y\_0 & 29.00 & 92.00 & 11.00 & 72.00 \\ 
  pct\_Y\_0 & 0.32 & 0.46 & 0.12 & 0.29 \\ 
  variance & 9146.73 & 15018.39 & 1870.21 & 4330.18 \\ 
  median\_Y & 2.00 & 1.00 & 4.50 & 2.00 \\ 
  ninetieth\_Y & 16.00 & 11.00 & 11.00 & 9.00 \\ 
  unsolved\_n\_0 & 37.00 & 116.00 & 23.00 & 115.00 \\ 
  unsolved\_pct\_0 & 0.41 & 0.59 & 0.24 & 0.46 \\ 
  unsolved\_variance & 2492.44 & 2609.37 & 865.28 & 1072.63 \\ 
  unsolved\_median & 1.00 & 0.00 & 2.00 & 1.00 \\ 
  unsolved\_ninetieth & 10.00 & 6.00 & 7.70 & 4.00 \\ 
  intersects\_n\_0 & 0.00 & 3.00 & 0.00 & 1.00 \\ 
  intersects\_pct\_0 & 0.00 & 0.02 & 0.00 & 0.00 \\ 
  intersects\_median & 69.00 & 93.50 & 99.00 & 82.00 \\ 
  intersects\_variance & 943725.60 & 2692932.15 & 363256.05 & 1250489.39 \\ 
  intersects\_ninetieth & 256.00 & 284.60 & 183.10 & 170.00 \\ 
   \bottomrule
\end{tabularx}
\caption{Descriptive statistics for regions in Chicago under alternative neighborhood definitions.} 
\end{sidewaystable}

### Limitations

One of the main limitations of this appendix is that there is no definitive boundary of Chicago's South Side. Indeed, setting up a spatial regime model asks the reader to ignore the threat of the MAUP at a second level. I chose to use a definition of the South Side based on the officially recognized community areas, but some areas right along I-94 are questionable as to which region they belong to. And it would also be possible to use a regime model approach to look at North Side, West Side, Southwest Side, etc. areas of Chicago. However, in terms of having a distinct regional politics, set of practices, and unique history, the South Side probably offers the most face validity as a true region warranting a spatial regime analysis. 

Additionally, there remains a curiosity in the finding that the LR tests suggest the superiority of the spatial regime models while correlograms of model residuals might suggest that they are worse than the global spatial model. This anomaly requires further research, but we can safely conclude that the four main findings from chapter 3 found globally in Chicago are found in both the South Side and the rest of Chicago. This strengthens the overall arguments in chapter 3 as the results can not be attributed to Flickr users avoiding or mislabeling ares of the city that are less white and less affluent.

\newpage

# Works Cited