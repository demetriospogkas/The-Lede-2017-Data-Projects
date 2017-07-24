# Project Diary  

### Log #01 2017-07-17 07:49EST
Initialize Project Diary. It will be used during project realisation to keep track of problems/helpful stackoverflow links/etc.

### Log #02 2017-07-17 10:21EST
Project pitch files uploaded on GitHub. Looking forward to some constructive feedback from my peers and instructors.

### Log #03 2017-07-17 10:47EST
Feedback session on!

### Log #04 2017-07-17 11:12EST
Feedback session over, my peers had a lot of helpful things to say. I should look into incorporating their input.

- adaskalopoulou commented 11 minutes ago  
I like the slider idea!  
What will be the level of "zoom" of your map? States, cities, neighborhoods?

- simon-pinkmartini commented 9 minutes ago  
Many of the questions you are asking will already have been asked by professionals in the real estate fields. They have tons of graphics on this stuff. I would try to focus on the user experience, i.e. the zip-code box where people can compare their own home with national or state averages.

- JulienAssouline commented 8 minutes ago  
I would recommend not using a slider for this map and maybe using a gif. Showing the year 2012 to 2017. Or, you could just put both images side by side as static.

### Log #05 2017-07-19 14:43EST
Talked about my project idea and work so far to Georgia. She advised me to combine the real-estate data with another dataset to try and answer some solid question, or focus on a specific geography, instead of just mapping the real-estate prices across the USA (that shouldn't be really interesting). Cannot say she's wrong...

### Log #06 2017-07-19 15:04EST
Getting feedback and opening up your thoughts and plans is always leading to some great different paths of thinking. I do need to pivot my project idea, and what looks really interesting to investigate is listing prices before, after and during Columbia University Manhattanville Campus expansion.

### Log #07 2017-07-19 16:11EST
Wikipedia brief history of Manhattanville Campus:
- Manhattanville is the site of a planned major expansion of Columbia University. The university purchased several square blocks of the neighborhood between 125th[8] and 133rd Streets on the south and north and between Broadway and 12th Avenue on the east side of Broadway from 131 to 134, west of the housing projects. (note: Because of the dogleg shape of 125th Street on the west side, 125th Street and 129th Street merge, and so only four or five blocks are involved in the tract.)  
- In June 2007, the New York City Department of City Planning certified that Columbia's application for the rezoning is complete. This action launched the public review and comment period under the city's Uniform Land Use Review Procedure, which lasted until the end of 2007.  
- In December of the [2007], the New York City Council voted to approve Columbia’s proposed rezoning of the site.  
Source: https://en.wikipedia.org/wiki/Manhattanville,_Manhattan#University_expansions

Columbia Manhattanville About page:
- overwhelmingly approved by New York City's Planning Commission and City Council in 2007.  
- It includes more than 17 acres of property on the blocks from West 125th Street to 133rd Street between Broadway and 12th Avenue, as well as several properties on the east side of Broadway, from 131st to 134th Street.  
- The local street grid, which will remain unchanged as part of the open campus plan, is defined by the distinctive northwesterly slant of the western-most blocks of 125th Street. As a result, at the southern end of the site, 125th Street intersects with 129th Street, creating a small triangle block that is also a key part of the campus design.  
- Above ground, both Broadway and 12th Avenue are distinguished by historic viaducts—the IRT number 1 subway line viaduct and the Riverside Drive viaduct—that provided inspiration for several of the new building designs.  
- The campus’s academic cornerstone, the Jerome L. Greene Science Center, is home to the Mortimer B. Zuckerman Mind Brain Behavior Institute that will join together scholars from across the University in interdisciplinary partnerships that will redefine the frontiers of neuroscience.  The Lenfest Center for the Arts will provide a variety of new spaces for Columbia's School of the Arts and Miriam and Ira D. Wallach Art Gallery, as well as a new West Harlem home for exhibitions, film screenings, performances, programs and creativity. In 2018, they will be joined by the University Forum and Academic Conference Center—all three buildings designed by Pritzker Prize-winning architect Renzo Piano Building Workshop. Soon to break ground will be a new home for Columbia Business School that will relocate from the Morningside Heights campus to the new Kravis and Perelman buildings designed by Diller Scofidio + Renfro. In between will be a landscaped one-acre green space, a welcoming amenity not only for the University community, but for the local community and general public as well.  

Source: http://manhattanville.columbia.edu/about



### Log #08 2017-07-19 16:16EST
Need to find pre-2012 data.
Zillow offers some data up to 1997. What index should I use? I will start working with Median Home Value per Sq Ft, or ZHVI All Homes (SFR, Condo/Co-op) Time Series ($),  or ZRI Time Series: Multifamily, SFR, Condo/Co-op ($)
Source: https://www.zillow.com/research/data/

### Log #09 2017-07-19 19:03EST
I just finished with Manhattanville Campus geometries. I need to think what my geometries of affected area should be in order to calculcate change in real-este prices in. A radius of 1-5 miles should be okay?

