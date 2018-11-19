# Unpaywall_Pull
Python code designed to pull open access counts from Unpaywall API  for a list of DOIs

Import a csv file with DOIs in the first column and this python program will export a csv file.

The csv file will have the following info for all the DOIS:
- DOI
- Document Type
- Journal
- Publisher
- Year
- Published OA (Will have a '1' if it was published OA, '0' if not)
- Hybrid OA (Will have a '1' if it is Hybrid, '0' if not)
- Bronze OA (Will have a '1' if it is Bronze, '0' if not)
- Self-Archived OA Count (Number of self-archived OA copies that unpaywall can find)
- Link (Link to the unpaywall API data page for this article)

Be careful when running large sets of DOIs. Program can take a long time.

