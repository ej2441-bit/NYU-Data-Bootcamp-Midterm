# Vogue 2024 Ready-to-Wear Analysis
This project presents an exploratory data analysis of the 2024 Ready-to-Wear collections from *Vogue Runway*. The study investigates relationships among fashion styles, designers, locations, and industry opinions, and more.

## Executive Summary

This project to analyze the fashion trends within the 2024 fashion season through *Vogue Runway*'s database covers 834 collections. The project is driven by three questions:
1. Do the most popular/common brands' collections match the most popular/common styles? If so, does that trend follow the industry's opinion of what the popular styles are for that year or season? Do the most influential brands in 2024 lead trends or follow consumerist style trends?
2. Which brands or designers had the most looks for each season?
3. Does a specific fashion week yield more brands? Are there more looks presented in a specific fashion week? If so, what could be the reason?
and yielded many innaccurate and incomplete results due to flaws and malfunctions with scraping, server load times, variances in coding languages, updated system versions, issues with hyperlinks, substantial scraping times (over 800 collections were scraped), and time restrictions. While some information was obtained, the statistics should be taken with a large amount of salt. The researched conducted indicates that it can be reasonable to determine that brands did not lead trends or follow consumerist style trends in the 2024 fashion season.

## Introduction
Hundreds, if not thousands, of fashion brands showcase their collections twice a year — in the *Fall/Winter* and *Spring/Summer* seasons. During these seasons, fashion collections are presented six months in advance to when they are released to the public for wear. With so many different brands releasing products annually, analyzing the patterns and statistics behind the two seasons presents a stimulating opportunity. 

Through sourcing data from *Vogue Runway*, this project aims to answer the following:
1. Do the most popular/common brands' collections match the most popular/common styles? If so, does that trend follow the industry's opinion of what the popular styles are for that year or season? Do the most influential brands in 2024 lead trends or follow consumerist style trends?
2. Which brands or designers get the most coverage in *Vogue* per season? Does a brand's look count correlate with more popular or widely referenced collections?
3. Does a specific fashion week yield more brands? Are there more looks presented in a specific fashion week? If so, what could be the reason?

## Research Question #1: Did the most popular/common brands' collections match the most popular/common styles? If so, did that trend follow the industry's opinion of what the popular styles are for that year or season? Did the most influential brands in 2024 lead trends or follow consumerist style trends?
For some, or perhaps most, the question of whether or not brands cater to industry trends is one that manifests itself quite frequently. In Figure 1, the top 10 brands (ignoring Unknown Brand: Sachin & Babi, H&M Studio, Cos, Emilio Pucci, Cult Gaia, Alexander Wang, Area, Simkhai, and Jacquemus) are displayed through considering their total collection count for the year. And for those brands, the styles that are prominent are — Classic and Bold.

As *Vogue* is arguably the leading fashion magazine globally, information was sourced from the magazine to discover what the most popular styles of the 2024 season were. For the *Spring/Summer* season, trends followed Minimalist, Romantic, Bohemian, Preppy, and Tailored styles (Abbas and Fass). For the *Fall/Winter* season, Utilitarian, Gothic, Structured, and Layered styles dominated (Abbas). Analyzing the results, there are of course overlapping styles, but the Figure yielded a minuscule amount of style keywords. Comparing the information between Figure 1 and what *Vogue* determined to be the trending styles, it can be deduced that there was a very minimal correlation with brand styles and trending styles in the 2024 fashion season. Since the correlation is negligible, it can be reasonable to determine that brands did not lead trends in the 2024 fashion season.

While there is information to suggest that brands did not lead trends, the question remains as to whether or not they follow consumerist style trends. Since collections are shown six months in advance, to analyze *Spring/Summer* 2024, which was showcased in September 2023, data and opinions from 2023 must be analyzed. Referring to *Vogue* again, 2023's trending styles were — Quiet Luxury, "Old-Money" Aesthetic, Barbiecore, Mermaidcore, Balletcore, Tomato-Girl Summer, Europecore, and Succubus Chic (Spellings). As for *Fall/Winter*, statistics from both 2023 and 2024 can be analyzed to come to a conclusion. When compared to Figure 1's results, it can be determined that brands don't follow consumerist style trends.

