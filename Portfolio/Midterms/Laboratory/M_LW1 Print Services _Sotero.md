+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| d5058af5348f49b39faf61b92ea8a5a6 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Shekinah Sotero            | DATE PERFORMED:        | /50      |
+----------------------------------+------------------------+----------+
| Section: IDC2                    | DATE SUBMITTED:        |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Monitoring Print Services in Windows Server 2019

# Requirement: 

-   A virtual machine running Linux and Windows OS

Part 1: Setting Up Print Services

1.  Install and configure **print.srv** domain

2.  Connect one client to the recently created domain

3.  Install Print Services Role:

4.  Search the internet for any printer installer and convert it to iso

+-----------------------------------------------------------------------+
| ![](vertopal_d5058af534                                               |
| 8f49b39faf61b92ea8a5a6/media/image2.png){width="2.5773917322834645in" |
| height="1.7521380139982503in"}                                        |
| ![](vertopal_d5058af53                                                |
| 48f49b39faf61b92ea8a5a6/media/image3.png){width="1.166829615048119in" |
| height="1.791917104111986in"}                                         |
| ![](vertopal_d5058af534                                               |
| 8f49b39faf61b92ea8a5a6/media/image4.png){width="1.2085017497812773in" |
| height="1.802334864391951in"}                                         |
|                                                                       |
| ![](vertopal_d5058af53                                                |
| 48f49b39faf61b92ea8a5a6/media/image5.png){width="5.773057742782152in" |
| height="0.9904166666666666in"}                                        |
+=======================================================================+
+-----------------------------------------------------------------------+

5.  Install and deploy it as network printer

Part 2: Monitoring Print Services

Objective: Familiarize yourself with monitoring tools available in
Windows Server 2019.

1.  Event Viewer:

    -   Open Event Viewer (run eventvwr.msc).

    -   Navigate to Applications and Services Logs \> Microsoft \>
        Windows \> PrintService.

    -   Review logs for print jobs, errors, and warnings.

+-----------------------------------------------------------------------+
| Admin: This log tracks errors and warnings related to print services. |
|                                                                       |
| Operational: This log records detailed information about each print   |
| job, including successful or failed print jobs.                       |
+=======================================================================+
+-----------------------------------------------------------------------+

2.  Performance Monitor:

    -   Open Performance Monitor (run perfmon).

    -   In the left pane, expand Data Collector Sets \> System.

    -   Right-click System Performance and select Start.

    -   Monitor performance metrics related to print services.

3.  Using Print Management Console:

    -   Open Print Management from Server Manager.

    -   View active print jobs and their status.

    -   Use the Printers node to check the status of all printers.

Part 3: Exploring Third-Party Monitoring Tools

1.  Research at least two third-party print monitoring tools

    -   Consider factors such as features, pricing, and compatibility
        with Windows Server 2019.

2.  Install and Configure:

    -   Choose one of the tools to install in your environment.

    -   Follow the installation instructions provided by the tool\'s
        documentation.

    -   Configure it to monitor your print services.

3.  Test and Report Findings:

    -   Generate a report or dashboard from the tool.

    -   Analyze the collected data (e.g., print volume, errors, user
        activity).

