# Tutorial scenario and prerequisites

In this tutorial, you work as a developer for a fictitious loan company. You are currently working on a decision service that validates loan requests. Called the Loan Validation Service, the decision service applies several criteria to determine the eligibility of potential borrowers, and contractual constraints for approved loans.

## Scenario

A business user is reviewing the results of the decision service. The user contacts you to tell you that the decision service rejects low-risk loans that actually qualify for approval. You must debug the decision service to determine why it rejects the loans.

In Rule Designer, you tag rule artifacts with breakpoints that stop the running of the decision service at key points. You can then examine the behavior of the rules in a step-by-step debugging process. You determine where the errors take place, and track them to specific rules. Then, you modify the rules to fix the errors.

## Prerequisites

You need the following component, projects and information:

-   Knowledge of business rule programming principles, Java™, and the Eclipse environment
-   Rule Designer: Download this component from the Operational Decision Manager on Cloud portal, and install it as directed.
-   The following project files in the [Tutorial: Debugging a decision service in Rule Designer](https://github.com/ODMDev/odm-on-cloud-debug) GitHub repository:

    -   answer: Contains the completed version of the decision service. You can run it to see the expected results.
    -   start: Contains the faulty version of the decision service. You look for errors in it during the debugging process.

In the GitHub repository, click the **Clone or download** button to download the contents of the repository to a directory on your computer. Expand the downloaded file in the directory. In the tutorial, the directory is referred to as InstallDir.

## Best practices

This tutorial includes the following best practices for debugging decision services:

-   Carefully read the error messages. They tell you where to look for errors.
-   Try automatic exception handling when an exception occurs in a rule condition.
-   Check the stack trace to get the names of ruleflows and rule tasks.
-   Switch to the debug mode to get more precise error information.
-   Use the rule search to find artifacts, and the Java search to find Java XOMs.
-   Use queries to find rules by their content.
-   Check the values in the Variables view at each breakpoint during debugging.
-   Check the Agenda view to see which rules are going to be run.

## More information

Use these links to find additional information:

-   [IBM Operational Decision Manager on Cloud Knowledge Center](https://www.ibm.com/support/knowledgecenter/SS7J8H/welcome/kc_welcome_cloud.html)
-   [IBM ODM on Cloud Tutorials](https://www.ibm.com/support/knowledgecenter/SS7J8H/com.ibm.odm.cloud.tutorial/topics/con_tutorials_intro.html)
-   [Developing decision services in Rule Designer](https://www.ibm.com/support/knowledgecenter/SS7J8H/com.ibm.odm.cloud.develop/topics/odm_cloud_develop.html)
-   [Running and debugging in Rule Designer](https://www.ibm.com/support/knowledgecenter/SS7J8H/com.ibm.odm.dserver.rules.designer.run/debugging_topics/tpc_running_debugging.html)
-   [Installing a stand-alone version of Rule Designer](https://www.ibm.com/support/knowledgecenter/SS7J8H/com.ibm.odm.cloud.tutorial/topics/tsk_install_rd_fullpackage.html)
-   [Installing Rule Designer in an existing Eclipse environment](https://www.ibm.com/support/knowledgecenter/SS7J8H/com.ibm.odm.cloud.tutorial/topics/tsk_install_rule_designer.html)
-   [Troubleshooting and support](https://www.ibm.com/support/knowledgecenter/SS7J8H/com.ibm.odm.cloud.troubleshooting/topics/odm_cloud_troubleshooting.html)
-   [IBM Operational Decision Manager on Cloud](https://www.ibm.com/us-en/marketplace/operational-decision-management)
-   [IBM Operational Decision Manager on Cloud - Detailed System Requirements](http://www.ibm.com/support/docview.wss?uid=swg27046500)
-   [Operational Decision Manager on Cloud FAQ](https://developer.ibm.com/odm/docs/frequently-asked-questions/odm-on-cloud-faq/)

[**Next** ![""](../tut_cloud_rd_debug_ghimages/next.jpg)](../tut_cloud_rd_debug_ghtopics/tut_cloud_rddebug_complete.md)

[![""](../tut_cloud_rd_debug_ghimages/home.jpg) **Back to table of contents**](../README.md)

© Copyright IBM Corporation 2018

