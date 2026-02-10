2026 Maltego CTF - 2nd place finish (Team SE4L)

THE GRINCH 

Challenge 1 - What is the IMO of the tanker mentionned in this BBC article?
https://www.bbc.com/news/articles/c62vke5dly2o

STEPS TO SOLVE: 
1. Locate ship name.
  - The Grinch
2. Search IMO number for The Grinch ship.
  - 9288851 (source: https://www.marinetraffic.com/en/ais/details/ships/shipid:2142/mmsi:620999912/imo:9288851/vessel:GRINCH)

Flag: 9288851

-------

Challenge 2 - During which year was the Grinch built?

STEPS TO SOLVE:
1. Locate year built from maritime website.
  - 2004 (source: https://www.vesselfinder.com/vessels/details/9288851)

Flag: 2004

-------

Challenge 3 - What company is the registered owner of the Grinch?

STEPS TO SOLVE: 
1. Locate information from another maritime website.
  - CUBE VENTURES SHIPPING SA (source: https://magicport.ai/vessels/tanker/grinch-mmsi-620999912)

Flag: CUBE VENTURES SHIPPING SA

------

Challenge 4 - This company (CUBE VENTURES SHIPPING S.A.) was recently annuled.What is the exact date of the annulment?

STEPS TO SOLVE:
1. Locate annulment info from business information website.
  - 2025-01-10 (source: https://sanctions.lursoft.lv/person/cube-ventures-shipping-sa/ofac-51721)

Flag: 2025-01-10

-----

Challenge 5 - What company was the previous owner of the Grinch?

STEPS TO SOLVE: 
1. Locate previous ship names due to new owners usually changing the name of the ship.
  - CARL (source: https://www.vesselfinder.com/vessels/details/9288851)
2. Locate ownership history for the ship CARL/
  - UML Dorset Ltd (source: https://ship-photo-roster.com/ship/carlton)

IMPORTANT: The ship name does NOT change if the owner changes the ship's name. This is important because you can track the ship over time by using the unique IMO number.

Flag: UML Dorset Ltd

-----

Challenge 6 - UML Dorset Ltd acquired this vessel using a loan. What is the name of the lender?

STEPS TO SOLVE:
1. Locate legal documents. These names appear on the UML Dorset charges register in connection with ship security.
2. Sift through documents for loan history.
  - Northern Shipping Fund III LP (source: https://find-and-update.company-information.service.gov.uk/company/09925326/charges)

Flag: Northern Shipping Fund III LP
