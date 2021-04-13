# BoranetWork
Coding for the benefit of Boranet 

# Amazon Bot v 1.01
### 3 different bots
1) Onscreen outputter 
2) CSV writer
3) *Current project: Pagination and product page looping

POINT 1: Executing a search with specific keywords will produce a SERP of products related to those keywords (for ex. Searching "mechanical keyboards" will produce SERPs of keyboards and computer related products.

POINT 2: The products that appear on the first SERP are either sponsored by a paid keyword, have good keyword SEO, or have high authority from many reviews/ratings/brand image.

POINT 3: Scraping the information from the first few pages provides us with 3 different reliable sources to reference from. Paid listings, SEO listings, and High Authority listings.

# Paid listings are promising because of the base level of competition for any industry. These listings tend to be heavily optimized, rather, "heavily prepped for good impression."
![image](https://user-images.githubusercontent.com/82443544/114599804-9590fd00-9c61-11eb-8dcf-4eb6baf7546e.png)


# SEO optimized listings have lower ratings and authority, but still rank on first page
![image](https://user-images.githubusercontent.com/82443544/114601923-0b966380-9c64-11eb-8347-0146f0cd81be.png)


# High Authority listings have extremely high ratings and at that point, the keyword revolves around the product, not the other way around.
![image](https://user-images.githubusercontent.com/82443544/114602381-89f30580-9c64-11eb-958e-ca202f2ff66c.png)

# Directions
<br> Step 1: Create folder on desktop and put Mozilla driver (gecko), Mhrome driver, or MSEDGE driver in that folder. </br>
<br>Step 2: Navigate to that the folder's directory when executing the code. Or set the folder path in code, whatever you want.</br>
<br>Step 3: Don't execute records.clear() first. Execute below the header "Boranet AMAZON SCRAPER version(1.01).</br>
<br>Step 4: Use records.clear() to clear the records cache after each search. No point executing it on the first search.</br>
