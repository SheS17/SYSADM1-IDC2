![image](https://github.com/user-attachments/assets/4ed86b51-a7db-4e14-b1c6-c7456d4b188d)


# SYSADM1 -- Capacity Management & Planning

## Part 1. A Simulated Dataset for Capacity Planning Exercise

**Scenario:** A mid-sized e-commerce
website is expecting a significant surge in traffic due to an upcoming
holiday sale.

### [Projected Traffic Increase]{.underline}

-   **Expected Peak Traffic:** 5x the normal peak traffic

-   **Peak Time:** 12:00 PM - 3:00 PM on the sale day

### [System Specifications]{.underline}

-   **Server Count:** 5

-   **CPU Cores per Server:** 8

-   **RAM per Server:** 32GB

-   **Network Bandwidth per Server:** 1Gbps

### [Additional Considerations]{.underline}

-   **New Product Launch:** A highly anticipated product will be
    released during the sale.

-   **Marketing Campaign:** A major marketing campaign will be launched
    to promote the sale.

-   **Potential Cyber Threats:** Increased traffic can attract malicious
    actors.

Tasks:

1.  Review the provided server performance data and identify potential
    bottlenecks

2.  Brainstorm possible solutions to address the identified bottlenecks.
    Propose potential solutions considering hardware and software-based
    solutions.

3.  Discuss the pros and cons of each proposed solution by filling out
    the table below.

+-------------+---------------+------------+--------------+-----------+
| Proposed    |               | Cost       | Complexity   | Potential |
| Solution    | ------------- |            |              | impact on |
|             |   Pros   Cons |            |              | system    |
|             |               |            |              | pe        |
|             | ------ ------ |            |              | rformance |
|             |               |            |              |           |
|             |               |            |              |           |
|             | ------------- |            |              |           |
+=============+===============+============+==============+===========+
+-------------+---------------+------------+--------------+-----------+

Grading Rubric:

  -------------------------------------------------------------------------------
  Criteria           Excellent \| 10pts Good \| 7pts        Needs Improvement \|
                                                            4pts
  ------------------ ------------------ ------------------- ---------------------
  **Problem          Accurately         Identifies the main Identifies a problem
  Identification**   identifies the     problem and         but lacks clarity or
                     primary problem    provides a basic    accuracy.
                     and provides a     explanation.        
                     detailed                               
                     explanation.                           

  **Solution         Proposes multiple  Proposes one or two Proposes a solution
  Proposal**         relevant solutions relevant solutions  but lacks feasibility
                     and provides       but lacks detailed  or relevance.
                     detailed           explanation.        
                     explanations,                          
                     including                              
                     potential                              
                     drawbacks and                          
                     benefits.                              

  **Evaluation of    Provides a         Provides a basic    Does not evaluate the
  Solutions**        thorough           evaluation of the   proposed solutions or
                     evaluation of the  proposed solutions, provides a
                     proposed           but lacks depth.    superficial
                     solutions,                             evaluation.
                     considering                            
                     factors like cost,                     
                     complexity, and                        
                     potential impact.                      

  Score:                                                    /30
  -------------------------------------------------------------------------------

**Part 2. Network Scalability Analysis**

Recall the e-commerce website scenario we discussed earlier. Given the
expected surge in traffic, analyze the provided network topology
diagram. Identify potential bottlenecks and areas where scalability
might be a concern. Propose specific strategies to improve the
network\'s scalability and performance to ensure a seamless user
experience during the peak traffic period. Consider factors such as
increased user demand, new applications, and security threats.

![](vertopal_d27bb325841f497d91710e4c6cd1bb9d/media/image3.webp){width="5.049483814523184in"
height="3.8229166666666665in"}

Identified Problems:

-   No redundancy

-   No Internet backup

-   If one switch fails, server and computer will not work connected to
    that device

-   

![image](https://github.com/user-attachments/assets/7de5e78e-98bd-477d-8e65-8e20304babad)


  ------------------------------------------------------------------------------
  Criteria          Excellent \| 10pts Good \| 7pts        Needs Improvement \|
                                                           4pts
  ----------------- ------------------ ------------------- ---------------------
  **Network         Accurately         Identifies key      Identifies some basic
  Analysis**        identifies         network components  network components
                    potential          and some potential  but lacks a
                    bottlenecks,       bottlenecks.        comprehensive
                    security risks,                        analysis.
                    and capacity                           
                    limitations.                           

  **Scalability     Proposes multiple  Proposes some       Proposes limited
  Planning**        relevant solutions relevant            scalability
                    and provides       scalability         strategies.
                    detailed           strategies but      
                    explanations,      lacks detail.       
                    including                              
                    potential                              
                    drawbacks and                          
                    benefits.                              

  **Evaluation of   Proposes           Provides a basic    Does not evaluate the
  Solutions**       comprehensive      evaluation of the   proposed solutions or
                    scalability        proposed solutions, provides a
                    strategies,        but lacks depth.    superficial
                    including specific                     evaluation.
                    recommendations                        
                    for hardware                           
                    upgrades, software                     
                    configurations,                        
                    and network                            
                    optimizations.                         

  **Proposed        Provides a         Provides a basic    Does not provide a
  Design**          detailed and       design but lacks    clear and detailed
                    well-justified     specific details    design.
                    design, including  and justifications. 
                    network diagrams,                      
                    configuration                          
                    details, and                           
                    implementation                         
                    plans.                                 

  **Evaluation and  Provides a         Provides a basic    Does not evaluate the
  Justification**   thorough           evaluation of the   proposed solutions or
                    evaluation of the  proposed solutions, provides a
                    proposed           but lacks depth.    superficial
                    solutions,                             evaluation
                    considering                            
                    factors like cost,                     
                    complexity, and                        
                    potential impact.                      

  Score:                                                   /50
  ------------------------------------------------------------------------------
