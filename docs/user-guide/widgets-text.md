# Text Widgets

Text Widgets allow you to display fully-customisable text, optionally retrieving data from a plain text file or an API Integration.

![Text](images/text.png)

## Selecting an API Integration

!!! info
    We will be using the **Total Computers** API integration example we previously set up.

    Visit [Setting up Accounts](../accounts) to find out more about setting up an example Account and API Integration.

1.  Select a text widget by clicking on the thumbnail in the sidebar, or on the widget itself in the dashboard section.

    !!! info
        You should see **Text** and **Style** sections in the inspector on the right.

    ![Select](images/text%20select.png)

1.  In the inspector, click on the **type** drop-down and select **API Integration**:

    ![Type](images/text%20type.png)

1.  Select the **Boardies Example** account, and select the **Total Computers** integration:

    ![Integration](images/text%20integration.png)

1.  Click **Test**:

    ![Test](images/text%20test.png)

    !!! warning
        We are getting output from the API Integration, however it is not in the format we want.

        The output is currently displaying data about all computers. We only care about the total count.

1.  In the inspector, ensure **Display as total count** is switched on.

    Click **Test** again:

    ![Test Total Count](images/text%20test%20total%20count.png)

!!! Success
    The text widget's API Integration has been configured successfully.
