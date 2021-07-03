# Election Analysis

* ## Overview of Election Audit

    * ### Background
        The project is started with helping Tom and Seth to go over the tasks that need to be completed for election audit,and discuss the information needed by the Colarodo Board of Elections. In the Initial stage Election commission requested the information about:

      * Total number of votes cast
      * A complete list of candidates who received votes
      * Total number of votes each candidate received
      * Percentage of votes each candidate won
      * The winner of the election based on popular vote
      * We have successfuly submitted the audit report to Election Commission.

      Now The Election commission want to get some additional information in order to complete the audit.

  * ### Purpose

    Puropse of this project is to help Tom and Set. Election Commission now wants some additional data to complete the audit which is:

    * The voter turnout for each county
    * The percentage of votes from each county out of teh total count
    * The county with highest turnout.

    The Deliverables are:
    1. The Election Results Printed to the Command Line
    2. Election Results Saved to a Text File
    3. A written Analysis of the Election Audit
    
 
* ## Election-Audit Results:

  * How many votes were cast in this congressional election?

    The total number of votes casted in congressional election are 369,711.

    The code for how to find and final results as as below:

    [Code Snippet](https://github.com/rachanamule/Election_Analysis/blob/00a9aa05913eca8915be839f940bf2ea38afd69e/resources/code_snippet_for_total_votes.png)

    [Result Total Number of Votes](https://github.com/rachanamule/Election_Analysis/blob/8fe035bd085c123a43bcf5f14c4ccc4eb3766e54/resources/Total_number_of_votes_casted.png)

  * Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

    Please refer below image for getting more information about countywise percentage of total number of votes. And the code for that is in code snippet as below:

    [Code Snippet](https://github.com/rachanamule/Election_Analysis/blob/00a9aa05913eca8915be839f940bf2ea38afd69e/resources/code_snippet_countywise_data.png)

    [Countiwise Results](https://github.com/rachanamule/Election_Analysis/blob/8fe035bd085c123a43bcf5f14c4ccc4eb3766e54/resources/countywise_total_percentage_votes.png)

  * Which county had the largest number of votes

    Denver county has the largest number of votes. Code and results are given in link:

    [code Snippet](https://github.com/rachanamule/Election_Analysis/blob/00a9aa05913eca8915be839f940bf2ea38afd69e/resources/code_snippet_county_largest_number_of_votes.png)

    [Output Image](https://github.com/rachanamule/Election_Analysis/blob/00a9aa05913eca8915be839f940bf2ea38afd69e/resources/winning_county.png)

  * Provide a breakdown of the number of votes and the percentage of the total votes each candidate recieved.

    Please refer below image for getting more information about candidate's percentage of total number of votes.

    [Code Snippet](https://github.com/rachanamule/Election_Analysis/blob/00a9aa05913eca8915be839f940bf2ea38afd69e/resources/code_snippet_candidate_data.png)

    [Output Image](https://github.com/rachanamule/Election_Analysis/blob/8fe035bd085c123a43bcf5f14c4ccc4eb3766e54/resources/votes_percent_breakdown_per_candidate.png)

  * Which candidate won the election,what was their vote count,and what was their percentage of the total votes?

    Diana DeGette Won the election and details are as shown in below link

    [Code Snippet](https://github.com/rachanamule/Election_Analysis/blob/00a9aa05913eca8915be839f940bf2ea38afd69e/resources/code_snippet_winning_candidate_data.png)

    [Output Image](https://github.com/rachanamule/Election_Analysis/blob/8fe035bd085c123a43bcf5f14c4ccc4eb3766e54/resources/winning_candidate_data.png)
    
    
   The Deliverable 1 output image is as follows:
    
    [Election Results Printed on Command Line](https://github.com/rachanamule/Election_Analysis/blob/9de932205d907a19de83b65f7250d46d3ac6efaf/resources/Election_Results_cmd.png)
    

* ## Election-Audit Summary:

   So, As we seen writing python script for election audit is really helpful and time saving. 

   [Code for retriving data from CSV](https://github.com/rachanamule/Election_Analysis/blob/8fe035bd085c123a43bcf5f14c4ccc4eb3766e54/resources/code_snippet1.png)

   Here we used election_result.csv for colarodo likewise we an use for any other state the only thing we need to change is csv in the above script.

   This script can be easily used to fit any type of election with some modifications.

   Lets say, If we want to analysis a federal congressional election, all you need to do is change the counties to states. 

   Another example, if you had a local election, all you need to do is change candidates to in favor or opponent.


