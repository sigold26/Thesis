# Data Collection and Cleaning Log

## Source
- Dataset: `shows.csv`
- Repository: [deadlyarchive-data](https://github.com/ednunezg/deadlyarchive-data)
- File path (local): `thesis-data/shows.csv`
- Date downloaded: 2025-09-26
- Notes: CSV contains columns:
  `date, venue, city, state, category, etree_comments, ia_sources`.

## Justification for Dataset Choice
- **Comprehensive coverage:** The dataset spans early Warlocks shows (1963) through later Grateful Dead concerts, giving nearly complete chronological coverage.  
- **Curated by researchers:** The archive is compiled from DeadBase, Dead.net, fan blogs, and etree sources, representing the most reliable community consensus.  
- **Rich metadata:** Fields include performance details (`date`, `venue`, `city`, `state`) plus historical notes (`category`, `etree_comments`) and links to recordings (`ia_sources`).  
- **Transparency:** The dataset explicitly flags uncertainty (e.g., “Day uncertain”), preserving data quality by not overstating confidence.  
- **Reproducibility:** Hosted openly on GitHub, with a version history, making it verifiable and reusable by other researchers.  

## Steps

### Step 1: Initial Data Import
- **Action:** Downloaded `shows.csv` from deadlyarchive-data GitHub.
- **Tool:** GitHub / VS Code
- **Notes:** Dataset covers Grateful Dead (and Warlocks) shows from 1963 onward. 
  Verified fields match repository documentation:  
  `date, venue, city, state, category, etree_comments, ia_sources`.





Deleted 7/10/69 it was show date not the recorded date on a tv show

11/4/69 show no where to be found deleted row

12/2/67 deleted no show found

1/2/68 deleted no show found

2/25/84

6 unknown locations deleted

4/7/66
10/19/70
9/14/87
12/28/68
3/27/69
10/17/69

2/1/66 deleted it was a rehersal


Creating the music venues csv
exported html from wikipedia with help from research librarian Bonnie and then went through in sheets and made each row have the city and state by dragging down the cells

then i cleaned the capacity field by making a new variable cleaned_capacity with only the numbers from the original capacity field



delete 

Winterland Arena (aftershow) as it doesnt have a date of the show

deleting all rows that don't have a show date







11-19-25_VENUE_PIVOT_TABLE    pivot table with just venue from dead shows still zip code needs 0s before


need to standardize street vs st etc