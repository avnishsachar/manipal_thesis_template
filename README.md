# Thesis Template

Latex template for writing a thesis in the style required by Manipal Institute of Technology. 
I tried to document it nicely and have it compile without any errors or
warnings. I have attached a preview of it in pdf format too.


## Writing your thesis:

File you will find a section near the top where you can specify the parameters (title, advisors, etc.) of your thesis. You can also set the template into proposal mode there if your are writing only a thesis proposal. This will exclude some stuff which is irrelevant for a proposal.

Your content should be defined in .tex files in Chapters folder. You can just write normal tex code and don't have to keep a special format in mind. Refer to the examples contained in the template.

To tell the template what chapters you have and in what order they go you have to specify filename and chapter title in the Thesis.tex file near the bottom. Use the \loadchapter{x}{y} command where you replace x by the filename of your chapter file (without .tex) and y by the title of your chapter. This will add a new chapter, set the chapter title and craete a label which you can reference by \ref{chapter:filename}.

Your bibliography should be located in the Bibliophy.bib file in Bibtex format. See the included examples to see how to use references.


## File and folder structure:

Below, you can find the file and folder structure along with the changes that are need to be made for ones thesis: 

* __main.tex__

  The entire document is based on this file. All one needs to do is, replace the *Title of the Project* field.
  
* __completioncertificate.tex__
  Attach the completion certificate recieved from the organisation you worked at here. The document needs to be attached in pdf format. Uncomment the line of code that is required for the task and delete the other lines of code.
  
* __certificate.tex__
  Replace the *project title, name, registration number, engineering branch* and *name of supervisor* fields here. 
  
* __references.bib__
  This is the file for the bibliography. I would suggest one to add references through a reference manager software(Zotero, Mendeley). Such softwares would automatically add the references in the preferred format from your library to the document.
  
* __studentdetailform.tex__
  This file is required to attach the student detail form in the end. I would suggest filling out the form and creating a pdf. The pdf can then be easily added to the document like we did for the completion certificate.
  
* __titlepage.tex__
  This file create the title page of the document. One needs to replace parameters like * title of project, engineering branch, name of the student, etc.*
  
* __chapters/__

    * __abstract.tex__
      This is where the abstract comes in
      
    * __acknowledgements.tex__
      This is where the acknowledgements comes in
      
    * __conclusion.tex__
      This is where the conclusion comes in
      
    * __introduction.tex__
      This is where the introduction comes in
      
    * __listoffigures.tex__
      An auto-generated list of figures 
      
    * __listofsymbols.tex__
      This is where one can list all the symbols. A sample has been given as a template to be followed
    
    * __listoftables.tex__
      An auto-generated list of tables
      
    * __literature_review.tex__
      This is where the literature review comes in
      
    * __objectives&methodology.tex__
      This is where the literature review comes in
    
    * __references.tex__
      Auto-generated bibliography through Zotero and Mendeley
      
    * __results&discussion.tex__
      This is where the literature review comes in
      
    * __Manipal_Institute_of_Technology__Thesis_Template.pdf__
      Preview of the template in pdf format
 
* __figures/__
  
  Put all the figures needed for the document in this folder


## License:

  This project is covered under the LaTeX Project Public License, version 1.3
