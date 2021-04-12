**Setting up the project.**

Welcome to the Lozan Chocolate Project setup guide.

We need to start by setting up everything we need in order to create the
Database.

1.  After you open the solution in Visual Studio you need to locate the
    appsettings.json file in the “ChocolateProject” project.\
    \
    ![](media/image1.png){width="2.783581583552056in"
    height="3.371376859142607in"}

2.  After you locate “ConnectionStrings”, in line 3 replace the “ . “
    after “Server= “ with the name of your local server. If you do not
    know the name of your local server, you should refer to step 3.\
    ![](media/image2.png){width="5.604477252843394in"
    height="2.088888888888889in"}

3.  In order to locate the name of your local server you need to launch
    Microsoft SQL Server Management Studio. You will find the server’s
    name in the popup that comes up automatically.\
    ![](media/image3.png){width="5.1361329833770775in"
    height="3.500488845144357in"}

4.  Warning! Repeat steps 1-3 in the appsettings.json file in the
    Chocolate.Eshop project.

5.  Next up, you need to navigate through the “Tools” tab to the “NuGet
    Package Manager” menu and select the “Package Manager
    Console” option. ![](media/image4.png){width="6.5in"
    height="2.470138888888889in"}

6.  After you have located the Package Manager Console window, which is
    typically in the bottom of the Visual Studio Window, set the Default
    project to Chocolate.DataAccess.![](media/image5.png){width="6.5in"
    height="1.8368055555555556in"}

7.  Your next step should be to type the “update-database” command in
    the console and press
    Enter.![](media/image6.png){width="6.355053587051619in"
    height="3.1150185914260717in"}

8.  Finally, if you followed the instructions correctly you should be
    able to see a success message in the console that looks like this.

> ![](media/image7.png){width="2.531603237095363in"
> height="1.156411854768154in"}
>
> **Setting up multiple Startup Projects**

1.  In the Solution Explorer you should right click the Solution Named\
    “ ChocolateProject “ and select the “Set Startup
    Projects…”.![](media/image8.png){width="6.5in"
    height="5.134327427821522in"}

2.  Next up, to run multiple projects simultaneously you need to select
    the “Multiple startup projects” option and then select “Start” from
    the drop-down menu for both Chocolate.Eshop &
    ChocolateProject.![](media/image9.png){width="4.970854111986002in"
    height="3.440298556430446in"}

3.  Finally, pressing the Start button should launch both applications
    in your <span id="_Hlk69002112"
    class="anchor"></span>browser.![](media/image10.png){width="6.625592738407699in"
    height="0.5851246719160105in"}

> **Existing accounts **
>
> We have prepared a few accounts with different roles for you to use to
> have access to different views and action depending on the role of
> each account.
>
> For the sake of convenience, the password for all the accounts is the
> same: P@ssw0rd.

  Username    Role
  ----------- -----------------
  Takis       Admin
  Thanasis    Accounting
  Angela      Human Resources
  Vasilis     Warehouse
  Zouzoulas   Department Head
