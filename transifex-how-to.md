Translating the OCDS into your own language is an important step to the adoption of the Standard as well understanding Open Contracting. 

This guide gives a general overview of the ways in which we have learnt to translate OCDS using Transifex. This guide does not cover the exact process to start using Transifex, we recommend that you read the [Using Transifex](http://ocds-standard-development-handbook.readthedocs.io/en/latest/standard/translation/#using-transifex) bit in the OCDS documentation. 

## Globally replacing a term

Replacing a term on Transifex can be divided in two parts. The first is the agreement with the community or publisher team that works on the translation and second is the actual process of replacing the term. 

### Agreeing on a term

The first step to replace a term globally is using the most neutral term you can find and add it to Transifex. It can happen that a language has variants by region, state or even country sharing the same language. So after this, you need to open the discussion to what each of the terms mean in those contexts. 

If you have a team working with you on the translation of OCDS, it is important to include someone who has knowledge of the procurement rules in your location, as well as someone who knows the techincal bits of your procurement system; this will help you make sure when you're translating you're adhering to the regulations and also the technical team is aware of the changes. 

If you have knowledge of other teams in different countries or cities that may help you in this discussion, reach out to them. Understanding these differences is crucial to reaching a useful term for a broader group of people.

An example of this excercise is the result of the workshop held to translate the Spanish version of OCDS with people from all over the Latin American region. You can see the results [here](https://docs.google.com/spreadsheets/d/1QLlt5EAJCEtIFXA3L6--cWey-FdQPP_bmwGQV6mXauc/edit#gid=1648356123)

### Modifying a term

The modification once you reach agreements about the terms is relatively easy. Depending on how many terms you're translating you can populate the Transifex Glossary directly, or upload a CSV file with the terms you'd like to include. 

> See the Spanish glossary [here](https://www.transifex.com/OpenDataServices/open-contracting-standard-1-1/glossary/es/)

## Adding a term and its definition
Adding an entry to the glossary will give you the correct translation every time this term appears during your work. If you aren't using the right term, the software will give a warning and keep it until you review the content. 

Another benefit of using this list is that you can add comments, where you can define what each term is, so translators can have more context of what they're looking at. 

## Translating and reviewing efficiently

The translation process can be tedious after the first 100 strings. To do this, we have found there are many shortcuts and tactics that you can use to make translation easier. 

In general, having more people translating and less people reviewing is a more effective way to translate, but in practical terms there are a few shortcuts that will make your life easier. 

### Save and next string
You can save the current entry and go to the next by pressing TAB on your keyboard. This will save you time and directly add the translation to the file. 

### Machine translation
This is a tool we recommend to use carefully, since the terms we're translating are quite specialized, but for short terms, especially those you have included in a glossary, it works pretty well. By pressin CTRL + h, you'll get a robot to translate the term. If you're aiming for a longer string, you should be careful when using this tool, since you'll probably need to fix a lot of pieces that Transifex doesn't know how to translate. 

### Suggestions
If you've translated a term before, Transifex will remember this and give you a suggestion to use. There will be cases when there is a 100% match and others when this will be a smaller percentage. 

### Copy source string
There are some terms, especially really technical terms or names in other languages which we don't translate. You can just copy the original string with CTRL + g.

## Checking previous translations of a given word

There might be words or terms that need to be revised as you advance on a translation. To do this, there is a tool inside Transifex, where you can see the history of a word or string, when it was edited and who edited the content. This will help you make changes efficiently as well as exchange with others as you develop the translation. 
