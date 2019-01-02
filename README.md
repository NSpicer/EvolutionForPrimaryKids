# EvolutionForPrimaryKids

**User Guide for editing the website**

***Setup and Access:***
- Sign up for a GitHub account via https://github.com/. GitHub is a code sharing and publishing service.
- Request access by emailing ns698@bath.ac.uk
- Add a new collaborator to the project by clicking 'Settings' and then 'Collaborators'
- Download Atom via https://atom.io/. Atom is a Text Editor  built for writing and editing code.
- Once you have gained access on GitHub, download the files by clicking the green 'Clone or download' button and then 'Download ZIP'.
- If you are unfamiliar with HTML, this website should help you to familiarise yourself https://www.w3schools.com/html/html_intro.asp.
- Equally, if you are unfamiliar with CSS, this website should help you to familiarise yourself https://www.w3schools.com/css/css_intro.asp.


***Committing changes to live website***
- Save the changes in the relevant Atom page by clicking ctrl + s.
- Open the GitHub desktop application, insert an update title and description for your changes in the boxes on the bottom left. Ensure these are clear.
- Click the blue 'Commit to master' button, then the black 'Fetch origin' button at the top
- Log into https://github.com/.
- Your changes will 


***Editing text on pages:***
Body of text on every page is below div class='container' and text shown on the website is written in white on Atom.


***Editing files for lesson plans:***
Open the html file for the lesson page that needs editing (Lesson1.html, Lesson2.html, Lesson3.html or Lesson4.html).
- To change the lesson plan file (green button), look for id='LessonPlans' and change the link in the <a href='-'> section.
- To change the PowerPoint Slide file (pink button), look for id='PowerPointSlides' and change the link in the <a href='-'> section.
- To change the other resources files (blue button), look for id='Other' change the link in the <a href='-'> section.


***Adding links to Useful Links:***
To add a new Useful Link, copy the follow text above the closing table tag </table>:
      <tr>
        <td height = '100'><a href='*insert website link*' class='UsefulLinkButton' id='PowerPointSlides'><strong>Go!</strong></a></td>
        <td>*insert short text description*</td>
      </tr>
Use id='PowerPointSlides' for a pink button and id='Other' for a blue button.


***Adding keywords:***
To add a new keyword to the list, insert the following text to the Keywords.html page in the correct alphabetical order. Ensure each keyword and definition is enclosed with <tr> and </tr>
      <tr>
        <td>*insest keyword*</td>
        <td>*insert keyword definition*</td>
      </tr>


***Adding News items:***
To add a new News item, open the News.html page and insert the following text immediately below <p>Find out what we have been doing to learn more about teaching evolution in primary schools, in order to continue improving our resources.</p> </div>.
      <div class='WrapperGreen'>
          <div class='container'>
            <img src='*insert image link*' id='NewsPicturePink' align='left' border-color: '#ffa6ff'>
            <br><p><strong>*insert news article title*</strong></p>
            <p class='sub'>19<sup>th</sup> January 2016<p>*<- replace date in this format*
            <p>*insert paragraph about news peice*</p>
          </div>
      </div>
Use class='WrapperGreen' for a green background and class='WrapperGrey' for a grey background.
Use id='NewsPicturePink' for a pink outline around the image and id='NewsPictureBlue' for a blue outline.
