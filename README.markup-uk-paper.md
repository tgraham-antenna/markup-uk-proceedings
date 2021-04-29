# 'Markup UK Paper' Transformation Scenario

The 'Markup UK Paper' transformation scenario makes it easy to preview how your paper will look in the Markup UK proceedings. The transformation scenario formats your paper using the same DocBook XSLT Stylesheets customisation as is used in the final proceedings.

The Markup UK proceedings are formatted using Antenna House Formatter. Accurate reproduction of the final proceedings requires that you also have a recent version of the Antenna House XSL Formatter installed and that Oxygen is configured to use it.

## 'Antenna House' external FO processor

The transformation scenario expects Oxygen to have an 'Antenna House' FO processor configuration that runs the Antenna House command-line formatter.

If your Oxygen is not already configured:

1. Install AH Formatter V7.1 then restart Oxygen.
1. If desired, export your current global options.
1. In Oxygen, under the **Options** menu, select **Import Global Options...**.
1. Select `resources/formatter-options/formatter-options.xml` then click on **Open**.
1. When the **Import Global Options** dialog box is displayed, click on **Open**.
1. Oxygen will overwrite your current FO processor configuration with the configuration from `formatter-options.xml`.
1. Oxygen will advise that a restart is required, but the FO processor configuration has been made already.