Rubric

  --------------------------------------------------------------------------------------------------------------
  **Criteria**   **1                  **2 (Needs       **3                **4        **5             **Score**
                 (Unsatisfactory)**   Improvement)**   (Satisfactory)**   (Good)**   (Excellent)**   
  -------------- -------------------- ---------------- ------------------ ---------- --------------- -----------

  --------------------------------------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------
  **Part 1: Setting Up Print Services**                                          
  --------------------------------------------------------------- -- -- -- -- -- --

  ---------------------------------------------------------------------------------

  ----------------------------------------------------------------------------------
  **Domain         No domain Domain     Domain      Domain       Domain           
  Installation**   created   created    created     configured   configured and   
                             with       correctly   well         documented       
                             errors                              thoroughly       
  ---------------- --------- ---------- ----------- ------------ ---------------- --

  ----------------------------------------------------------------------------------

  --------------------------------------------------------------------------------
  **Client       Client not  Connection   Client      Client      Client        
  Connection**   connected   attempt      connected   connected   connected and 
                             failed       but with    correctly   documented    
                                          issues                  well          
  -------------- ----------- ------------ ----------- ----------- ------------- --

  --------------------------------------------------------------------------------

  ------------------------------------------------------------------------------------
  **Print Services Role not    Role        Role        Role         Role installed, 
  Role             installed   installed   installed   installed    configured, and 
  Installation**               with issues correctly   and          documented      
                                                       configured   thoroughly      
  ---------------- ----------- ----------- ----------- ------------ --------------- --

  ------------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------
  **Printer      No          Installer    Installer   Installer   Installer      
  Installer      installer   conversion   converted   converted   converted,     
  Conversion**   found       attempted    but not     and used    used, and      
                             but failed   used                    documented     
                                                                  well           
  -------------- ----------- ------------ ----------- ----------- -------------- --

  ---------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------
  **Network      Printer    Deployment   Printer      Printer     Printer        
  Printer        not        failed       deployed but deployed    deployed,      
  Deployment**   deployed                not          correctly   tested, and    
                                         functional               documented     
                                                                  well           
  -------------- ---------- ------------ ------------ ----------- -------------- --

  ---------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------
  **Part 2: Monitoring Print Services**                                          
  --------------------------------------------------------------- -- -- -- -- -- --

  ---------------------------------------------------------------------------------

  ------------------------------------------------------------------------------
  **Event   Event     Opened but  Logs reviewed Logs        Logs reviewed     
  Viewer    Viewer    no logs     but           reviewed    with thorough     
  Usage**   not       reviewed    superficial   with some   analysis and      
            opened                              analysis    documentation     
  --------- --------- ----------- ------------- ----------- ----------------- --

  ------------------------------------------------------------------------------

  ----------------------------------------------------------------------------------
  **Performance   Performance   Opened but  Metrics     Metrics     Metrics       
  Monitor Usage** Monitor not   no metrics  monitored   monitored   monitored,    
                  opened        monitored   but not     with some   analyzed, and 
                                            analyzed    analysis    documented    
                                                                    thoroughly    
  --------------- ------------- ----------- ----------- ----------- ------------- --

  ----------------------------------------------------------------------------------

  ----------------------------------------------------------------------------------
  **Print       Console   Opened but      Active jobs     Active    Active jobs   
  Management    not       functionality   viewed          jobs      viewed and    
  Console       opened    not used        superficially   viewed    documented    
  Usage**                                                 with some thoroughly    
                                                          detail                  
  ------------- --------- --------------- --------------- --------- ------------- --

  ----------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------
  **Part 3: Exploring Third-Party Tools**                                        
  --------------------------------------------------------------- -- -- -- -- -- --

  ---------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------
  **Research   No tools     Research     Research on Research on  Research on    
  on Tools**   researched   incomplete   one tool    two tools    two tools,     
                                         completed   with some    detailed       
                                                     analysis     analysis, and  
                                                                  comparison     
  ------------ ------------ ------------ ----------- ------------ -------------- --

  ---------------------------------------------------------------------------------

  ----------------------------------------------------------------------------------------
  **Installation    Tool not    Installation   Tool         Tool         Tool           
  and               installed   failed         installed    installed    installed,     
  Configuration**                              but not      and          configured,    
                                               configured   configured   and documented 
                                                            with issues  thoroughly     
  ----------------- ----------- -------------- ------------ ------------ -------------- --

  ----------------------------------------------------------------------------------------

  -------------------------------------------------------------------------------
  **Reporting   No report   Report   Report      Report      Comprehensive     
  Findings**    generated   lacks    generated   generated   report with       
                            detail   but lacks   with some   thorough analysis 
                                     analysis    analysis    and documentation 
  ------------- ----------- -------- ----------- ----------- ----------------- --

  -------------------------------------------------------------------------------
