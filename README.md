# Reentry 2030 Dashboard Mockup

## Project overview  

The goal of the Reentry 2030 Dashboard is to provide states with the tools to track, analyze, and improve reentry outcomes for individuals transitioning from the criminal justice system back into the community. The dashboard will focus on a set of standardized outcome measures related to recidivism, employment, housing, and health.  

This particular dashboard mockup and visualization work will facilitate conversation with Reentry staff and eventually external designers, who will ultimately build the public-facing dashboard, as well as potential attempts to collect additional data from Reentry 2030 states.

**Analysis Plan for Reentry 2030 Dashboard:** https://csgorg.sharepoint.com/:w:/r/sites/Team-JC-Research/Shared%20Documents/CRD_Reentry%202030/Deliverables/Analysis%20Plan%20for%20Reentry%202030%20Dashboard.docx?d=wb7166caab9de4394a552b401c6bcee08&csf=1&web=1&e=DgzGIf

## Data  
All CJARS county- and state-level data is stored on SharePoint here: https://csgorg.sharepoint.com/:f:/r/sites/Team-JC-Research/Shared%20Documents/CRD_Reentry%202030/Background/CJARS%20Documentation?csf=1&web=1&e=7oNMfK

## Netlify site
Link: https://reentry-2030-dashboard-mockup.netlify.app/ 
Password: csgjc_reentry_2030

## Assigned Research Staff
Becky Cohen, Shradha Sahani, Andrew Byrum (dashboard work only)


## Repo Structure

```
|-- jr-nc 
  |-- .github               
  |-- _freeze                
  |-- _site                 # folder with netlify site html files stored and structured
  |-- fonts
  |-- .gitignore
  |-- R               # folder wtih additional utils script (for storing function, etc.)
            |-- utils.r               # files with frequently used functions, etc. that are called in other qmd files
  |-- _quarto.yml              # file with specified structure for netlify site
  |-- index.qmd    # netlify landing page -- serves as national page mockup
  |-- reentry_dashboard_state_page.qmd    # mockup for state pages (using one state as example)
  |-- reentry_dashboard_cleaning_code.qmd    # script with all cleaning/prep code for CJARS state- and county-level files
  |-- README.md              
  |-- reentry-2030-dashboard.Rproj    # R project file
  |-- style.css   # file with custom CSS script for html output
```

