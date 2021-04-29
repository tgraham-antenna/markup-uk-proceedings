# Markup UK Presentation Paper

This project contains a presentation paper for Markup UK 2019.

If you want to create your own paper you can fork this project, for more details see [How to create my own paper](fork.md) 

## Access the Dashboard

After you [create your own paper](fork.md) a Dashboard will be created for your project that allows you to:

- Edit the paper online using Oxygen XML Web Author (https://www.oxygenxml.com/xml_web_author.html).
- See a preview of the generated PDF, that is automatically generated each time you commit using Netlify (https://netlify.com).
- Download an archive with the paper source and all the supporting files, that you can submit as your paper.

To access the Dashboard, go to your Netlify home page: https://app.netlify.com, choose the project and then open its URL.

## Edit the paper in Oxygen XML Editor

To edit the paper:

- Clone the repository locally.
- Open the .xpr file in Oxygen XML Editor.
- From the project view, open the `paper.xml` file.

To generate the PDF:

- From the **Project** panel
  - Select and right-click on `paper.xml`
  - Choose **Transform** > **Transform with...**
  - Choose **Conference Paper** or **[Markup UK Paper](README.markup-uk-paper.md)** and press **Apply**

- From the editor, once `paper.xml` is opened
  - Use the "Apply transformation scenario" action from the toolbar
