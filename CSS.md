# What is CSS

- CSS (Cascading Style Sheets) allows you to create great-looking web pages

- CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

- A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.

- Presenting a document to a user means converting it into a form usable by your audience. Browsers, like Firefox, Chrome, or Edge , are designed to present documents visually, for example, on a computer screen, projector or printer.

- CSS can be used for very basic document text styling — for example changing the color and size of headings and links. It can be used to create layout — for example turning a single column of text into a layout with a main content area and a sidebar for related information. It can even be used for effects such as animation. Have a look at the links in this paragraph for specific examples.

# CSS Syntax

- CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

- CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text."

- The following code shows a very simple CSS rule that would achieve the styling described above:

h1 {
    color: red;
    font-size: 5em;
}

- The rule opens with a selector . This selects the HTML element that we are going to style. In this case we are styling level one headings (<h1>).

- We then have a set of curly braces { }. Inside those will be one or more declarations, which take the form of property and value pairs. Each pair specifies a property of the element(s) we are selecting, then a value that we'd like to give the property.

- Before the colon, we have the property, and after the colon, the value. CSS properties have different allowable values, depending on which property is being specified. In our example, we have the color property, which can take various color values. We also have the font-size property. This property can take various size units as a value.

# Internal CSS
- An internal style sheet may be used if one single HTML page has a unique style.

- The internal style is defined inside the <style> element, inside the head section.

# External CSS

- With an external style sheet, you can change the look of an entire website by changing just one file!

- Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

- An external style sheet can be written in any text editor, and must be saved with a .css extension.

- The external .css file should not contain any HTML tags.

# Inline CSS

- An inline style may be used to apply a unique style for a single element.

- To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property

# Cascading Order

- an inline style has the highest priority, and will override external and internal styles and browser defaults.