However, other factors such as top-grossing movies, celebrity endorsements and brand deals, sudden innovation in brands, top-performing shows, popular events, and more also need to be considered in the analysis. The figure is just utilizing information from *Vogue Runway*'s database. Furthermore, Figure 1 provides limited information and a lot of "No Style Keywords", likely due to the scraping method failing to capture data for all brands, yielding minimal results for various fashion styles. With that in mind, the analysis is not applicable to the industry. Unfortunately, due to time restrictions and the substantial execution time for scraping, no further explorations or adjustments were made to the code.

## Research Question #2: Which brands or designers had the most looks for each season?

Although a more basic question, the number of looks provides some insight into numerous factors such as: brand dedication for the collection, brand popularity, and brand wealth. Utilizing Figures 2 and 3, for *Spring/Summer*: Jacquemus, Sachin & Babi, Cos, Cult Gaia, Sumkhai, Simon Miller, H&M Studio, Alexander Wang, and Emilio Pucci all had three looks; *Fall/Winter*: Area, Apiece Apart, Sachin & Babi, Moncler Genius, Cos, Cult Gaia, Alexander Wang, H&M Studio, and Emilio Pucci also all had three looks.

However, this data is unreliable. When inspecting the DataFrame, every collection only had one look — a clear sign of failed scraping. The look_count code may have missed images if the HTML structure is different or if images are lazy-loaded dynamically. As a result, any analysis requiring the factor of look counts is jeopardized. And like with the first figure, there was no more time to rework and refine the code.

## Research Question #3: Did a specific fashion week yield more brands? Were there more looks presented in a specific fashion week? If so, what could be the reason?

When it comes to fashion, location is one of the primary aspects towards the medium. As seen in Figure 4, London Fashion Week and Milan Fashion Week had an average of two looks per brand while
New York Fashion Week had one. No information was given for Paris Fashion Week. On the other hand, Unknown also had an average of two looks per brand.

Sometimes, there may simply be no indicator of a specific fashion week for the brand. Still, having fewer than 10 fashion week locations (as indicated by the DataFrame) strongly suggests that the scraper did not function properly — or perhaps it did, but didn’t interact well with *Vogue*'s system.

However, for the sake of having some sort of analysis using the data collected, it could be inferred that London and Milan Fashion Weeks did have more collections than New York Fashion Week and Paris Fashion Week. Italy, and Milan in particular, is known as the home of fashion. London on the other hand also has a renowned fashion scene. The prestigious college, Central Saint Martins resides there. But again, with the flaws in the code, this is all mere speculation.

## Conclusion

Overall, while an intriguing opportunity, the many technical difficulties compounded with the time constraints did not allow for an accurate collection and analysis of the 2024 fashion season with *Vogue*'s Ready-to-Wear database. If given more time, perhaps the statistics and results could be more solid.

## Works Cited

“Vogue Runway.” Vogue, Condé Nast, 2024, www.vogue.com/fashion-shows. Accessed 25 Oct. 2025.

Abbas, Talia, and Madeline Fass. “11 Spring 2024 Fashion Trends You Can Shop Right Now.” Vogue, 23 Feb. 2024, https://www.vogue.com/article/spring-2024-fashion-trends. Accessed 25 Oct. 2025.

Abbas, Talia. “15 Winter Trends Vogue Editors Are Adding to Their Carts, ASAP.” Vogue, 6 Nov. 2024, https://www.vogue.com/article/fall-shopping-list-editor-picks-2024. Accessed 25 Oct. 2025.

Pandas Development Team. “pandas-dev/pandas.” GitHub, 2025, github.com/pandas-dev/pandas. Accessed 25 Oct. 2025.

Spellings, Sarah. "The Aesthetics, -Cores, and Microtrends That Defined 2023." Vogue, 12 Dec. 2023, www.vogue.com/article/core-aesthetic-microtrends-2023. Accessed 25 Oct. 2025.

Playwright Team. Playwright for Python Documentation. Microsoft, 2025, playwright.dev/python. Accessed 25 Oct. 2025.

Python Software Foundation. Python 3.11 Documentation. 2025, docs.python.org/3/. Accessed 25 Oct. 2025.

W3C. *HTML Living Standard*. WHATWG, 2025, html.spec.whatwg.org/. Accessed 25 Oct. 2025.
