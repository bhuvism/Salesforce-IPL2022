# Salesforce-IPL2022

Implementation Details 

Component 1: uses two to display the Teams dropdown. It fetches the Team Name and Code from the Object Team__c and renders dynamically. There is a Reset Button, upon clicking it reset the dropdowns in Component 1, Reset the Component 1 and Component 3 as well. 

Component 2: shows the Team Icons and Owner Details upon Team Selection in Component 1. The communication between Component 1 and Component 2 happens via LMS. The Team Tiles are based on boatTile from LWC Super Badge. Same code can be reused. 

Component 3: initially shows all the IPL2022 matches. Upon Team Selection in Component 1 the results are filtered to show specific team matches. 

Component 4: This component shows IPL news in Tiles. News Tiles are based on bearTile from (Build a Bear-Tracking App with Lightning Web Components). Same code can be reused. 

Validations Used: 

  1.Upon selection of same team in both dropdown an error message gets displayed. 

  2.Team tile displays None if there is no Team selected in Component 1. 
