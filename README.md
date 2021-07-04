**Project Title**

Code Refactor Ticket: Horiseon

**Description**

Horiseon is requesting a refactor of it's codebase for adherence to accessibility standards, and ultimatley for increased optimization of it's site for search engines. Horiseon has included a list of scenario-oriented acceptance criteria along with the refactor request. The criteria are enumerated below alongside developer refactor comments in italics.

**Acceptance Criteria**
1. GIVEN a webpage meets accessibility standards
    WHEN I view the source code
    THEN I find semantic HTML elements

    _Introduced semantic elements such as: header, nav, article, aside, section, footer, and main where appropriate into the source code to increase web page accessibility quality_

2. WHEN I view the structure of the HTML elements
    THEN I find that the elements follow a logical structure independent of styling and positioning

    _semantic elements are now in place to correctly characterize web element containers relative to the section and purpose_

3. WHEN I view the image elements
    THEN I find accessible alt attributes

    _where needed, alt attributes where introduced into img elements- and where given descriptive verbiage_

4. WHEN I view the heading attributes
    THEN they fall in sequential order

    _source code was scanned to make sure header elements followed in sequence_

5. WHEN I view the title element
    THEN I find a concise, descriptive title

    _titled page-> Horiseon: Optimize Online Presence_

**Other Developer Refactor Comments**

_Cleaned up index.html by fixing an id link to "SEO" section of page main content, removed footer text from page according to mock up-added spacing via margin property, in the stylesheet consolidated multiple CSS rules for more consise code, and linked rules to re-purposed semantic elements_

**Screenshot**
[view Horiseon-Refactor page screenshot!](./assets/images/projects_Horiseon_Refactor_Develop_index.html.png)

**Application**

[view link to Horiseon-Refactor deployed application](https://coderjake91.github.io/Horiseon-Refactor/)

**Horiseon-Refactor github repo URL**

[Horiseon-Refactor repo](https://github.com/coderjake91/Horiseon-Refactor.git)

